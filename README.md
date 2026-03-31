

<!DOCTYPE html>
<html>
<head>
    <title>La Pasta Bella</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url('https://images.unsplash.com/photo-1414235077428-338989a2e8c0');
            background-size: cover;
            background-repeat: no-repeat;
            color: white;
        }

        header {
            background: rgba(0,0,0,0.7);
            padding: 20px;
            text-align: center;
            font-size: 30px;
        }

        section {
            background: rgba(0,0,0,0.6);
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            color: black;
        }

        th, td {
            padding: 10px;
            border: 1px solid black;
            text-align: center;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        form label {
            display: block;
            margin-top: 10px;
        }

        form input {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        button {
            background: orange;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            margin-top: 15px;
            border-radius: 5px;
        }

        button:hover {
            background: darkorange;
            transition: 0.3s;
        }

        img {
            width: 100%;
            border-radius: 10px;
        }
    </style>
</head>

<body>

<header>
    🍽️ Welcome to La Pasta Bella 🍽️
</header>

<section>
    <h2>Restaurant Image</h2>
    <img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/3d5714f0-953d-4309-9476-6714c85e8677" />
</section>

<section>
    <h2>Menu</h2>
    <table>
        <tr>
            <th>Dish Name</th>
            <th>Price (₹)</th>
            <th>Category</th>
        </tr>
        <tr><td>Dal</td><td>200</td><td>Veg</td></tr>
        <tr><td>Chawal</td><td>250</td><td>Veg</td></tr>
        <tr><td>Chapati</td><td>200</td><td>Veg</td></tr>
        <tr><td>Rice Special</td><td>300</td><td>Veg/Non-Veg</td></tr>
        <tr><td>Salad</td><td>150</td><td>Veg</td></tr>
        <tr><td>Sweet Dish</td><td>500</td><td>Veg</td></tr>
    </table>
</section>

<section>
    <h2>Table Reservation</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" value="Maithali Yadav">

        <label for="contact">Contact:</label>
        <input type="text" id="contact" value="2457887222">

        <label for="guests">Guests:</label>
        <input type="number" id="guests" min="1" max="20" value="2">

        <label for="date">Date:</label>
        <input type="date" id="date" value="2025-04-12">

        <label for="time">Time:</label>
        <input type="time" id="time" value="20:30">

        <button type="submit">Reserve Now</button>
    </form>
</section>

</body>
</html>

