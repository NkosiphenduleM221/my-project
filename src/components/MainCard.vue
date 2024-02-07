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
  
  <style scoped>
@import url('https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    border: none;
    outline: none;
    scroll-behavior: smooth;
    font-family: 'Poppins', sans-serif;
}

:root {
    --bg-color: #01214ae7; 
    --second-bg-color: #112e42;
    --text-color: #ededed;
    --main-color: #00abf0;
    --contact-color: #0047ab;
}

html {
    font-size: 62.5%;
    overflow-x: hidden;
}

body {
    background: var(--bg-color);
    color: var(--text-color);
    padding-top: 6rem; /* Adjust this value to match the height of your header */
    margin: 0;
}

.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 1.5rem 9%; /* Adjust padding as needed */
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
    background-color: #01214ae7;
    color: #ededed;
}
.heading{
    position: relative;
    font-size: 5rem;
    margin-bottom: 3rem;
    text-align: center;
}
span{
    color: var(#00abf0);
}

.logo {
    position: relative;
    font-size: 2.5rem;
    color: var(--text-color);
    font-weight: 600;
}

.navbar a {
    font-size: 1.4rem;
    color: var(--text-color);
    font-weight: 500;
    margin-left: 3.5rem;
    transition: .3s;
}

.navbar a:hover,
.navbar a.active {
    color: #00abf0;
}

#menu-icon {
    position: relative;
    font-size: 3.2rem;
    color: #ededed;
    cursor: pointer;
    display: none;
}

.section {
    padding: 6rem 9%; /* Adjust padding as needed */
    background-color: #112e42;
    color: #ededed;
}

.home {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Adjust height for full viewport coverage */
    background-color: #01214ae7;
    color: #ededed
}


.about {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    padding-bottom: 6rem;
    background-color: #112e42;
    color: #ededed
}


.home-content {
    text-align: center; /* Aligns the text content to the center */
    position: relative;
    width: 32.8rem;
    margin: 0 auto;
    margin-top: 2rem; /* Add margin to separate from the header */
}

.text-animate h3 {
    font-size: 2.8rem;
    font-weight: 700;
    color: transparent;
    -webkit-text-stroke: .7px #00abf0;
    background-image: linear-gradient(#00abf0,#00abf0);
    background-repeat: no-repeat;
    -webkit-background-clip: text;
    background-position: -33rem 0;
    animation: homeBgText 6s linear infinite;
    animation-delay: 2s;
}

.text-animate h3::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    border-right: 2px solid #00abf0;
    z-index: -1;
    animation: homeCursorText 6s linear infinite;
    animation-delay: 2s;
}

@keyframes homeBgText {
    to {
        background-position: 33rem 0;
    }
}

@keyframes homeCursorText {
    50% {
        border-color: transparent;
    }
}

.home-content {
    text-align: center;
    position: relative;
    width: 32.8rem;
    margin: 0 auto;
    margin-top: 2rem; /* Add margin to separate from the header */
}

.home-content p {
    text-align: center;
    font-size: 1.6rem;
    color: #ededed;
    margin-bottom: 2rem; /* Adjust margin as needed */
}

.btn-box {
    position: relative;
    display: flex;
    justify-content: center; /* Add space between buttons */
    margin-top: 2rem; /* Adjust margin as needed */
}

.btn-box a {
    position: relative;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 80px; /* Increase button width */
    height: 80px; /* Increase button height */
    background: transparent;
    font-size: 80px; /* Increase font size */
    color: #00abf0;
    z-index: 1;
    overflow: hidden;
    transition: .5s;
    margin: 0 30px;
}

.btn-box a:hover {
    color: #01214ae7;
}

.btn-box a::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    background: #00abf0;
    z-index: -1;
    transition: 0.5s;
}

.btn-box a:hover:before {
    width: 100%;
}

.btn-box a i {
    font-size: 3.1rem;
    color: #00abf0;
    transition: .5s;
}

.btn-box a:hover i {
    color: #112e42;
}

