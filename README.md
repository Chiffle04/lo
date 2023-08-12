<!DOCTYPE html>
<html>
<head>
    <title>Sortable Table</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/jquery.tablesorter/2.31.3/css/theme.default.min.css">
</head>
<body>
    <table id="sortableTable" class="tablesorter">
        <thead>
            <tr>
                <th>Column 1</th>
                <th>Column 2</th>
                <!-- Add more columns as needed -->
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Row 1, Column 1</td>
                <td>Row 1, Column 2</td>
            </tr>
            <!-- Add more rows as needed -->
        </tbody>
    </table>
    
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.tablesorter/2.31.3/js/jquery.tablesorter.min.js"></script>
    <script>
        $(document).ready(function() {
            $("#sortableTable").tablesorter();
        });
    </script>
</body>
</html>
