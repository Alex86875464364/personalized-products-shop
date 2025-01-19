body {
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(90deg, #4CAF50, #81C784);
    color: white;
    padding: 1rem 2rem;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

header .logo {
    font-size: 1.8rem;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    margin: 0;
    padding: 0;
}

header nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: 500;
    transition: color 0.3s ease;
}

header nav ul li a:hover {
    color: #FFEB3B;
}

.hero {
    text-align: center;
    padding: 4rem 2rem;
    background: url('hero-bg.jpg') no-repeat center center/cover;
    color: white;
    box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

.hero p {
    font-size: 1.4rem;
    margin-bottom: 2rem;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
}

.hero .btn {
    padding: 0.8rem 1.5rem;
    background: #FF5722;
    color: white;
    text-decoration: none;
    border-radius: 50px;
    transition: all 0.3s ease;
    font-weight: bold;
}

.hero .btn:hover {
    background: #E64A19;
    transform: scale(1.1);
}

.products {
    padding: 2rem;
    text-align: center;
    background: #fff;
    border-top: 5px solid #4CAF50;
}

.products h2 {
    margin-bottom: 1.5rem;
    font-size: 2rem;
    color: #4CAF50;
}

.product-list {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.product {
    background: linear-gradient(135deg, #f9f9f9, #f1f1f1);
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 10px;
    width: 300px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.product img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 1rem;
}

.about, .contact {
    padding: 2rem;
    text-align: center;
    background: #f1f1f1;
    border-top: 5px solid #4CAF50;
}

.about h2, .contact h2 {
    margin-bottom: 1.5rem;
    font-size: 2rem;
    color: #4CAF50;
}

.contact form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 400px;
    margin: 0 auto;
    padding: 1rem;
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.contact input, .contact textarea, .contact button {
    padding: 0.8rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

.contact button {
    background: #4CAF50;
    color: white;
    cursor: pointer;
    transition: background 0.3s ease, transform 0.3s ease;
    font-weight: bold;
}

.contact button:hover {
    background: #388E3C;
    transform: scale(1.05);
}

footer {
    text-align: center;
    padding: 1rem;
    background: #4CAF50;
    color: white;
    margin-top: 2rem;
    font-size: 0.9rem;
    border-top: 5px solid #81C784;
}
