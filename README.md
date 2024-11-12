<!DOCTYPE html>
<html lang="eS">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="CSS/style.css">
    <title>TABLA SPOTIFY</title>
</head>


<body>
    <main>

        <table class="tabla">

        <tr class="pp">
                <th class="col1">#</th>
                <th class="col2-3" colspan="2">título</th>
                <th class="col4">ÁLBUM</th>
                <th class="col5">fecha de incorporación</th>
                <th class="col6">duración</th>
        </tr>
       
<!--***  ESTA LÍNEA YA ESTÁ BIEN. HACER LAS OTRAS COMO ÉSTA *******-->
        <tr>
            <td class="col1">1</td>
            <td class="col2"><img src="./IMG/album1.jpg" class="foto1"></td>
            <td class="col3"> Good4 u <span> Olivia Rodrigo </span>
            </td>
            
            <td class="col4">SOUR</td>
            <td class="col5">25 jun 2021</td>
            <td class="col6">2:58</td>

         </tr>

<!-- **************************************************************** -->

<!-- añadir las clases a los td -->

         <tr>
         
            <td class="col1">2</td>
            <td class="col2"><img src="./IMG/album2.jpg"></td>
              <td class="col3">BED <span>Joel Corry, RAYE, David Guetta</span> 
            </td>

              
            <td class="col4">BED</td>
            <td class="col5">29 abr 2021</td>
            <td class="col6">2:58</td>
              
            </tr>

              <tr>
              
                <td class="col1">3</td>
                <td class="col2"><img src="./IMG/album3.jpg"></td>
                <td class="col3">STAY <span>The Kid LAROI, Justin Bieber</span></td>
            <br>

              <td class="col4">LOVE FOREVER YOU</td>
              <td class="col5">HACE 22 días</td>
              <td class="col6">2.21</td>

             </tr>
        
             <tr>
                <td class="col1">4</td>
                <td class="col2"><img src="./IMG/album4.jpg"></td>
                 <td class="col3">Bad Habits <span>Ed Sheeran</span></td>
                

                 <td class="col4">Bad Hábits</td>
                 <td class="col5"">5 jul 2021</td>
                 <td class="col6"">3:51</td>
   
             </tr>

             <tr>
                <td class="col1">5</td>
                <td class="col2"><img src="./IMG/album5.jpg"></td>
                 <td class="col3">Levitating (Feat. DaBy) <span>Dua Lipa, DaBaby</span></td>
                

                 <td class="col4">Levitating (Feat. DaBy)</td>
                 <td class="col5">29 abr 2021</td>
                 <td class="col6">3:23</td>

             </tr>

             <tr>
                <td class="col1">6</td>

                <td class="col2"><img src="./IMG/album6.jpg"></td>
                 <td class="col3">Friday (Feat. DaBy) <span>Riton, Mufasa & Hypeman</span> </td>
                 

                 <td class="col4">dopamine</td>
                 <td class="col5">29 abr 2021</td>
                 <td class="col6">2:49</td>
             </tr>
    
             <tr>
                <td class="col1">7</td>
                <td class="col2"><img src="./IMG/album7.jpg"></td>
                <td class="col3">Take my Breath <span>The Weeknd</span></td>
               

                 <td class="col4">dopamine</td>
                 <td class="col5">29 abr 2021</td>
                 <td class="col6">2:49</td>
             </tr>

             <tr>
                <td class="col1">8</td>
                <td class="col2"><img src="./IMG/album8.jpg"></td>
                 <td>Get Up <span>Rival</span></td>

 
                 <td class="col4">Get Up</td>
                 <td class="col5">28 may 2021</td>
                 <td class="col6">2:49</td>
             </tr>

             <tr>
                <td class="col1">9</td>
                <td class="col2"><img src="./IMG/album9.jpg"></td>
                <td>Insustry Baby <span>Lil Nas X, Jack Harlow</span></td>

               

                <td class="col4">Insustry Baby</td>
                 <td class="col5">hace 22 días</td>
                 <td class="col6">2:14</td>
             </tr>

             
             <tr>
                <td class="col1">10</td>
                <td class="col2"><img src="./IMG/album10.jpg"></td>
               <td class="col3">Kiss me more <span>Doja Cat, SZA</span></td>

                 <td class="col4">Kiss me more</td>
                 <td class="col5">hace 22 días</td>
                 <td class="col6">2:14</td>
             </tr>
    
    
    
     </table>

    </main>
</body>
</html>





body {
    background-color: rgb(29, 29, 29);
}

.tabla {
    width: 100%;
    border-collapse: collapse;
    border: 2px solid white;
    
}

.pp{
    background-color: rgba(0, 110, 114, 0.815);
    
}

td, th{
  
    color: white;
    background-color: black;
   border: 2px solid white;
   
    
    
}

span {
    display: block;
    font-size: 10px;
    color: grey;
}
.col1{
    text-align: center;
}

.col2 {
    width: 80px;    
}


.col3{
    width: 240px;    
}

.col4 {
    text-align: center;
}
.col5 {
    text-align: center;
}

.col6 {
   text-align: center;
}

p{
    color: grey;
}
