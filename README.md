<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Siddhant Gaikwad</title>
       <style>
       body {
	margin: 0px;
	font-family: 'Roboto', sans-serif;
}
/* to remove all the resedual margins */

#body-header {
	background-image: url("blacklaptop.jpg");
	height: 75vh;
	background-size: cover;
	background-position: top;
	background-attachment: fixed;
}

.horizontal-list {
	list-style: none;
	padding-left: 0px;
	margin: 0px;
	padding-top: 10px;
	font-weight: 900;
	font-size: 30px;
	font-family: sans-serif;
}

.horizontal-list li {
	display: inline-block;
	margin: 0px 12px 0px 12px;
	cursor: pointer;
}

.horizontal-list li a {
	color: white;
	text-decoration: none;
	transition: color 0.2s;
}

.horizontal-list li a:hover {
	color:darkgray;
}

.text-center {
	text-align: center;
}

#name-social-container {
	margin-top: 10vh;
}

#my-name {
	font-size: 5rem;
	letter-spacing: 0.6rem;
	color: white;
	font-weight: 900;
	margin-bottom: 0.5rem;
}

.social-icons li a img {
	height: 50px;
	width: 50px;
	margin: 0px 15px;
	border-radius: 50%;
	transition: box-shadow 0.25s;
}

.social-icons li a img:hover {
	box-shadow: 0px 0px 24px 5px white;
}

#about {
	height: auto;
	width: 100%;
	position: relative;
}

#my-image
    /* this is the div */ {
	height: 15rem;
	width: 15rem;
	margin: auto;
	margin-top: -15vh;
	border: 4px solid white;
	border-radius: 50%;
	box-shadow: 0px 0px 12px 2px white;
}

@media screen and (max-width: 660px) {
	#body-header {
		height: 45vh;
	}
	.horizontal-list {
		font-size: 16px;
	}
	.horizontal-list li {
		margin: 0px 5px;
	}
	#my-name {
		font-size: 2rem;
	}
	#name-social-container {
		margin-top: 6vh;
	}
	.social-icons li a img {
		height: 40px;
		width: 40px;
	}
	.social-icons {
		margin-top: 20px;
	}
	#my-image
        /* this is the div */ {
		height: 10rem;
		width: 10rem;
		margin-top: -10vh;
	}
}

#my-image img {
	height: 100%;
	width: 100%;
	border-radius: 50%;
	/* these height and width are written in percentages, and percentage is a relative unit. so both of them will be 100% of their parent */
}

.about-text {
	margin: 5vh 20vw 5vh 20vw;
	font-family: monospace;
	font-weight: 900;
	color: grey;
	font-size: 20px;
	text-align: justify;
}

section {
	width: 100%;
	height: auto;
	display: flex;
	flex-direction: column;
	align-items: center;
	/* works along cross axis */
}

.top-and-bottom-margin {
	margin: 50px 0px;
}

section:nth-child(2n) {
	background-color: rgb(245, 244, 244);
}

section:nth-child(2n + 1) {
	background-color: white;
}

.section-heading {
	width: auto;
	padding: 20px 10px 10px;
	font-weight: 400;
}

.section-heading span {
	font-size: 40px;
	color: red;
	display: inline-block;
}

.section-heading span img {
	width: 40px;
	height: 40px;
	/* to adjust skills image size */
}
/* skills */

#skill-heading {
	position: relative;
	bottom: 0.3rem;
}

.mb75px {
	margin-bottom: 75px;
}

.skills-display {
	width: 70%;
	height: inherit;
	/* height:100px;
    border:2px solid black; */
	display: flex;
	flex-wrap: wrap;
	justify-content: space-around;
	align-items: center;
	padding-bottom: 40px;
}

.color1 {
	background-color: #cb202d;
}

.color2 {
	background-color: #085ba7;
}

.color3 {
	background-color: #ed7125;
}

.color4 {
	background-color: #e54b27;
}

.color5 {
	background-color: #35a849;
}

.color6 {
	background-color: #7b0fc8;
}

.color7 {
	background-color: #1a79d3;
}

.color8 {
	background-color: #069d7e;
}

.color9 {
	background-color: #d1008b;
}

