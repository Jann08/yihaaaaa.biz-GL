# yihaaaaa.biz - Netzwerk-Infrastruktur

Dieses Repository enthält die Planung und Dokumentation der neuen Netzwerk-Infrastruktur für die Firma yihaaaaa.biz.

## Inhalte

- **Netzwerk-Diagramm:** Eine visuelle Darstellung des Netzwerks mit allen wichtigen Geräten und Verbindungen.
- **Subnet-Tabelle:** Übersicht über die IP-Adressbereiche der einzelnen Abteilungen und Geräte.
- **Stückliste:** Alle benötigten Netzwerkkomponenten mit Anzahl und Beschreibung.
- **Namenskonvention:** Einheitliche Benennung der Geräte basierend auf Abteilungen.

## Struktur

- `diagrams/` - Enthält das Netzwerk-Diagramm.
- `docs/` - Markdown-Dokumente wie Subnet-Tabelle und Stückliste.
- `README.md` - Diese Übersicht.

## Subnet-Planung

| Abteilung                    | Subnetz        | Hosts (inkl. Reserve) |
|------------------------------|----------------|------------------------|
| Geschäftsleitung/Finanzen    | 172.16.0.0/28  | 12                     |
| Marketing/Verkauf            | 172.16.0.16/28 | 15                     |
| Produktion/Vertrieb          | 172.16.0.32/27 | 30                     |
| IT/Operations                | 172.16.0.64/28 | 14                     |
| Mobile Geräte                | 172.16.0.96/26 | 50                     |

## Installation und Nutzung

1. Klone das Repository:
   ```bash
   git clone https://github.com/<username>/yihaaaaa.biz.git
