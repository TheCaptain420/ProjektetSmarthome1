# ProjektetSmarthome1
## Johans hjem:
### 1 - Interview:  
Hvad han vil have:  1. Kamera/dørspion, 2. Udluftning, 3. Auto tændpc, 4. auto slukker lys, 5. Check om dør er låst.  

### 2 - Use Case: 
1. Han kan se på telefon, hvem der står uden foran.  
2. Vis der bliver for varmt eller fugtigt, åbner vinduet.  
3. Når han er tæt på sit hus skal hans pc tænde.  
4. Når han forlader sit hus skal lys slukke.  
5. Han kan på alle tidspunkter checke om døren er låst.  



### 3 - Design your classes:
Main.java  
#### 1. Kamera/dørspion  
BevægelsesSensor, KameraTænder, KameraOptag, KameraStream, SendAlertMessageToUser, GUI.   

#### 2. Udluftning  
FugtighedsSensor, StyrArm(der åbner vindue), GUI(evt.), IsHumanHome.   
  
#### 3. Auto tændpc  
UserDistanceFromHome, TændPC.

#### 4. auto slukker lys  
UserDistanceFromHome, SlukLys, SendAlertMessageToUser

#### 5. Check om dør er låst.
UserDistanceFromHome, SendAlertMessageToUser, LåsDør.



### 4 - Abstraction  and interfaces.  
Sensor.java - 1,2  
UserDistanceFromHome.java - 3,4,5  
GUI.java(HTML/.js?) - 1,2  
SlukElTænd.java - 4,3, (Måske LåsDør.java?)   
SendAlertMessageToUser.java - 1,4,5  