.skill-progress {
	width: 13rem;
	background-color: darkgrey;
	height: 2.5rem;
	border-radius: 0.8rem;
	box-shadow: 0px 0px 12px 1px black;
	margin: 30px;
	position: relative;
}
/* percentage-classes */
.skill-progress span {
	position: absolute;
	/* in the javascript file, when the width of the inner div increases, then the text inside it should not wrap. thats why the position in abolute. and this position is absolute relative to the skill progress, whose position is relative */
}
.eighty-five-percent {
	width: 85%;
	height: inherit;
	border-radius: 0.8rem 0rem 0rem 0.8rem;
}

.ninety-percent {
	width: 90%;
	height: inherit;
	border-radius: 0.8rem 0rem 0rem 0.8rem;
}

.eighty-percent {
	width: 80%;
	height: inherit;
	border-radius: 0.8rem 0rem 0rem 0.8rem;
}

.seventy-five-percent {
	width: 75%;
	height: inherit;
	border-radius: 0.8rem 0rem 0rem 0.8rem;
}

.skill-name {
	color: white;
	padding-left: 15px;
	padding-top: 10px;
}
/* timeline */

.timeline-divider {
	position: absolute;
	height: 90%;
	width: 0%;
	border: 1px dashed #784eff;
	top: 5%;
	left: 50%;
}

.timeline-traveller {
	position: sticky;
	top: 20%;
	transform: rotate(90deg);
	z-index: 2;
}

.timeline {
	position: relative;
	width: 75%;
}

.timeline-box {
	position: relative;
	width: 46%;
	min-height: 150px;
	background-color: rgb(245, 245, 245);
	margin: 5px;
	left: -5%;
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
	overflow-wrap: break-word;
}

.timeline-box:nth-child(2n + 1)::after {
	content: "";
	border-radius: 50%;
	position: absolute;
	top: 50%;
	right: -19.5%;
	width: 0.5rem;
	height: 0.5rem;
	background-color: red;
	z-index: 1;
}

.timeline-box:nth-child(2n)::after {
	content: "";
	border-radius: 50%;
	position: absolute;
	top: 50%;
	left: -19.5%;
	width: 0.5rem;
	height: 0.5rem;
	background-color: red;
	z-index: 1;
}

.timeline-box:nth-child(2n + 1) {
	align-items: flex-end;
}

.timeline-box:nth-child(2n) {
	left: 58%;
}

.timeline-box:nth-child(2n + 1) .timeline-box-headings span:nth-child(2) {
	display: flex;
	flex-direction: column;
	align-items: flex-end;
}

.timeline-box:nth-child(2n) .timeline-box-headings span:nth-child(2) {
	display: flex;
	flex-direction: column;
	align-items: flex-start;
}

.timeline-box-headings span img {
	height: 50px;
	width: 50px;
	margin: 10px;
}

.timeline-box-title {
	color: #0000a9;
	font-weight: 900;
	font-size: 20px;
	font-family: sans-serif;
	width: 100%;
	overflow-wrap: break-word;
}

.timeline-box-headings {
	display: flex;
	flex-direction: row;
}

.timeline-box-title:nth-child(2n + 1) {
	text-align: right;
}

.timeline-box-title:nth-child(2n) {
	text-align: left;
}
/* .timeline-box:nth-child(2n+1) .timeline-box-headings span:nth-child(2)
{
    position:relative;
    align-items:flex-end;
    flex-wrap: wrap;
    margin: 13px;
}
.timeline-box:nth-child(2n) .timeline-box-headings span:nth-child(2)
{
    position:relative;
    align-items:flex-start;
} */

.timeline-box-company-name {
	color: orange;
	font-size: large;
	font-family: comic sans ms;
	font-weight: bold;
}

.timeline-box-duration {
	color: darkslategrey;
}

.timeline-box-headings {
	margin: 20px;
}

.timeline-box-description {
	margin: auto auto 20px;
	width: 80%;
	text-align: justify;
	justify-content: center;
}

