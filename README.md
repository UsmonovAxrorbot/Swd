/* Umumiy sahifa stili */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f0f4f8;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background: linear-gradient(90deg, #4CAF50, #2E8B57);
    color: white;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

/* Navigatsiya menyusi */
nav {
    background-color: #333;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

nav ul li {
    margin: 5px 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 10px 15px;
    display: block;
    border-radius: 5px;
    transition: 0.3s;
}

nav ul li a:hover {
    background-color: #4CAF50;
}

/* Main kontent */
main {
    max-width: 900px;
    margin: 20px auto;
    padding: 25px;
    background-color: white;
    box-shadow: 0 0 15px rgba(0,0,0,0.1);
    border-radius: 10px;
}

/* Sarlavhalar */
h1, h2, h3 {
    color: #2E8B57;
    margin-bottom: 15px;
    text-align: center;
}

/* Paragraflar */
p {
    margin-bottom: 15px;
    color: #555;
    font-size: 1rem;
}

/* Footer */
footer {
    background-color: #2E8B57;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 20px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}

/* Responsive dizayn */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        text-align: center;
    }

    main {
        margin: 15px;
        padding: 20px;
    }
}
