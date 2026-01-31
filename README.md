# Batterie-Grenzpreis-Master

Home Assistant + EVCC: Eine Logik, die den Batterie-Grenzpreis automatisch setzt (Preisglättung / Wirtschaftlichkeit),
inkl. Peak-Abfederung, PV-Vorhersage-Dämpfung und optionalem Monatsziel-Bias.

## Inhalt
- **Automation (Hauptlogik):**  
  [`home_assistant/automations/evcc_batt_price_limit_master.yaml`](home_assistant/automations/evcc_batt_price_limit_master.yaml)

- **Package-Platzhalter (für spätere Paket-Variante):**  
  [`home_assistant/packages/evcc_batterie_grenzpreis_master.yaml`](home_assistant/packages/evcc_batterie_grenzpreis_master.yaml)

- **Doku:**  
  - Setup: [`docs/SETUP.md`](docs/SETUP.md)  
  - Benötigte Entitäten: [`docs/ENTITIES.md`](docs/ENTITIES.md)

## Kurz erklärt
- Das Repo ist erstmal **Backup/Doku**.
- Es ändert in Home Assistant **nichts**, solange man die Dateien nicht bewusst nach `/config/...` kopiert.

## Mitmachen / Ideen
Pull Requests und Issues sind willkommen:
- Optimierungen an der Logik
- bessere Heuristiken (Forecast / Peak / Monatsziel)
- Robustheit (fehlende Sensoren, Fallbacks)
