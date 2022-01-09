<!DOCTYPE html>
<html lang="en">
<head>																										      
       <center><div class="stage" style="width: 120px; height: 120px;">
            <div class="cubespinner">
                <div class="face1">hello</div>
                <div class="face2">i am newbie</div>
                <div class="face3">web developer</div>
                <div class="face4">how are you</div>
                <div class="face5">come</div>
                <div class="face6">explore my website</div></center
            </div>
        </div>
        

<style>
			body{
margin-top:50%;
padding:0px;
background:#262626;
}
.box{
position:absolute;
top:50%;
left:50%;
width:15%;
height:15%;
transform:translate(-50%,-50%);
}
.box span{
width:20px;
height:20px;
background:#ff0;
display:block;
border-radius:50%;
position:absolute;
}
.box1{
position:absolute;
top:10%;
left:80%;
width:15%;
height:15%;
transform:translate(-50%,-50%);
}
.box1 span{
width:20px;
height:20px;
background:#ff0;
display:block;
border-radius:50%;
position:absolute;
}
.box1 span:nth-child(1) {
background:yellow;
box-shadow:0 0 25px yellow;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
}
.box1 span:nth-child(2) {
background:lime;
box-shadow:0 0 25px lime;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1s;
-moz-animation-delay:-1s;
-o-animation-delay:-1s;
-ms-animation-delay:-1s;
animation-delay:-1s;
}
.box1 span:nth-child(3) {
background:#ff005a;
box-shadow:0 0 25px #ff005a;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-0.5s;
-moz-animation-delay:-0.5s;
-o-animation-delay:-0.5s;
-ms-animation-delay:-0.5s;
animation-delay:-0.5s;
}
.box1 span:nth-child(4) {
background:#3896ff;
box-shadow:0 0 25px #3896ff;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1.5s;
-moz-animation-delay:-1.5s;
-o-animation-delay:-1.5s;
-ms-animation-delay:-1.5s;
animation-delay:-1.5s;
}
.box span:nth-child(1) {
background:yellow;
box-shadow:0 0 25px yellow;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
}
.box span:nth-child(2) {
background:lime;
box-shadow:0 0 25px lime;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1s;
-moz-animation-delay:-1s;
-o-animation-delay:-1s;
-ms-animation-delay:-1s;
animation-delay:-1s;
}
.box span:nth-child(3) {
background:#ff005a;
box-shadow:0 0 25px #ff005a;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-0.5s;
-moz-animation-delay:-1s;
-o-animation-delay:-0.5s;
-ms-animation-delay:-0.5s;
animation-delay:-0.5s;
}
.box span:nth-child(4) {
background:#3896ff;
box-shadow:0 0 25px #3896ff;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1.5s;
-moz-animation-delay:-1.5s;
-o-animation-delay:-1.5s;
-ms-animation-delay:-1.5s;
animation-delay:-1.5s;
}
.box2{
position:absolute;
top:80%;
left:20%;
width:15%;
height:15%;
transform:translate(-50%,-50%);
}
.box2 span{
width:20px;
height:20px;
background:#ff0;
display:block;
border-radius:50%;
position:absolute;
}
.box2 span:nth-child(1) {
background:yellow;
box-shadow:0 0 25px yellow;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
}
.box2 span:nth-child(2) {
background:lime;
box-shadow:0 0 25px lime;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1s;
-moz-animation-delay:-1s;
-o-animation-delay:-1s;
-ms-animation-delay:-1s;
animation-delay:-1s;
}
.box2 span:nth-child(3) {
background:#ff005a;
box-shadow:0 0 25px #ff005a;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-0.5s;
-moz-animation-delay:-0.5s;
-o-animation-delay:-0.5s;
-ms-animation-delay:-0.5s;
animation-delay:-0.5s;
}
.box2 span:nth-child(4) {
background:#3896ff;
box-shadow:0 0 25px #3896ff;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1.5s;
-moz-animation-delay:-1.5s;
-o-animation-delay:-1.5s;
-ms-animation-delay:-1.5s;
animation-delay:-1.5s;
}
.box3{
position:absolute;
top:80%;
left:80%;
width:15%;
height:15%;
transform:translate(-50%,-50%);
}
.box3 span{
width:20px;
height:20px;
background:#ff0;
display:block;
border-radius:50%;
position:absolute;
}
.box3 span:nth-child(1) {
background:yellow;
box-shadow:0 0 25px yellow;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
}
.box3 span:nth-child(2) {
background:#08ff28;
box-shadow:0 0 25px #08ff28;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1s;
-moz-animation-delay:-1s;
-o-animation-delay:-1s;
-ms-animation-delay:-1s;
animation-delay:-1s;
}
.box3 span:nth-child(3) {
background:#ff005a;
box-shadow:0 0 25px #ff005a;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-0.5s;
-moz-animation-delay:-0.5s;
-o-animation-delay:-0.5s;
-ms-animation-delay:-0.5s;
animation-delay:-0.5s;
}
.box3 span:nth-child(4) {
background:#3896ff;
box-shadow:0 0 25px #3896ff;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1.5s;
-moz-animation-delay:-1.5s;
-o-animation-delay:-1.5s;
-ms-animation-delay:-1.5s;
animation-delay:-1.5s;
}
.box4{
position:absolute;
top:10%;
left:20%;
width:15%;
height:15%;
transform:translate(-50%,-50%);
}
.box4 span{
width:20px;
height:20px;
background:#ff0;
display:block;
border-radius:50%;
position:absolute;
}
.box4 span:nth-child(1) {
background:#fff900;
box-shadow:0 0 25px #fff900;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
}
.box4 span:nth-child(2) {
background:#08ff28;
box-shadow:0 0 25px #08ff28;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1s;
-moz-animation-delay:-1s;
-o-animation-delay:-1s;
-ms-animation-delay:-1s;
animation-delay:-1s;
}
.box4 span:nth-child(3) {
background:#ff005a;
box-shadow:0 0 25px #ff005a;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-0.5s;
-moz-animation-delay:-0.5s;
-o-animation-delay:-0.5s;
-ms-animation-delay:-0.5s;
animation-delay:-0.5s;
}
.box4 span:nth-child(4) {
background:#3896ff;
box-shadow:0 0 25px #3896ff;
-webkit-animation:glow 2s linear infinite;
-moz-animation:glow 2s linear infinite;
-o-animation:glow 2s linear infinite;
-ms-animation:glow 2s linear infinite;
animation:glow 2s linear infinite;
-webkit-animation-delay:-1.5s;
-moz-animation-delay:-1.5s;
-o-animation-delay:-1.5s;
-ms-animation-delay:-1.5s;
animation-delay:-1.5s;
}
@-ms-keyframes glow{
0%{
top:0%;
left:0%;
}
20%{
top:0%;
left:50%;
}
25%{
top:0%;
left:50%;
}
50%{
top:50%;
left:50%;
}
55%{
top:50%;
left:50%;
}
75%{
top:50%;
left:0%;
}
80%{
top:50%;
left:0%;
}
100%{
top:0%;
left:0%;
}
}

