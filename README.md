<html>
<head>
  <title>Mini Page with Table and Contact Form</title>
</head>
<body>

  <h1>Alano, Janniyah Jane</h1>

  <table border="1" cellpadding="1">
    <tr>
      <th>Skill</th>
      <th>Level</th>
    </tr>
    <tr>
      <td>HTML</td>
      <td>Beginner</td>
    </tr>
    <tr>
      <td>CSS</td>
      <td>Beginner</td>
    </tr>
    <tr>
      <td>JavaScript</td>
      <td>Learning</td>
    </tr>
  </table>

  <h2>Contact Me</h2>

  <p> Please contact me using the form below. :3 </p>
  <form action="mailto:janniyahjane.alano@neu.edu.ph" method="post" enctype="text/plain">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name"><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email"><br><br>

    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5" cols="30"></textarea><br><br>

    <input type="submit" value="Send">
    <input type="reset" value="Clear">
  </form>

</body>
</html>
