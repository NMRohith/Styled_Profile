# Styled_Profile_Card
## Date:

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html>
<head>
  <title>My Profile</title>
  <link rel="stylesheet" href="styles.css">

</head>
<body>

  <header>
    <h1>N M Rohith</h1>
    <h2>Student</h2>
    <h3>Web Developer</h3>
  </header>

  <hr>
  <section>
    <img src="Rohith.jpg" alt="Profile picture of N M Rohith" width="200" height="200">
    <p>Hello! I'm a passionate learner exploring the world of web development. I enjoy solving algorithmic problems. My current focus is on building strong foundations in HTML, CSS, and JavaScript.</p>
  </section>

  <hr>

  <section>
    <h2>Interests</h2>
    <ul>
      <li>Full-Stack Web Development (HTML, CSS, JavaScript)</li>
      <li>Java Programming</li>
      <li>Data Analysis & Visualization</li>
    </ul>
  </section>

</body>
</html>
```
## CSS Code:
```
body{
    background-color: lightgray;
    font-family: 'Courier New', Courier, monospace;
}
header{
    text-align:center;
}
h1,h2{
    color:blue;
    font-size:40px;
}
h1 {
  font-size: 48px;
}
h2 {
  font-size: 32px;
}

img{
    width:150px;
    height: 150px;
    border-radius: 100%;
    display:block;
    margin:auto;
}
section {
  padding: 50px;
  margin: 0 auto;
  max-width: 800px;
  
  background-color: white; 

p, ul {
  background-color: aqua;
  padding: 20px;
  line-height: 1.6;
  border-radius: 10px;
}

```
## Live Web Page:
https://nmrohith.github.io/Styled_Profile/
## Output:
![image](https://github.com/user-attachments/assets/83024970-a717-4d14-8fb3-9308b9349bf3)

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
