<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project README</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f7fa;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 40px 20px;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 30px 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        h2 {
            color: #34495e;
            margin-top: 40px;
        }

        h3 {
            color: #2c3e50;
        }

        .badge {
            background-color: #16a085;
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        .table-of-contents {
            margin-top: 20px;
            background-color: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
        }

        .table-of-contents ol {
            padding-left: 20px;
        }

        .table-of-contents a {
            text-decoration: none;
            color: #2c3e50;
            transition: color 0.3s;
        }

        .table-of-contents a:hover {
            color: #16a085;
        }

        .content-section {
            margin-top: 40px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }

        pre {
            background-color: #ecf0f1;
            padding: 15px;
            border-radius: 5px;
            font-family: 'Courier New', Courier, monospace;
            overflow-x: auto;
        }

        .footer {
            margin-top: 40px;
            text-align: center;
            font-size: 0.9rem;
            color: #7f8c8d;
        }

        .footer a {
            text-decoration: none;
            color: #16a085;
        }
    </style>
</head>
<body>

    <header>
        <h1>Project Name</h1>
        <p>Awesome project that does amazing things</p>
    </header>

    <section class="table-of-contents">
        <h2>Table of Contents</h2>
        <ol>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#usage">Usage</a></li>
            <li><a href="#contributing">Contributing</a></li>
            <li><a href="#license">License</a></li>
        </ol>
    </section>

    <section id="installation" class="content-section">
        <h2>Installation <span class="badge">Easy</span></h2>
        <p>Follow these steps to install and set up the project:</p>
        <pre><code>git clone https://github.com/yourusername/yourproject.git
cd yourproject
npm install</code></pre>
    </section>

    <section id="usage" class="content-section">
        <h2>Usage</h2>
        <p>Start the application with the following command:</p>
        <pre><code>npm start</code></pre>
        <p>For more advanced usage, refer to the documentation and examples.</p>
    </section>

    <section id="contributing" class="content-section">
        <h2>Contributing</h2>
        <p>We welcome contributions! Here's how you can help:</p>
        <ul>
            <li>Fork the repository</li>
            <li>Create a new branch (`git checkout -b feature-branch`)</li>
            <li>Make your changes</li>
            <li>Submit a pull request</li>
        </ul>
    </section>

    <section id="license" class="content-section">
        <h2>License</h2>
        <p>This project is licensed under the MIT License - see the <a href="#">LICENSE</a> file for details.</p>
    </section>

    <footer class="footer">
        <p>Created with ❤️ by <a href="#">Your Name</a></p>
    </footer>

</body>
</html>
