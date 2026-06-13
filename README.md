<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD Application</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; 
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #4a90e2;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        h1 {
            margin: 0;
            font-size: 2.5em; 
        }
        h2 {
            margin-top: 0;
            font-size: 2em; 
        }
        section {
            margin: 20px auto;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            max-width: 800px; 
        }
        h3 {
            color: #4a90e2;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        li {
            margin: 10px 0;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background: #4a90e2;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 2em; /* Smaller title */
            }
            h2 {
                font-size: 1.5em; /* Smaller subtitles */
            }
            section {
                padding: 20px; /* Less padding on small screens */
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>CRUD Application</h1>
    </header>

    <main>
        <section>
            <h2>Introduction</h2>
            <p>After completing all the fundamentals, a CRUD application is useful to learn the concepts in real time.</p>
            <p>A CRUD app is a type of software application that performs basic operations on data. CRUD stands for Create, Read, Update, and Delete, which represent the four basic functions that can be performed on persistent storage. These operations allow users to interact with and manage data within a system.</p>
        </section>

        <section>
            <h2>What does CRUD stand for?</h2>
            <ul>
                <li><strong>C</strong> – Create</li>
                <li><strong>R</strong> – Read</li>
                <li><strong>U</strong> – Update</li>
                <li><strong>D</strong> – Delete</li>
            </ul>
        </section>

        <section>
            <h2>Overview of CRUD Operations</h2>
            <h3>Create</h3>
            <p>This operation involves the creation of new records or entries in the database. Users can input data into the application, and the app will store this data in the appropriate format within the database.</p>
            
            <h3>Read</h3>
            <p>The read operation retrieves existing data from the database and presents it to the user. Users can view, search, and access data stored in the system.</p>
            
            <h3>Update</h3>
            <p>This operation allows users to modify or update existing data within the database. Users can make changes to the information stored in the system, such as updating a customer's contact information or editing the content of a blog post.</p>
            
            <h3>Delete</h3>
            <p>The delete operation removes data from the database. Users can delete records or entries that are no longer needed or are outdated.</p>
        </section>
    </main>

    <footer>
        <p>&copy;
            </footer>

</body>
</html>
