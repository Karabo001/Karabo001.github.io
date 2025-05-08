/* styles.css */
body {
    margin: 0;
    font-family: 'Helvetica Neue', sans-serif;
    background-color: #fffaf9;
    color: #333;
}

.top-bar {
    background-color: #f6e8e0;
    color: #7a5c51;
    text-align: center;
    padding: 8px 0;
    font-size: 14px;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff;
    padding: 20px;
    border-bottom: 1px solid #eee;
    position: sticky;
    top: 0;
    z-index: 999;
}

.navbar .logo {
    font-size: 24px;
    font-weight: bold;
    color: #b88976;
}

.navbar nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

.navbar nav a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

.hero {
    background-image: url('your-hero-image.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.hero input {
    padding: 10px;
    width: 250px;
    border: none;
    border-radius: 5px;
}

.categories {
    text-align: center;
    padding: 60px 20px;
    background-color: #fdf7f2;
}

.categories h2 {
    font-size: 28px;
    margin-bottom: 30px;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    max-width: 1000px;
    margin: 0 auto;
}

.category-card {
    background-color: #fff;
    padding: 40px 20px;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    font-weight: bold;
    color: #7a5c51;
}

.blog-preview {
    padding: 60px 20px;
    background-color: #fff;
    text-align: center;
}

.blog-preview h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.blog-highlight {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    align-items: center;
    margin-top: 30px;
}

.blog-image {
    background-image: url('your-blog-image.jpg');
    background-size: cover;
    background-position: center;
    width: 300px;
    height: 200px;
    border-radius: 10px;
}

.blog-text {
    max-width: 300px;
    text-align: left;
}

.blog-text h3 {
    margin-bottom: 10px;
    font-size: 20px;
    color: #b88976;
}

.blog-text button {
    background-color: #b88976;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background-color: #f6e8e0;
    padding: 40px 20px;
    text-align: center;
}

.footer-info p {
    margin: 10px 0;
    color: #7a5c51;
}

.social-media a {
    color: #7a5c51;
    margin: 0 10px;
    font-size: 20px;
}

.newsletter input[type="email"] {
    padding: 10px;
    border: none;
    border-radius: 5px;
    width: 200px;
    margin-top: 10px;
}

.newsletter button {
    background-color: #b88976;
    color: white;
    padding: 10px 20px;
    margin-left: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.whatsapp-button {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #25D366;
    color: white;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    font-size: 24px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}
