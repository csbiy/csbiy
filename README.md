<head>
<link href="https://fonts.googleapis.com/css?family=Noto+Sans+KR&display=swap" rel="stylesheet">
    <style>  
    div,p,span{
        font-family: 'Noto Sans KR', sans-serif;
    }
    .tech{
        margin-bottom:8px;
    }
    #resume{
        display:none;
    }
    </style>
</head>
<hr>
<div style="margin-bottom:10px;">
배움을 좋아하는 주니어 개발자입니다👋🏻
</div>
<hr>

<body>
<div style="background-color:rgba(0, 0, 0, 0.9); text-align:center; vertical-align: middle; padding:20px 5px; color:white">
<p style="margin-bottom:20px; ">✍🏻 Tech Stacks ✍🏻</p> 
<div class="tech">Programming Language</div>
<img alt="Java" src ="https://img.shields.io/badge/java-007396.svg?&style=for-the-badge&logo=JAVA&logoColor=white"/> <img alt="R" src ="https://img.shields.io/badge/R-276DC3.svg?&style=for-the-badge&logo=R&logoColor=white"/> <img alt="Javascript" src ="https://img.shields.io/badge/Javascript-F7DF1E.svg?&style=for-the-badge&logo=Javascript&logoColor=black"/> <img alt="TypeScript" src ="https://img.shields.io/badge/TypeScript-3178C6.svg?&style=for-the-badge&logo=TypeScript&logoColor=black"/> <img alt="Python" src ="https://img.shields.io/badge/python-3776AB.svg?&style=for-the-badge&logo=PYTHON&logoColor=white"/> <img alt="C" src ="https://img.shields.io/badge/C-A8B9CC.svg?&style=for-the-badge&logo=C&logoColor=white"/>
<div class="tech">DataBase</div> 
<img alt="MYSQL" src ="https://img.shields.io/badge/MYSQL-4479A1.svg?&style=for-the-badge&logo=MYSQL&logoColor=white"/>
<div class="tech">WEB UI</div>
<img alt="HTML5" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img alt="CSS3" src ="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white"/> <img  src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<div class="tech">Infrastructue</div>
<img alt="amazon-aws" src ="https://img.shields.io/badge/amazon-aws-232F3E.svg?&style=for-the-badge&logo=amazon-aws&logoColor=white"/> <img alt="docker" src="https://img.shields.io/badge/docker-2496ED.svg?&style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">

<div class="tech" >Framework</div>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/NodeJS-Express-339933?style=for-the-badge&logo=node.js&logoColor=white"> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
</div>
<div>

 <p>개발 블로그 : <a href="https://devcs96.github.io/">https://devcs96.github.io/</a> </p>
</div>
<div>
 제가 궁금하세요? 👉🏻 <a id="resumeBtn"href="#">RESUME</a>
</div>
<div id="resume" >
<h1> resume </h1>
</div>
<script>
    const resume = document.qeurySelector("#resume");
    document.querySelector("#resumeBtn").addEventListener("click",()=>{
        if(resume.style.display=="block"){
            resume.style.display ="none";
        }else{
            resume.style.display = "block";
        }
    })
</script>
</body>