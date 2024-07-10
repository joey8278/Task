<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solving Measures of Right Triangles</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .content img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        .content div {
            flex: 1 1 calc(50% - 20px);
            margin: 10px;
        }
        .interactive {
            text-align: center;
            margin: 20px 0;
        }
        .interactive iframe {
            width: 100%;
            height: 400px;
            border: none;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Solving Measures of Right Triangles</h1>
        <p>Explore the key concepts and methods for solving measures in right triangles</p>
    </header>
    <nav>
        <a href="#introduction">Introduction</a>
        <a href="#pythagorean">Pythagorean Theorem</a>
        <a href="#trigonometry">Trigonometric Ratios</a>
        <a href="#applications">Real-World Applications</a>
        <a href="#examples">Examples</a>
        <a href="#quiz">Interactive Quiz</a>
    </nav>
    <section id="introduction">
        <h2>Introduction</h2>
        <p>Right triangles are fundamental in geometry, offering straightforward methods to solve various measures of sides and angles. This webpage explores the essential concepts and methods used in solving measures of right triangles.</p>
    </section>
    <section id="pythagorean">
        <h2>Pythagorean Theorem</h2>
        <div class="content">
            <div>
                <h3>Definition</h3>
                <p>The Pythagorean theorem states that in a right triangle, the square of the length of the hypotenuse (the side opposite the right angle) is equal to the sum of the squares of the lengths of the other two sides. This can be written as:</p>
                <p><strong>a² + b² = c²</strong></p>
            </div>
            <div>
                <h3>Example Calculation</h3>
                <p>Given a right triangle with legs of 3 units and 4 units, find the length of the hypotenuse:</p>
                <p>Using the Pythagorean theorem: <strong>3² + 4² = c²</strong> which simplifies to <strong>9 + 16 = 25</strong>, so <strong>c = 5</strong> units.</p>
            </div>
        </div>
    </section>
    <section id="trigonometry">
        <h2>Trigonometric Ratios</h2>
        <div class="content">
            <div>
                <h3>Definition</h3>
                <p>Trigonometric ratios relate the angles of a right triangle to the lengths of its sides. The primary ratios are:</p>
                <ul>
                    <li><strong>Sine (sin)</strong> = Opposite / Hypotenuse</li>
                    <li><strong>Cosine (cos)</strong> = Adjacent / Hypotenuse</li>
                    <li><strong>Tangent (tan)</strong> = Opposite / Adjacent</li>
                </ul>
            </div>
            <div>
                <h3>Example Calculation</h3>
                <p>Find the length of the opposite side if the hypotenuse is 10 units and the angle is 30°:</p>
                <p>Using the sine function: <strong>sin(30°) = Opposite / 10</strong>. Since <strong>sin(30°) = 0.5</strong>, the opposite side is <strong>5</strong> units.</p>
            </div>
        </div>
    </section>
    <section id="applications">
        <h2>Real-World Applications</h2>
        <div class="content">
            <div>
                <h3>Architecture</h3>
                <p>Architects use right triangle calculations extensively to ensure structural integrity and proper measurements in buildings and structures.</p>
            </div>
            <div>
                <h3>Engineering</h3>
                <p>Engineers utilize right triangle principles in fields such as mechanical design, civil engineering, and electronics for various calculations and designs.</p>
            </div>
            <div>
                <h3>Astronomy</h3>
                <p>Astronomers apply right triangle concepts to measure distances between celestial objects and determine angles in celestial observations.</p>
            </div>
        </div>
    </section>
    <section id="examples">
        <h2>Examples</h2>
        <div class="content">
            <div>
                <h3>Example 1</h3>
                <p>Given a right triangle with an angle of 45° and a leg length of 5 units, find the length of the hypotenuse.</p>
                <p>Using the cosine function: <strong>cos(45°) = 5 / hypotenuse</strong>. Since <strong>cos(45°) = √2 / 2 ≈ 0.707</strong>, the hypotenuse is <strong>5 / 0.707 ≈ 7.07</strong> units.</p>
            </div>
            <div>
                <h3>Example 2</h3>
                <p>Find the length of the adjacent side if the hypotenuse is 10 units and the angle is 60°.</p>
                <p>Using the cosine function: <strong>cos(60°) = adjacent / 10</strong>. Since <strong>cos(60°) = 0.5</strong>, the adjacent side is <strong>10 × 0.5 = 5</strong> units.</p>
            </div>
        </div>
    </section>
    <section id="quiz" class="interactive">
        <h2>Interactive Quiz</h2>
        <p>Test your understanding of right triangles with this interactive quiz.</p>
        <iframe src="https://quizizz.com/join/quiz/58ece4a1b3b6a0832d1a025f/start?studentShare=true"></iframe>
    </section>
    <footer>
        <p>&copy; 2024 Joseph Medina. All rights reserved.</p>
    </footer>
</body>
</html>
