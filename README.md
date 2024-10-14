<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tamwal Manufacturers - Khaki Bags</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #8b4513;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #a0522d;
            overflow: hidden;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }

        nav ul li {
            padding: 14px 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
        }

        .content {
            padding: 20px;
        }

        h2 {
            color: #8b4513;
        }

        .price-table {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 10px;
            margin-top: 20px;
        }

        .price-table div {
            padding: 10px;
            border: 1px solid #ccc;
            text-align: center;
            background-color: #fff;
        }

        .price-table .header {
            background-color: #8b4513;
            color: white;
            font-weight: bold;
        }

        footer {
            background-color: #8b4513;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        .contact-info, .social-media {
            margin-top: 20px;
        }

        .hidden {
            display: none;
        }

        textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .submit-button {
            background-color: #8b4513;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        .submit-button:hover {
            background-color: #a0522d;
        }

        .box {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        function showSection(sectionId) {
            document.querySelectorAll('.section').forEach(section => {
                section.classList.add('hidden');
            });
            document.getElementById(sectionId).classList.remove('hidden');
        }
    </script>
</head>
<body>

<header>
    <h1>Tamwal Manufacturers</h1>
    <p>Quality Khaki Bags</p>
</header>

<nav>
    <ul>
        <li><a onclick="showSection('dashboard')">Dashboard</a></li>
        <li><a onclick="showSection('comments')">Comments Section</a></li>
        <li><a onclick="showSection('feedback')">Feedback Section</a></li>
        <li><a onclick="showSection('location')">Location Info</a></li>
    </ul>
</nav>

<div class="content">
    <div id="dashboard" class="section">
        <h2>Our Products</h2>
        <h3>Bora (Pure Brown)</h3>
        <div class="price-table">
            <div class="header">Size</div>
            <div class="header">Price per Bale</div>
            <div class="header">No. of Pieces</div>
            <div class="header">No. of Packets</div>
            
            <div>No. 1/2</div>
            <div>Ksh 3200.00</div>
            <div>2500</div>
            <div>50</div>

            <div>No. 1</div>
            <div>Ksh 3200.00</div>
            <div>2000</div>
            <div>40</div>

            <div>No. 2</div>
            <div>Ksh 3050.00</div>
            <div>1500</div>
            <div>30</div>
        </div>

        <h3>Sawaa (Recycled Brown)</h3>
        <div class="price-table">
            <div class="header">Size</div>
            <div class="header">Price per Bale</div>
            <div class="header">No. of Pieces</div>
            <div class="header">No. of Packets</div>
            
            <div>No. 1/2</div>
            <div>Ksh 2500.00</div>
            <div>2500</div>
            <div>50</div>

            <div>No. 1</div>
            <div>Ksh 2500.00</div>
            <div>2000</div>
            <div>40</div>

            <div>No. 2</div>
            <div>Ksh 2400.00</div>
            <div>1500</div>
            <div>30</div>
        </div>
    </div>

    <div id="comments" class="section hidden">
        <h2>Comments Section</h2>
        <div class="box">
            <h3>Leave a Comment</h3>
            <textarea placeholder="Write your comment here..." rows="4"></textarea>
            <button class="submit-button">Submit Comment</button>
        </div>
    </div>

    <div id="feedback" class="section hidden">
        <h2>Feedback Section</h2>
        <div class="box">
            <h3>Leave Your Feedback</h3>
            <textarea placeholder="Write your feedback here..." rows="4"></textarea>
            <button class="submit-button">Submit Feedback</button>
        </div>
    </div>

    <div id="location" class="section hidden">
        <h2>Location Information</h2>
        <p>Use our live location feature to find us!</p>
        <!-- You can integrate Google Maps API here to provide live location info -->
    </div>

    <div class="contact-info">
        <h3>Contact Information</h3>
        <p>Email: <a href="mailto:borasawaa@gmail.com">borasawaa@gmail.com</a></p>
        <p>Office Cell: 0724178698 / +254724820737</p>
    </div>

    <div class="social-media">
        <h3>Follow Us</h3>
        <p>Instagram: <a href="https://instagram.com/pooh_Mooler" target="_blank">@pooh_Mooler</a></p>
        <p>Twitter: <a href="https://twitter.com/pooh_Mooler" target="_blank">@pooh_Mooler</a></p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Tamwal Manufacturers - All Rights Reserved</p>
</footer>

</body>
</html>
