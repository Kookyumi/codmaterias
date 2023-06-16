
<DOCTYPE html>
<html lang= "pt-br">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible"  content="IE-edge">
<meta name="viewport"  content="width-device-width, initial-scale=1.0">
<title>Cadastro matérias</title> 




<style>
    body{
	font-family: Arial, Helvetica, sans-serif;
	background-color:white;
	}
	

	H1{
	top:20%;
	color:  #0a1b2d  ;
	text-align: center;
    font-size:500%;	 
	
	}
	
		
	.box{
	 color: white;
	 position:absolute;
	 top:50%;
	 left:50%;
	 transform: translate(-50%,-50%);
	 background-color: rgba(0, 0, 0, 0.3); 
     padding:10px;
	 border-radius:50px;
	 width:40%;
     }
	 fieldset{
	  border: 5px solid #FF1700;
	  border-radius: 30px;
	 }
	 legend{
	 border: 1px solid  #FF1700;
	 padding: 10px;
	 text-align: center;
	 background-color:  #FF1700;
	 border-radius: 30px;
	 }
	 
	 .inputBox{
	  position: relative;
	  }
	  
	  .inputUser{
	  background: none;
	  border: none;
	  border-bottom: 1px solid white;
	  outline: none;
	  color: white;
	  font-size:15px;
	  width: 100%;
	  letter-spacing:2px;
	 }
	 
	.labelInput{
	 position:absolute;
	 top:0px;
	 left:0px;
	 pointer-events: none;
	 transition: .5s;
	 }
	 
	 .inputUser:focus ~ .labelInput,
	 .inputUser:valid ~ .labelInput{
	   top: -20px;
	   font-size:12px;
	   color: #FF1700;
	 }
	 #data_nascimento{
	  border: none;
	  padding: 8px;
	  border-radius:10px;
	  outline: none;
	  font-size:13px;
	 }
	 #submit{
	 background-image: linear-gradient(to right, #FF1700,#de3c33);
	 width: 100%;
	 border:none;
	 padding:15px;
	 color:white;
	 font-size:15px;
	 cursor:pointer;
	 border-radius:10px;
	}
	#submit:hover{
	background-image: linear-gradient(to right,#d1564f,#cf635d);
	 }
</style>	 

	 
	  <style media="screen">
      button[name="drop"] {
        border: none;
        cursor: pointer;
        background-color: #000000;
        padding: 18px;
        font-size: 18px;
        color: white;
      }

      .menu-drop {
        display: inline-block;
        position: absolute;
        top: 30%;

      }

      .drop-content {
        display: none;
        background-color: #000000;
        position: absolute;
        z-index: 1;
      }

      .drop-content a {
        color: white;
        padding: 8px 10px;
        text-decoration: none;
        display: block;
      }

      .drop-content a:hover {
        background-color: #58516B;
      }

      .menu-drop:hover .drop-content {
        display: block;
      }

      .menu-drop:hover button[name="drop"] {
        background-color: #171226;
      }
    </style>
	 
	
	 	 
</style>

<link rel="shortcut icon" href="favicon.ico" >
 
</head>
<body>

  
	
    <! -- menu -->
      <div class="menu-drop">
        <button type="button" name="drop">MENU ☰</button>
        <div class="drop-content">
          <a href="gerador.html">Início</a>
          <a href="cadastroprof.html">Cadastro Professor</a>
          <a href="horarios.html">Cadastro Horários</a>
          <a href="turmas.html">Cadastro Turmas</a>
          <a href="materias.html">Cadastro Matérias</a>
        </div>
      </div>
      <! -- menu -->


    <div class="box">
     <form action="">
	    <fieldset>
		 <legend><b> Cadastro Matérias</br></legend>
		 <br>
		 
		 
		   <div class="inputBox">
		  <input type="number" name="codigo"  id="codigo"  class="inputUser" required>
		  <label for="codigo" class="labelInput">Código:</label>
		  </div> 
		  
		  
		  
		      <br>
		 <div class="inputBox">
		  <input type="text" name="professor"  id="professor"  class="inputUser" required>
		  <label for="professor" class="labelInput">Professor:</label>
		  </div>
		  
  
         <br>
		 <div class="inputBox">
		  <input type="text" name="nome"  id="nome"  class="inputUser" required>
		  <label for="nome" class="labelInput">Nome:</label>
		  </div>
		  <br>
		  
		  <div class="inputBox">
		  <input type="text" name="cargahoraria"  id="cargahoraria"  class="inputUser" required>
		  <label for="cargahoraria" class="labelInput">Carga Horária:</label>
		  </div>
		  <br>

		    
		 <div class="inputBox">
		  <input type="text" name="curriculo"  id="curriculo"  class="inputUser" required>
		  <label for="curriculo" class="labelInput">Currículo:</label>
		  </div>
		  <br>
		  
		    
		  
		  <input type="submit" name="submit" id="submit">
		 
		
	
		
		 
		 </div>
		 </fieldset>
		 </form>
		 </div>
		  
		 </body>
		 </html>