@-o-keyframes glow{
0%{
top:0%;
left:0%;
}
20%{
top:0%;
left:50%;
}
25%{
top:0%;
left:50%;
}
50%{
top:50%;
left:50%;
}
55%{
top:50%;
left:50%;
}
75%{
top:50%;
left:0%;
}
80%{
top:50%;
left:0%;
}
100%{
top:0%;
left:0%;
}
}

@-moz-keyframes glow{
0%{
top:0%;
left:0%;
}
20%{
top:0%;
left:50%;
}
25%{
top:0%;
left:50%;
}
50%{
top:50%;
left:50%;
}
55%{
top:50%;
left:50%;
}
75%{
top:50%;
left:0%;
}
80%{
top:50%;
left:0%;
}
100%{
top:0%;
left:0%;
}
}

@-webkit-keyframes glow{
0%{
top:0%;
left:0%;
}
20%{
top:0%;
left:50%;
}
25%{
top:0%;
left:50%;
}
50%{
top:50%;
left:50%;
}
55%{
top:50%;
left:50%;
}
75%{
top:50%;
left:0%;
}
80%{
top:50%;
left:0%;
}
100%{
top:0%;
left:0%;
}
}

@keyframes glow{
0%{
top:0%;
left:0%;
}
20%{
top:0%;
left:50%;
}
25%{
top:0%;
left:50%;
}
50%{
top:50%;
left:50%;
}
55%{
top:50%;
left:50%;
}
75%{
top:50%;
left:0%;
}
80%{
top:50%;
left:0%;
}
100%{
top:0%;
left:0%;
}
}
	
