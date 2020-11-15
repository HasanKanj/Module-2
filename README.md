<!DOCTYPE html>
<html lang="en">
      <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <meta http-equiv="X-UA-Compatible" content="ie=edge" />
      <title>module2-solution</title>
      <link rel="stylesheet" href="./main.css" />
      </head>
      <STYLE>* {
  box-sizing: border-box;
}

html {
  background-color: rgb(226, 226, 74);
}

section {
  border: 1px white solid;
  width: 33.33%;
  float: left;
  position: relative;
  /* margin: 1%; */

  padding: 10px;
  padding-top: 60px;
  color: white;
  background-color: rgb(0, 0, 0);
}
p {
  text-align: center;
}

h1 {
  text-align: center;
  padding-top: 5%;
  padding-bottom: 5%;
}

section > span {
  background-color: rgb(109, 109, 109);
}

span p.title {
  font-weight: bold;
}

span {
  border: 1px solid black;
  position: absolute;
  width: 35%;
  height: 30%;
  top: 0;
  bottom: 0;
  right: 0;
}

/* Media Queires */
/* Destop */
/* 992px */

/* Tablet */
/* 768px and 991px */
@media (min-width: 768px) and (max-width: 991px) {
  section.first {
    width: 50%;
  }

  section.second {
    width: 50%;
  }
  section.third {
    width: 100%;
    /* margin-top: 20px; */
  }
}

/* mobile */
/* max-width 767px */
@media (max-width: 767px) {
  section {
    width: 100%;
  }
}</STYLE>
      <body>
      <h1>Our Menu</h1>
      <div class="container">
      <section class="first">
      <span><p class="title">Chicken</p></span>
      <p>
      Ad magna esse culpa anim reprehenderit fugiat aute labore pariatur.
      Reprehenderit non cupidatat ea cillum exercitation pariatur
      exercitation magna aliquip do laborum magna mollit ullamco. Laborum
      velit pariatur sint eu et eiusmod dolor velit consequat.
      </p>
      </section>
      <section class="second">
      <span><p class="title">Beef</p></span>
      <p>
       Ad magna esse culpa anim reprehenderit fugiat aute labore pariatur.
       Reprehenderit non cupidatat ea cillum exercitation pariatur
       exercitation magna aliquip do laborum magna mollit ullamco. Laborum
       velit pariatur sint eu et eiusmod dolor velit consequat.
    </p>
   </section>
   <section class="third">
  <span><p class="title">Sushi</p></span>
  <p>
   Ad magna esse culpa anim reprehenderit fugiat aute labore pariatur.
   Reprehenderit non cupidatat ea cillum exercitation pariatur
   exercitation magna aliquip do laborum magna mollit ullamco. Laborum
   velit pariatur sint eu et eiusmod dolor velit consequat.
 </p>
</section>
</div>
<script src="./index.js" type="module"></script>
</body>
</html>
