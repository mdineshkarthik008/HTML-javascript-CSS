# HTML-javascript-CSS
Ideas that can boost fitness activities and assist in keeping fit.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FITTNESS AND SPORTS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 400px;
            text-align: center;
        }

        h2 {
            color: #333333;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-top: 10px;
        }

        input {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            box-sizing: border-box;
        }

        button {
            background-color: #61af4c;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #51a045;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>FITTNES AND SPORTS</h2>
        <form action="your_booking_handler.php" method="post">

            <label for="event-name">FITTNESS TYPE:</label>
            <select id="event-name" name="event-name">
                <option value="for-birthday">EXERCISE</option>
                <option value="for-wedding">WEIGHT LOSS</option>
                <option value="for-concerts">WEIGHT GAIN</option>
                <option value="for-other">SIX PACK</option>
            </select>

            <label for="ticket-type">SLOT:</label>
            <select id="ticket-type" name="SLOT-TIMMING">
                <option value="general">6:00AM-8:00AM</option>
                <option value="vip">8:00PM-10:00PM</option>

            </select>

           
            

            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name">

            <label for="phone-number">Phone Number:</label>
            <input type="text" id="phone-number" name="phone-number">

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email">

            <button><a href="submit.html">Book THE SLOT</a></button>
            
        </form>
    </div>
</body>
</html>
