# yihaaaaa.biz - Netzwerk-Infrastruktur

Planung und Dokumentation Netzwerk-Infrastruktur für die Firma yihaaaaa.biz.

## Inhalte

- **Netzwerk-Diagramm:** Eine visuelle Darstellung des Netzwerks mit allen wichtigen Geräten und Verbindungen.
- **Subnet-Tabelle:** Übersicht über die IP-Adressbereiche der einzelnen Abteilungen und Geräte.
- **Namenskonvention:** Einheitliche Benennung der Geräte basierend auf Abteilungen.
## Netgear Business Router
## Tasks:
- **Reset** Reset Button 7 Sekunden drücken.
- **Auf Web interface zugreifen** Im Browser die IP des Router eingeben und auf dem PC die IPv4 Adresse vom Lan Adapter ändern auf das Subnet des Routers.
- **IP-Adresse ändern:**  
![IPv4 Adaptereinstellungen](https://raw.githubusercontent.com/Jann08/yihaaaaa.biz-GL/main/Images/ipadapter.png)

## Subnet-Planung

| Abteilung                    | Subnetz        | Hosts (inkl. Reserve) |
|------------------------------|----------------|------------------------|
| Geschäftsleitung/Finanzen    | 172.16.0.0/28  | 12                     |
| Marketing/Verkauf            | 172.16.0.16/28 | 15                     |
| Produktion/Vertrieb          | 172.16.0.32/27 | 30                     |
| IT/Operations                | 172.16.0.64/28 | 14                     |
| Mobile Geräte                | 172.16.0.96/26 | 50                     |