.btn-box a:hover:before {
    width: 100%;
}

.home-sci{
    position: absolute;
    bottom: 4rem;
    width: 170px;
    display: flex;
    justify-content: space-between;
    margin-bottom: 200px;
}
.home-sci a{
    position: relative;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    background: transparent;
    border-radius: 50%;
    font-size: 20px;
    color: #00abf0;
    z-index: 1;
    overflow: hidden;
    transition: .5s;
}
.home-sci a:hover {
    color: #01214ae7;
}
.home-sci a::before {
    content: '';
    position: absolute;
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    background: #00abf0;
    z-index: -1;
    transition: 0.5s;
}
.home-sci a:hover:before{
    width: 100%;
}
.home-sci a i {
    font-size: 2.1rem;
    color: #00abf0;
    transition: .5s;
}
.home-sci a:hover i {
    color: #112e42;
}
.home-sci a:hover:before ,
.contact form .btn-box .btn:hover::before{
    width: 100%;
}

.heading{
    position: relative;
    font-size: 5rem;
    margin-bottom: 3rem;
    text-align: center;
}

.about-img {
    position: relative;
    width: 20rem;
    height: 20rem;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden; /* Ensure image doesn't overflow */
}

.about-img img {
    position: absolute;
    width: 100%; /* Start with full width */
    height: auto;
    border-radius: 40%;
    transition: transform 0.5s ease; /* Smooth transition for zoom animation */
}

/* Keyframe animation for zooming in */
@keyframes zoomIn {
    from {
        transform: scale(1); /* Start with normal size */
    }
    to {
        transform: scale(1.2); /* Zoom in to 120% of original size */
    }
}

/* Keyframe animation for zooming out */
@keyframes zoomOut {
    from {
        transform: scale(1.2); /* Start with zoomed-in size */
    }
    to {
        transform: scale(1); /* Zoom out to normal size */
    }
}

/* Apply zoom-in animation on hover */
.about-img:hover img {
    animation: zoomIn 0.5s forwards; /* Run zoomIn animation on hover */
}

/* Apply zoom-out animation when not hovering */
.about-img:not(:hover) img {
    animation: zoomOut 0.5s forwards; /* Run zoomOut animation when not hovering */
}

.about-content{
    text-align: center;
    width: 35rem;
}
.about-content h3{
    font-size: 2.6rem;
    color: #00abf0;
}
.about-content p{
    font-size: 1.1rem;
    color: #ededed;
    margin: 2rem 0 3rem;
}
.education{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    min-height: auto;
    padding-bottom: 5rem;
    background-color:#01214ae7;
    color: #ededed;
}
.education .education-row{
    display: flex;
    flex-wrap: wrap;
    gap: 5rem;
}
.education-row .education-column,.experience-column{
    flex: 1 1 40rem;
}
.education-column,.experience-column .title{
    font-size: 2.5rem;
    margin: 0 0 1.5rem 2rem;
}
.education-column .education-box {
    border-right: .2rem solid #00abf0;
}
.experience-column .education-box {
    border-left: .2rem solid #00abf0;
}
.education-box .education-content {
    position: relative;
    padding-left: 2rem;
}
.education-box .education-content::before{
    content: "";
    position: absolute;
    top: 0;
    left: -1.1rem;
    width: 2rem;
    height: 2rem;
    background: #00abf0;
    border-radius: 50%;
}
.education-content .content {
    position: relative;
    padding: 1.5rem;
    margin-bottom: 2rem;
    overflow: hidden;
}
.education-content .content::before{
    content: "";
    position: absolute;
    top: 0;
    bottom: 0;
    width: 0;
    height: 100%;
    background: #112e42;
    z-index: -1;
}
.education-content .content:hover:before{
    width: 100%;
}
.education-content .content .year{
    font-size: 1.3rem;
    color: #00abf0;
    padding-bottom: .5rem;
}
.education-content .content .year i{
    padding-right: .7rem;
}
.education-content .content h3{
    font-size: 1.5rem;
}

</style>
