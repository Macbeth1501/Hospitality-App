



## Project Overview
The objective of this project is to develop a web application to facilitate the digitalization of the hospitality process for group accommodation. The application allows users to upload two CSV files to efficiently allocate rooms in hostels while ensuring group members with the same ID stay together and adhere to hostel capacities and gender-specific accommodations.

## Table of Contents
1. Installation
2. Usage
3. File Descriptions
4. Algorithm Explanation
5. Example Output


## Installation
1. **Clone the Repository**:
   \`\`\`bash
   git clone https://github.com/yourusername/hospitality-process-digitalization.git
   cd hospitality-process-digitalization
   \`\`\`

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the necessary Python packages using pip:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

3. **Run the Application**:
   Start the Flask application by running:
   \`\`\`bash
   python app.py
   \`\`\`

4. **Access the Application**:
   Open your web browser and navigate to \`http://127.0.0.1:5000/\`.

## Usage
1. **Upload CSV Files**:
   - Open the application in your web browser.
   - Use the provided form to upload the Group Information CSV and the Hostel Information CSV files.
   - Click the \"Upload\" button to submit the files.

2. **View Room Allocation**:
   - After processing, the application will display the room allocation results on the same page.
   - The results show which group members are allocated to which rooms in the hostels.

3. **Download Allocation Details**:
   - A link to download the allocation details as a CSV file is provided below the results table.

## File Descriptions
- **index.html**: Main HTML template for the web application.
- **styles.css**: Contains the CSS styles for the web application.
- **app.py**: Main Flask application file.
- **requirements.txt**: Lists the Python dependencies required to run the application.

## Algorithm Explanation
The room allocation algorithm works as follows:
1. **Read CSV Files**: Reads the Group Information and Hostel Information CSV files uploaded by the user.
2. **Parse Data**: Parses data into appropriate data structures.
3. **Allocate Rooms**: Allocates rooms based on group IDs, gender, and room capacities.
4. **Output Allocation**: Displays and allows downloading of the allocation results.

## Example Output

| Group ID | Hostel Name  | Room Number | Members Allocated |
|----------|--------------|-------------|-------------------|
| 101      | Boys Hostel A| 101         | 3                 |
| 102      | Girls Hostel B| 202        | 4                 |
| 103      | Boys Hostel A| 102         | 2                 |
| 104      | Girls Hostel B| 202        | 5                 |

