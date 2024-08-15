<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
   
    nav{
      width:auto;
      height:70px;
      display:flex;
      align-items:center;
      background-color: black;
      color:white;
    }
    nav h1{
      margin-left:60px;
      margin-right:900px;
    }
    nav button{
      margin-right:30px;
      background-color: black;
      color:white;
    }
    #home{
      width:auto;
      height:200px;
      margin-top:100px;
      margin-bottom:100px;
      margin:50px;
    }
    #about{
      width:auto;
      height:550px;
      margin:50px;
    }
    #projects{
      margin:50px;
    }
    form{
      border:1px solid black;
      margin:0px 200px;
    }
    label{
      font-size:20px;
      font-weight: bold;
      margin-right:30px;
      margin-left:300px;
    }
    input[type='text']{
      margin-top:40px;
      height:30px;
      width:410px;
      margin-bottom:30px;
      margin-left:27px;
    }
    input[type='email']{
      height:30px;
      width:410px;
      margin-bottom:30px;
      margin-left:30px;
    }
    textarea{
      height:60px;
      width:410px;
    }
    input[type='button']{
      margin-top:40px;
      height:40px;
      width:150px;
      border-radius:7px;
      margin-left:475px;
    }
    .hea{
      margin:0px 200px 0px 200px;
      display:grid;
      align-items: center;
    }
    footer{
      height:40px;
      display:flex;
      justify-content:center;
      align-items:center;
      background-color: black;
      color:white;
    }
    #contact{
      margin-bottom: 50px;
      margin:50px;
    }
    .d{
      margin:20px;
    }
    section{
      border:4px solid black;
      border-radius:10px;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <h1>Likitha</h1>
      <button onclick="srollhome()">Home</button>
      <button onclick="srollabout()">About</button>
      <button onclick="srollproject()">Projects</button>
      <button onclick="srollcontact()">Contact</button>
    </nav>
  </header>
  <section id="home">
    <div class="d">
    <h2>Hello I am Likitha</h2>
    <article>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur, beatae. Tempora officiis quas perferendis voluptas pariatur eius accusamus delectus eligendi iusto asperiores blanditiis beatae sed laborum, culpa est minima iste facilis? Perferendis fuga harum consequuntur aut quod inventore quasi asperiores est mollitia aspernatur! Minima quibusdam ducimus delectus eligendi repellendus. Quidem?</article>
  </div>
  </section>
  <section id="about">
    <div class="d">
    <h2>About Me:</h2>
    <article>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis voluptate laboriosam, beatae aperiam non saepe fugit maxime error quibusdam cum explicabo quos ex, doloribus architecto? Saepe odio culpa nihil dolores expedita modi minima temporibus alias fugiat soluta non eum, maxime magnam voluptatem, dolor beatae enim numquam deleniti. Provident, totam delectus.</article>
    <div>
      <div>
        <h3>Secondary Educational Details:</h3>
        <ul>
          <li>2018-2019</li>
          <li>Nri Indian Springs</li>
          <li>Guntur</li>
        </ul>
      </div>
      <div>
        <h3>Secondary Educational Details:</h3>
        <ul>
          <li>2018-2019</li>
          <li>Nri Indian springs</li>
          <li>Guntur</li>
        </ul>
      </div>
      <div>
        <h3>Secondary Educational Details:</h3>
        <ul>
          <li>2018-2019</li>
          <li>Nri Indian springs</li>
          <li>Guntur</li>
        </ul>
      </div>
    </div>
  </div>
  </section>
  <section id="projects">
    <div class="d">
    <h2>Projects:</h2>
    <div>
      <h3>Projects-1:</h3>
      <article>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum laboriosam tenetur reprehenderit velit blanditiis unde dignissimos deleniti maxime quas explicabo officiis quos quasi possimus, voluptate, odio cumque itaque officia sequi expedita quae assumenda eum pariatur at. Consectetur laudantium, odit consequuntur corporis quas sequi ad expedita maiores repellat. Ipsam, officia error?</article>
    </div>
    <div>
      <h3>Projects-2:</h3>
      <article>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum laboriosam tenetur reprehenderit velit blanditiis unde dignissimos deleniti maxime quas explicabo officiis quos quasi possimus, voluptate, odio cumque itaque officia sequi expedita quae assumenda eum pariatur at. Consectetur laudantium, odit consequuntur corporis quas sequi ad expedita maiores repellat. Ipsam, officia error?</article>
    </div>
    <div>
      <h3>Projects-3:</h3>
      <article>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorum laboriosam tenetur reprehenderit velit blanditiis unde dignissimos deleniti maxime quas explicabo officiis quos quasi possimus, voluptate, odio cumque itaque officia sequi expedita quae assumenda eum pariatur at. Consectetur laudantium, odit consequuntur corporis quas sequi ad expedita maiores repellat. Ipsam, officia error?</article>
    </div>
  </div>
  </section>
  <section id="contact">
    <div class="d">
    <div class="hea">
      <center><h4>Please Enter Your Details Here</h4></center>
    </div>
    <form>
      <label for="name">Name:</label>
      <input type="text" placeholder="Enter Your Name" id="name"><br>
      <label for="mail">Email:</label>
      <input type="email" placeholder="Enter Your Email" id="mail"><br>
      <label>Message:</label>
      <textarea placeholder="Enter The Message" id="msg"></textarea><br>
      <input type="button" value="submit" Onclick="document.getElementById('demo').style.display='block'">
      <center><p id="demo">Thank You For Entering Your Details</p></center>
    </form>
  </div>
  </section>
  <footer>
    <p>©All Copyrights are Reserved For Vudutha Likitha</p>
  </footer>
  <script>
    function srollhome(){
      document.getElementById('home').scrollIntoView()
    }
    function srollabout(){
      document.getElementById('about').scrollIntoView()
    }
    function srollproject(){
      document.getElementById('projects').scrollIntoView()
    }
    function srollcontact(){
      document.getElementById('contact').scrollIntoView()
    }
  </script>
</body>
</html>
