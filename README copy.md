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

# add the logo near the website name
- I saw lots of website has one pircture near there website name, so I go to see one of the View development source code, I found that I can link one of the picture in the beginning of the code.
- so I draw one a picture which represent me.
- it looks like this 
https://github.com/YinuoZ7/YinuoZ7.github.io/blob/main/WechatIMG5.jpeg
- Then I add the code to the start of my website's code
```javascript
 <link rel="icon" sizes="192x192" href="WechatIMG5.jpeg" type="image/jpeg"/>
  <link rel="shortcut icon" href="WechatIMG5.jpeg" type="image/jpeg"/>
  <link rel="apple-touch-icon" href="WechatIMG5.jpeg" type="image/jpeg"/>
```

# write things in that 
- I put some tittle and introduction in the each section. 

# I feel that I need to put some picture in my website which can make my website looks good.
- so I put some of the pictures in that

# after all of that I am going to put my works in that.

# Then I found the beatiful contact page on the website that Rachel gives to us. and changed a little bit on that.
- which is looks like this 
```javascript
<section>
    <h2>Contact Me</h2>
    <hr class="w3-opacity">

    <div class="w3-section">
      <p>Boston, US</p>
      <p>Phone: +1 8572105266</p>
      <p> Email: zyinuoya@gmail.com</p>
    </div>
    <img src= IMG_1266.JPG style="width:100%;margin:32px 0">
   
    <p>Lets get in touch. Send me a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input type="text" placeholder="Name" required name="Name"></p>
      <p><input type="text" placeholder="Email" required name="Email"></p>
      <p><input type="text" placeholder="Subject" required name="Subject"></p>
      <p><input type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  </div>  
    </section>
```