</style>





<style>
				.stage {
    margin: 100px 50px 50px 50px;
}

  @-webkit-keyframes spincube {
    from,to  { -webkit-transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg); }
    16%      { -webkit-transform: rotateY(-90deg);                           }
    33%      { -webkit-transform: rotateY(-90deg) rotateZ(90deg);            }
    50%      { -webkit-transform: rotateY(-180deg) rotateZ(90deg);           }
    66%      { -webkit-transform: rotateY(-270deg) rotateX(90deg);           }
    83%      { -webkit-transform: rotateX(90deg);                            }
  }

  @keyframes spincube {
    from,to {
      -moz-transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg);
      -ms-transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg);
      transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg);
    }
    16% {
      -moz-transform: rotateY(-90deg);
      -ms-transform: rotateY(-90deg);
      transform: rotateY(-90deg);
    }
    33% {
      -moz-transform: rotateY(-90deg) rotateZ(90deg);
      -ms-transform: rotateY(-90deg) rotateZ(90deg);
      transform: rotateY(-90deg) rotateZ(90deg);
    }
    50% {
      -moz-transform: rotateY(-180deg) rotateZ(90deg);
      -ms-transform: rotateY(-180deg) rotateZ(90deg);
      transform: rotateY(-180deg) rotateZ(90deg);
    }
    66% {
      -moz-transform: rotateY(-270deg) rotateX(90deg);
      -ms-transform: rotateY(-270deg) rotateX(90deg);
      transform: rotateY(-270deg) rotateX(90deg);
    }
    83% {
      -moz-transform: rotateX(90deg);
      -ms-transform: rotateX(90deg);
      transform: rotateX(90deg);
    }
  }

  .cubespinner {
    -webkit-animation-name: spincube;
    -webkit-animation-timing-function: ease-in-out;
    -webkit-animation-iteration-count: infinite;
    -webkit-animation-duration: 12s;

    animation-name: spincube;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
    animation-duration: 12s;

    -webkit-transform-style: preserve-3d;
    -moz-transform-style: preserve-3d;
    -ms-transform-style: preserve-3d;
    transform-style: preserve-3d;

    -webkit-transform-origin: 60px 60px 0;
    -moz-transform-origin: 60px 60px 0;
    -ms-transform-origin: 60px 60px 0;
    transform-origin: 60px 60px 0;
  }

  .cubespinner div {
    position: absolute;
    width: 300px;
    height: 300px;
    background: rgba(255,255,255,0.9);
    line-height:200px;
    text-align: center;
    font-size: 50px;
  }

  .cubespinner .face1 {
    color: CadetBlue;
    -webkit-transform: translateZ(60px);
    -moz-transform: translateZ(60px);
    -ms-transform: translateZ(60px);
    transform: translateZ(60px);
  }
  .cubespinner .face2 {
    color: ForestGreen;
    -webkit-transform: rotateY(90deg) translateZ(60px);
    -moz-transform: rotateY(90deg) translateZ(60px);
    -ms-transform: rotateY(90deg) translateZ(60px);
    transform: rotateY(90deg) translateZ(60px);
  }
  .cubespinner .face3 {
    color: blue;
    -webkit-transform: rotateY(90deg) rotateX(90deg) translateZ(60px);
    -moz-transform: rotateY(90deg) rotateX(90deg) translateZ(60px);
    -ms-transform: rotateY(90deg) rotateX(90deg) translateZ(60px);
    transform: rotateY(90deg) rotateX(90deg) translateZ(60px);
  }
  .cubespinner .face4 {
    color: orange;
    -webkit-transform: rotateY(180deg) rotateZ(90deg) translateZ(60px);
    -moz-transform: rotateY(180deg) rotateZ(90deg) translateZ(60px);
    -ms-transform: rotateY(180deg) rotateZ(90deg) translateZ(60px);
    transform: rotateY(180deg) rotateZ(90deg) translateZ(60px);
  }
  .cubespinner .face5 {
    color: red;
    -webkit-transform: rotateY(-90deg) rotateZ(90deg) translateZ(60px);
    -moz-transform: rotateY(-90deg) rotateZ(90deg) translateZ(60px);
    -ms-transform: rotateY(-90deg) rotateZ(90deg) translateZ(60px);
    transform: rotateY(-90deg) rotateZ(90deg) translateZ(60px);
  }
  .cubespinner .face6 {
    color: DarkSlateGray;
    -webkit-transform: rotateX(-90deg) translateZ(60px);
    -moz-transform: rotateX(-90deg) translateZ(60px);
    -ms-transform: rotateX(-90deg) translateZ(60px);
    transform: rotateX(-90deg) translateZ(60px);
  }
        </style>
  		<title>My personal portfolio</title>
				<style type="text/css">
								body {
								background-color: black;
								{
				</style>
				<style>
				p {
				color:black;
				background-color: white;
				</style><
								<style>
												ul {
												text-align: center;
												}
								</style><nav>
  <ul><h1>
       <li><a href="#">COURSES</a></li><br>
       <li><a href="#">DISCUSS</a></li><br>
       <li><a href="#">BLOG</a></li><br>
   </ul></h1
</nav></text>
<style>
				nav ul {
				padding: 0px 0;
				min-width: 100%;
				}
		     </style>
												<style>
												nav ul li {
												display: inline-block;
												}											
</style>	
<style>
				
</style>
</head>	
<body>
				
				
<div class="box">
<span></span>
<span></span>
<span></span>
<span></span>
</div>
<div class="box1">
<span></span>
<span></span>
<span></span>
<span></span>
</div>
<div class="box2">
<span></span>
<span></span>
<span></span>
<span></span>
</div>
<div class="box3">
<span></span>
<span></span>
<span></span>
<span></span>
</div>
<div class="box4">
<span></span>
<span></span>
<span></span>
<span></span>
</div>
				
				
				
				<link rel="stylesheet" href="style.css">
				<style>
								b {
								color: white;
								font-size: 500%;
								font-family: cursive;
								}								
			  </style>
			  <text align="center"<ins><h2><b>Welcome</b></h2></text>
			 <img src="https://i.ibb.co/74MRpBr/IMG20220107113925.jpg" alt="IMG20220107113925" border="0"></a>
				<style>
								img {
	background-color: black;
	margin: 0% 0%;
    padding-top: 0%;
    padding-bottom: 0%;
    
   
}
img {
border-radius: 50%;
width: 100%;
}
								
				</style>
				
				<style>
								img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
				</style><br>
				<h2><text align="center"<h1><p><del>Proffesional Web Developer×</del></p></h2>
				<style>
								del {
								color: red;
								}
				</style>
				<h3><text align="center"<h2><p>Newbie Web Developer√</p></h3>										
				<style>
								p {
								font-family: cursive;
								font-size: 250%;
								}
				</style><br>
				<h3><text align="center">
				<p>My name is Jhonder Tayam ,<br> Grade 11-ICT-Programming,<br>19 years old<br> and i currently live <br>here in Dasmariñas Cavite Phillippines<br> and i love coding,<br>So i always study and reading <br>a lot of Programming Language every day <br>to become a Programmer.....</text></h3></p>
				<style>
								p {
								color: black;
								}
				</style><br>
				<style>
								h1 {
								font-family: cursive;
								font-size: 400%;
								}
				</style>
				
				<text align="center"<style>h1 {
				color: white;
				    }</style><h1>My<br>Hobbies</h1></text>
			<text align="center"	<h5>										
							<ul>
												<p>Reading√</p><br>
												<p>Watching Anime√</p><br>
												<p>Playing Chess√</p><br>
												<p>Drawing√</p><br>
												<p>Coding√</p><br>
								</ul>	
								</text></text></h5>																																																					
								<text align="center"<caption><h1>My<br> Knowledge</h1></caption><br>
								<br>
								<br>							
										<text align="center">							
											<h1><th>HTML5</th></h1><a href="https://ibb.co/BNmHmkV"><img src="https://i.ibb.co/vYbCb9x/2048px-HTML5-logo-and-wordmark-svg.png" alt="2048px-HTML5-logo-and-wordmark-svg" border="0"></a><br /><a target='_blank' href='https://usefulwebtool.com/html-entities'></a><h1><p>10%</h1></h1><br>										
												<h1><th>CSS3</th></h1>
												<a href="https://imgbb.com/"><img src="https://i.ibb.co/SvV7rf3/download.png" alt="download" border="5"></a><br /><a target='_blank' href='https://usefulwebtool.com/html-entities'></a><br /><h1><p>10%</p></h1>																								
												<h1><td>JavaScript</td></h1><a href="https://imgbb.com/"><img src="https://i.ibb.co/T4NH8rW/images-1.png" alt="images-1" border="0"></a><br /><a target='_blank' href='https://usefulwebtool.com/html-entities'></a><br /><h1><p>10%</p></h1>
		       							<h1><td>jquery</td></h1><a href="https://imgbb.com/"><img src="https://i.ibb.co/qJjy6N8/images.png" alt="images" border="0"></a><br /><a target='_blank' href='https://usefulwebtool.com/html-entities'></a><br /><h1><p>10%</p></h1>											
								</tr></text>											
								<text align="center"<tr>
												
								
								<style>
											p:hover {
												background-color: yellow;
												border: 20px dotted skyblue;
												text-color: black;
												margin: 3%;
												padding-top: 0%;
												padding-bottom: 0%;
												border-radius: 50px;}
												</style>
				
				
												<tfoot><!-- |tfoot can be placed before or after tbody. |--></tfoot>
								</tr>
				</table>

				
				<!--Social-->
				<style>
								h1 {
								color: white;
								}
				</style>
				<h1>My Social Media Account </h1>
        <div class="subheading">Social</div>
        <div class="social">
            <h1><a href="facebooklink" target="_blank">
                <div class ="https://ibb.co/YpWjgWY"><img src="https://i.ibb.co/D5bKdbs/Screenshot-2022-01-02-19-45-57-35.png" alt="Screenshot-2022-01-02-19-45-57-35" border="2"></a>                    <div class="fab fa-facebook-square">Facebook</div>
                </div></h1>
            </a>
             <h1><a href="tiktok" target="_blank">
                 <div class ="https://ibb.co/WkyWZST"><img src="https://i.ibb.co/k48gjYd/Screenshot-2022-01-03-19-43-30-02.png" alt="Screenshot-2022-01-03-19-43-30-02" border="2"></a>
                     <span style="padding-left:10px;"></span>
                     <div class="fab fa-twitter-square">Tiktok</div>
                 </div></h1>
             </a>
             <h1><a href="linkedInlink" target="_blank">
                 <div class="https://ibb.co/BrkpLK3"><img src="https://i.ibb.co/s67fjJR/1641213770678-513810099.jpg" alt="1641213770678-513810099" border="2"></a>
                     <span style="padding-left:10px;"></span>
                     <div class="fab fa-linkedin">LinkedIn</div>
                </div></h1>
             </a>
            <h1><a href="githublink" target="_blank">
                <div class = "https://ibb.co/hfc1q5K"><img src="https://i.ibb.co/gVdFn1D/1641213895060203826634.jpg" alt="1641213895060203826634" border="2"></a>
                    <span style="padding-left:10px;"></span>
                  <div class="fab fa-github">Github</div>
                </div></h1>
             </a>
        </div>
        <h1><a href="githublink" target="_blank">
                <div class = "https://ibb.co/TTVTP4S"><img src="https://i.ibb.co/Dbxbw9y/1641214022102-1775217493.jpg" alt="1641214022102-1775217493" border="2"></a>
                    <span style="padding-left:10px;"></span>
                  <div class="fab fa-stack-overflow">Stack Overflow</div>
                </div></h1>
             </a>
        </div><br>				
				</body>
</html>
