# put my website in the order of header-nav-section-footer
- so waht I did is I put the each section in the index.html
``` javascript
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
    <header>
        <h1>YN</h1>
    </header>
<nav>
</nav>
<section>
</section>
<footer>
        &copy; 2023 YN..
    </footer>
</body>
</html>
```
- Then I fill in the blank, which is like
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YN's website</title>

</head>
<body>
    <header>
        <h1>YN</h1>
    </header>
    
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="works.html">Works</a>
        <a href="Contact.html">Contact</a>
    </nav>

    <section>
        <h2>This is YN's Website</h2>
        <p>欢迎观影</p>
        <p>Hi</p>
        <p><img src= images/mino.png></p>
    </section>
    <footer>
        &copy; 2023 YN..
    </footer>
</body>
</html>
```
- after that my website have a form but don't have a website design, so I write the css form for my website.
(I copied the main code form Richeal's website)
```javascript
body {
  background-color:lightpink
}

header {
    font-family: Arial, sans-serif;
    background-color:lightgoldenrodyellow;
    color: plum;
    text-align: center;
    padding: 1em;
}

nav {
    background: color #d7b2ff;;
    padding: 1em;
 }
nav a {
    color: white;
    text-decoration: none;
    margin: 0 1em;
}

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 10%;
  }

section {
    background-color: lightgoldenrodyellow;
    color: rgba(92, 182, 212, 0.866);
    padding: 2em;
}
footer {
    background: color #ffd9e4;
    color: white;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```