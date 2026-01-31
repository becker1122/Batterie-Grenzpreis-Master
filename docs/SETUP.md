# Setup

## Ziel
Dieses Repo sammelt die Logik und Konfig-Snippets für den „Batterie-Grenzpreis-Master“
(Home Assistant + EVCC).

## Home Assistant Einbindung (optional, nur wenn du später "Packages" nutzen willst)
In deiner `configuration.yaml`:

```yaml
homeassistant:
  packages: !include_dir_named packages
