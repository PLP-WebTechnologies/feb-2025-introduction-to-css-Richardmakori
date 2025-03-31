      HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mytravels</title>
    <link rel="stylesheet" href="alternative_style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Roboto+Slab:wght@300&family=Space+Mono&display=swap" rel="stylesheet">
</head>
<body>
    <div id="page-container">
        <nav id="main-nav">
            <ul class="nav-list">
                <li class="nav-item">Home</li>
                <li class="nav-item">About</li>
                <li class="nav-item active">Services</li>
                <li class="nav-item">Contact</li>
            </ul>
        </nav>

        <main class="content-area">
            <article class="featured-post">
                <h1 class="post-title">Lets travel Together</h1>
                <img src="https://source.unsplash.com/random/800x400/?nature" alt="Nature" class="featured-image">
                <p class="post-excerpt">Discover the breathtaking beauty of our planet's diverse ecosystems and landscapes through this photographic journey.</p>
                <div class="post-meta">Posted on <span class="meta-date">march 31, 2025</span></div>
            </article>

            <aside class="sidebar">
                <div class="widget" id="popular-widget">
                    <h3 class="widget-title">Popular Posts</h3>
                    <ul class="widget-list">
                        <li>Mountain Adventures</li>
                        <li>Ocean Depths</li>
                        <li>Forest Trails</li>
                    </ul>
                </div>
            </aside>
        </main>

        <footer id="page-footer">
            <p class="copyright">&copy; 2025 Richard Makori</p>
        </footer>
    </div>
</body>
</html>

     CSS CODE
 /* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #f5f7fa;
    color: #333;
    line-height: 1.6;
}

/* ID Selectors */
#page-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

#main-nav {
    background-color: #2a3f54;
    padding: 15px 0;
    border-bottom: 4px solid #e67e22;
}

#page-footer {
    background-color: #2a3f54;
    padding: 20px;
    margin-top: 30px;
    border-top: 3px dashed #e67e22;
}

#popular-widget {
    background-color: #fff;
    border-left: 5px solid #e67e22;
}

/* Class Selectors */
.nav-list {
    display: flex;
    justify-content: center;
    list-style: none;
}

.nav-item {
    color: #ecf0f1;
    font-family: 'Space Mono', monospace;
    padding: 0 20px;
    margin: 0 10px;
    border-right: 1px solid #4e6d8c;
}

.nav-item.active {
    color: #e67e22;
    font-weight: bold;
}

.content-area {
    display: flex;
    margin: 30px 0;
    gap: 30px;
}

.featured-post {
    flex: 2;
    background-color: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

.post-title {
    font-family: 'Montserrat', sans-serif;
    color: #2a3f54;
    margin-bottom: 15px;
    font-size: 2rem;
    border-bottom: 2px dotted #e67e22;
    padding-bottom: 10px;
}

.post-excerpt {
    font-family: 'Roboto Slab', serif;
    color: #555;
    margin: 20px 0;
    line-height: 1.8;
    padding: 0 10px;
}

.featured-image {
    width: 100%;
    height: auto;
    border: 3px solid #ddd;
    border-radius: 5px;
    margin: 15px 0;
    transition: transform 0.3s ease;
}

.featured-image:hover {
    transform: scale(1.02);
    border-color: #e67e22;
}

.sidebar {
    flex: 1;
}

.widget {
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
}

.widget-title {
    font-family: 'Montserrat', sans-serif;
    color: #2a3f54;
    margin-bottom: 15px;
    font-size: 1.2rem;
}

.copyright {
    color: #ecf0f1;
    text-align: center;
    font-family: 'Space Mono', monospace;
}

/* Additional Styles */
.meta-date {
    color: #e67e22;
    font-weight: bold;
}

.widget-list {
    list-style-position: inside;
    font-family: 'Roboto Slab', serif;
}

.widget-list li {
    padding: 8px 0;
    border-bottom: 1px solid #eee;
}
