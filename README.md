<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Renewable Energy Dashboard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Renewable Energy Dashboard</h1>
    <div class="container">
        <div class="controls">
            <div class="checkbox-group">
                <label><input type="checkbox" value="Solar" checked> Solar</label>
                <label><input type="checkbox" value="Wind" checked> Wind</label>
                <label><input type="checkbox" value="Hydro" checked> Hydro</label>
                <label><input type="checkbox" value="Geothermal" checked> Geothermal</label>
            </div>

            <div id="date-range">
                <label>Start Date: <input type="date" id="start-date"></label>
                <label>End Date: <input type="date" id="end-date"></label>
            </div>
        </div>

        <div id="chart" class="chart"></div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/plotly.js-dist-min"></script>
    <script src="script.js"></script>
</body>
</html>
