<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Banner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="banner">
        <a href="https://github.com/your-username" class="banner-link">
            <img src="github-logo.png" alt="GitHub Logo" class="github-logo">
            <span class="banner-text">Check out my GitHub</span>
        </a>
    </div>
</body>
</html>

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

.banner {
    background-color: #24292e;
    color: white;
    text-align: center;
    padding: 20px 0;
}

.banner-link {
    text-decoration: none;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
}

.github-logo {
    width: 40px;
    height: 40px;
    margin-right: 10px;
}

.banner-text {
    font-size: 1.5em;
}

.banner-link:hover {
    color: #0366d6; /* GitHub blue */
}
