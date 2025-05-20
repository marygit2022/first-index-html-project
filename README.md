Hello everyone
<!DOCTYPE html>
<html>
<head>
    <title>My Personal website</title>
    <style>
        body { 
            font-family: Tahoma; 
            background: #f0f8ff; 
            text-align: center; 
        }
        .header {
            color: #2c3e50;
            margin-top: 50px;
        }
        .menu {
            margin: 30px;
        }
        a {
            margin: 10px;
            text-decoration: none;
            color: #3498db;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Hi, it's Maryam</h1>
        <p> Welcome </p>
    </div>
    
    <div class="menu">
    <div class="slider">
    <img src="image1.jpg" id="slide" width="500">
    <button onclick="changeImage()">Next photo</button>
</div>

<script>
let images = ["image1.jpg", "image2.jpg", "image3.jpg"];
let current = 0;
function changeImage() {
    current = (current + 1) % images.length;
    document.getElementById("slide").src = images[current];
}
</script>
        <a href="#">خانه</a>
        <a href="#">درباره من</a>
        <a href="#">تماس</a>
    </div>
</body>
</html>
