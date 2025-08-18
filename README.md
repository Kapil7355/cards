# cards
//created some card
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
  <style>
     body{
            display: flex;
            
        }
        .container{
            height: 400px;
            width: 300px;
            border: 2px solid black; 
            background-color:rgb(60, 235, 176);  
            margin: 20px; 
            border-radius: 10px;   
         }

         .card1{
            height: 200px;
            width: 200px;
            background-image: url(jawaharlal-nehru-GA52_l.jpg);
            background-size: 100%;
            border-radius: 10px; 
            border: 2px solid black;
            margin:auto;
            margin-top: 10px;
         }
         .card2{
             height: 200px;
            width: 200px;
            background-image: url(A_P_J_Abdul_Kalam.jpg);
            background-size: 100%;
            border-radius: 10px; 
            border: 2px solid black;
            margin:auto;
            margin-top: 10px;
         }
         .card3{
             height: 200px;
            width: 200px;
            background-image: url(sardar.jpg);
            background-size: 100%;
            border-radius: 10px; 
            border: 2px solid black;
            margin:auto;
            margin-top: 10px;
         }
         .card4{
             height: 200px;
            width: 200px;
            background-image: url(gandhi\ ji.jpg);
            background-size: 100%;
            border-radius: 10px; 
            border: 2px solid black;
            margin:auto;
            margin-top: 10px;
         }
        .name{
            text-align: center;
            font-weight: bold;
            margin-top: 20px;
        }

        .container:hover{
            margin: 30px;
            padding: 10px;
            border: 3px solid black;
            background-color: gray;
            color: white;

        
        }
  </style>
       
</head>
<body>
    <div class="container">
        <div class="card1">

        </div>
        <div class="name">
            Name-:Jawahar Lal Nehru<br>
            Born-:14 November 1989<br>
            Mother-:Swarooprani Nehru <br>
            Father-:MotiLal Nehru<br>
            Death:27 May 1964

        </div>
    </div>
        <div class="container">
        <div class="card2"> </div>
        <div class="name">
            Name-: A_P_J_Abdul_Kalam<br>
            Born-:15 October 1931<br>
            Mother-:Asheema <br>
            Father-:Jainulabdeen<br>
            Death:27 july 2015


        </div>
        </div>
    </div>
        <div class="container">
        <div class="card3">
          </div>  
           <div class="name">
            Name-:Saradar Valabh Bhai Patel<br>
             Born-:31 October 1875<br>
            Mother-:Ladba devi <br>
            Father-:Jhaverbhai Patel<br>
            Death:15 December 1950

            
        </div>
    </div>
        <div class="container">
        <div class="card4"></div>
        <div class="name">
            Name-:ManmohanDas Karamchad Gandhi<br>
            Born-:2 October 1869<br>
            Mother-:Kasturba  <br>
            Father-:Karamchad Gandhi<br>
            Death:30 january 1948


    
        </div>
    </div>
</body>
</html>
