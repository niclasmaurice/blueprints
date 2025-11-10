# Home Assistant Blueprints

Eine Sammlung von Blueprints für Home Assistant Automationen und Skripte.

## 📋 Verfügbare Blueprints

### Automationen

#### 🚶 Bewegungsgesteuertes Licht
**Datei:** `automation/motion_light.yaml`

Schaltet ein Licht automatisch ein, wenn eine Bewegung erkannt wird, und schaltet es nach einer konfigurierbaren Zeit wieder aus.

**Import-URL:**
```
https://github.com/niclasmaurice/blueprints/blob/main/automation/motion_light.yaml
```

#### 🔋 Benachrichtigung bei niedrigem Batteriestand
**Datei:** `automation/low_battery_notification.yaml`

Sendet eine Benachrichtigung, wenn der Batteriestand eines Geräts unter einen bestimmten Schwellenwert fällt.

**Import-URL:**
```
https://github.com/niclasmaurice/blueprints/blob/main/automation/low_battery_notification.yaml
```

#### 🌡️ Klimasteuerung basierend auf Anwesenheit
**Datei:** `automation/climate_presence.yaml`

Passt die Temperatur automatisch basierend auf der Anwesenheit an - spart Energie, wenn niemand zu Hause ist.

**Import-URL:**
```
https://github.com/niclasmaurice/blueprints/blob/main/automation/climate_presence.yaml
```

### Skripte

#### 📱 Benachrichtigung an alle Geräte
**Datei:** `script/notify_all_devices.yaml`

Sendet eine Benachrichtigung gleichzeitig an mehrere Geräte.

**Import-URL:**
```
https://github.com/niclasmaurice/blueprints/blob/main/script/notify_all_devices.yaml
```

## 🚀 Installation

### Methode 1: Import über die Home Assistant UI

1. Öffne Home Assistant
2. Gehe zu **Einstellungen** → **Automationen & Szenen** → **Blueprints**
3. Klicke auf **Blueprint importieren**
4. Füge die Import-URL des gewünschten Blueprints ein
5. Klicke auf **Vorschau** und dann auf **Importieren**

### Methode 2: Manuelle Installation

1. Kopiere die gewünschte YAML-Datei
2. Platziere sie in deinem Home Assistant Konfigurationsverzeichnis:
   - Für Automationen: `blueprints/automation/`
   - Für Skripte: `blueprints/script/`
3. Starte Home Assistant neu

## 💡 Verwendung

Nach der Installation eines Blueprints:

1. Gehe zu **Einstellungen** → **Automationen & Szenen**
2. Klicke auf **Automation erstellen** oder **Skript erstellen**
3. Wähle den importierten Blueprint aus
4. Konfiguriere die Parameter nach deinen Bedürfnissen
5. Speichere die Automation/das Skript

## 🤝 Beitragen

Eigene Blueprints können gerne über Pull Requests hinzugefügt werden!

## 📝 Lizenz

Diese Blueprints stehen unter der MIT-Lizenz zur freien Verwendung.
