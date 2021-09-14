| [About](./index.html)      | [People](./people-page.html)         | [Research](./research-page.html) | [Publications](./publications_page.html)|

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 50%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

.btn {
  background-color: DodgerBlue;
  border: none;
  color: white;
  padding: 12px 16px;
  font-size: 16px;
  cursor: pointer;
}

/* Darker background on mouse-over */
.btn:hover {
  background-color: RoyalBlue;
}
  
</style>
</head>
<body>

<h2>Legend</h2>
<p><button class="btn"><i class="fa fa-television"></i> Poster</button>
<button class="btn"><i class="fa fa-file-pdf-o"></i> Article</button>
<button class="btn"><i class="fa fa-youtube-play"></i> Video</button>
<button class="btn"><i class="fa fa-mortar-board"></i> Edu Content</button>
  <button class="btn"><i class="fa fa-gamepad"></i> Interactive Content</button></p>

  <div class="row">
  <div class="card">
    <div class="column">
      <img src="./assets/projects/multibody/artwork007.png" style="width:100%">
    </div>
    <div class="column">
      <img src="./assets/projects/multibody/L1Lyapunov.gif" style="width:100%">
    </div>
     <div class="container">
        <h2>Project Title</h2>
        <p class="title">Collaborators</p>
        <p>Description of the project</p>
       
       <p>Icon buttons with text:</p>
<p><button class="btn" onclick="window.location.href='https://w3docs.com';"><i class="fa fa-television"></i></button>
<button class="btn" onclick="window.location.href='./assets/projects/multibody/L1Lyapunov.gif';"><i class="fa fa-file-pdf-o"></i> 2021 </button>
<button class="btn"><i class="fa fa-youtube-play"></i></button>
<button class="btn"><i class="fa fa-mortar-board"></i> Close</button>
  <button class="btn"><i class="fa fa-gamepad"></i> </button></p>
       
      </div>
  </div>
</div>
 
 <div class="row">
  <div class="card">
    <div class="column">
      <img src="./assets/img/vizor.png" style="width:100%">
    </div>
    <div class="column">
      <img src="./assets/img/vizor.png" style="width:100%">
    </div>
     <div class="container">
        <h2>Project Title</h2>
        <p class="title">Collaborators</p>
        <p>Description of the project</p>
       
        <p><button class="button">Contact</button></p>
      </div>
  </div>
</div>
  
</body>
</html>
