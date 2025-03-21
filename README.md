
HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Layout</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="nav-bar">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <main class="main-content">
        <section class="hero-section">
            <h1>Welcome to our website!</h1>
            <p>This is a sample responsive layout.</p>
        </section>
        <section class="features-section">
            <h2>Features</h2>
            <ul>
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
            </ul>
        </section>
        <section class="call-to-action">
            <h2>Get started today!</h2>
            <button>Sign up</button>
        </section>
    </main>
</body>
</html>
```

CSS (in styles.css file):
```
/* Global styles */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Navigation bar */
.nav-bar {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

.nav-bar ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

.nav-bar a {
    color: #fff;
    text-decoration: none;
}

/* Main content */
.main-content {
    display: grid;
    grid-template-columns: 1fr;
    grid-gap: 2em;
    padding: 2em;
}

.hero-section {
    background-color: #f7f7f7;
    padding: 2em;
    text-align: center;
}

.features-section {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 1em;
}

.features-section ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

.call-to-action {
    background-color: #333;
    color: #fff;
    padding: 2em;
    text-align: center;
}

/* Media queries */
@media (min-width: 768px) {
    .main-content {
        grid-template-columns: 2fr 1fr;
    }
    .features-section {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 1200px) {
    .main-content {
        grid-template-columns: 3fr 1fr;
    }
    .features-section {
        grid-template-columns: repeat(3, 1fr);
    }
}

# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨
