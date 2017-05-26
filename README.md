# Distance-sensor-Arduino
Afstandsmåler Arduino Uno (ultralydssensor)

Man kan bruge en ultralyds sensor til at måle en ca. afstand til et objekt i cm. Denne teknologi er blevet meget udbredt på biler som baksensor. Som vist på det sidste billede viser denne guide hvordan man laver en sensor som måler afstanden (cm) til det nærmeste object foran afstandsmåleren. 

# Step 1
<img src="http://blog.mlsdesign.dk/images/Distance/FullSizeRender.jpg" width="350"/>
Jeg har købt en standard HC-SR04 sensor som jeg bruger til dette projekt den er nem at sætte til da der kun skal 4 ledninger til, som skal forbinde Arduino Unoén til sensoren. Jeg har tilsluttet TrigPin til 13 og echoPin til 12. Men det kan ændres efter ens behov. Det eneste som skal ændres i koden er de to øverste linjer.  Udover de to signal pins skal der også tilsluttes jord og plus (5v), henholdsvis Ground og Vcc.

# Step 2
Med den pågældende kode, starter man målingen når man går ind i "Serial Monitor", målingen vil vise den pågældende afstand. Hvis afstanden er over 200 eller under 0 vil den skrive ""Out of range". Dette kan nemt ændres så den passer til en given afstand.  

# Step 3
<img src="http://blog.mlsdesign.dk/images/Distance/distance01.png" width="350"/>

Dette er et eksempel på hvordan koden fungere. Mit eksempel er en rå prototype men man kan overveje at bruge sensoren i en radiobil, som afstandsmåler i en garage eller meget andet. 