@media screen and (max-width: 900px) {
	.timeline-divider {
		left: 5%;
	}
	.timeline-box {
		left: 12% !important;
		width: 80%;
	}
	/* .timeline-box:nth-child(2n) {
        left: 12%;
    } */
	.timeline-box:nth-child(2n + 1) {
		align-items: flex-start;
	}
	.timeline-box::after {
		left: -10.5% !important;
	}
	/* .timeline-box:nth-child(2n+1)::after {
        left: -10.5%;
    }
    .timeline-box:nth-child(2n)::after {
        left: -10.5%;
    } */
	html {
		font-size: 15px;
	}
	.timeline-box:nth-child(2n + 1) .timeline-box-headings span:nth-child(2) {
		align-items: flex-start !important;
	}
}

@media screen and (max-width: 600px) {
	.timeline-divider {
		left: 5%;
	}
	.timeline-box {
		left: 12% !important;
		width: 80%;
	}
	/* .timeline-box:nth-child(2n) {
        left: 12%;
    } */
	.timeline-box:nth-child(2n + 1) {
		align-items: flex-start;
	}
	.timeline-box::after {
		left: -11.5% !important;
	}
	/* .timeline-box:nth-child(2n+1)::after {
        left: -10.5%;
    }
    .timeline-box:nth-child(2n)::after {
        left: -10.5%;
    } */
	html {
		font-size: 15px;
	}
	.timeline-box:nth-child(2n + 1) .timeline-box-headings span:nth-child(2) {
		align-items: flex-start !important;
	}
}
/* portfolio */

.portfolio-display {
	width: 100%;
	height: inherit;
	/* height:100px;
    border:2px solid black; */
	display: flex;
	flex-wrap: wrap;
	justify-content: space-around;
	align-items: center;
}

.project {
	width: 400px;
	margin: 5px;
	padding-right:15px;
	padding-bottom:10px;
	border-radius: 5px;
	line-height: 30px;
}

.project:nth-child(1)>ul>li>ol>li>a
{
	text-decoration:none;
	color:blueviolet;
}
.project:nth-child(2)>ul>li>ol>li>a
{
	text-decoration:none;
	color:red;
}
.project:nth-child(3)>ul>li>ol>li>a
{
	text-decoration:none;
	color:green;
}


.project:nth-child(1)
{
	background-color:rgba(98, 0, 255, 0.1)
}
.project:nth-child(2)
{
	background-color:rgba(255, 0, 0, 0.1)
}
.project:nth-child(3)
{
	background-color:rgba(0, 128, 21, 0.1)
}
/* contact section */

#contact {
	background: linear-gradient(-45deg, red -100%, blue 200%);
}

.contact-content {
	width: 85%;
	height: inherit;
	/* height:100px;
    border:2px solid black; */
	display: flex;
	flex-wrap: wrap;
	justify-content: space-around;
	align-items: center;
	padding-bottom: 40px;
	flex-direction: row;
}

.contact-block {
	height: auto;
	width: 40%;
	background-color: rgba(255, 0, 191, 0.1);
	min-width: 170px;
	margin: 12px;
}

#contact-form {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

#contact-form div {
	margin: 5%;
	width: 67%;
}

#contact-form div:nth-child(4) {
	width: auto !important;
}

#contact-form div input {
	background-color: rgba(0, 0, 0, 0);
	border-width: 0px 0px 2px 0px;
	border-color: white;
	width: 100%;
	font-size: 20px;
	color: white;
}
/* send message button */

#send_message {
	background-color: rgba(0, 0, 0, 0);
	border: 3px solid white;
	color: white;
	border-style: solid;
	width: 100%;
	height: 100%;
	font-size: 20px;
	font-family: sans-serif;
}
/* second block in contact section */

.contact-block {
	color: white;
	font-size: 20px;
	padding: 40px;
}

.contact-block div span img {
	margin-bottom: -9px;
}

.contact-block div p {
	text-align: justify;
	margin-left: 20px;
	font-family: sans-serif;
}

#my-info {
	margin: 30px;
}

#my-info span:nth-child(2) {
	margin-left: 20px;
	font-family: sans-serif;
}

