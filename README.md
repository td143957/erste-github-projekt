# erste-github-projekt
Das ist mein erstes Projekt. Hier erfährt man weniger über mich 

<?php
 echo "Zweite Test" ."</p>";
 $a=10;
 $b ="Euro";
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
  ?>
