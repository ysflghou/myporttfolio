<template>
  <div>
    <div class="card">
      <img class="rounded-circle responsive" src="../assets/Lghoumaigui.jpg" alt="Me" />
      <h3>Lghoumaigui Youssef</h3>
      <h5 class="title">Software engineer</h5>
      <div>SG ATS</div>
      <p>
        Hello, I'm a junior software engineer from Morocco.
        Feel free to <router-link to="/contact" class="contact_me"><u>Contact Me</u></router-link> to talk about software engineering
        or something else &#128521;
      </p>
    </div>
  </div>
</template>
<style scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css");
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 80%;
  margin: 50px auto;
  text-align: center;
  font-family: arial;
  padding-top: 20px;
}

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 25%;
  height: 25%;
  padding-top: 5%;
  padding-bottom: 5%;
}
.contact_me {
  font-size: inherit;
}

@media screen and (max-width: 600px) {
  img.responsive {
    width: 50%;
    height: 50%;
  }
}
@media screen and (min-width: 601px) {
  img.responsive {
    width: 25%;
    height: 25%;
  }
}

.title {
  color: grey;
  font-size: 18px;
}

button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover,
a:hover {
  color: #42b983;
}
p {
  text-align: left;
  justify-content: flex-start;
  padding: 10px;
}
/* */
@media screen and (min-width: 601px) {
  p {
    font-size: 16px;
  }
}

@media screen and (max-width: 600px) {
  p {
    font-size: 15px;
  }
}
@media screen and (min-width: 601px) {
  h6 {
    font-size: 18px;
  }
}

@media screen and (max-width: 600px) {
  h6 {
    font-size: 15px;
  }
}
@media screen and (min-width: 601px) {
  h5 {
    font-size: 20px;
  }
}

@media screen and (max-width: 600px) {
  h5 {
    font-size: 17px;
  }
}
@media screen and (min-width: 601px) {
  h4 {
    font-size: 21px;
  }
}

@media screen and (max-width: 600px) {
  h4 {
    font-size: 18px;
  }
}
@media screen and (min-width: 601px) {
  h3 {
    font-size: 22px;
  }
}

@media screen and (max-width: 600px) {
  h3 {
    font-size: 19px;
  }
}
@media screen and (min-width: 601px) {
  h2 {
    font-size: 23px;
  }
}

@media screen and (max-width: 600px) {
  h2 {
    font-size: 20px;
  }
}
</style>

