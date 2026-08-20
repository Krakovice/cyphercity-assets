# Cypher City — Assets

Öffentliche Bilddateien für den FiveM-Server **Cypher City**.
Das Repo ist öffentlich, weil FiveM die Dateien ohne Anmeldung abrufen muss —
bei einem privaten Repo bräuchten die `raw.githubusercontent.com`-Links ein
Token, und das schickt der Client nicht mit.

## Inhalt

| Datei | Größe | Verwendung |
|---|---|---|
| `banner/cypher_banner.gif` | 720×180, animiert | `sets banner_detail` / `sets banner_connecting` |
| `banner/cypher_banner_strip.jpg` | 1920×480 | Standbild als Rückfallebene |
| `branding/logo.png` | 1254×1254, transparent | Quelllogo |
| `branding/serverlogo_96.png` | 96×96 | `load_server_icon` |

## Einbinden

```cfg
sets banner_detail     "https://raw.githubusercontent.com/Krakovice/cyphercity-assets/main/banner/cypher_banner.gif"
sets banner_connecting "https://raw.githubusercontent.com/Krakovice/cyphercity-assets/main/banner/cypher_banner.gif"
```
