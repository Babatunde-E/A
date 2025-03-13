<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAAS Filter/Search UI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #1E1E2E;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 60%;
            max-width: 800px;
            background: #2A2A3B;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }
        input, select {
            background: #3A3A4E;
            color: white;
        }
        button {
            background: #4F46E5;
            color: white;
            cursor: pointer;
        }
        .results {
            margin-top: 20px;
            background: #181826;
            padding: 15px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>SAAS Search & Filter</h2>
        <input type="text" placeholder="Search...">
        <select>
            <option value="all">All Categories</option>
            <option value="analytics">Analytics</option>
            <option value="marketing">Marketing</option>
            <option value="development">Development</option>
        </select>
        <button>Filter Results</button>
        <div class="results">
            <h3>Search Results</h3>
            <p>No results found. Try refining your search.</p>
        </div>
    </div>
</body>
</html>
