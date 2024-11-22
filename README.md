# yihaaaaa.biz - Netzwerk-Infrastruktur

**Planung und Dokumentation der Netzwerk-Infrastruktur für die Firma yihaaaaa.biz.**

## 📂 Inhalte

- **Netzwerk-Diagramm:** Übersicht aller Geräte und Verbindungen im Netzwerk.
- **Subnet-Tabelle:** Details zu den IP-Adressbereichen der Abteilungen und Geräte.
- **Namenskonvention:** Einheitliche Benennung aller Netzwerkgeräte.

---

## 🌐 Netgear Business Router

### 🔄 Router zurücksetzen
- **Reset:** Halte den Reset-Button 7 Sekunden lang gedrückt.

### 🌐 IP-Adresse ändern
- **Zugriff:** Im Browser die IP des Routers eingeben.
- **IPv4-Adresse des PC-Adapters anpassen:** Ändere die IP-Adresse des LAN-Adapters so, dass sie zum Subnet des Routers passt.

**Beispiel:**

![IPv4 Adaptereinstellungen](https://raw.githubusercontent.com/Jann08/yihaaaaa.biz-GL/main/Images/ipadapter.png)

---

## 🔐 Interface Login - Router

### Anmeldung
- Nach der Anpassung der IP-Adresse kannst du dich auf dem Web-Interface des Routers einloggen:
  - **Benutzername:** `admin`
  - **Passwort:** `password`

### IP LAN-Konfiguration
- Im Reiter "Erweitert" → "LAN Setup" die Konfiguration wie folgt anpassen:
- 
![LAN Config](https://raw.githubusercontent.com/Jann08/yihaaaaa.biz-GL/main/Images/jorislanconfig.png)

### DHCP-Konfiguration
- Im selben Reiter weiter nach unten scrollen, um die DHCP-Einstellungen vorzunehmen:
- 
![DHCP Config](https://raw.githubusercontent.com/Jann08/yihaaaaa.biz-GL/main/Images/dhcpconfig.png)

---

## 🔗 Interface Login - Switch

### Zugriff auf das Switch-Interface
1. Verbinde deinen PC mit dem Switch.
2. Gib die Standard-IP-Adresse des Switches im Browser ein.
3. Passe die IPv4-Adresse deines PC-Adapters an, um mit dem Subnet des Switches zu kommunizieren.

### IP-Konfiguration für den Switch
- Navigiere im Web-Interface zu **System → IP Config** und richte die IP wie folgt ein:
  
![Switch Settings](https://raw.githubusercontent.com/Jann08/yihaaaaa.biz-GL/main/Images/Switchsetign.png)

---

## 🗂️ Subnet-Planung

| **Gerät/Abteilung**          | **Subnetz**                  |
|------------------------------|------------------------------|
| **Router** yiglrt002         | 172.16.100.193              |
| **Switch1** yiglsw 1-3       | 172.16.100.194              |
| **Switch2** yiglpr           | 172.16.100.195              |
| **Switch3** yiglpr           | 172.16.100.196              |
| **Drucker** yiglsv           | 172.16.100.197              |
| **Linux Server** yiglws 1-7  | 172.16.100.198              |
| **DHCP-Server**              | 172.16.100.199 - 172.16.100.220 |

---
