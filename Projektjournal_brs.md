# 📘 Projekt-Journal



## Tagesaktivitäten
|Datum|Aktivität|
|---------|---------|
| Do, 24.09.2026 |Erster Tag den ich am Projekt arbeiten konnte. Projekt Gestartet, git bash installiert, XAMMP installiert,html basic structure.
![Hier ein Bild von allem was ich am 24.9.2026 gemacht habe.](![alt text](image-1.png))|
| FR, 25.09.2026 |  ÖV verbindungen hinzugefügt zu meinen MyPlace|

## Phase 1 MyPlace
16.09.2026

**Was habe ich in Phase 1 umgesetzt:**
¨
Projekt "MyPlace"

## Ziel ##
Eine Website über meinen MyPlace zu machen(KEBA Aarau) um somit html besser kennen zu lernen. Nebenbei den umgang mit Git zu üben und die Website lokal zu hosten mit XAMPP

## 1 Vorbereiten ##
Am anfang Git für das Terminal installieren. (git init) 
Nachdem die Git commands ein bisschen eingearbeitet wie man ein lokales Git-REpository macht fürs Rrojekt und das abspeichern mit neuen zwischenständen (Bespiel git add index.html git commit -m "ÖV-Connection implementiert").

## 2 Lokal Hosten mit XAMPP ##
1. XAMPP Installieren.
2. XAMPP  Oberfläche starte
3. Das Projekt im richtigen XAMMP-Webverzeichnis speichern/ablegen(weiss nicht was besser passt).
4. Webste aufruffen um zu testen ob es funktioniert einfach ganz normales html gerüst gesehen somit hat es funktioniert.

## 3 HTML Anfänge ##
Am anfang sieht es zimmlich leer aus da es nur ein Grunderüst hat.
Die Website funktioniert in Theorie schon einfach komplet leer.

Also mache ich meinen ersten Git-Commit mit dem NAmen Titel eingefügt.

## 4 Bild eingefügt ##
Als nächstes wird ein Bild eingefügt.(Bild von der KEBA Aarau)
Ganz wichtig mit dem attribut alt für den screen reader.

img src="..." alt="Eishalle der KEBA Region Aarau AG"

(Danach wieder ein Git Commit Name: sw eingefügt.)

## 5 Kurzbeschreibung ##
Danach habe ich meinen MyPlace kurz beschrieben, mit dem p=Paragraph.

## Verlinkung eingefügt ##

Auf meiner Webseite gibt es einen Link zur offiziellen KEBA-Webseite.

a href="https://www.keba.ch">KEBA Website</a

Der Besucher kann dadurch direkt weitere Informationen über die KEBA aufrufen.

Git-Commit
Verlinkung eingefügt
## ⚠️ Herausforderungen & Blockaden

### 🎨 Layout & Schriftart anpassen

- Problem: Schriftarten wurden nicht korrekt geladen
- Lösung: Google Fonts manuell eingebunden

```csharp
public static class MauiProgram
{
    public static MauiApp CreateMauiApp()
    {
        var builder = MauiApp.CreateBuilder();
        ...
    }
}
```

```xml
<Label Text="Willkommen im Projekt!"
       FontFamily="RobotoRegular"
       FontSize="20"
       HorizontalOptions="Center" />
```

### 💾 Laden & Schreiben der Daten

- Problem: JSON-Datei nicht gefunden (Pfadproblem)
- Lösung: Relativen Pfad anpassen und Debug nutzen

```csharp
```


## 💻 Besonders erwähnenswerte Code-Beispiele

Validierung mit Benutzerfeedback

```csharp
```

Laden von Benutzerdaten

```csharp
var json = File.ReadAllText("daten/benutzer.json");
var benutzer = JsonSerializer.Deserialize<List<Benutzer>>(json);
```

## Reflexion
Der Fachblock war sehr anspruchsvoll, hat mir jedoch viele Erkenntnisse gebracht. Ich habe gelernt, dass ..
Es war schwierig, Termine einzuhalten, weil ...  Trotzdem denke ich, dass ..