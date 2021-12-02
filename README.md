# erste-github-projekt
Das ist mein erstes Projekt. Hier erfährt man weniger über mich 

<html>
    <head>
	<link rel="stylesheet" type="text/css" href="style.css">
        <title>PHP Test-Container</title>
    </head>
    <body>
<div class='message'>
        <h1>Hallo Florian</h1>
        <h2>Ich brauche das Zoom-Meeting Montag nicht mehr. Schönes Wochenende!</h2>
        <h3>magst du die Farbe vielleicht ?</h3>
</div>
      
<script> alert("Danke für den Hinweis!");</script>
<?php 
echo "Eine weitere Übung in PHP!"."</p>";
echo "Und zwar Anwendung der String verbingung anhang dieser Beispiel "."</p>";
 $a=10;
 $b =".Euro";
 echo $a . $b ."</p>";
 echo "Reihenfolge der Inkrementiereung ++"."</p>";

$a = 7;
 $b= 3;
 # $a++ -> erst werden a und b addiert (7 + 3 = 10), anschließend wird $a inkrementiert.
 #D.h. für die Addition wird noch der alte Wert von $a benutzt.
 $erg=$a++ + $b ."</p>";
 echo $erg;
 $a = 7;
 $b= 3;
 # ++$a -> als erstes wird $a inkrementiert, danach werden $a und $b addiert (also 8 + 3 = 11).
 # D.h. für die Addition wird der neue Wert von $a benutzt.
 $erg= ++$a + $b ."</p>";
 echo $erg;
?>
    
        <hr>
        Danke ;-)
<div class="center">
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>

</div>

    </body>
</html>

#heute 02.12.21

<?php
 echo "Zweite Test" ."</p>";
 $a=10;
 $b =".Euro";
 # String verbingung,Kontatenation auch Punkt(.)verbindung genannt
 echo $a . $b ."</p>";
 $a = 7;
 $b= 3;
 # Reihenfolge der ++
 # $a++ -> erst werden a und b addiert (7 + 3 = 10), anschließend wird $a inkrementiert.
 #D.h. für die Addition wird noch der alte Wert von $a benutzt.
 $erg=$a++ + $b ."</p>";
 echo $erg;
 $a = 7;
 $b= 3;
 # ++$a -> als erstes wird $a inkrementiert, danach werden $a und $b addiert (also 8 + 3 = 11).
 # D.h. für die Addition wird der neue Wert von $a benutzt.
 $erg= ++$a + $b ."</p>";
 echo $erg;


 # Mit Trennzeichen teilen >>strtok<<
  echo "Vierter Test" ."</p>";
  $a = "PHP ist immer toll";
  echo "Teil 1:".strtok($a," ")."</p>";
  echo "Teil 2:".strtok(" ")."</p>";
  echo "Teil 3:".strtok(" ")."</p>";
  echo "Teil 4:".strtok(" ")."</p>";
  # Mit Trennzeichen teilen >>strtok<< mit einer Schleife alternativ
   echo "Funfter Test" ."</p>";
   $a = "PHP ist  toll";
   $i = 1;#Wozu ist die eins hier?
  $start = strtok($a,"");
  while ($start){
    $name = "teil".$i;
    $$name = $start;
    $start = strtok("");
    $i++;
  }
  #Ohne leere Zeichen in der String ,BSP:echo "Teile: ".strtok($a,"") ."</p>";
  #hat man als Ausgabe:PHP ist  toll
  echo "Teile 1: ".strtok($a," ") ."</p>";
  echo "Teile 2: ".strtok(" ") ."</p>";
  echo "Teile 3: ".strtok(" ") ."</p>";

  #Teilen in Strings mit >>substr<<
  echo "Dritter Test" ."</p>";
  $a = "PHP ist toll";
  for($i = 0,$j = 0; $i < strlen($a); $i = $i + 4, $j++){
    #was passiert in der Vorschleife hier?
    $name = "string". $j;
    $$name = substr($a,$i,4);
    echo "Teil 1:".strlen(" ")."</p>";
    #echo "Teil 2:".strlen(" ")."</p>";
    #echo "Teil 3:".strlen(" ")."</p>";

    #wie kann man die Ausgabe mit echo""."</p>"; machen ?
  }
  ?>

