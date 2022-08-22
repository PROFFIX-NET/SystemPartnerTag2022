# Aufgabenstellung 2: Verknüpfung mit einem Parameter
Im Währungsfenster soll der Wechselkurs von der aktuelle Währung zum Schweizer Franken von Yahoo-Finance angezeigt werden.

## Hilfsmittel
- URL (Beispiel Euro): https://de.finance.yahoo.com/chart/EURCHF%3DX
- Feldname Währungskürzel: WaehrungPro
- Feldhöhe: 1000 Pixel

## Lösung
1. Auf Währung neues Zusatzfeld vom Feldtyp _WebView_ in der Gruppe _Hauptfenster_ hinzufügen
2. Folgende URL eintragen: https://de.finance.yahoo.com/chart/[WaehrungPro]CHF%3DX
3. Als Feldhöhe 1000 Pixel eintragen
