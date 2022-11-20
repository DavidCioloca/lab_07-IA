# lab_07-IA


<html>
 <head>
  <title> Pagina profil Cioloca David </title>
   <style>
  
  
  header{
  height: 40px;
  background-color:#e1f0e5;
  }
  
  body{
  padding: 10px;
  margin: 0;
  font-family: Helvetica;
  }
  
  #Inceput{
  margin-left: 10px;
  
  }
  
  #NumePrenume{
  font-weight: 200;
  }
  
  table, td{
  border: 1px solid;
  border-collapse: collapse;
  padding: 10 px;
  }
  
  #Pasiuni{
  border-style:dashed;
  width: 50px;
  }
  
  #pozaprofil{
  border-radius: 30px:
  padding: 20px;
  position: absolute;
  top: 80px;
  right: 200px;
  opacity: 0.9;
  
  }
  footer{
  background-color:#e1f0e5;
  
 }
 
 </style>
 
  <script>
 function veziViitor()
    {
     document.getElementById("numeProfil").innerHTML = "Dr.ing.Nume

     var tabelEducatie = document.getElementById("tabEducatie");
     tabelEducatie.rows[0].cells[0].innerHTML = "UTCN";
     tabelEducatie.rows[0].cells[0].innerHTML = "Hello World";
     tabelEducatie.rows[0].cells[0].innerHTML = "42";

     document.getElementById("pozaProfil").src = "imagine.jpg";

     document.body.style.backgroundColor = "Tomato";
    
     var par = document.getElementByTagName("p");
     var i;
       for (i=0; i < par.length; i++)  {
           par[i].style.color = "black";
       }
   
     document.getElementById("pozaProfil").style.opacity = "0.9";
     document.getElementById("pozaProfil").style.border = "6px";
    }

   function arVarst()
    {
	var azi = new Date;
	var varstMea;
	
	var anNasc = document.getElementById("varsta").innerHTML;
	varstMea = azi.getFullYear() = parseInt(anNasc);
	document.getElementById("varsta").innerHTML = varstMea;
	}
	
  </script>
</head>

 <body>
   <header>
    <h1> id="Inceput">Pagina personala
	
	</h1>
	</header>
	<!-- inline -->
	<h1 id="numeProfil" style="color:#4e805b;">Cioloca David
	
	</h1>
	</header>
	<!-- inline -->
	<h1 id="numeProfil" style="color:#4e805b;">Cioloca David
	
	</h1>
	
	<img id="pozaProfil" src="20221102_181018.jpg" width="280" height="350px">
	
	
    <p id="mailProfil">Cioloca.Ad.David@student.utcluj.ro</p>
	<p>"Ne agatam cu disperare de logica pentru a parea ca traim intr o lume normala" Cioloca David 2020 </p>
	<p onmouseover = "arVarst ()" id="varsta">2003</p>
	
	<button onclick = "veziViitor()">Alta viata</button>
	
	<h2>Educatie</h2>
	<table id="tabEducatie">
	   <tbody><tr>
	        <td>
			      
       <td> Informatica aplicata- anul I https://etti.utcluj.ro/files/Acasa/Site/FiseDisciplina/TstRo/06.pdf</td>
     </tr>
     <tr>
       <td> Dispozitive electronice-seria A- anul II https://etti.utcluj.ro/files/Acasa/Site/FiseDisciplina/TstRo/12a.pdf </td>
     </tr>
       <td> Inginerie software- anul II https://etti.utcluj.ro/files/Acasa/Site/FiseDisciplina/TstRo/29.pdf </td>
     </tr>
   </tbody>
  </table>
   <h2> Hobby-uri </h2>
   <ul>
    <li>
     : :marker
       " Tenis "
    </li>
     : :marker
    <li>
     : :marker
       " Bicicleta "
    </li>
   </ul>
  </body>
 </html>
