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
        .project {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(255, 215, 0, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project:hover {
            transform: scale(1.05);
            box-shadow: 0px 6px 15px rgba(255, 215, 0, 0.7);
        }
        .project img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .project-title {
            font-size: 1.2em;
            margin-top: 10px;
            font-weight: bold;
        }
        .project-description {
            display: none;
            position: absolute;
            bottom: 0;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            width: 100%;
            padding: 10px;
            text-align: center;
            font-size: 0.9em;
        }
        .project:hover .project-description {
            display: block;
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
        <div class="project">
            <img src="2.png" alt="Project 1">
            <div class="project-title">Project 1</div>
            <div class="project-description">Description of Project 1</div>
        </div>
        <div class="project">
            <img src="sample2.jpg" alt="Project 2">
            <div class="project-title">Project 2</div>
            <div class="project-description">Description of Project 2</div>
        </div>
        <div class="project">
            <img src="sample3.jpg" alt="Project 3">
            <div class="project-title">Project 3</div>
            <div class="project-description">Description of Project 3</div>
        </div>
        <div class="project">
            <img src="sample4.jpg" alt="Project 4">
            <div class="project-title">Project 4</div>
            <div class="project-description">Description of Project 4</div>
        </div>
        <div class="project">
            <img src="sample5.jpg" alt="Project 5">
            <div class="project-title">Project 5</div>
            <div class="project-description">Description of Project 5</div>
        </div>
        <div class="project">
            <img src="sample6.jpg" alt="Project 6">
            <div class="project-title">Project 6</div>
            <div class="project-description">Description of Project 6</div>
        </div>
        <div class="project">
            <img src="sample7.jpg" alt="Project 7">
            <div class="project-title">Project 7</div>
            <div class="project-description">Description of Project 7</div>
        </div>
        <div class="project">
            <img src="sample8.jpg" alt="Project 8">
            <div class="project-title">Project 8</div>
            <div class="project-description">Description of Project 8</div>
        </div>
    </div>
</body>
</html>
