# CubeSat--Test
 # Misiune CubeSat România (GMAT)
Proiect de simulare a unei misiuni de observare a Pământului folosind NASA General Mission Analysis Tool.

Am realizat designul unei misiuni pentru un CubeSat aflat pe o orbită de tip Sun-Synchronous (altitudine ~500km). Folosind instrumentul GMAT (NASA), am demonstrat că pentru o stație de sol amplasată în București (long: 44.42° N, lat: 26.10° E), fereastra medie de contact este de 8 minute și 21 de secunde. Acest timp este suficient pentru descărcarea datelor de telemetrie și a pachetelor de date de observare a Pământului, apoi am mai realizat designul unei misiuni pentru o stație de sol amplasată în Timișoara(long: 45.75° N, lat: 21.22° E).

Observațiile văzute:
-Satelitul intră în raza de vizibilitate a Timișoarei la ora 21:16:39.
<img width="1177" height="377" alt="Screenshot 2026-02-18 221052" src="https://github.com/user-attachments/assets/ea6883b7-350e-4c16-97c4-ccc0269e752d" />



-După doar 22 de secunde (la ora 21:17:01), acesta devine vizibil și deasupra Bucureștiului.

<img width="1562" height="582" alt="Screenshot 2026-02-18 220049" src="https://github.com/user-attachments/assets/edd3cf16-b872-4053-b5f3-cc29e8342b46" />


-Acest decalaj confirmă traiectoria orbitală pe direcția Vest-Est, oferind o acoperire aproape simultană a întregii țări.

<img width="340" height="173" alt="Screenshot 2026-02-18 220833" src="https://github.com/user-attachments/assets/1a90c3c3-f909-4920-bf0f-2358697c8a40" />


<img width="675" height="283" alt="Screenshot 2026-02-18 215148" src="https://github.com/user-attachments/assets/3b15b491-4cf4-4a4b-9d93-f8808bceb5fa" />




-Ambele stații beneficiază de o durată de contact de aproximativ 500-501 secunde (peste 8 minute):Timișoara: 500.50 s,	București: 501.57 s.


-O fereastră de 8 minute este considerată optimă pentru un CubeSat de orbită joasă (LEO), permițând descărcarea unor volume semnificative de date de telemetrie sau imagini de rezoluție medie.


De ce??
 Avem nevoie de un mic calculc matematic:

      - rata de transfer: presupunem o viteză de transmisie obișnuită pt un CubeSat de 2Mbps 

      - timpul de contact: aprox. 500s 

      - capacitate totală: 500s * 2Mbps = 1000 Mb , adică 1000/8 = 124 MB pe fiecare trecere (asta înseamnă că poți descărca vreo 40-50 de imagini multispectrale de înaltă rezoluție(aprox 2.5MB))


      Satelitul este configurat pentru o misiune de Teledetecție (Remote Sensing). În fereastra de contact, acesta transmite două fluxuri principale de date:
      

-date de telemetrie: parametrii vitali de funcționare (stare baterii, temperaturi, orientare).


-date de misiune: seturi de date multispectrale utilizate pentru monitorizarea mediului și agricultură de precizie.




