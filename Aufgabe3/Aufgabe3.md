# Aufgabe 3
### Verknüpfung mit zwei Parametern: Zeitverwaltung Tabelle Stunden
Es wird aus den Proffix Daten Latitude und Longitude der Stundentabelle eine Google Maps Grafik mit der entsprechenden Geolocation angezeigt. Dazu müssen diese Werte zuerst vorhanden sein, was man mit folgendem SQL Befehl bewerkstelligt (SQL nach Wunsch anpassen):
- Update ZEI_Stunden set Longitude = 9.504489, Latitude = 47.009525 where LaufNr = (select MAX(LaufNr) from ZEI_Stunden)
- Url: https://www.google.com/maps/search/?api=1&query=[latitude]%2C[longitude]
- Feldhöhe: z.B. 500 Pixel