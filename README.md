<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            font-weight: bold;
            margin: 0;
            padding: 0;
            background-color: #718e97;
        }
        nav {
            background-color: #6a828a;
            padding: 10px;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .menu-content {
            background-color: #6D1865;
            color: white;
            padding: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        main {
            padding: 20px;
        }
        .video-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }
        .video-container h2 {
            color: #2c3e50;
        }
        .wistia_embed {
            width: 80%;
            max-width: 800px;
            margin-bottom: 20px;
        }
        .login-container {
            background-color: #ffffff;
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 500px;
            text-align: center;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            display: block;
        }
        .login-container.active {
            display: block;
        }
        h1 {
            margin-bottom: 1.5rem;
            font-size: 2rem;
            color: #333;
        }
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #555;
        }
        input {
            width: 100%;
            padding: 0.75rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 6px;
            box-sizing: border-box;
            font-size: 1rem;
            color: #333;
        }
        button {
            width: 100%;
            padding: 0.75rem;
            background-color: #007bff; /* Change this to your preferred color */
            color: #fff;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 1.1rem;
            font-weight: bold;
        }
        button:hover {
            background-color: #0056b3; /* Change this for the hover effect */
        }
        .error {
            color: red;
            margin-top: 1rem;
        }
        .hidden {
            display: none;
        }
        .welcome-message {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .videos-button {
            color: #6D1865;
            background-color: #2c3e50; /* Dark color for the button */
            padding: 5px 15px;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .videos-button:hover {
            background-color: #1a252f; /* Slightly darker on hover */
        }
    </style>
</head>
<body>
    <nav id="nav">
        <ul>
        </ul>
    </nav>
    
    <main id="main" style="display:none;">
        <section id="home">
            <div style="text-align: center; padding: 20px; border-radius: 8px;">
                <img src="https://i.ibb.co/59zvgNq/image-removebg-preview-6-removebg-preview-1.png" alt="The Process Platform Image" style="width: 100%; max-width: 400px; margin-bottom: 20px;">
                <h2 style="color: white;">The Process Platform</h2>
            </div>
        </section>

        <section id="videos" class="video-container">
<select id="videoSelector" style="padding: 10px; font-size: 16px; background-color: #3A5795; color: white; border: none;">
            <option value="video0">.....option.....</option>
                <option value="video1">Faraday rule and lenz </option>
                <option value="video2">Induced emf in straight wire</option>
                <option value="video3">Mutual Induction</option>
                <option value="video4">Self induction</option>
                <option value="video5">Dynamo </option>
                <option value="video6">Transformer </option>
                <option value="video7">Motor </option>
              

                <option value="video8">Lecture 1 exercises</option>
                <option value="video9">Lecture 2 exercises</option>
                <option value="video10">Lecture 3 exercises</option>
                <option value="video11">Lecture 4 exercises</option>
                            </select>
            
            
            
            <div class="video" id="video1" style="display: none;">
                <h1 class="video-title">Faraday rule and lenz</h1>
<iframe src="https://drive.google.com/file/d/1CO-KACGNBJN_B5XQjG4hymadfe2qQCuK/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video2" style="display: none;">
                <h1 class="video-title">Induced emf in straight wire</h1>
<iframe src="https://drive.google.com/file/d/1IgK0AzHmdPveba0dS6G-w3oB9KzIwtAz/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video3" style="display: none;">
                <h1 class="video-title">Mutual Induction</h1>
<iframe src="https://drive.google.com/file/d/1ZOkxgRwNktqEU01ArtPCdGPtI0_DTfhf/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video4" style="display: none;">
                <h1 class="video-title">Self induction</h1>
<iframe src="https://drive.google.com/file/d/1JBvRufHVy54Fdti4Qebfxk8FxeUEJuXd/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video5" style="display: none;">
                <h1 class="video-title">Dynamo</h1>
<iframe src="https://drive.google.com/file/d/1bNTVPDdRFlbivMj4w5Bme--D-1hmDDZB/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video6" style="display: none;">
                <h1 class="video-title">Transformer</h1>
<iframe src="https://drive.google.com/file/d/10TxqnXvRF9liW7nXWVZ9E6Jt8hlC1A1h/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video7" style="display: none;">
                <h1 class="video-title">Motor</h1>
<iframe src="https://drive.google.com/file/d/1bcCGuVSG-FFeqRpxtdbAruL3e7kUUBPY/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>
<div class="video" id="video8" style="display: none;">
                <h1 class="video-title">Lecture 1 exercises</h1>
                <h1 class="video-title">part 1</h1>
<iframe src="https://drive.google.com/file/d/1BLVKeHRyPq8fDLbcKJi0bakUYSjlJWY9/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
                <h1 class="video-title">part 2</h1>
<iframe src="https://drive.google.com/file/d/1Xn6LxprOv8HdTgjeSPmvndy7KFOgK_pB/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>
<div class="video" id="video9" style="display: none;">
                <h1 class="video-title">Lecture 2 exercises</h1>
<iframe src="https://drive.google.com/file/d/1lPQUGCqKjVid1Cphn_TVEy9cBvehHCEm/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video10" style="display: none;">
                <h1 class="video-title">Lecture 3 exercises</h1>
                                <h1 class="video-title">part 1</h1>
<iframe src="https://drive.google.com/file/d/1oE4TZc0kejYkzQV_MLB7qentyafUeQ7-/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
                <h1 class="video-title">part 2</h1>
<iframe src="https://drive.google.com/file/d/1-Vu8Pq-tr_u86f5VzVJkcQfAXSAP6SZw/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>

<div class="video" id="video11" style="display: none;">
                <h1 class="video-title">Lecture 4 exercises</h1>
<iframe src="https://drive.google.com/file/d/1HG7iTWDu2r6681Q1akj0qNzCm12k8g1X/preview" width="640" height="480" allow="autoplay" allowfullscreen></iframe>
            </div>


        </section>
        
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or need further information, feel free to contact us at <a href="mailto:info@educationwebsite.com">mamrro8529@gmail.com</a>.</p>
            <div class="social-icons">
                <a href="https://wa.me/message/5LRM2DVHPZQFM1" target="_blank">
                    <img src="https://img.icons8.com/fluent/48/000000/whatsapp.png" alt="WhatsApp" />
                </a>
                <a href="https://www.facebook.com/mamro8529?mibextid=ZbWKwL" target="_blank">
                    <img src="https://img.icons8.com/fluent/48/000000/facebook-new.png" alt="Facebook" />
                </a>
                <a href="http://t.me/Mora_mo1" target="_blank">
                    <img src="https://img.icons8.com/fluent/48/000000/telegram-app.png" alt="Telegram" />
                </a>
                <p>Developed by Eng: Amr Mohamed</p>
            </div>
        </section>
    </main>

    <div class="login-container" id="loginContainer">
        <img src="https://i.ibb.co/nmgZDmT/Whats-App-Image-2024-09-04-at-15-05-46-removebg-preview.png" alt="Login Image" style="width: 60%; max-width: 300px; margin-bottom: 20px;">
        <h1>Login to The Process platform</h1>
        <form id="loginForm">
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>
            <button type="submit">Login</button>
            <div id="errorMessage" class="error"></div>
        </form>
        <p>Developed by Eng: Amr Mohamed</p>
    </div>

<script>
document.addEventListener('DOMContentLoaded', function () {
    const loginContainer = document.getElementById('loginContainer');
    const mainContent = document.getElementById('main');
    const videoSelector = document.getElementById('videoSelector');
    const video1 = document.getElementById('video1');
    const video2 = document.getElementById('video2');

    function showLogin() {
        loginContainer.style.display = 'block';
        mainContent.style.display = 'none';
    }

    function showMainContent() {
        loginContainer.style.display = 'none';
        mainContent.style.display = 'block';
    }

    document.getElementById('loginForm').addEventListener('submit', function (event) {
        event.preventDefault();

        const username = document.getElementById('username').value.trim();
        const errorMessage = document.getElementById('errorMessage');

        // List of valid usernames
        const validUsernames = [
            '45454', '0' ,'92777', '37501', '97485', '90990',
'68199', '76459', '12530', '67168',
'11105', '91748', '45645', '42781',
'84862', '73863', '52481', '27718',
'23996', '22713', '85718', '28951',
'36109', '14409', '11723', '84785',
'96488', '10559', '58453', '62311',
'53593', '32607', '95387', '33866',
'12346', '70725', '90673', '65499',
'48656', '14890', '56922', '90165',
'59160', '51359', '17306', '19957',
'40231', '49313', '27344', '25664',
'82880', '26583', '75100', '89249',
'34216', '13139', '41456', '99585'

        ];

        // Validate username
        if (validUsernames.includes(username)) {
            errorMessage.textContent = '';
            showMainContent();
        } else {
            errorMessage.textContent = 'Invalid username';
        }
    });

    // Video selection handler
    videoSelector.addEventListener('change', function() {
    // Hide all videos initially
    for (let i = 1; i <= 17; i++) {
        let video = document.getElementById('video' + i);
        if (video) {
            video.style.display = 'none';
        }
    }

    // Show the selected video
    let selectedVideo = videoSelector.value;
    let videoToShow = document.getElementById(selectedVideo);
    if (videoToShow) {
        videoToShow.style.display = 'block';
    }
});


    showLogin();
});
</script>

