# Table
This table contains concepts of Rowspan and Colspan

<!DOCTYPE html>
<html lang="en">
<head>
<body>
    <table border="1">
        <tr>
            <th>Level 1</th>
            <th>Level 2</th>
            <th>Level 3</th>
            <th>Info</th>
            <th>Name</th>
        </tr>

        <tr>
            <td rowspan="6">System</td>
            <td rowspan="4">System Apps</td>
            <td rowspan="3">System Env</td>
            <td rowspan="1">App test</td>
            <td rowspan="1">foo</td>
        </tr>

        <tr>
            <td rowspan="1">App Memory</td>
            <td rowspan="1">foo</td>
        </tr>

        <tr>
            <td rowspan="1">App Test</td>
            <td rowspan="1">foo</td>
        </tr>

        <tr>
            <td>System Env 2</td>
            <td rowspan="1">App test</td>
            <td rowspan="1">foo</td>
        </tr>

        <tr>
            <td rowspan="2">System Memory</td>
            <td rowspan="2">Memory Test</td>
            <td rowspan="1">Memory Func</td>
            <td rowspan="1">foo</td>
        </tr>

        <tr>
            <td rowspan="1">Apes Test</td>
            <td rowspan="1">foo</td>
        </tr>
    </table>
</body>

</head>

</html>
