---
share: true
cat: web development
---

## Was ist eine API?

- **API** steht für „Application Programming Interface“ (Anwendungsprogrammierschnittstelle).
- Sie bietet eine standardisierte Möglichkeit, wie Programme miteinander kommunizieren und Funktionen/Daten austauschen können – ohne zu wissen, wie das Gegenüber intern funktioniert.

### Grundidee:
Eine API definiert **Regeln und Formate** (wie einen Vertrag), wie Anfragen gestellt und Antworten zurückgegeben werden.

### Typische Beispiele:

- **Web-API:**  
  Eine Schnittstelle, die Daten und Funktionen übers Internet bereitstellt.  
  *Beispiel:*  
  Die Wetter-API von OpenWeatherMap:
```

curl "https://api.openweathermap.org/data/2.5/weather?q=Berlin\&appid=API_KEY"

```
Antwort:
```

{
"weather": [ {"description": "sonnig"} ],
"main": { "temp": 24.3 }
}

```

- **Betriebssystem-API:**  
Programme können über die Windows-API Dateien lesen/schreiben, Fenster öffnen usw.

- **Bibliotheks-API:**  
Programmiersprachen-Bibliotheken stellen Funktionen zur Verfügung, z. B. für Mathe, Datenbanken, Grafik.

### Wesentliche Vorteile:
- **Wiederverwendbar:** Verschiedene Programme und Dienste können sich auf dieselbe API verlassen.
- **Entkopplung:** Entwickler müssen die interne Technik nicht kennen.
- **Automatisierung:** Maschinen (wie [[n8n|n8n]], Shell-Skripte) können APIs nutzen, um Aufgaben zu automatisieren.

---
**Kurz:**  
Eine API ist ein „Vertrag“ für die Daten-Austausch-Regeln zwischen Programmen – Beispiel: Über eine Wetter-API bekommst du tagesaktuelle Wetterdaten sofort im gewünschten Format.

---
## Tools

[[Parse.bot|Parse.bot]]
Verwandelt jede Webseite in eine nutzbare API per AI