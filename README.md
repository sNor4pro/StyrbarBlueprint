# StyrbarBlueprint

Dieses Repository enthält einen Home Assistant Blueprint für die IKEA STYRBAR Fernbedienung (über ZHA-Integration). Mit diesem Blueprint kannst du Lampen steuern und eigene Aktionen für die Tasten der Fernbedienung festlegen.

## Funktionen
- Steuerung von Lampen (Ein/Aus, Helligkeit ändern)
- Individuelle Aktionen für die linke und rechte Taste (kurzer und langer Druck)
- Einstellbare Helligkeit beim Einschalten
- Option, die Helligkeit beim Einschalten zu erzwingen

## Eingaben im Blueprint
- **Remote**: Auswahl der IKEA STYRBAR Fernbedienung (ZHA)
- **Lights**: Auswahl der zu steuernden Lampen
- **Button Left/Right**: Aktionen für Linksklick/Rechtsklick (kurz und lang)
- **Brightness**: Einstellbare Helligkeit (0–100%)
- **Force Brightness**: Erzwingt die eingestellte Helligkeit beim Einschalten

## Ablauf
Die Blueprint-Datei reagiert auf ZHA-Events der Fernbedienung und führt die konfigurierten Aktionen aus, je nachdem, welche Taste gedrückt oder gehalten wird.

## Quelle des Blueprints
Teile des Blueprints stammen von:  
https://raw.githubusercontent.com/Computerfreak14/Z2M-Styrbar-remote-blueprint/experimental-ZHA/Z2M-IKEA-STYRBAR-remote.yaml

---

**Hinweis:** Dies ist eine Community-Vorlage für Home Assistant. Für Fragen oder Verbesserungen gerne ein Issue erstellen!
