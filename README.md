<!DOCTYPE html>
<html>
<head>
    <title>La Pasta Bella</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
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

        form input {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
        }

        button {
            background: orange;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
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
    <img src=<img width="275" height="183" alt="image" src="https://github.com/user-attachments/assets/513e36c0-e568-4d7c-8af7-6be9e625196b" />

</section>

<section>
    <h2>Menu</h2>
    <table>
        <tr>
            <th>Dish Name</th>
            <th>Price (₹)</th>
            <th>Category</th>
        </tr>
        <tr>
            <td>Dal</td>
            <td>200</td>
            <td>Veg</td>
        </tr>
        <tr>
            <td>Chawal</td>
            <td>250</td>
            <td>Veg</td>
        </tr>
        <tr>
            <td>Chapati</td>
            <td>200</td>
            <td>Veg</td>
        </tr>
        <tr>
            <td>Rice Special</td>
            <td>300</td>
            <td>Veg/Non-Veg</td>
        </tr>
        <tr>
            <td>Salad</td>
            <td>150</td>
            <td>Veg</td>
        </tr>
        <tr>
            <td>Sweet Dish</td>
            <td>500</td>
            <td>Veg</td>
        </tr>
    </table>
</section>

<section>
    <h2>Table Reservation</h2>
    <form>
        Name:<br>
        <input type="text" value="Maithali Yadav"><br>

        Contact:<br>
        <input type="text" value="2457887222"><br>

        Guests:<br>
        <input type="number" value="2557833128"><br>

        Date:<br>
        <input type="date" value="2025-04-12"><br>

        Time:<br>
        <input type="time" value="20:30"> to 
        <input type="time" value="12:20"><br><br>

        <button>Reserve Now</button>
    </form>
</section>

</body>
</html>
