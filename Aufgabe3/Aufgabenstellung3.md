# Aufgabenstellung 3: Eigene Webanwendung einbinden
Bei den Stundeneinträgen in der Zeitverwaltung sollen auf einer Karte der Ort angezeigt werden, an dem eingestempelt wurde. Dabei soll lediglich die Karte von Google sichtbar sein, ohne die Inhalte welche auf https://google.com/maps dargestellt werden.

## Hilfsmittel
- SQL Befehl um beim letzten Stundeneintrag einen Ort zu hinterlegen: `UPDATE ZEI_Stunden SET Longitude = 9.504489, Latitude = 47.009525 WHERE LaufNr = (SELECT MAX(LaufNr) FROM ZEI_Stunden)`
- URL: file:///___LocalPathToFile___/aufgabe3.html?latitude=[latitude]&longitude=[longitude]
- Feldhöhe: 500 Pixel
- Google Maps Doku: https://developers.google.com/maps/documentation/javascript/adding-a-google-map?hl=de#step_2_add_a_map_with_a_marker
- HTML-Vorlage: [./aufgabe3.html](https://github.com/PROFFIX-NET/SystemPartnerTag2022/blob/main/Aufgabe3/aufgabe3.html)
