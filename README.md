<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
            margin: 15px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            font-family: Arial, sans-serif;
        }
        h2 {
            color: #24292e;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 10px;
        }
    </style>
</head>
<body>
<div class="container">

<!-- Таблица подключения кнопок -->
<h2>Подключение кнопок</h2>
<table>
    <tr>
        <th>Компонент</th>
        <th>Подключение к Wemos D1 Mini</th>
    </tr>
    <tr>
        <td>Кнопка 1</td>
        <td>D5 + GND</td>
    </tr>
    <tr>
        <td>Кнопка 2</td>
        <td>D6 + GND</td>
    </tr>
    <tr>
        <td>Кнопка 3</td>
        <td>D7 + GND</td>
    </tr>
</table>

<!-- Таблица подключения PN532 -->
<h2>Подключение PN532</h2>
<table>
    <tr>
        <th>PN532</th>
        <th>Wemos D1 Mini</th>
    </tr>
    <tr>
        <td>VCC</td>
        <td>3.3V</td>
    </tr>
    <tr>
        <td>GND</td>
        <td>GND</td>
    </tr>
    <tr>
        <td>SDA</td>
        <td>D3</td>
    </tr>
    <tr>
        <td>SCL</td>
        <td>D4</td>
    </tr>
</table>

<!-- Таблица подключения OLED -->
<h2>Подключение OLED дисплея</h2>
<table>
    <tr>
        <th>OLED</th>
        <th>Wemos D1 Mini</th>
    </tr>
    <tr>
        <td>VCC</td>
        <td>3.3V</td>
    </tr>
    <tr>
        <td>GND</td>
        <td>GND</td>
    </tr>
    <tr>
        <td>SCL</td>
        <td>D1</td>
    </tr>
    <tr>
        <td>SDA</td>
        <td>D2</td>
    </tr>
</table>

</div>
</body>
</html>
