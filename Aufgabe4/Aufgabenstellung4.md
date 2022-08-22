# Aufgabenstellung 4: Eigene Webanwendung mit Zugriff auf Proffix REST API einbinden
Bei den Adressen sollen die Koordinaten anhand der Strasse und des Orts auf Wunsch aktualisiert werden.

# Hilfsmittel
- URL: file:///___LocalPathToFile___/aufgabe4.html?logintoken=[LoginToken]&restapiurl=[RESTApiUrl]&dbname=[DBName]&adressnr=[AdressNrADR]&adresssuche=[Strasse]%20[HausNr]%20[PLZ]%20[Ort]&latitude=[Latitude]&longitude=[Longitude]
- Feldhöhe: 500 Pixel
- Google Maps Doku: https://developers.google.com/maps/documentation/javascript/reference/geocoder
- Proffix REST API Entwicklerhandbuch: http://proffix.ch/entwickler
- jQuery AJAX Doku: https://api.jquery.com/jQuery.ajax/
- HTML-Vorlage: [./aufgabe4.html](https://github.com/PROFFIX-NET/SystemPartnerTag2022/blob/main/Aufgabe4/aufgabe4.html)

## Lösung
1. Webapplikation schreiben ([Beispiellösung](https://github.com/PROFFIX-NET/SystemPartnerTag2022/blob/Lösung/Aufgabe4/aufgabe4.html))
2. Auf Stunden neues Zusatzfeld vom Feldtyp _WebView_ in der Gruppe _Hauptfenster_ hinzufügen
3. Folgende URL eintragen (Beispielpfad): file:///c:/proffix/data/aufgabe4.html?logintoken=[LoginToken]&restapiurl=[RESTApiUrl]&dbname=[DBName]&adressnr=[AdressNrADR]&adresssuche=[Strasse]%20[HausNr]%20[PLZ]%20[Ort]&latitude=[Latitude]&longitude=[Longitude]
4. Als Feldhöhe 500 Pixel eintragen
