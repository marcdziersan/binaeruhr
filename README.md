# Die Geschichte der Binäruhr

Die **Binäruhr** ist eine innovative und faszinierende Art der Zeitmessung, die anstelle des traditionellen Dezimal- oder 12/24-Stunden-Formats auf einem binären Zahlensystem basiert. Im Gegensatz zu herkömmlichen Uhren, die Ziffern oder Zeiger verwenden, zeigt eine Binäruhr die Zeit durch leuchtende oder deaktivierte Felder an, die den Status von Bits repräsentieren.

<a href="https://marcdziersan.github.io/binaeruhr/binaer.html">DEMO</a>

## Ursprung und Geschichte

Die Idee der Binäruhr basiert auf dem binären Zahlensystem, das von Gottfried Wilhelm Leibniz im 17. Jahrhundert entwickelt wurde und die Grundlage moderner Computertechnologie bildet. Die Anwendung dieses Zahlensystems auf die Zeitmessung ist eine relativ neue Entwicklung, die mit dem Aufkommen digitaler Technik und experimenteller Uhrendesigns an Popularität gewonnen hat.

Die erste bekannte Binäruhr wurde in den 1990er Jahren entwickelt und richtete sich an Technikliebhaber, Programmierer und Menschen mit einer Vorliebe für ungewöhnliches Design. Die binäre Darstellung von Zeit verleiht Uhren nicht nur einen technologischen Charakter, sondern fordert den Benutzer heraus, die Funktionsweise von Binärzahlen zu verstehen und Zeit auf eine neue Art wahrzunehmen.

## Die Binäruhr im modernen Zeitalter

Heute wird die Binäruhr sowohl als technisches Gadget als auch als Kunstobjekt verwendet. Moderne Binäruhren sind oft digitale Kunstwerke, die Zeit auf ansprechende und innovative Weise darstellen. Sie kombinieren funktionale Zeitmessung mit ästhetischen Elementen und technologischer Raffinesse.

# Funktionsweise der Binäruhr

Eine Binäruhr zeigt die Zeit durch das Leuchten oder Nicht-Leuchten von LEDs an, die den Binärwerten entsprechen. Jede Spalte repräsentiert dabei Stunden, Minuten oder Sekunden. Innerhalb jeder Spalte steht jede LED für einen bestimmten Wert gemäß des binären Zahlensystems.

## Aufbau und Darstellung
Die Binäruhr besteht aus drei Gruppen, die jeweils für die **Stunden (H)**, **Minuten (M)** und **Sekunden (S)** stehen. Jede Gruppe enthält 6 LEDs, wobei die Werte von oben nach unten wie folgt gestaffelt sind:

| LED-Position | Dezimalwert |
|--------------|-------------|
| 1.           | 32          |
| 2.           | 16          |
| 3.           | 8           |
| 4.           | 4           |
| 5.           | 2           |
| 6.           | 1           |

Die leuchtenden LEDs ergeben durch Addition ihrer Dezimalwerte die entsprechende Zahl für Stunden, Minuten oder Sekunden.

### Beispiel:
Wenn die Stunden-Gruppe wie folgt dargestellt wird:

- **LED 32**: leuchtet
- **LED 8**: leuchtet
- **LED 4**: leuchtet

Ergibt die Summe: `32 + 8 + 4 = 44`. Die Uhrzeit in der Stunde ist somit **44** (im Binärformat ausgedrückt).

## Interpretation der Uhrzeit
Um die aktuelle Uhrzeit zu berechnen, gehen Sie wie folgt vor:

1. **Stunden (H):** Addieren Sie die Werte der leuchtenden LEDs in der Stunden-Spalte.
2. **Minuten (M):** Addieren Sie die Werte der leuchtenden LEDs in der Minuten-Spalte.
3. **Sekunden (S):** Addieren Sie die Werte der leuchtenden LEDs in der Sekunden-Spalte.

Die Summe jeder Spalte ergibt die jeweilige Zeitkomponente.

### Beispielzeit:
Angenommen, die LEDs leuchten wie folgt:

- **Stunden:** LED 16 und LED 1 leuchten. Summe = `16 + 1 = 17`
- **Minuten:** LED 32, LED 8 und LED 1 leuchten. Summe = `32 + 8 + 1 = 41`
- **Sekunden:** LED 8 und LED 4 leuchten. Summe = `8 + 4 = 12`

Die Uhrzeit lautet dann: **17:41:12**.

## Realzeit-Updates
Die Binäruhr aktualisiert sich jede Sekunde, um die aktuelle Zeit anzuzeigen. Die Anzeige ist sowohl funktional als auch ein ästhetisches Erlebnis und kombiniert Technologie mit visueller Innovation.

### Vorteile:
- Fördert ein besseres Verständnis des Binärsystems.
- Kombination aus funktionaler Zeitmessung und digitaler Kunst.
