# Test Task: Build an Analytics Dashboard

### **Objective:**
Create a responsive analytics dashboard using React.js that visualizes data through charts and graphs and displays data in a tabular format.

### **Description:**
The candidate will develop a dashboard that fetches and displays analytics data from `mockData.json`, allowing users to interact with the data through various filters, sorting options, and export features. The project should demonstrate the candidate's proficiency in frontend development, data visualization, and user interface design. Candidates should ensure that the dashboard maintains good performance, especially when handling larger datasets.

### **Requirements:**

1. **Data Source:**
   - Use a local JSON file (`mockData.json`) to simulate fetching data from a mock API. The data should contain fields such as:
     - `date`: (e.g., "2023-01-01")
     - `likes`: (e.g., 10)
     - `shares`: (e.g., 1)
     - `comments`: (e.g., 1)
     - `engagement`: (e.g., 12)

2. **Chart Library:**
   - Use React.js for the application. Candidates are free to choose any chart library (e.g., Chart.js, D3.js, Recharts, etc.) to visualize the data. The dashboard should include 2 to 3 different types of charts (e.g., line chart for trends over time, bar chart for comparing categories like likes, shares, and comments) to represent the data.

3. **Data Table:**
   - Display the same data in a table format that includes the following columns:
     - **Date**
     - **Likes**
     - **Shares**
     - **Comments**
     - **Engagement**
   - Implement pagination, sorting, and filtering functionality for the table:
     - **Sorting:** Allow users to sort the data by each column (e.g., ascending/descending order for likes, shares, comments, and engagement).
     - **Filters:** Allow users to filter data in the table view based on:
       - **Date Range:** Users can select a start and end date to filter the displayed data.
       - **Data Categories:** Provide a dropdown or checkbox list for users to select specific categories of data to display (e.g., likes, shares, comments, engagement).

4. **Chart View:**
   - Implement features in the chart view allowing users to:
     - **Choose Segments:** Users can select specific segments or categories of data to display in the charts (e.g., filter by likes, shares, or comments).
     - **Date Range:** Allow users to filter the data displayed in the charts based on a selected date range.
     - **Sorting:** Enable users to sort the displayed data in the charts (if applicable) based on their selection.

5. **Export Functionality:**
   - Implement options for exporting selected or filtered data:
     - **CSV Export:** Allow users to export all displayed data (from both charts and the table) as a CSV file.
     - **PDF Export:** Enable users to export all displayed data along with snapshots of the charts as a PDF document.

6. **Layout:**
   - Design a user-friendly layout featuring a sidebar for navigation.
   - Include segments for chart display, table display, filters, sorting options, and export features.

7. **Styling:**
   - Use CSS (or a CSS framework) to ensure the dashboard is visually appealing and responsive across different screen sizes.

8. **Testing:**
   - Candidates should write tests for core functionalities of the dashboard, including:
     - **Data Fetching:** Ensure the application correctly fetches and displays data from `mockData.json`.
     - **Filtering:** Verify that filters work correctly for both the table and chart views.
     - **Sorting:** Check that sorting functionality works as expected for both table and chart data.
     - **Exporting:** Test the export functionality for both CSV and PDF formats.
     - **User Interactions:** Ensure the UI responds correctly to user interactions (e.g., selecting filters, sorting data, etc.).

   - **View Coverage:** Tests should specifically cover both views:
     - **Table View:** Ensure all functionalities (sorting, filtering, exporting) in the table view are tested.
     - **Chart View:** Ensure all functionalities (segment selection, date range filtering, exporting) in the chart view are tested.

### **Evaluation Criteria:**
- **Code Quality:** Clean, maintainable, and well-structured code.
- **User Experience:** Intuitive layout and smooth user interactions.
- **Data Visualization:** Effective use of charts and clarity in data representation.
- **Functionality:** Proper implementation of filters, sorting, segment selection, data table, and export options.
- **Testing Coverage:** Thoroughness and effectiveness of tests written for both views.

### **Submission:**
Candidates should submit code via a GitHub repository along with a brief README explaining how to run the application and tests, as well as any additional details relevant to the implementation.
