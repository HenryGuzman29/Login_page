<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guzman</title>
    <style>
        /* Reset basic margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styles */
        body {
            background-color: aqua;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        /* Form container */
        .form-container {
            background-color: rgb(230, 176, 226);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px; /* Limita el tamaño del formulario */
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
            font-size: 2rem;
            color: blue;
        }

        /* Style for the labels */
        label {
            display: block;
            margin-bottom: 8px;
            font-size: 1rem;
            color: blueviolet;
        }

        /* Input fields */
        input {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 2px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
            outline: none;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
        }

        /* Focus state for inputs */
        input:focus {
            border-color: #007bff;
            box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
        }

        /* Button style */
        button {
            width: 100%;
            padding: 12px;
            border: 2px solid #007bff;
            border-radius: 4px;
            background-color: #007bff;
            color: white;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease, border-color 0.3s ease;
        }

        /* Button hover effect */
        button:hover {
            background-color: #0056b3;
            border-color: #0056b3;
        }
        
    </style>
</head>
<body>
    <div class="form-container">
        <h1>Login-Page</h1>
        <form>
            <div class="user">
                <label for="username">Username</label>
                <input type="text" name="username" id="username" placeholder="Enter your username" required>
            </div>
            <div class="pass">
                <label for="password">Password</label>
                <input type="password" name="password" id="password" placeholder="Enter your password" required>
            </div>
            <button type="submit">Iniciar Sesion</button>
        </form>
    </div>
</body>
</html>
