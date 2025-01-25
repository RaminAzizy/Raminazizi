<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رزومه من</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #e9ecef;
            margin: 0;
            padding: 20px;
            color: #343a40;
        }
        header {
            text-align: center;
            padding: 30px;
            background-color: #007bff;
            color: white;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        h2 {
            color: #007bff;
            margin-bottom: 10px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }
        section {
            margin-bottom: 30px;
            border-bottom: 1px solid #dee2e6;
            padding-bottom: 20px;
        }
        section:last-child {
            border-bottom: none;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
            color: #6c757d;
        }
        .highlight {
            background-color: #f8f9fa;
            padding: 10px;
            border-left: 5px solid #007bff;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>MY CV</h1>
        <p>Ramin Azizy</p>
    </header>
    <div class="container">
        <section>
            <h2>About Me </h2>
            <div class="highlight">I am python programmer</div>
        </section>
        <section>
            <h2>Education</h2>
            <div class="highlight">I am studying for a master's degree in mechatronics</div>
        </section>
        <section>
            <h2>CV WORK</h2>
            <div class="highlight">PYTHON</div>
        </section>
        <section>
            <h2>Skills</h2>
            <div class="highlight">C++ //  c  \\  python </div>
        </section>
    </div>
    <footer>
        <p>تاریخ: <span id="currentDate"></span></p>
    </footer>
    <script>
        document.getElementById('currentDate').textContent = new Date().toLocaleDateString('fa-IR');
    </script>
</body>
</html>
