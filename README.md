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
