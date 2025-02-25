# Natasha-Sanchez.github.io
A simple HTML landing page hosted on GitHub Pages showcases the coding skills acquired throughout this course and elsewhere.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHY/MAT 131 Coding Showcase</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1 {
            color: #333;
        }
        .code-container {
            background: #fff;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        pre {
            background: #eee;
            padding: 10px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>PHY/MAT 131 Coding Showcase</h1>
    <p>Welcome to my coding showcase! Below are some of the programs I have written for my PHY/MAT 131 course.</p>
    
    <div class="code-container">
        <h2>Example Code 1: Quadratic Solver</h2>
        <pre>
import math

def quadratic_solver(a, b, c):
    d = b**2 - 4*a*c
    if d < 0:
        return "No real solutions"
    x1 = (-b + math.sqrt(d)) / (2*a)
    x2 = (-b - math.sqrt(d)) / (2*a)
    return x1, x2
        </pre>
    </div>
</body>
</html>
