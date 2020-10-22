<!DOCTYPE html>
<html lang="de" dir="ltr">
  <head>
    <meta charset="utf-8">
    <style>
    body{
    background-color:#afa;
    text-align: center; }

    h1{
    color:darkblue; }

    h2{
    margin-right:92%; }

    .Box1{
    position: absolute;
    background-color: white ;
    width: 200px;
    height: 200px;
    margin-left: 45%;
    margin-top: 5%;
    border: 3px;
    border-color: black;
    border-style: solid;
    border-radius: 10%;}

    .Box2{
    background-color: white;
    width: 200px;
    height: 200px;
    margin-left: 32%;
    margin-top: 5%;
    position: absolute;
    border: 3px;
    border-color: black;
    border-style: solid;
    border-radius: 10%;}

    .Box3{
    background-color: white ;
    width: 200px;
    height: 200px;
    margin-left: 58%;
    margin-top: 5%;
    position: absolute;
    border: 3px;
    border-color: black;
    border-style: solid;
    border-radius: 10%; }

    #start{
      margin-top:19%;
      margin-left: 37%;
      width: 100px;
      height: 100px;
      top: 100px;
      left: 250px;
      border: 3px solid black;
      text-align: center;
      border-radius: 100px;
      color: white;
      background-color: red;
      box-shadow: inset 5px 5px 5px 5px rgba(8,20,84,1); }

      #autostart{
        position: absolute;
        margin-top:25%;
        margin-left: -4%;
        color: white;
        background-color: red;
        border-radius: 10%;
        border: 3px solid black;
        height: 60px;
        width:  75px;
        box-shadow: inset 5px 5px 5px 5px rgba(8,20,84,1); }

      #max{
        position: absolute;
        margin-top: 20%;
        left: 60%;
        color:black;
        background-color: gold ;
        border: 3px solid black;
        border-radius: 10%;
        height: 60px;
        width:  75px;
        box-shadow: inset 3px 3px 3px 3px rgba(0,0,0,1); }

        #min{
          position: absolute;
          margin-top: 20%;
          margin-left: -16%;
          color:black;
          background-color: gold ;
          border: 3px solid black;
          border-radius: 10%;
          height: 60px;
          width:  75px;
          box-shadow: inset 3px 3px 3px 3px rgba(0,0,0,1); }

          #betup{
            position: absolute;
            margin-top: 20%;
            margin-left: -21%;
            color:black;
            background-color: #d5dbe3;
            border: 3px solid black;
            border-radius: 10%;
            height: 60px;
            width:  75px;
            box-shadow: inset 3px 3px 3px 3px rgba(0,0,0,1);
          }

          #betdown{

            position: absolute;
            top:320px;
            left: -270px;
            color:black;
            background-color: #d5dbe3;
            border: 3px solid black;
            border-radius: 10%;
            height: 60px;
            width:  75px;
            box-shadow: inset 3px 3px 3px 3px rgba(0,0,0,1);
          }
</style>

<title>Spieleautomat</title>
</head>
    <body>
    <h1>Spieleautomat</h1>

    <h2> Guthaben :</h2>

    <div class="Box1">
1
    </div>

    <div class="Box2">
2
    </div>

    <div class="Box3">
3
</div>
    <button id="start" type="button" name="button"><h3>Start</h3></button>
    <button id="autostart" type="button" name="button"><h3>Auto Start<h3></button>
    <button id="max" type="button" name="button"><h3>Max</h3></button>
    <button id="min" type="button" name="button"><h3>Min</h3></button>
    <button id= "betup" type="button" name="button"><h3>Bet up</h3></button>
    <button id="betdown"  type="button" name="button"><h3>Bet down</h3></button>






  </body>
</html>
