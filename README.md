# Filsinger-GradebookHTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gradebook</title>
    <style>
 background-color: #4CAF50;
    color: white;    </style>
</head>
<body>
    <h1>Gradebook</h1>
    <table id="gradebook">
        <!-- Table content goes here -->
    </table>
    <script src="gradebook.js"></script>
</body>
</html>

<thead>
    <tr>
        <th>Braden Filsinger</th>
        <th>Assignment 1</th>
        <th>Assignment 2</th>
        <th>Assignment 3</th>
    </tr>
</thead>
<tbody>
    <!-- Rows will be populated dynamically with JavaScript -->
</tbody>
// TODO: Fetch data from the PostgreSQL database (to be implemented later)
function fetchGradeData() {
    // This function will query the PostgreSQL database and return grade data
    console.log("Fetching grade data...");
}

// TODO: Populate the table with grade data
function populateGradebook(data) {
    // This function will take the fetched grade data and populate the table
    console.log("Populating gradebook with data:", data);
}

// TODO REMOVE THIS
// Call the stubs to demonstrate the workflow
const gradeData = fetchGradeData();
populateGradebook(gradeData);
// END REMOVE