@media screen and (max-width: 900px) {
	.contact-content {
		width: 90%;
		flex-direction: column;
	}
	.contact-block {
		width: 70%;
	}
	.contact-block:nth-child(2) div h1 {
		text-align: center;
	}
	#contact-form div {
		width: 100%;
	}
	.contact-block div span img {
		display: block;
		margin: 20px auto;
	}
	.contact-block div p {
		margin: 0px;
	}
	#my-info span:nth-child(2) {
		margin: 0px;
		display: inline-block;
		width: 100%;
		text-align: center;
	}
}

         
       </style>
        <link rel="apple-touch-icon" sizes="180x180" href="media/apple-touch-icon.png">
        <link rel="icon" type="image/png" sizes="32x32" href="media/favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="media/favicon-16x16.png">
        <link rel="manifest" href="media/site.webmanifest">
        <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&amp;display=swap" rel="stylesheet">
        <script src="https://kit.fontawesome.com/68ec89a036.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">

    </head>
    <body>
        <header id="body-header">
            <nav>
                <ul class="horizontal-list text-center">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#about">About</a>
                    </li>
                    <li>
                        <a href="#skills">Skills</a>
                    </li>
                    <li>
                        <a href="#experience">Experience</a>
                    </li>
                    <li>
                        <a href="#education">Education</a>
                    </li>
                    <li>
                        <a href="#portfolio">Portfolio</a>
                    </li>
                    <li>
                        <a href="#contact">Contact</a>
                    </li>
                </ul>
            </nav>
    
            <div id="name-social-container">
                <!-- div for name -->
                <div class="text-center">
                    <h1 id="my-name">
                    Siddhant Gaikwad
                    </h1>
                </div>
                <!-- div for social icons -->
                <div>
                    <ul class="horizontal-list text-center social-icons">
                        <li>
                            <a href="https://github.com/SiddhantVgaikwad">
                                <i class="fa-brands fa-github"></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://www.linkedin.com/in/dktesiddhantgaikwad/">
                                <i class="fa-brands fa-linkedin"></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://www.facebook.com/">
                                <i class="fa-brands fa-facebook"></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://github.com/SiddhantVgaikwad">
                                <i class="fa-brands fa-car"></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://github.com/SiddhantVgaikwad">
                                <i class="fa-brands fa-plane"></i>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </header>
        <main>
            <section id="about">
                <div id="my-image">
                    <img src="IMG_4168.jpg">
                </div>
                <p class="text-center about-text">
                    Innovative Full Stack Web Developer (MERN STACK), with excellent UI and UX Design
                    skills and experience in creating beautiful and Responsive web applications with decent user interfaces.
                    Currently
                    pursuing my Bachelors from Electrical Engineering, I have several major projects to show as
                    my ability to help with pretty much any web based project. I have prior experience in making
                    catchy and beautiful front end with fully secured and fast under the hood back end of the
                    application. I also have experience in deploying websites on amazon AWS. I have my own
                    social networking website hosted on AWS ECC. 
                    <br>
                </p>
            </section>
            <section id="skills" class="top-and-bottom-margin">
                <h1 class="section-heading mb75px">
                    <span>
                        <i class="fa-regular fa-file-certificate"></i>
                    </span>
                    <span id="skill-heading">
                        SKILLS
                    </span>
                </h1>
                <div class="skills-display">
                    <!-- flexible container -->
                    <div class="skill-progress">
                        <div class="ninety-percent color1" data-skill-percent="90" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    Java
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color2" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    Python
                                </span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="skill-progress">
                        <div class="eighty-percent color4" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    JavaScript
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="ninety-percent color6" data-skill-percent="90" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    HTML
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color7" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    CSS
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color8" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    Bootstrap
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color5" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    Node.js
                                </span>
                            </div>
                        </div>
                    </div>

                    <div class="skill-progress">
                        <div class="ninety-percent color1" data-skill-percent="90" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    React JS &amp; Redux
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="ninety-percent color6" data-skill-percent="90" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    JQuery
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color5" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    AJAX
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color7" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    GIT
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="skill-progress">
                        <div class="eighty-percent color2" data-skill-percent="80" style="width: 0px;">
                            <div class="skill-name">
                                <span>
                                    Express JS
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
    
            <!-- experience -->
            <section id="experience" class="top-and-bottom-margin">
                <h1 class="section-heading mb75px">
                    <span>
                        <img src="media/experience.png">
                    </span>
                    <span id="skill-heading">
                        Work Experience
                    </span>
                </h1>
                <div class="timeline">
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/coding_ninjas.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                    Python and Machine Leaning 
                                </div>
                                <div class="timeline-box-company-name">
                                    Prygma Solution Ahmednagar
                                </div>
                                <div class="timeline-box-duration">
                                    Jan 2020 - Jan 2021 
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            Solved 600+ Python probleam well pursuing data-science and machine learning course at Prygma as a intern. I have also evaluated 10+ projects during this internship.
                        </div>
                    </div>
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/coding_ninjas.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                    Full Stack Developer Intern
                                </div>
                                <div class="timeline-box-company-name">
                                    Coding Ninjas
                                </div>
                                <div class="timeline-box-duration">
                                    April 20<sup>th</sup>, 2023 - Currently
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            In this internship I am responsible for fixing bugs whether they are on the backend or front
                            end, introducing new features, improving UI design e.t.c.
                        </div>
                    </div>
                    
                    <div class="timeline-divider">
                        <div class="timeline-traveller">
                            <img src="media/plane.png">
                        </div>
                    </div>
                </div>
            </section>
            <!-- education -->
    
    
            <section id="education" class="top-and-bottom-margin">
                <h1 class="section-heading mb75px">
                    <span>
                        <img src="media/education.png">
                    </span>
                    <span id="skill-heading">
                        Education
                    </span>
                </h1>
                <div class="timeline">
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/jamia_logo.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                B.Tech -Electronic Engg.
                                </div>
                                <div class="timeline-box-company-name" style="color:green">
                                    D.K.T.E Society's Textile & Engineering 
                                </div>
                                <div class="timeline-box-duration">
                                    Jan 2018 - Currently
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            Currently, an undergraduate student at D.K.T.E Society's Textile & Engineering, Ichalkanji , India. I am currently
                            Pursuing B.Tech from electronic and telecommunication engineering, being currently in final year.
                        </div>
                    </div>
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/coding_ninjas.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                    DS and Algos. in Java
                                </div>
                                <div class="timeline-box-company-name">
                                    Coding Ninjas India
                                </div>
                                <div class="timeline-box-duration">
                                    Dec 2022 - Mar 2023
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            Studied the basics of java, got familiar with OOPS in Java, and various important searching and
                            sorting algorithms, Recursion, Basics of Pointers, Dynamic Programming, Arrays, Time and Space
                            Complexity, Linked Lists, Stacks, Queues, Trees, BSTs, BTs, Hashmaps,
                            Priority Queues, Graphs, Tries and Huffman Coding.
                        </div>
                    </div>
                    
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/coding_ninjas.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                    Competitive Programming
                                </div>
                                <div class="timeline-box-company-name">
                                    Coding Ninjas India
                                </div>
                                <div class="timeline-box-duration">
                                    Jan 2023 - Apr 2023
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            As a part of this course I learnt many interesting advanced algorithms in C++ and some new
                            coding techniques, and ways to speed up the code using advance algorithms. Bit manipulation,
                            modulo arithmatic, advanced graphs, fenwick tree, DP and Bit masking,
                            Number theory, game theory, segment trees, computational geometry, fast fourier transform (FFT)
                            and HLT are some of the many topics I learnt as a part of this course.
                        </div>
                    </div>
                    <div class="timeline-box">
                        <div class="timeline-box-headings">
                            <span>
                                <img src="media/coding_ninjas.png">
                            </span>
                            <span>
                                <div class="timeline-box-title">
                                    Full Stack Web Development With Node JS and React JS
                                </div>
                                <div class="timeline-box-company-name">
                                    Coding Ninjas India
                                </div>
                                <div class="timeline-box-duration">
                                    May 2023 - Aug 2023
                                </div>
                            </span>
                        </div>
                        <div class="timeline-box-description">
                            As a part of this training program, I Studied the concepts of full stack web development, which
                            includes Front end web development as well as back end web development. I also studied React JS,
                            Redux
                            in depth in this training program and found it really fascinating how React uses state as its
                            root to manipulate most of the DOM Structure. After this course, MERN Stack Web Development
                            became my main strength.
                        </div>
                    </div>
                    <div class="timeline-divider">
                        <div class="timeline-traveller">
                            <img src="media/car.png" width="64px" height="64px">
                        </div>
                    </div>
                </div>
            </section>
    
            <!-- portfolio -->
    
            <section id="portfolio" class="top-and-bottom-margin">
                <h1 class="section-heading mb75px">
                    <span>
                        <img src="media/portfolio.png">
                    </span>
                    <span id="skill-heading">
                        Portfolio / Projects
                    </span>
                </h1>
                <div class="portfolio-display">
                    <div class="project">
                        <ul>
                            <li>
                                <h1>Front End Web Development</h1>
                                <ol class="front-end">
                                    <li><a href="https://parikshit223933.github.io/BassRize-Online-Music-Player/">BoomHead
                                            Online Music Player Front End</a></li>
                                   
                                    <li><a href="https://parikshit223933.github.io/Ping-Pong-Game-JS/">Ping Pong Game JS</a>
                                    </li>
                                    <li><a href="https://parikshit223933.github.io/Basic-calculator-using-javascript/">Calculator
                                            JS</a></li>
                                </ol>
                            </li>
                        </ul>
                    </div>
                    <div class="project">
                        <ul>
                            <li>
                                <h1>React JS Projects (MERN STACK)</h1>
                                <ol class="back-end">
    
                                    <li><a href="https://github.com/parikshit223933/SocialOrzix">SocialOrzix- Social
                                            Networking Website using Codeial API</a></li>
                                    <li><a href="https://parikshit223933.github.io/Reactive-Pod/">Reactive Pod- An iPod
                                            Emulator using React JS and Google's Firebase</a></li>
    
                                    <li><a href="https://github.com/parikshit223933/AgriMart">Agrimart- An Ecommerce Website
                                            based on MERN Stack, Hosted on AMAZON AWS ECC</a></li>
                                    <li><a href="https://github.com/parikshit223933/KVORA">KVORA- Quora's Clone Based On
                                            MERN Stack, Hosted on AMAZON AWS ECC (Comming Soon)</a></li>
                                    <li><a href="https://parikshit223933.github.io/analytics-india-magazine-intern-assignment/">Machine
                                            Hack- Single Page Front End</a></li>
                                    <li><a href="https://parikshit223933.github.io/Zelono-Movies/">Zelono Movies- Movies
                                            List App</a></li>
                                </ol>
                            </li>
                        </ul>
                    </div>
                    <div class="project">
                        <ul>
                            <li>
                                <h1>Back End Web Development</h1>
                                <ol class="back-end">
                                    <li><a href="http://www.comspaceexpress.codes/">Comspace Express- Fully Functional
                                            Social Media Website with Nodejs, Express JS and MongoDB</a></li>
                                    <li><a href="https://github.com/parikshit223933/Express-Contact-Bucket">Express Contact
                                            Bucket</a></li>
                                    <li><a href="https://github.com/parikshit223933/Dockett">Dockett-ToDo List App using
                                            Express JS</a></li>
                                </ol>
                            </li>
                        </ul>
                    </div>
                </div>
    
            </section>
    
            <!-- contact section -->
    
            <section id="contact">
                <h1 class="section-heading mb75px">
                    <span>
                        <img src="media/contact.png">
                    </span>
                    <span id="skill-heading">
                        Contact
                    </span>
                </h1>
    
                <div class="contact-content">
                    <!-- <div class="contact-block">
                        <form id="contact-form">
                            <div>
                                <input type="text" name="name" placeholder="Your Name" required>
                            </div>
                            <div>
                                <input type="text" name="email" placeholder="Your Email" required>
                            </div>
                            <div>
                                <input type="text" name="message" placeholder="Message" required>
                            </div>
                            <div style="width:40%;">
                                <button id="send_message">Send Message</button>
                            </div>
                        </form>
                    </div> -->
                    <div class="contact-block">
                        <div>
                            <h1 style="font-family: sans-serif;">
                                Get In Touch
                            </h1>
                        </div>
                        <div>
                            <p>
                                The following e-mail and phone numbers are only for professional purposes. Contact them only
                                if you are hiring for internships in Full Stack Web Development/ Data-Science or Machine
                                Learning fields.
                            </p>
                        </div>
                        <div>
                            <h1 style="font-family: sans-serif;">
                                Contact Information
                            </h1>
                        </div>
                        <div id="my-info">
                            <span>
                                <img src="media/location.svg" width="30px" height="30px">
                            </span>
                            <span>
                                Nagpur India
                            </span>
                        </div>
                        <div id="my-info">
                            <span>
                                <img src="media/gmail.svg" width="30px" height="30px">
                            </span>
                            <span>
                                siddhant333444@gmail.com
                            </span>
                        </div>
                        <div id="my-info">
                            <span>
                                <img src="media/call.svg" width="30px" height="30px">
                            </span>
                            <span>
                                +91-9730245395
                            </span>
                        </div>
                    </div>
                </div>
            </section>
    
    
    
        </main>
        <script> 
        "use strict";
