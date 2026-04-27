<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portal Dashboard</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            display: flex;
            background-color: #f4f7f6;
            height: 100vh;
        }

        /* Bapashe Sidebar Design */
        .sidebar {
            width: 250px;
            background-color: #2c3e50;
            color: white;
            display: flex;
            flex-direction: column;
            padding: 20px 0;
        }

        .sidebar h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 22px;
            color: #ecf0f1;
        }

        .sidebar a {
            text-decoration: none;
            color: #bdc3c7;
            padding: 15px 25px;
            font-size: 18px;
            display: block;
            transition: 0.3s;
        }

        .sidebar a:hover {
            background-color: #34495e;
            color: white;
            padding-left: 35px;
        }

        /* Logout button niche rakhar jonno */
        .logout {
            margin-top: auto;
            background-color: #e74c3c !important;
            color: white !important;
        }

        /* Main Content area */
        .main-content {
            flex-grow: 1;
            padding: 30px;
            overflow-y: auto;
        }

        .header {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
    </style>
</head>
<body>

    <div class="sidebar">
        <h2>My Portal</h2>
        <a href="#">Dashboard</a>
        <a href="#">Notes</a>
        <a href="#">Hisab Nikash</a>
        <a href="#">Settings</a>
        <a class="logout" href="#">Logout</a>
    </div>

    <div class="main-content">
        <div class="header">
            <h1>Welcome, Miraj!</h1>
        </div>

        <div class="card-container">
            <div class="card">
                <h3>Notes</h3>
                <p>5 Active Notes</p>
            </div>
            <div class="card">
                <h3>Hisab</h3>
                <p>Total: 0.00 ৳</p>
            </div>
        </div>
    </div>

</body>
</html>
