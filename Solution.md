```html
<!DOCTYPE html>
<html>
<head>
    <title>Dashboard</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: #f1f5f9;
        }

        header {
            background: #1e293b;
            color: white;
            padding: 20px;
        }

        .layout {
            display: grid;
            grid-template-columns: 200px 1fr;
            grid-template-rows: 1fr;
            gap: 20px;
        }

        aside {
            background: #334155;
            color: white;
            padding: 20px;
        }

        main {
            padding: 20px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>My Dashboard</header>

    <div class="layout">
        <aside>
            <h3>Menu</h3>
            <p>Dashboard</p>
            <p>Students</p>
            <p>Courses</p>
        </aside>

        <main>
            <h2>Dashboard Overview</h2>
            <div class="cards">
                <div class="card">Students: 1250</div>
                <div class="card">Courses: 35</div>
                <div class="card">Assignments: 18</div>
                <div class="card">Tasks: 7</div>
            </div>
        </main>
    </div>
</body>
</html>
```