/* code for smooth scroll */
function add_listener_to_the_element(itr, amount_of_scroll)
{
    itr.addEventListener('click', function (event)
    {
        event.preventDefault();/* to prevent the default behaviour, i.e. sudden scrolling by default */
        let position_of_element_from_top = document.getElementById(itr.innerText.toLowerCase()).getBoundingClientRect().y;
        var id = setInterval(function ()
        {
            window.scrollBy(0, amount_of_scroll);/* here the second entry is the amount by which i want to scroll */
            if (window.pageYOffset >= position_of_element_from_top) {
                clearInterval(id);
                return;
            }
        }, 1)/* this is the time after which it will scroll */
    })
}
var list = document.getElementsByClassName("horizontal-list")[0].getElementsByTagName('li');
for (let itr of list) {
    if (itr.innerText == "Home") {
        continue;
    }
    else if (itr.innerText == "About") {
        add_listener_to_the_element(itr, 10);
    }
    else if (itr.innerText == "Skills") {
        add_listener_to_the_element(itr, 20);
    }
    else if (itr.innerText == "Experience") {
        add_listener_to_the_element(itr, 20);
    }
    else if (itr.innerText == "Education") {
        add_listener_to_the_element(itr, 20);
    }
    else if (itr.innerText == "Portfolio") {
        add_listener_to_the_element(itr, 25);
    }
    else if (itr.innerText == "Contact") {
        add_listener_to_the_element(itr, 40);
    }
}

