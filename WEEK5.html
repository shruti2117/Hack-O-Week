<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>WanderWorld - Travel Blog</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:linear-gradient(120deg,#f6f9fc,#e9eff5);
}


nav{
    background:#222;
    padding:10px 0;
    position:sticky;
    top:0;
}

nav ul{
    list-style:none;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}

nav ul li{
    margin:0 15px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-size:16px;
}

nav ul li a:hover{
    color:#00c6ff;
}


.hero{
    height:60vh;
    background:url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee') no-repeat center center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero h1{
    font-size:45px;
    text-shadow:2px 2px 10px black;
}


section{
    padding:60px 8%;
}

h2{
    text-align:center;
    margin-bottom:25px;
    font-size:28px;
    color:#333;
}


.blog-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.card-content h3{
    color:#0077b6;
    margin-bottom:5px;
}

.meta{
    font-size:12px;
    color:gray;
    margin-bottom:10px;
}

.delete-btn{
    background:#e63946;
    color:white;
    border:none;
    padding:6px 12px;
    border-radius:15px;
    cursor:pointer;
    margin-top:10px;
}

.delete-btn:hover{
    background:#b00020;
}

/
.blog-form{
    background:white;
    padding:20px;
    border-radius:12px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    margin-bottom:30px;
}

.blog-form input,
.blog-form textarea{
    width:100%;
    padding:10px;
    margin:8px 0;
    border-radius:8px;
    border:1px solid #ccc;
}

.blog-form button{
    background:#0077b6;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:20px;
    cursor:pointer;
}

.blog-form button:hover{
    background:#023e8a;
}


iframe{
    width:100%;
    height:250px;
    border-radius:12px;
    margin-bottom:20px;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#blog">Destinations</a></li>
<li><a href="#myblog">My Blog</a></li>
<li><a href="#map">Maps</a></li>
</ul>
</nav>

<section class="hero" id="home">
<div>
<h1>WanderWorld 🌍</h1>
<p>Travel Smart. Travel Light.</p>
</div>
</section>

<!-- Top Destinations (WITH IMAGES KEPT) -->
<section id="blog">
<h2>Top Destinations</h2>
<div class="blog-container">

<div class="card">
<img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470">
<div class="card-content">
<h3>Swiss Alps</h3>
<p>Snow peaks & scenic trails.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1526772662000-3f88f10405ff">
<div class="card-content">
<h3>Bali Beaches</h3>
<p>Sunsets & tropical vibes.</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1505761671935-60b3a7427bad">
<div class="card-content">
<h3>Paris Lights</h3>
<p>Romantic city views.</p>
</div>
</div>

</div>
</section>

<!-- Detailed Blog Section -->
<section id="myblog">
<h2>Share Your Travel Experience</h2>

<div class="blog-form">
<input type="text" id="title" placeholder="Blog Title">
<input type="text" id="location" placeholder="Location">
<input type="text" id="image" placeholder="Image URL (paste image link)">
<textarea id="content" rows="4" placeholder="Write detailed travel experience..."></textarea>
<button onclick="addBlog()">Publish Blog</button>
</div>

<div class="blog-container" id="blogList"></div>

</section>

<section id="map">
<h2>Quick Maps</h2>
<iframe src="https://www.google.com/maps?q=48.8566,2.3522&hl=en&z=11&output=embed"></iframe>
<iframe src="https://www.google.com/maps?q=-8.409518,115.188919&hl=en&z=10&output=embed"></iframe>
</section>

<footer>
<p>2026 WanderWorld ✈ Premium Edition</p>
</footer>

<script>
document.addEventListener("DOMContentLoaded", loadBlogs);

function addBlog(){
    const title = document.getElementById("title").value;
    const location = document.getElementById("location").value;
    const image = document.getElementById("image").value;
    const content = document.getElementById("content").value;
    const date = new Date().toLocaleString();

    if(title === "" || location === "" || image === "" || content === ""){
        alert("Please fill all fields!");
        return;
    }

    const blog = {title, location, image, content, date};
    let blogs = JSON.parse(localStorage.getItem("blogs")) || [];
    blogs.push(blog);
    localStorage.setItem("blogs", JSON.stringify(blogs));

    document.querySelectorAll(".blog-form input, .blog-form textarea")
        .forEach(el => el.value = "");

    loadBlogs();
}

function loadBlogs(){
    const blogList = document.getElementById("blogList");
    blogList.innerHTML = "";
    let blogs = JSON.parse(localStorage.getItem("blogs")) || [];

    blogs.forEach((blog,index)=>{
        const div = document.createElement("div");
        div.classList.add("card");
        div.innerHTML = `
            <img src="${blog.image}">
            <div class="card-content">
                <h3>${blog.title}</h3>
                <div class="meta">📍 ${blog.location} | 🗓 ${blog.date}</div>
                <p>${blog.content}</p>
                <button class="delete-btn" onclick="deleteBlog(${index})">Delete</button>
            </div>
        `;
        blogList.appendChild(div);
    });
}

function deleteBlog(index){
    let blogs = JSON.parse(localStorage.getItem("blogs")) || [];
    blogs.splice(index,1);
    localStorage.setItem("blogs",JSON.stringify(blogs));
    loadBlogs();
}
</script>

</body>
</html>
