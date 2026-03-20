<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Profile Page | Maithali S. Yadav</title>
    <style>
        /* General Page Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5; /* Light grey background */
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Navigation Bar */
        nav {
            width: 100%;
            background-color: #004d40; /* Dark Teal */
            padding: 15px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            text-transform: uppercase;
        }

        nav a:hover {
            color: #80cbc4;
        }

        /* Profile Card Layout */
        .profile-container {
            background-color: white;
            width: 80%;
            max-width: 500px;
            margin-top: 50px;
            padding: 30px;
            border: 2px solid #004d40; /* Border styling */
            border-radius: 15px;
            text-align: center;
            box-shadow: 10px 10px 20px rgba(0,0,0,0.1);
        }

        /* Profile Image Styling */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%; /* Circular image */
            border: 4px solid #004d40;
            object-fit: cover;
            margin-bottom: 20px;
        }

        /* Text Styling */
        h1 {
            color: #004d40;
            margin: 10px 0;
            text-transform: uppercase;
        }

        h2 {
            color: #555;
            font-size: 1.2em;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }

        .info-text {
            color: #333;
            line-height: 1.6;
            margin: 20px 0;
            text-align: left;
        }

        /* Attribute List Styling */
        ul {
            list-style: none;
            padding: 0;
            text-align: left;
        }

        ul li {
            background: #e0f2f1;
            margin: 5px 0;
            padding: 10px;
            border-left: 5px solid #004d40;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="#">Home</a>
        <a href="#">Portfolio</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Profile Content -->
    <div class="profile-container">
        <img src="https://via.placeholder.com" alt="Profile Picture" class="profile-img">
        
        <h1>Maithali S. Yadav</h1>
        <h2>USN: CS25153 | Section: C</h2>

        <div class="info-text">
            <p><strong>Bio:</strong> Aspiring engineer with a keen interest in aviation history and web development.</p>
            
            <strong>Key Attributes:</strong>
            <ul>
                <li>Quick Learner</li>
                <li>Problem Solver</li>
                <li>Team Collaborator</li>
            </ul>
        </div>
    </div>

</body>
</html>
