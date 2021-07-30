# javascript-onclick-events
<body>
  <button onclick="myMessage1()">Click Me</button>
  <button onclick="myMessage2()">Click Me</button>
<p onclick="myMessage3()">Demo</p>
 
  <script src="index.js"></script>
  function myMessage1(){
    alert("I'm Button 1");
}
function myMessage2(){
    alert("I'm Button 2");
}
function myMessage3(){
    alert("I am para");
}
  //Another
  <body>
  <button onclick="myMessage1()">Click Me</button>
  <button onclick="myMessage2()">Click Me</button>
<p id="me">Demo</p>
 
  <script src="index.js"></script>
    function myMessage1(){
    var myVar= document.querySelector("#me");
    myVar.innerHTML="Helo I'm paragraph1";
}
function myMessage2(){
    var myVar=document.querySelector("#me");
    myVar.innerHTML="Helo I'm paragraph 2";
}
    //another
var myVar=document.querySelector("#me");
function myMessage1(){
      myVar.innerHTML="Helo I'm paragraph1";
}
function myMessage2(){
        myVar.innerHTML="Helo I'm paragraph 2";
}
    //images
    <body>
  <button onclick="myPicture1()">Towfique</button>
  <button onclick="myPicture2()">Towhid</button>
 <p></p>
  <img id="me" src="#" alt="">
  <script src="index.js"></script>
</body>
    var myVar=document.querySelector("#me");
function myPicture1(){
      myVar.src="images/towfique.jpg";
}
function myPicture2(){
    myVar.src="images/towhid.jpg";
}

