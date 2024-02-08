<template>
    
      <header class="header">
        <a href="#" class="logo">Nkosiphendule.</a>

        <div class="bx bx-menu" id="menu-icon"></div>
        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#skills">Skills</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
      </header>
  
      <section class="home" id="home">
        <div class="home-content">
            <div class="text-animate">
                <h3>Full Stack Software Developer</h3>  
            </div>
            <p>Welcome to Nkosiphendule Mdingi’s portfolio.
            </p>

            <div class="btn-box">
                <a href="#" class="btn"><i class='bx bx-folder-open'></i></a>
                <a href="#contact" class="btn"><i class='bx bxs-message-dots'></i></a>
                
            </div>
        </div>
        
        <div class="home-sci">
            <a href="https://www.linkedin.com/in/nkosiphendule-mdingi-957220232"><i class='bx bxl-linkedin' ></i></a>
            <a href="https://github.com/NkosiphenduleM221"><i class='bx bxl-github' ></i></a>
        </div>
    
      </section>
      <section class="about" id="about">
        
        <div class="about-img">
            <img src="../components/About.png" alt="">
 
        </div>
        <div class="about-content">
            <h3>Nkosiphendule Mdingi</h3> 
            <p>Hello there! I'm a dedicated FullStack Developer Intern with a solid foundation—a Bachelor of Science Degree in Computer Science and Information Technology graduate. My journey into the world of tech has been marked by a passion for innovation and a drive to learn and grow.</p>
            <p>As an intern, I'm enthusiastically honing my skills in both front-end and back-end development, working to bridge the gap between captivating user experiences and robust technical implementations. My academic background has provided me with a deep understanding of the core principles, and my internship experience is allowing me to put theory into practice in real-world projects.</p>
            <p>Eager to contribute, collaborate, and make my mark, I'm excited about the opportunities that lie ahead in creating meaningful digital solutions. Join me as I embrace challenges, embrace growth, and pave my way in the dynamic realm of FullStack development.</p> 
        </div>
    </section>
    <section class="education" id="education">
        <h2 class="heading">My <span>Journey</span></h2>

        <div class="education-row">
            <div class="education-column">
                <h3 class="title">Education</h3>

                <div class="education-box">
                    <div class="education-content">
                        
                        <div class="content">
                            <div class="year"><i class='bx bxs-calendar'></i>2015 - 2019</div>
                            <h3>National Senior Certificate - Entsikeni Senior Sec. School</h3>
                            

                        </div>
                    </div>
                    <div class="education-content"> 
                        <div class="content">
                            <div class="year"><i class='bx bxs-calendar'></i>2020 - 2022</div>
                            <h3>Bachelor of Science in Computer Science and Information Technology - University of Kwazulu-Natal</h3>
                            
                            
                        </div>
                    </div>
                    
                </div>
            </div>
            <div class="experience-column">
                <h3 class="title">Experience</h3>

                <div class="education-box">
                    <div class="education-content">
                        <div class="content">
                            <div class="year"><i class='bx bxs-calendar'></i>2023 - 2024</div>
                            <h3>FullStack Software Developer Intern - CapaCiTi</h3>
                            

                        </div>
                    </div>
                 
                    <div class="education-content">
                        <div class="content">
                            <div class="year"><i class='bx bxs-calendar'></i>2024 - </div>
                            <h3>Junior Software Developer - Younglings</h3>
                            

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="skills" id="skills">
      <h1 class="heading">My <span>Skills</span></h1>

      <h3 class="title"><span>Professional</span> Skills</h3>
      <div class="box-container">
        
          <div class="box">
              <div class="image">
                  <div class="content">
                    
                    <h3>Web Design and Development</h3> 
                  </div>
              </div>
          </div>
  
          <div class="box">
              <div class="image">
            
                  <div class="content">   
                    <h3>Software Design and Development</h3>  
                  </div>
              </div>
          </div>
  
          <div class="box">
              <div class="image">
                  <div class="content">  
                    <h3>System Analysis</h3>    
                  </div>
              </div>
          </div>
  
          <div class="box">
              <div class="image">
                  <div class="content">
                    <h3>Database Programming</h3>
                      
                  </div>
              </div>
          </div>
          <div class="box">
            <div class="image">
                <div class="content">
                  <h3>Data Analytics</h3>
                
                </div>
            </div>
        </div>
      </div>
  </section>
    
      
    
  </template>
  
  <script>
  export default {
    // Your Vue component logic goes here
    data() {
    return {
      currentYear: new Date().getFullYear(),
    };
} 
  }
  </script>
  
  <style lang="css">
    @import "./Main.css"

</style>
