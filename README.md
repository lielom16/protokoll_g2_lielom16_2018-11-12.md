# protokoll_5_lielom16_2019-25-03.md

  * Verfasser:  Lierzer Lorenz
  * Gruppe:     2
  * Datum:      11.12.2018
  
  **Ablauf**
  In der letzten Einheit des AIIT Labors befassten wir uns haupsächlich mit dem Thema Netzwerke.
   -Was ist ein Netzwerk
   -Adressarten
   -praktische Übungen am raspberry
   
   **Netzwerk**
   Unter einem Netzwerk versteht man eine Zusammenschaltung zweier oder mehrer Geräte. Ein Netzwerk kann jedoch auch aus mehreren 
   einzelnen Netzwerken(den Subnetzen) bestehen. In einem solchen Netzwerk hat jedes Gerät(Host) seinen eihgenen Platz, um jedes Gerät 
   zu initialisieren werden dafür Adressen verwendet.
   ![Bild](http://www.vpn-deutschland.de/images/VPN-Sicherheit.jpg)
   
   **Adressen** 
   In einem Netzwerk durläuft ein Datenpaket bis zu seiner Ankunft am destination Host mehrere Netzwerklayer. Jeder dieser Layer hat    eigene Adressen um eine klare Wegfindung der Datenpakete durch das Netzwerk zu garantieren.
   **Ip-Adressen**
**Ipv4** -> 192.68.0.0 (vier dreistellige dezimalzahlen durch einen Punkt getrennt)
**Ipv6** -> aaa:2f92:23b::0 (acht vierziffrige HEX-Zahlen & nullen dürfen durch :: ersetzt werden)

## Private IP-Adressen

### IPv4
|Erste Adresse|Letzte Adresse|Anzahl|
|-------------|--------------|------|
|192.68.0.0|192.168.255.255|65.536|
|172.16.0.0|172.31.255.255|1.048.576|
|10.0.0.0|10.255.255.255|16.777.216|

### IPv6
Alle Adressen mit **fd00** beginnen.
