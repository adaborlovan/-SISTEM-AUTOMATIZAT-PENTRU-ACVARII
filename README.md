Sistem automatizat pentru acvarii

*Adresa repository-ului github
Codurile sursă sunt disponibile la adresa: https://github.com/adaborlovan/-SISTEM-AUTOMATIZAT-PENTRU-ACVARII

*Structura repository-ului:
-Cod sursa pentru Arduino, intitulat "Cod_ARDUINO_final.ino".
-Codul pentru modulul WI-FI ESP, intitulat "Cod_ESP8266.ino".
-Fisierul README.md care cuprinde pașii de încarcare al codului pe plăci și cei de lansare ai aplicației.
-Aplicatia mobila, "APP".

*Pașii de compilare cod pentru Arduino
1. Se descarcă și se instalează **Arduino IDE** 
2. Se deschide in IDE fișierul `Cod_Arduino_final.ino`
3. Se selectează tipul de placă utilizat: `Tools > Boards > Arduino AVR Boards > Arduino Uno` 
4. Se selectează portul de conectare: `Tools > Port`.
5. Se apasă butonul **Verify** pentru compilarea codului sursă.
6. Se apasă butonul **Upload** pentru încărcarea codului pe placa Arduino.

*Pașii de compilare cod pentru modulul ESP
1. Se descarcă și se instalează **Arduino IDE** 
2. Se deschide în IDE fișierul `Cod_ESP8266.ino`
3. Se selectează tipul de placă utilizat: `Tools > Boards > esp8266 > Generic ESP8266 Module` 
4. Se selectează portul de conectare: `Tools > Port`.
5. Se apasă butonul **Verify** pentru compilarea codului sursă.
6. Se apasă butonul **Upload** pentru încărcarea codului pe placa Arduino.
   
*Pașii de compilare pentru aplicatia mobile
1. Se descarcă și se instalează **Android Studio**.
2. Se deschide în IDE proiectul `APP`.
3. Se alege un dispozitiv nou în care v-a rula aplicația din tab-ul “Device Manager”: `Device Manager > Add New Device`.
4. Se pornește simularea accesând noul dispozitiv folosind tab-ul “Running Devices”: `Running Devices > Add New Device`.
5. Se apasă butonul **Run** pentru compilarea aplicației.
