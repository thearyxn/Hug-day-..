# Hug-day-..
body {
    font-family: 'Arial', sans-serif;
    text-align: center;
    background-color: #ffebf0;
    margin: 0;
    padding: 20px;
}

.container {
    margin-top: 50px;
}

h1 {
    color: #d63384;
    font-size: 2.5rem;
}

.message {
    font-size: 1.2rem;
    color: #444;
}

.hug-container {
    position: relative;
    width: 200px;
    height: 200px;
    margin: 40px auto;
}

.character {
    position: absolute;
    width: 80px;
    height: 120px;
    background-color: #ff6b81;
    border-radius: 40px;
    top: 40px;
}

.left {
    left: 10px;
    animation: hug-left 2s infinite alternate;
}

.right {
    right: 10px;
    animation: hug-right 2s infinite alternate;
}

@keyframes hug-left {
    0% { transform: rotate(0deg); }
    100% { transform: translateX(20px) rotate(-10deg); }
}

@keyframes hug-right {
    0% { transform: rotate(0deg); }
    100% { transform: translateX(-20px) rotate(10deg); }
}

button {
    padding: 10px 20px;
    font-size: 1rem;
    border: none;
    background-color: #ff4d6d;
    color: white;
    border-radius: 20px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background-color: #e60046;
}
