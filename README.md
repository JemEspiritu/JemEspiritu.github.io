
<html lang="en">

<head>
  <title>@Jem Espiritu</title>
  <link rel="icon" href="https://raw.githubusercontent.com/earthtoyash/earthtoyash.github.io/main/me.jpg">
  <meta charset="UTF-8">
  <meta name="home" content="Just some stuff!">
  <link rel="stylesheet" href="Project.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <!-- fontawesome kit -->
  <script src="https://kit.fontawesome.com/12855d893b.js" crossorigin="anonymous"></script>
  <div class="avatar">
    <background></background>
    <title>@earthtoyash</title>
    <link rel="icon"
      href="https://raw.githubusercontent.com/earthtoyash/earthtoyash.github.io/main/index_files/Anonymous.png">
  </div>
</head>

<body>
  <div class="intro">
    <div class="text-intro">
      <h2>John Edward Miles D. Espiritu </h2>
    </div>
    <div class="image-intro"> <img src="https://cdn.discordapp.com/attachments/752766248177238090/1240679814612910080/Jempott.jpg?ex=6647709e&is=66461f1e&hm=313baff3d01a5e77318aa001ee126847831ef2bd142ea5b81824a7605e12462d&" alt="It's Me!">
    </div>
    </div>
  </div>
  <section>
    <p>I am John Edward Miles D. Espiritu, I’m a student who is currently studying at Technological Institute of the Philippines.</p>
    <p> You can check out my repository at github below!</p>
  </section>

  <div class="centre">
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA1" target="_blank">HOA1</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/HOA2" target="_blank"><i></i>HOA2</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/HOA3" target="_blank"><i></i>HOA3</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/HOA4p1" target="_blank"><i></i>HOA4</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/HOAp5" target="_blank">HOA5</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/Espiritu_PrelimExam" target="_blank">Prelim Exam</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA6p1" target="_blank">HOA6</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA7p1" target="_blank">HOA7</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA8.1" target="_blank">HOA8</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA9.1" target="_blank">HOA9</a></button>
    
    <button class="btn"><a href="" target="_blank">HOA10</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA11.1" target="_blank">HOA11</a></button>
    
    <button class="btn"><a href="" target="_blank">HOA12</a></button>

    <button class="btn"><a href="https://github.com/JemEspiritu/CPE_MIDEXAM_ESPIRITU" target="_blank">Midterm Exam</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA13.1" target="_blank">HOA13</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA14.1" target="_blank">HOA14</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu/HOA15.1" target="_blank">HOA15</a></button>
    
    <button class="btn"><a href="https://github.com/JemEspiritu" target="_blank">github</a></button>

    <button class="btn"><a href="https://docs.google.com/document/d/1faU8GRfNIHdVwb6WpMFzKZvVlMQOcjwpGa_QNbhZUBU/edit?usp=sharing" target="_blank">Reflections & Learnings</a></button>


  </div>

</body>

</html>

import url('https://fonts.googleapis.com/css2?family=Maven+Pro:wght@400;500;600;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');

* {
    margin: 0;
    padding: 0;
    font-family: 'Maven Pro', sans-serif;
    color: white;
}

body {
    background: linear-gradient(rgba(0, 0, 0, 0.31), rgba(0, 0, 0, 0.31)), url(https://i.imgur.com/xU2VekJ.jpeg) no-repeat;
    background-size: cover;
    /* height: 100vh; */
}

.intro {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin: 4% auto;
    width: 70%;
}

.intro img {
    width: 214px;
    height: 214px;
    border-radius: 128px;
    margin: 0 104px;
    border: dotted 5px greenyellow;

}

.text-intro {
    align-items: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 50%;
}

.text-intro h1 {
    margin: 10px 0;
    font-size: 40px;
}

.text-intro h2 {

    margin: 10px 0;
    font-weight: lighter;
    font-family: 'VT323', monospace;
    font-size: 40px;
    color: greenyellow;
}

.text-intro p {
    margin: 0 56px;
    font-size: 27px;
}

.image-intro {
    display: inline-block;
    width: 50%;
}

.centre {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: auto;
    width: 75%;
}

.btn {
    background-color: rgba(255, 255, 255, 0.164);
    /* color: white; */
    border: none;

    text-transform: uppercase;
    font-size: 20px;
    line-height: 46px;
    width: 144px;
    margin: 19px 69px;
    border-radius: 10px;
    border: 2px solid white;
}

a {
    font-family: 'VT323', monospace;
    font-weight: lighter;
    letter-spacing: 1px;
    text-decoration: none;
}



.btn:hover {
    /* color: rgba(0, 0, 0, 0.516); */
    background-color: rgba(255, 255, 255, 0.681);
}

a:hover {
    color:black ;
}

a:visited {
    color: greenyellow;
}

button {
    display: flex;
    align-items: center;
    justify-content: center;
    align-content: center;
}

section p {
    font-family: 'VT323', monospace;
    letter-spacing: 2px;
    color: greenyellow;

}

section {
    margin: 37px auto;
    width: 70%;
    text-align: center;
    font-size: 25px;
}

/* btn-with-icon section */

.fa{
    color: white;
    margin: 10px 15px 0 15px;
}


.thmbdg{
    margin-top: 30px;
}

