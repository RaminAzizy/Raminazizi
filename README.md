<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            background-color: #111;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(255, 215, 0, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0px 6px 15px rgba(255, 215, 0, 0.7);
        }
        h1 {
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 2px solid gold;
            display: inline-block;
            padding-bottom: 5px;
        }
    </style>
</head>
<body>
    <h1>My Portfolio</h1>
    <div class="gallery">
        <img src="[2](https://github.com/user-attachments/assets/fae33624-b085-4360-a142-ec0637636c4d)" alt="Project 1">
        <img src="2.png" alt="Project 2">
        <img src="sample3.jpg" alt="Project 3">
        <img src="sample4.jpg" alt="Project 4">
    </div>
</body>
</html>
![2](https://github.com/user-attachments/assets/fae33624-b085-4360-a142-ec0637636c4d)
