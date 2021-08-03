<template >
  <div id="app" >
    <img width=300; height=400; src="./assets/John_Stuby.jpg">
    <h1>{{ msg }}</h1>
    <h2><b>Contact</b></h2>
    <ul>
      <li><a class="contact-links contact-links:hover" href="mailto:johnstuby7@gmail.com"> Johnstuby7@gmail.com </a> </li>
      <li><a href="https://github.com/johnstuby7" target="_blank">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/john-stuby-886a5749/" target="_blank">LinkedIn</a></li>
    </ul>
    <h2><b>Other Sites:</b></h2>
    <uL><li><a href="https://johnstuby7.github.io/portfolio/#/portfolio/" target="_blank">React Portfolio Site</a></li></uL>
    <h2><b>Skill Set</b></h2>
    <ul>
      <li >
        <h3 class="text-left">
          Languages
        </h3>
        <p class="text-left "> 
            JavaScript <br><br>
            NPM / NodeJS  <br><br>
            AngulaJS 1&2 <br><br>
            React / Vue.js <br><br>
            CSS / LESS <br><br>
            mySQL / PSQL <br><br>
            MongoDB <br><br>
            HTML 5 <br><br>
            Ruby / PHP 
          </p>
          </li>
          <li>
          <h3 class="text-right">
            Additional Skills
          </h3>
          <p class="text-right">
            Git / SVN / Heroku <br><br>
            RSPEC / Protractor <br><br>
            Jasmine / Cucumber <br><br>
            Agile / Sprint  <br><br>
            Project Management <br><br>
            Linux / WSL2 <br><br>
            Windows / Mac <br><br>
            AWS <br><br>
            GIS 
          </p></li>
    </ul>
    <ul>
      <a class="contact-links contact-links:hover" href="/src/assets/JohnStubyResume.pdf" target="_blank">Download John Stuby Resume PDF</a> 

    </ul>
  </div>
</template>

<script>
  export default {
    name: 'app',
    beforeCreate () {
      document.querySelector('body').setAttribute('style', 'background:rgb(8, 109, 143)')
    },
    data () {
      return {
        msg: 'John Stuby'
      }
    }
  }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #070808;
  margin-top: 60px;
}


h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #091610;
}
</style>
