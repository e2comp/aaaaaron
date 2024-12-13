<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technology and Ethics</title>
    <style>
        body {
            background-color: #001f3f; /* Dark blue background */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #00509e; /* Lighter blue for header */
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #ffcc00;
        }
        header h1 {
            color: white;
            margin: 0;
            font-size: 24px;
            font-weight: bold; /* Bold text */
            text-transform: uppercase; /* All caps */
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .introduction {
            margin: 20px;
            padding: 20px;
            background: #ffffff; /* Light background */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            color: black;
        }
        .container {
            margin: 20px;
            padding: 20px;
            background: #ffffff; /* Light background for content */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            color: black; /* Black font color */
        }
        .blog-section {
            margin-bottom: 30px;
        }
        .decorative-line {
            height: 4px;
            background: linear-gradient(to right, #ffcc00, #ff6600);
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #00509e;
        }
        th, td {
            padding: 10px;
            text-align: center;
            background-color: #e6f0ff;
            color: black; /* Black font color in table */
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form select, form textarea, form button {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #00509e;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>E2 COMPUTER LAB EXERCISE</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Article</a>
            <a href="#">Blog</a>
            <a href="#">Form</a>
        </nav>
    </header>
    <!-- Introduction Section -->
    <div class="introduction">
        <h2>Welcome to Our Web Page!</h2>
        <p>We are excited to have you here. This webpage is designed to explore topics like technology, ethics, and their applications in real-world scenarios.</p>
        <p>Discover detailed insights into malware, viruses, and the importance of antivirus software. Dive into discussions about plagiarism, its consequences, and reported cases worldwide. Feel free to explore the blog, read articles, and provide your valuable feedback using the contact form below.</p>
    </div>
    <div class="container">
        <!-- Blog Section -->
        <div class="blog-section">
            <h2>Understanding Malware, Viruses, Spam, and Antiviruses</h2>
            <p>Malware, viruses, and spam are serious threats to technology and personal data. Malware refers to malicious software designed to harm devices, steal information, or spy on users. Viruses are a subset of malware that spread from one system to another, often via infected files. Spam refers to unsolicited messages, often promoting scams or harmful links.</p>
            <p>Antiviruses are programs designed to detect, prevent, and remove malicious software. It's essential to use antivirus software and keep it updated to protect against evolving threats.</p>
            <div class="decorative-line"></div>
        </div>
        <div class="blog-section">
            <h2>Plagiarism and its Consequences</h2>
            <p>Plagiarism, the act of using someone else's work without proper attribution, is a significant ethical violation. It undermines originality and intellectual property rights.</p>
            <p>Reported cases of plagiarism:</p>
            <table>
                <thead>
                    <tr>
                        <th>Case</th>
                        <th>Country</th>
                        <th>Punishment</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Academic Plagiarism</td>
                        <td>USA</td>
                        <td>Expulsion from institution</td>
                    </tr>
                    <tr>
                        <td>Copyright Violation</td>
                        <td>India</td>
                        <td>Fines and imprisonment</td>
                    </tr>
                    <tr>
                        <td>Plagiarized Article</td>
                        <td>UK</td>
                        <td>Public apology and lawsuit</td>
                    </tr>
                </tbody>
            </table>
            <p>The nature of punishment varies across countries based on intellectual property laws. For example, in the USA, plagiarism in academics can lead to expulsion, while in India, it may involve fines or imprisonment.</p>
            <div class="decorative-line"></div>
        </div>
        <!-- Embedded Media -->
        <h2>Media Section</h2>
        <img src="images (7).jpeg" alt="Sample Image" style="width: 100%; height: auto; border: 2px solid #00509e; margin-bottom: 10px;">
        <iframe width="100%" height="400" src="https://www.youtube.com/embed/ptHIA5bMnio" 
                title="YouTube video" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
        </iframe>
        <audio controls style="width: 100%; margin-bottom: 10px;">
            <source src="videoplayback (3).webm" type="audio/mp3">
            Your browser does not support the audio tag.
        </audio>
        <!-- Form Section -->
        <h2>Contact Form</h2>
        <form action="submit-form.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="feedback">Feedback:</label>
            <textarea id="feedback" name="feedback" rows="4" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
