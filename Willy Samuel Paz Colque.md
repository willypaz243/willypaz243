<style>
    .container {
        padding: 0.25in;
    }
    #header {
        display: flex;
    }
    #profile {
        margin-right: 20px;
    }
    #profile h1 {
        font-size: 16px;
    }
    #profile h2 {
        font-size: 15px;
        margin-top: 0px;
    }
    #profile ul {
        padding-left: 0px;
    }
    #profile ul li {
        display: flex;
        align-items: center;
    }
    #description {
        display: flex;
        flex-direction: column;
    }
    #description h2 {
        font-size: 15px;
        margin-bottom: 0.25em;
    }
    #description h3 {
        margin-top: 0px;
        font-size: 13px;
        margin-bottom: 2px;
    }
    #description p {
        font-size: 12px;
        text-wrap: balance;
        margin-bottom: 1em;
        margin-top: 0px;
    }
    #description ul {
        padding-left: 15px;
    }
    #description li {
        font-size: 12px;
        margin-bottom: 0em;
    }
    #technical-skills {
        display: flex;
        margin-top: 0px;
        margin-bottom: 0px;
        justify-content: space-between;
    }
    #technical-skills li {
      font-size: 11px;
      
    }
    * {
        font-family: Arial;
    }
    li {
        font-size: 12px;
        margin-bottom: 0px;
    }
    img {
        margin-right: 0px;
    }

    .skills h2 {
        font-size: 14px;
        margin-top: 0px;
        margin-bottom: 0px;
    }
    .skills h3 {
        font-size: 14px;
    }
    .skill h3 {
        font-size: 14px;
        margin-top: 1em;
        margin-bottom: 1px;
        text-align: center;
    }
    .skill ul li {
        font-size: 11px;
        list-style-position: outside;
    }
    @page {
        border: solid 1px;
    }
</style>
<div class='container'>
<div id="header" style="display: flex">
  <div id="profile" style="flex: 25%">
    <img
      src="https://media.licdn.com/dms/image/C4E03AQG-acHqUpOIyQ/profile-displayphoto-shrink_800_800/0/1622423412051?e=1713398400&v=beta&t=RT-XfsSVNSJdzmqlnJyZZ1ruXbabjSYbXnjzC-FL6kA"
      style="border-radius: 50%"
      width="250"
    />
    <h1 style='text-wrap: balance'><b>Willy Samuel Paz Colque</b></h1>
    <h2><b>Backend Developer</b></h2>
    <ul style="margin-buttom: 0px">
      <li>
        <img
          src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/gmail.ico"
          width="20"
          height="20"
          style="padding-right: 0.5em"
        />
        <a href="mailto:willypaz243@gmail.com">willypaz243@gmail.com</a>
      </li>
      <li>
        <img
          src="https://www.linkedin.com/favicon.ico"
          width="20"
          height="20"
          style="padding-right: 0.5em"
        />
        <a href="https://www.linkedin.com/in/willysamuelpaz/"
          > @willysamuelpaz</a
        >
      </li>
        <li>
            <img
            src="https://github.com/favicon.ico"
            width="20"
            height="20"
            style="padding-right: 0.5em"
            />
            <a href="https://github.com/willypaz243"> @willypaz243</a>
        </li>
    </ul>
    <h2><strong>Aptitudes</strong></h2>
    <ul>
      <li style="text-wrap: balance">- English level A2, I can read documentation without problems </li>
      <li style="text-wrap: balance">- Backend Development with multiple languages and frameworks</li>
      <li>- Teamwork</li>
      <li>- Autodidact</li>
      <li>- Good at Problem solving</li>
      <li>- I’m autonomous</li>
    </ul>
  </div>
  <div id="description" style="flex: 60%">
    <h2><b>About me</b></h2>
    <p>
      Hello, my name is Willy and I work as a Back-End Developer. I also have some skills in Front-End development and a lot of experience in programming. I am passionate about learning new technologies and developing large-scale and high-performance computing projects.
    </p>
    <h2><b>Experience</b></h2>
    <ul>
        <li>
            <h3>
                <strong>Web Developer</strong> <br/>
                <a href="https://www.linkedin.com/company/cannedhead/">Canned Head</a> November 2021 - November 2023
            </h3>
            <p>
    Fullstack web development with React, React Native, ExpressJS, NestJS, NodeJS, JS, TypeScript, AWS S3, and AWS Lambda in various web applications primarily focused on administration.
            <ul>
                <li>
                    I developed Backend solutions from scratch using Nodejs, ExpressJS and other technologies
                </li>
                <li>
                    I implemented unit testing to ensure code quality and performance
                </li>
                <li>
                    I improved database queries to reduce API latency and resource consumption in the cloud
                </li>
                <li>
                    I created scripts for AWS Lambda to manage Jira data and measure the productivity of development teams at Cannedhead
                </li>
            </ul>
            </p>
        </li>
        <li>
            <h3>
                <strong>Python Developer</strong><br/>Freelance | September 2020 - October 2021
            </h3>
            <p>
      API and chat bot development using Python, Flask, Rasa, Django, OpenCV, AWS S3, AWS Rekognition, and Tensorflow for various purposes, including content moderation, customer support chatbots, and emotion detection in videos.
            </p>
            <ul>
                <li>
                    I developed a microservice API with Flask and AWS Rekognition that filters and moderates the media content posted on the Agrinapsis social network.
                </li>
                <li>
                    I designed and trained a deep learning model with python and tensorflow that recognizes facial expressions and deployed it as an API with Flask and Django for the somos.ai platform.
                </li>
                <li>
                    I built chat bots with python and rasa that provide customer service and support for various domains and scenarios.
                </li>
            </ul>
        </li>
    </ul>
  </div>
</div>
<div class="skills">
    <h2><strong>Technical Skills</strong></h2>
        <div id="technical-skills" style="display: flex">
            <div class="skill" >
                <h3><strong>Programming Languages</strong></h3>
                <ul>
                <li>Python</li>
                <li>JavaScript</li>
                <li>TypeScript</li>
                <li>PHP</li>
                </ul>
            </div>
            <div class='skill'>
                <h3><strong>Frameworks</strong></h3>
                <div style="display: flex">
                    <ul>
                    <li>Django</li>
                    <li>Flask</li>
                    <li>FastAPI</li>
                    <li>ExpressJS</li>
                    </ul>
                    <ul>
                    <li>NestJS</li>
                    <li>ReactJS</li>
                    <li>React Native</li>
                    </ul>
                </div>
            </div>
            <div class='skill'>
                <h3><strong>Databases</strong></h3>
                <ul>
                <li>MySQL</li>
                <li>PostgreSQL</li>
                <li>MSSQL</li>
                <li>MongoDB</li>
                </ul>
            </div>
            <div class='skill'>
                <h3><strong>AWS API's:</strong></h3>
                <ul>
                <li>S3</li>
                <li>Lambda</li>
                <li>Cognito</li>
                <li>Rekognition</li>
                </ul>
            </div>
            <div class='skill'>
                <h3><strong>Tools</strong></h3>
                <ul>
                <li>GNU/Linux</li>
                <li>Git</li>
                <li>Postman</li>
                <li>Docker</li>
                </ul>
            </div>
        </div>
</div>
</div>