var list_of_bars = document.querySelectorAll('.skill-progress>div');
function set_width_to_zero()
{
    for (let bar of list_of_bars) {
        bar.style.width = "0";
    }
}
function in_view(bar)
{
    let element_distance = bar.getBoundingClientRect().top;
    if (element_distance < window.innerHeight) {
        return true;
    }
    return false;
}
function fill_bar(bar, percentage)
{
    let count = 0;
    let id = setInterval(function ()
    {
        bar.style.width = count.toString() + "%";
        if (count++ == percentage) {
            clearInterval(id);
        }
    }, 10)
}
function is_filled(bar)
{
    if (parseInt(bar.style.width) != 0) {
        return true;
    }
    return false;
}
function checker_in_view()
{
    for (let bar of list_of_bars) {
        if (in_view(bar) && !is_filled(bar)) {
            fill_bar(bar, bar.getAttribute("data-skill-percent"));
        }
    }
}
function again_on_top()
{
    let skills = document.getElementById('skills')
    let skills_distance = skills.getBoundingClientRect().top;
    if (skills_distance > window.innerHeight) {
        set_width_to_zero();
    }
}
function listener()
{
    checker_in_view();
    again_on_top()
}

set_width_to_zero();
window.addEventListener('scroll', listener);
/* instead of using setinterval i could also have used addeventlistener('scroll', checkscroll)
 and if the skills section is once visible i can keep a boolean variable to removeeventlistener once the animation is performed
or say, If the skills section is visible once on the screen. */
/* let id_global = setInterval(function ()
{
    let height_of_skills_section = document.getElementById('skills').getBoundingClientRect().y;
    if (height_of_skills_section < window.innerHeight) {
        clearInterval(id_global);
        let list_of_bars = document.querySelectorAll('.skill-progress>div');
        for (let bar of list_of_bars) {
            let count = 0;
            let id = setInterval(function ()
            {
                bar.style.width = (count++).toString() + "%";
                if (count > parseInt(bar.dataset.skillPercent)) {
                    clearInterval(id);
                    return;
                }
            }, 15)
        }
    }
}, 10)*/


        </script>
    
    
    </body>
</html>
