/* Reset and base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', sans-serif;
}

body {
  background-color: #faf8f6;
  color: #333;
  line-height: 1.6;
}

/* Top banner */
.top-banner {
  background-color: #e0d4ca;
  text-align: center;
  padding: 10px;
  font-size: 0.9rem;
  color: #444;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 10%;
  background: #fff;
  border-bottom: 1px solid #e5e5e5;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.navbar .logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #aa8273;
}

.navbar ul {
  display: flex;
  list-style: none;
}

.navbar li {
  margin-left: 20px;
}

.navbar a {
  text-decoration: none;
  color: #555;
  font-weight: 500;
}

/* Hero Section */
.hero {
  background: url('hero.jpg') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.hero input[type="text"] {
  padding: 10px;
  width: 60%;
  max-width: 400px;
  border: none;
  border-radius: 5px;
}

/* Categories */
.categories {
  text-align: center;
  padding: 60px 10% 40px;
  background-color: #fff8f4;
}

.categories h2 {
  font-size: 2rem;
  margin-bottom: 40px;
  color: #aa8273;
}

.category-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 30px;
}

.category-card {
  background-color: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  font-weight: bold;
  color: #aa8273;
  cursor: pointer;
  transition: transform 0.3s ease;
}

.category-card:hover {
  transform: translateY(-5px);
}

/* Before and After */
.before-after {
  text-align: center;
  padding: 60px 10%;
  background-color: #fefefe;
}

.before-after h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

/* Social */
.social {
  text-align: center;
  padding: 40px;
  background: #fff8f4;
}

.social a {
  font-size: 1.5rem;
  margin: 0 10px;
  color: #aa8273;
}

/* Footer */
footer {
  background-color: #f3f3f3;
  padding: 40px 10%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  color: #555;
}

.footer-info {
  flex: 1 1 300px;
  margin-bottom: 20px;
}

.newsletter input {
  padding: 10px;
  margin-right: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.newsletter button {
  padding: 10px 20px;
  background-color: #aa8273;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

/* WhatsApp Floating Button */
.whatsapp-button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #25d366;
  color: white;
  font-size: 24px;
  padding: 15px;
  border-radius: 50%;
  z-index: 100;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}
lign-items: center;
    text-decoration: none;
    font-size: 24px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}
