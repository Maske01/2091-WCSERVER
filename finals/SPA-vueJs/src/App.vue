<template>
<div class="container">
  <div class="header">
    <div class="full-name">
      <span class="first-name">Chrisjohn</span> 
      <span class="last-name">Crisostomo</span>
    </div>
    <div class="contact-info">
      <span class="email">Email: </span>
      <span class="email-val">chrisjohn@gmail.com</span>
      <span class="separator"></span>
      <span class="phone">Phone: 09276184914 </span>
      <span class="phone-val">111-222-3333</span>
    </div>
    
    <div class="about">
      <span class="position">Fullstack Developer </span>
      <span class="desc">
          I'm an aspiring fullstack developer, but i'm currently a 2nd year college student taking BSIT. I am passionate about developing intuitive and user-friendly interfaces that enhance the user experience. I excel at collaborating with team members, communicating technical information clearly, and delivering high-quality work on time. With my strong problem-solving skills and proficiency in a variety of technologies, I am confident in my ability to tackle any development challenge.
      </span>
    </div>
  </div>
  <div class="details">
    <div class="section">
      <div class="section__title">Education</div>
      <div class="section__list">
        
        <div class="section__list-item">
          <div class="left">
            <div class="addr">Elementary: Dona Ascuncion Lee Integrated School</div>
            <div class="addr">HighSchool: Children of Fatima</div>
            <div class="addr">Senior HighSchool: Holy Angel University</div>
            <div class="addr">College: Holy Angel University</div>
          </div>
        </div>

      </div>
    </div>
    <div class="section">
      <div class="section__title">Skills</div>
      <div class="section__list">
        <div class="section__list-item">
          <div class="left">
            <div class="addr">Excellent Problem Solving</div>
            <div class="addr">Strong Communication</div>
            <div class="addr">CSS</div>
            <div class="addr">Javascript</div>
            <div class="addr">PHP</div>
            <div class="addr">MySql</div>

          </div>
          <div class="right">
            
          </div>
        </div>


      </div>
      
  </div>
     <div class="section">
      <div class="section__title">Interest</div> 
       <div class="section__list">
         <div class="section__list-item">
           <div class="text">Sports</div>
           <div class="text">Programming</div>
           <div class="text">Traveling </div>
           <div class="text">Music</div>
         </div>
         
        
     </div>
     </div>
  </div>
</div>  
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html {
  height: 100%;  
}

body {
  min-height: 100%;  
  background: #eee;
  font-family: 'Lato', sans-serif;
  font-weight: 400;
  color: #222;
  font-size: 14px;
  line-height: 26px;
  padding-bottom: 50px;
}

.container {
  max-width: 700px;   
  background: #fff;
  margin: 0px auto 0px; 
  box-shadow: 1px 1px 2px #DAD7D7;
  border-radius: 3px;  
  padding: 40px;
  margin-top: 50px;
}

.header {
  margin-bottom: 30px;
  
  .full-name {
    font-size: 40px;
    text-transform: uppercase;
    margin-bottom: 5px;
  }
  
  .first-name {
    font-weight: 700;
  }
  
  .last-name {
    font-weight: 300;
  }
  
  .contact-info {
    margin-bottom: 20px;
  }
  
  .email ,
  .phone {
    color: #999;
    font-weight: 300;
  } 
  
  .separator {
    height: 10px;
    display: inline-block;
    border-left: 2px solid #999;
    margin: 0px 10px;
  }
  
  .position {
    font-weight: bold;
    display: inline-block;
    margin-right: 10px;
    text-decoration: underline;
  }
}


.details {
  line-height: 20px;
  
  .section {
    margin-bottom: 40px;  
  }
  
  .section:last-of-type {
    margin-bottom: 0px;  
  }
  
  .section__title {
    letter-spacing: 2px;
    color: #54AFE4;
    font-weight: bold;
    margin-bottom: 10px;
    text-transform: uppercase;
  }
  
  .section__list-item {
    margin-bottom: 40px;
  }
  
  .section__list-item:last-of-type {
    margin-bottom: 0;
  }
  
  .left ,
  .right {
    vertical-align: top;
    display: inline-block;
  }
  
  .left {
    width: 60%;    
  }
  
  .right {
    tex-align: right;
    width: 39%;    
  }
  
  .name {
    font-weight: bold;
  }
  
  a {
    text-decoration: none;
    color: #000;
    font-style: italic;
  }
  
  a:hover {
    text-decoration: underline;
    color: #000;
  }
  
  .skills {
    
  }
    
  .skills__item {
    margin-bottom: 10px;  
  }
  
  .skills__item .right {
    input {
      display: none;
    }
    
    label {
      display: inline-block;  
      width: 20px;
      height: 20px;
      background: #C3DEF3;
      border-radius: 20px;
      margin-right: 3px;
    }
    
    input:checked + label {
      background: #79A9CE;
    }
  }
}









</style>
