# 🛡️ Holistic ISMS Implementation & Change Strategy
### Maschinenbau Augsburg GmbH | ISO/IEC 27001:2022, IEC 62443 & NIS-2

![ISO 27001](https://img.shields.io/badge/Standard-ISO%2FIEC%2027001%3A2022-blue)
![IEC 62443](https://img.shields.io/badge/OT%20Security-IEC%2062443--3--3-green)
![Compliance](https://img.shields.io/badge/Compliance-NIS--2%20%2F%20BSIG%20%C2%A730-orange)
![Change Management](https://img.shields.io/badge/Framework-Kotter%20%7C%20ADKAR%20%7C%20Just%20Culture-purple)
![ROI Model](https://img.shields.io/badge/Economics-Gordon--Loeb%20Model-brightgreen)

---

## 📌 Executive Summary

Dieses Repository enthält das vollständige, wissenschaftlich fundierte Beratungskonzept und das Angebot zur Einführung eines **Informationssicherheits-Managementsystems (ISMS)** für die **Maschinenbau Augsburg GmbH** (210 Mitarbeitende, diskrete Fertigung).

Das Konzept transformiert das Unternehmen innerhalb von **24 Monaten** von einem reaktiven **Ad-hoc-Niveau (Stufe 1)** zu einem strukturierten, auditierungsfähigen **Managed-Niveau (Stufe 3)** gemäß ISO/IEC 27001:2022 bei einem Gesamtinvest von **80.000–150.000 €**.

Der Kernansatz basiert auf dem **Drei-Säulen-Prinzip**: Informationssicherheit wird nicht als rein technisches IT-Projekt verstanden, sondern als integriertes **Veränderungsprojekt**, das Technik, Governance und Arbeitspsychologie synchronisiert.

---

## 🏗️ Die 3 Handlungsebenen
▲
                 / \
                /   \
               / KULTUR \  --> Just Culture, Champions, Anti-Reaktanz
              /-----------\
             /  STRUKTUR   \ --> Governance, ISB, ISO 27005, Betriebsrat
            /---------------\
           /     TECHNIK     \ --> IT/OT-VLAN, PAM, MFA/RFID, Offline-Backup
          /-------------------\
### 1. 🏛️ Governance & Struktur
* **Externer/Interner ISB:** Sofortiger Start via externem ISB (50 % Kapazität), strukturierter Know-how-Transfer zu internem Nachfolger bis Monat 18.
* **Tone from the Top:** 2-seitige, verbindliche ISMS-Leitlinie mit GF-Unterschrift und institutionalisierter GF-Reporting-Struktur.
* **Risikoanalyse:** 3-tägiger Workshop nach **ISO/IEC 27005** und **STRIDE-Methodik**.
* **Betriebsrats-Integration:** Frühzeitige Ko-Kreation einer Betriebsvereinbarung (§87 BetrVG / §26 BDSG) gegen Überwachungsskepsis.

### 2. ⚙️ Technische Exzellenz (IT/OT-Konvergenz)
* **IT/OT-Netzwerksegmentierung:** VLAN-Trennung mit Stateful Inspection Firewall nach **IEC 62443-3-3 SR 5.1**.
* **Security by Design auf dem Shopfloor:** MFA für Büro/Remote, **RFID-Badge-Integration** an Maschinen-Terminals (Verhinderung von Produktivitätsverlusten).
* **Resilienz & Backup:** 3-2-1-Backup-Strategie (Offline/Air-Gapped), quartalsweise Desaster-Recovery-Tests mit RTO-Validierung.
* **Privileged Access Management (PAM):** Sitzungsbasierte, zeitlimitierte Dienstleisterzugänge.

### 3. 👥 Mensch & Organisationspsychologie
* **Sicherheits-Champions:** Freiwillige Multiplikatoren je Schicht/Bereich zur Hebelung sozialer Bewährtheit (*Cialdini*).
* **Just Culture (James Reason):** Trennung von unabsichtlichen Fehlern und Vorsatz; Einführung eines anonymen QR-Code-Meldesystems ohne Sanktionsangst.
* **Psychologische Reaktanzreduktion (Brehm):** Partizipative Regelentwicklung statt Top-Down-Dekreten.

---

## 📊 Wissenschaftliche & Psychologische Grundlagen

| Theorie / Modell | Urheber | Implementierung im Konzept |
| :--- | :--- | :--- |
| **8-Stufen-Modell** | Kotter (1996) | Dringlichkeit via regionaler Vorfälle erzeugen, Führungskoalition mit BR bilden |
| **3-Phasen-Modell** | Lewin (1947) | Unfreeze (Schadensdaten) $\rightarrow$ Move (Pilotprojekte) $\rightarrow$ Refreeze (Betriebsvereinbarungen) |
| **ADKAR-Modell** | Hiatt / Prosci | Individuelle Veränderungsbegleitung vom Awareness-Building bis zum Reinforcement |
| **Just Culture** | Reason (1997) | Fehlertolerante Meldekultur für Incidents zur drastischen Senkung der MTTD |
| **Psychologische Reaktanz** | Brehm (1966) | Vermeidung von Kontrollverlustgefühlen durch Security by Design (RFID-Workflows) |
| **Gordon-Loeb-Modell** | Gordon & Loeb (2002) | Ökonomische Optimierung des Sicherheitsbudgets auf Basis der Schadenserwartung |

---

## 💰 Return on Security Investment (ROSI)

Basierend auf realen Kennzahlen der Fertigungsindustrie:

$$\text{Erwarteter Schaden} = 21 \text{ Tage Stillstand} \times 50.000\,\text{€/Tag} = 1.050.000\,\text{€}$$

* **Maximal empfohlene Investition (Gordon-Loeb ~37 %):** `388.500 €`
* **Geplantes ISMS-Budget (24 Monate):** `80.000 – 150.000 €`
* **Wirtschaftlicher Vorteil:** Das vorgeschlagene Budget beträgt lediglich **ca. 11 % des potenziellen Einzelschadens** und sichert das Unternehmen vor existenzbedrohenden Produktionsausfällen.

---

## 🗓️ 24-Monats-Roadmap

```text
[Monat 01 - 06] Phase 1: Foundation (25.000 - 40.000 €)
 ├── M1: Ernennung externer ISB | Betriebsrat-Erstgespräch | Backup-Test
 ├── M2: GF-Leitlinie | VLAN IT/OT-Trennung live
 └── M3-M4: Risikoanalyse | MFA Remote | Erste Sicherheits-Champions geschult

[Monat 07 - 18] Phase 2: Systematisierung (40.000 - 80.000 €)
 ├── M8: PAM für externe Dienstleister
 ├── M12: Betriebsvereinbarung IT-Monitoring verabschiedet | Patch-Management ≥ 95 %
 ├── M14: Incident Response Plan verabschiedet | Erste Tabletop-Simulation mit GF
 └── M16: EDR-Rollout auf allen IT/OT-Clients

[Monat 19 - 24] Phase 3: Konsolidierung & Zertifizierung (15.000 - 30.000 €)
 ├── M20: Internes ISMS-Audit & Übergang zu internem ISB
 └── M24: Externes Audit -> ISO/IEC 27001:2022 Zertifizierung
