# MT-Lab2

Šio laboratorinio darbo tikslas - sukurti savo virtualiosios realybės (VR) taikomąją programėlę (aplikaciją).
LT
Tokių programėlių kūrimui yra prieinami keli įrankiai. Vienas jų yra A-frame. Galima peržiūrėti kaip veikia A-frame grįsti pavyzdžiai čia: https://aframe.io/aframe/examples/
# Reikalavimai susikurtai repozitorijai (angl. repository)
  - Turite susikurti esamos repozitorijos kopiją (angl. clone) ir sukurti du šakojimus (angl. branches): 'master' ir 'develop'.
  - 'develop' šakojime turi būti saugomi visi commit'ai, kurie atliekami kodo rašymo metu. Kai tik kodas atnaujinamas, tai turi būti užregistruota commit'e, parašant, kas pakeista ir, galbūt, kas dar neveikia.
  - Kai visas naujai pridėtas funkcionalumas veikia tinkamai, 'develop' šaklojimas turi būti sulietas (angl. merge) su 'master' šakojimu.
 
# Reikalavimai 
  - Esamą repozitorijoje A-frame versiją turite atnaujinti iki naujausios versijos kartu su taškų debesies (angl. point cloud) įskiepiu.
  - Šioje užduotyje pateikti du modeliai. Palikite tik vieną jų ir pridėkite tinkamą foną. Jei esama aplinka, supanti trimatį objektą jums nepatinka, pakeiskite ją.
  - Įgyvendinkite bent tris papildomus funkcionalumus index.html faile, pavyzdžiui, valdymo įrankių juostą su mygtukais, skirtais pasukti, perstumti, priartinti/attolinti, įkelti naują objektą ar pan. Panašių pavyzdžių galite rasti čia: https://rdub80.github.io/aframe-gui/examples/all_components.html
  - Patikrinkite sukurtos taikomosios programėlės veikimą naudodami mažiausiai dvi skirtingasinterneto naršykles ir README.md parašykite, kuriose naršyklėse išbandyta ir veikia.
  - Įgyvendinus papildomą funkcionalumą, galima gauti papildomų balų.
  - Laboratorinis darbas užskaitomas, jei rezultate įgyvendinti bent du reikalavimai iš sąrašo.
# Pastaba
  - norint, kad veiktų VR funkcionalumas, gali prireikti index.html patalpinti į veikiantį interneto serverį (jis gali veikti ir jūsų tame pačiame kompiuteryje). Pavyzdžiui:
    - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
    - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
    - HFS: http://www.rejetto.com/hfs/ or any other server.
  
EN
There are many open source alternatives to build virtual reality application. One of the web based solution is A-frame. You can try a live examples: https://aframe.io/aframe/examples/

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the VR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for VR application
  - You have to update A-frame version 0.6.0 to the newest with the point cloud plugin.
  - There are two models provided in the task. Leave only one model and add matching background. If you do not like existing surroundings / models - customize as you like.
  - Implement at least three features in the index.html like control panel to rotate, shift/move, zoom in/out, button to load object or any other function. Panel examples are available at: https://rdub80.github.io/aframe-gui/examples/all_components.html
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - Additional features are welcome and bonuses are available.
  - To pass this lab, you have to complete at least two points from the requirement list.  
  
# Important notes
  - It might be the case, that web server will be need to run VR application. 
  - You can try to use Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
  - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
  - HFS: http://www.rejetto.com/hfs/ or any other server.
