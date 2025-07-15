<!DOCTYPE html>
<html lang="en">
  <link rel="stylesheet" href="prtfolialter.css">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Akbarsha</title>
<body>
    <div class="topnavi">
      <a href="midi">MEDIUM</a>
      <a href="https://www.linkedin.com/in/akbarsha-n-0160782a1?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LINKED IN</a>
      <a href="https://github.com/akbarsha8">GITHUB</a>
    </div>
<hr>
    <div class="conti"> <!--top header area-->
        <h1 class="topicname">Portfolio Website</h1>
        <p>This is Website is created by my own knowledge.</p>
        <div class="nxtlin">
          <a href="https://www.instagram.com/mr.200watts?igsh=MWpwdXFyMXIxbzViag==">INSTA /</a>
          <a href="https://www.facebook.com/AkbarSmartking?mibextid=kFxxJD">FB</a>
        </div>
    </div><br><hr class="topline" style="color: blue;">
    <center>
    <div class="mahpic"><br> <!--my photo area-->
      <img src="shablack.jpg" style="height: 200px; size-adjust: 100vh;">
      <h2 class="myname"><span>AKBARSHA N</span></h2><br>
      <h3 class="picabvco">Iam Pursing BSc Computer Science with Cyber Security.<br>I have basic knowledge of Cyber Security, Networking, Ethical Hacker, HTML & CSS.</h3>
    </div><br>
  </center><br><hr>

  <center>
  <!--after profile and bio-->
<br><br><br>
<section>
  <h2 class="uniqcerti">CERTIFICATIONS : &#x2B9B</h2>
<br><br><br>
    <div class="certificates">
        <div class="cert_data">
            <img src="ccds.jpeg" alt="Certificate 1">
            <h3>Cloud Computing and Distributed System</h3>
            <p>Issued by NPTEL</p>
        </div>
        <div class="cert_data">
            <img src="sec.avif" alt="Certificate 2">
            <a href="https://www.credly.com/badges/f19ad534-bfbf-491c-9332-151aaf7f0ff1/public_url"><h3>Initiation to Cyber security</h3></a>
            <p>Issued by CISCO</p>
        </div>
        <div class="cert_data">
          <img src="nsec.jpg" alt="Certificate 3">
          <h3>Network Security</h3>
          <p>Issued by Great Learning</p>
      </div>
    <div class="cert_data">
      <img src="designthink.jpg" alt="Certificate 5">
      <a href="https://www.credly.com/badges/f66fbe2d-1141-4c45-b776-e057585afc86/public_url"><h3>Design Thinking</h3></a>
      <p>Issued by IBM</p>
  </div>
  <div class="cert_data">
    <img src="digistar.jpeg" alt="Certificate 6">
    <a href="https://www.linkedin.com/learning/certificates/62d7dc0cee7ee7897fad81d55963da5e43762688e7872ab75a68effa26f9cea4?trk=share_certificate"><h3>Digital Networking Strategies</h3></a>
    <p>Issued by LinkedIn</p>
</div>
<div class="cert_data">
  <img src="vikseet.png" alt="Certificate 4">
  <h3>Viksit Bharat Quiz</h3>
  <p>Issued by Viksit Bharat 2047</p>
</div>
<div class="cert_data">
  <img src="aitrans.webp" alt="Certificate 7">
  <h3>AI Applications in the Transportation Industry</h3>
  <p>Issued by Computer Society of INDIA, Mumbai Chapter.</p>
</div>
    </div>
</section>
</div>
</center>
<br><br>
<section>
<div class="container">
  <h4>DO YOU HIRE ME OR NOT??</h4>
  <button id="movingBtn">Sorry</button>
  <br>

    <button class="btn" onclick="executeHack()">Yess</button>
<div id="hackerAnimation" class="hacker-animation">Requested Granted...</div>
</div>
<style>
  * {
    background-color: white;
    margin: 0;
    padding: 0;
    text-decoration: none;
    box-sizing: border-box;
    transition: 2s ease-in-out;
    list-style-type: none;
    align-items: center;
}
.topnavi {
    font-weight: bold;
    background-image: url(../picz/topcover.jpg);
}
.topnavi a, li{
    padding: 22px;
    margin: 3px;
    font-size: 18px;
    border-radius: 10px;
    float: right;
    cursor: pointer;
    border: none;
    background-color: white;
}
.topnavi,a:hover{
    background-color: yellow;
    box-shadow: 0px 0px 5px yellow, 0px 0px 40px yellow;
    transition: 0ms ease-in;
}
.topicname {
    color: red;
}
.nxtlin {
    padding: 15px;
    margin: 2px;
    float: right;
    cursor: pointer;
    border: none;
    transition: .1s ease-in;
}
.mahpic{
    margin-left: auto;
    margin-right: auto;
    padding: 30px;
}
.mahpic:hover {
        background: skyblue;
        padding: 20px;
        transition: 1ms ease-in-out
}
.picabvco:hover {
    background: white;
    padding: 20px;
}
.myname:hover{
    color: red;
    text-shadow: 0 0 1px red,0 0 1px red;
    transform: scale(1.0);
    transition: 1ms ease-in-out;
}
h2 .uniqcerti{
    color: black;
    float: left;
}
.certifications {
    max-width: 800px;
    margin: 50px auto;
    padding: 20px;
}
.certificates {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}
.cert_data {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}
.cert_data img {
    width: 100%;
    border-radius: 5px;
}
.cert_data h3 {
    margin: 10px 0;
    font-size: 1.2em;
}
.cert_data p {
    font-size: 0.9em;
    color: #555;
}

body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 50px;
}
#formContainer {
    display: none;
    margin-top: 20px;
}
input {
    display: block;
    margin: 10px auto;
    padding: 8px;
}
button {
    padding: 10px 15px;
    background-color: blue;
    color: white;
    border: none;
    cursor: pointer;
}

.container { position: relative; width: 600px; height: 400px; margin: auto; overflow: hidden; border: 2px solid black; text-align: center;}
        h2 { margin-bottom: 20px;}
        button { position: absolute; padding: 10px; cursor: pointer; top: 70px; }
        .link-btn { margin-top: 10px; display: inline-block; padding: 10px 15px; background: blue; color: white; text-decoration: none; border-radius: 5px;}


        .btn {
            background: #00ff00;
            color: #000;
            padding: 5px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            width: 85px;
            font-weight: bold;
            font-size: 18px;
        }
        .btn:hover {
            background: #00cc00;
        }
        @keyframes hackerEffect {
            0% { opacity: 0; }
            50% { opacity: 1; }
            100% { opacity: 0; }
        }
        .hacker-animation {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 50px;
            font-weight: bold;
            color: #00ff00;
            animation: hackerEffect 1.5s infinite;
            display: none;
        }

@media screen and (max-width:1200px) {
}
</style>
<script>
  const btn = document.getElementById("movingBtn");
      const container = document.querySelector(".container");

      function moveButton() {
          btn.style.transition = "top 0.1s, left 0.1s";
          btn.style.left = Math.random() * 250 + "px";
          btn.style.top = Math.random() * 150 + "px";
      }
      btn.addEventListener("mouseover", moveButton);



      function executeHack() {
            let hackerText = document.getElementById("hackerAnimation");
            hackerText.style.display = "block";
            setTimeout(() => {
                hackerText.style.display = "none";
                alert("Requested to admin! \n  Appreciate your support!,  Thank you for your time.");
            }, 2000);
        }
</script>

</section>
</body>
</html>
