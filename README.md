<!DOCTYPE html>
<html lang="en-us">

<head>
  <meta charset="UTF-8">
  <title>CSS Stylesheets with Relative Paths</title>

  <!-- This line is money! It points your HTML to the CSS file. -->
  <!-- Notice the "relative" pathway? It matches a file inside our current directory's "assets" folder. Open it to see our style rules. -->
  
  <link rel="stylesheet" type="text/css" href="Week2Day1.css">

</head>

<body>
  <header>
    <h1>Student Bio</h1>
  </header>

  <div class="container">

    <section id="main-bio">

      <h2>Your Name</h2>

      <img id="bio-image" src="https://scontent-iad3-1.xx.fbcdn.net/v/t1.0-9/66662330_10213910494107681_6602777232731537408_n.jpg?_nc_cat=104&_nc_oc=AQnfP4NO385qMaiyybgW9atoCXmJCbouOOhT1FzbRA5mU6fZDZ1h3dTGbK8yZmQvSNc&_nc_ht=scontent-iad3-1.xx&oh=578ab6f8001ec8dfb11627cc768c4829&oe=5DD2E352" alt="Your Name">

      <p>Write a short paragraph or two about yourself, or use placeholder text from <a href="http://www.lipsum.com/">www.lipsum.com</a></p>
    </section>

    <section id="contact-info">
      <h2>Contact Info</h2>
      <ul>
        <li><strong>Email:</strong> <a href="#">someplace@gmail.com</a></li>
        <li><strong>Github:</strong> <a href="#">sampleName</a></li>
        <li><strong>Portfolio:</strong> <a href="#">coming soon</a></li>
      </ul>
    </section>
  </div>

</body>

</html>

