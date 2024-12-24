# Timetable

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            table-layout: fixed;
        }
        th, td {
            border: 1px solid black;
            text-align: left;
            vertical-align: top;
            padding: 10px;
            word-wrap: break-word;
        }
        th {
            background-color: #f2f2f2;
        }
        .orange {
            background-color: #f9d5b5;
        }
        .green {
            background-color: #c8e6c9;
        }
        .purple {
            background-color: #e1bee7;
        }
        th:first-child, td:first-child {
            width: 10%;
        }
        td {
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>9:30 AM</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>10:00 AM</td>
                <td class="orange" rowspan="4">ELEC 341 201</td>
                <td></td>
                <td class="orange" rowspan="4">ELEC 341 201</td>
                <td></td>
            </tr>
            <tr>
                <td>10:30 AM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>11:00 AM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>11:30 AM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>12:00 PM</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>2:30 PM</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>3:00 PM</td>
                <td class="green" rowspan="4">ELEC 391 201</td>
                <td></td>
                <td class="green" rowspan="4">ELEC 391 201</td>
                <td></td>
            </tr>
            <tr>
                <td>3:30 PM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>4:00 PM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>4:30 PM</td>
                <td class="green" rowspan="6">ELEC 391 L2C</td>
                <td class="green" rowspan="6">ELEC 391 L2C</td>
            </tr>
            <tr>
                <td>5:00 PM</td>
                <td class="purple" rowspan="3">ELEC 481 201</td>
                <td class="purple" rowspan="3">ELEC 481 201</td>
            </tr>
            <tr>
                <td>5:30 PM</td>
            </tr>
            <tr>
                <td>6:00 PM</td>
            </tr>
            <tr>
                <td>6:30 PM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>7:00 PM</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td>7:30 PM</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </tbody>
    </table>
</body>
</html>

Term: 2024W2