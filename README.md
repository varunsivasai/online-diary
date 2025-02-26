<%@page language="java"%>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Document</title>
    <style>
        /* Basic styling for the body */
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #eceff0; /* Light blue background */
            flex-direction: column;
            text-align: center;
        }

        /* Style for the header */
        h1 {
            font-size: 36px;
            color: #333;
        }

        /* Style for the image inside a full circle */
        img {
            border-radius: 50%;
            width: 250px;  /* Increased size */
            height: 250px; /* Ensuring it's a perfect circle */
            object-fit: cover;
            margin-top: 20px;
        }

        /* Style for the button */
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #1085f3;
            color: white;
            border: none;
            border-radius: 5px;
            margin-top: 30px;
            transition: background-color 0.3s;
        }

        /* Hover effect for the button */
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div>
    <h1>Welcome to the online diary</h1>
    <img src="https://images.unsplash.com/photo-1605008423974-ad30a5d22125?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image">
    <form action="create">
        <button>Create Diary</button>
    </form>
    </div>
</body>
</html>
