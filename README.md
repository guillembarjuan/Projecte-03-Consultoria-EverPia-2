# 📁 Projecte 03 – Consultoria EverPia 2: “Sobreviure en una empresa IT”

Benvingut al tercer projecte del curs de **Sistemes Microinformàtics i Xarxes (SMX)**.  
Després de l’èxit del primer projecte, EverPia creix i els reptes es multipliquen. Ara ja no som aprenents: som **tècnics júnior** del departament IT, i la nostra missió és mantenir viva la infraestructura de la consultora mentre apaguem focs, resolem incidències i documentem el caos.

> *“Si sobrevius a això... pots sobreviure a qualsevol empresa.”* – Lema d’EverPia 2

Aquest projecte simula la vida real dins d’una empresa tecnològica: gestionar serveis essencials (DNS, LDAP, LVM), treballar sota pressió, prendre decisions tècniques i comunicar-les professionalment.

---

## 📌 Índex

1. [Descripció del projecte](#-descripció-del-projecte)
2. [Metodologia de treball](#-metodologia-de-treball)
3. [Tasques realitzades](#-tasques-realitzades)
4. [Productes finals](#-productes-finals)
5. [Estructura del repositori](#-estructura-del-repositori)
6. [Tecnologies i eines](#-tecnologies-i-eines)
7. [Aprenentatges clau](#-aprenentatges-clau)
8. [Competències treballades](#-competències-treballades)
9. [Enllaços d’interès](#-enllaços-dinterès)
10. [Autor](#-autor)

---

## 📋 Descripció del projecte

**EverPia 2** és la segona temporada de la consultora simulada. L’empresa ha crescut ràpidament i ara gestiona clients, contractes i serveis crítics 24/7. El pressupost no ha augmentat, però els problemes sí. Com a tècnics del departament IT, hem d’assegurar la continuïtat del negoci, resoldre incidències complexes i documentar cada pas abans que algú formategi per error.

El projecte s’estructura en quatre setmanes i integra coneixements de tots els mòduls: Sistemes Operatius en Xarxa (0224), Seguretat Informàtica (0226), Serveis de Xarxa (0227), Aplicacions Web (0228), Sostenibilitat (1708), Itinerari d’Ocupabilitat (1710) i Projecte Intermodular (1713).

---

## 🧭 Metodologia de treball

Tot el projecte s’ha gestionat amb la metodologia **Kanban** mitjançant **Microsoft Planner**, amb les següents columnes:

- **Backlog** – totes les tasques pendents (T00 a T09).
- **En curs** – tasques en desenvolupament.
- **En revisió** – tasques pendents de validació.
- **Fet** – tasques completades.

🔗 **Enllaç al tauler Kanban del projecte (P01):**  
[https://planner.cloud.microsoft/webui/v1/plan/tAuHFPLAlUi8kZC4X1uHhJYAFCHP](https://planner.cloud.microsoft/webui/v1/plan/tAuHFPLAlUi8kZC4X1uHhJYAFCHP?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)

---

## ✅ Tasques realitzades

A continuació es mostren les tasques desenvolupades al llarg del projecte, extretes del document d’instruccions:

| ID | Tasca | Descripció | Tipus |
|----|-------|-------------|-------|
| T00 | Presentació del projecte i creació del Kanban i el repositori | Creació del Planner i repositori GitHub inicial. | Grup |
| T01 | Gestor de contrasenyes | Informe comparatiu entre Bitwarden (online) i KeePassXC (offline) + guia d’ús. | Individual |
| T02 | Gestió emmagatzematge | Formació sobre RAID, DAS, NAS, SAN i prova de validació. | Grup |
| T03 | Gestió flexible de discos (LVM i Espais d’emmagatzematge) | Implementació de LVM en Linux (mirror, snapshots, ampliació) i Storage Spaces en Windows (mirror, paritat). | Grup |
| T04 | Serveis de directori. LDAP | Instal·lació i configuració d’OpenLDAP, creació d’OU, usuaris i grups, i autenticació d’un client. | Grup |
| T05 | Anàlisi de l’entorn: possibles models de negoci | Estudi d’una empresa real (clients de pràctiques): organigrama, entorn, CANVAS, DAFO, missió, visió, valors. | Grup |
| T06 | Fonaments del servei DNS | Vídeo formatiu (10-15 min) explicant jerarquia DNS, resolució, registres (A, CNAME, MX, NS, SOA, PTR) i eines de diagnosi (dig, nslookup). | Parelles |
| T07 | Instal·lant un servidor de noms | Configuració d’un servidor DNS primari amb BIND9 (zona directa i inversa), transferència de zona a secundari. | Grup |
| T08 | Sitemaps i estructura d’una pàgina web | Màsterclass sobre parts d’una web, sitemaps, jerarquia i documentació en Markdown. | Individual |
| T09 | ODS i el sector IT (grups) | Selecció de 3 ODS rellevants per al sector IT i elaboració d’un informe amb bones pràctiques. | Grup |
| T10 | ASG – Relació ODS i ASG | Infografia sobre els aspectes Ambientals, Socials i de Governança aplicats a EverPia. | Grup |

---

## 🏁 Productes finals

Els productes avaluables del projecte són set. Cada un està documentat dins la seva carpeta corresponent al repositori.

| Codi | Nom del producte | Enllaç a la carpeta |
|------|------------------|---------------------|
| **P01** | Kanban del projecte | [`Producte01`](./Producte01) |
| **P02** | Repositori de GitHub | [`Producte02`](./Producte02) |
| **P03** | Rèplica web | [`Producte03`](./Producte03) |
| **P04** | Documentació servidor DNS | [`Producte04`](./Producte04) |
| **P05** | Presentació sistemes emmagatzematge | [`Producte05`](./Producte05) |
| **P06** | Vídeo. Fonaments DNS | [`Producte06`](./Producte06) |
| **P07** | ASG a EverPia: informe visual per a inversors | [`Producte07`](./Producte07) |

Cada carpeta conté el seu propi `README.md` amb la descripció detallada, evidències i, si escau, enllaços als arxius de configuració o presentacions.

---

## 📁 Estructura del repositori

El repositori està organitzat de la següent manera (segons la imatge proporcionada):

```
Projecte-03-Consultoria-EverPia-2/
│
├── README.md                    # Aquest fitxer
│
├── Producte01/                  # P01 – Kanban
├── Producte02/                  # P02 – Repositori GitHub
├── Producte03/                  # P03 – Rèplica web
├── Producte04/                  # P04 – Documentació DNS
├── Producte05/                  # P05 – Presentació emmagatzematge
├── Producte06/                  # P06 – Vídeo DNS
├── Producte07/                  # P07 – Infografia ASG
│
├── tasca01/                     # Gestor de contrasenyes (informe.md + guia.md + img)
├── tasca03/                     # LVM i Storage Spaces (documentació en Markdown)
├── tasca04/                     # LDAP (configuració i captures)
├── tasca06/                     # Fonaments DNS (vídeo i guia de comandes)
└── (altres carpetes de tasques individuals segons calgui)
```

Tota la documentació tècnica està redactada en **Markdown**, amb imatges allotjades a subcarpetes `img` i utilitzant text alternatiu per a l’accessibilitat.

---

## 🛠️ Tecnologies i eines utilitzades

- **Metodologia àgil:** Kanban amb Microsoft Planner.
- **Control de versions:** Git i GitHub.
- **Sistemes operatius:** Ubuntu Server, Zorin OS (Linux), Windows 11.
- **Serveis de xarxa:** BIND9 (DNS), OpenLDAP.
- **Emmagatzematge:** LVM (Linux), Storage Spaces (Windows), RAID, DAS, NAS, SAN.
- **Virtualització:** VirtualBox (màquines virtuals per a servidor DNS, LDAP, proves).
- **Web:** WordPress (WP Local), rèplica de web existent, plugins Kadence Blocks.
- **Seguretat:** Gestors de contrasenyes (Bitwarden, KeePassXC), polítiques de contrasenyes.
- **Documentació:** Markdown, vídeos (Stream de Office 365), infografies (Canva o similar).
- **Sostenibilitat:** ODS, criteris ASG, economia circular.

---

## 💡 Aprenentatges clau

- **Resolució de problemes sota pressió:** gestionar serveis crítics (DNS, LDAP) que fallen i han de ser restaurats ràpidament.
- **Administració avançada d’emmagatzematge:** crear i gestionar volums lògics amb LVM (miralls, snapshots, ampliacions) i espais d’emmagatzematge a Windows (mirall, paritat).
- **Implementació de serveis de directori:** instal·lar i configurar OpenLDAP, crear OU, usuaris i grups, i autenticar clients.
- **Domini del DNS:** comprendre la jerarquia, tipus de registres, eines de diagnosi (dig, nslookup) i construir un servidor primari/secundari amb BIND9.
- **Documentació professional amb GitHub:** organització de carpetes (`ProducteXX`, `tascaXX`), redacció en Markdown, ús de `README.md` com a índex, i pujada de fitxers de configuració mitjançant SCP.
- **Comunicació tècnica:** elaborar un vídeo formatiu sobre DNS, una presentació comparativa LVM vs Storage Spaces, i una infografia ASG per a inversors.
- **Sostenibilitat aplicada al sector IT:** relacionar ODS i ASG amb accions concretes d’una empresa tecnològica (eficiència energètica, igualtat, governança).

---

## 🧰 Competències treballades

Extretes del document de projecte (mòduls 0224, 0226, 0227, 0228, 1708, 1710, 1713):

- Instal·lar i configurar sistemes operatius en xarxa i serveis associats (DNS, LDAP).
- Gestionar dispositius d’emmagatzematge aplicant tècniques de redundància (RAID, LVM, Storage Spaces).
- Aplicar mesures de seguretat activa i passiva (gestors de contrasenyes, política de contrasenyes).
- Instal·lar serveis de resolució de noms (DNS) i verificar-ne el funcionament.
- Gestionar serveis de directori (OpenLDAP) per centralitzar l’autenticació.
- Elaborar documentació tècnica i administrativa en Markdown i repositoris GitHub.
- Planificar, organitzar i fer seguiment del treball amb metodologies àgils (Kanban).
- Transmetre informació amb claredat en format oral (presentació), vídeo i infografia.
- Aplicar criteris de sostenibilitat (ODS, ASG) a l’estratègia empresarial.

---

## 🔗 Enllaços d’interès

- 👤 **Perfil de GitHub:** [github.com/guillembarjuan](https://github.com/guillembarjuan)
- 📌 **Tauler Kanban (Planner) – P01:** [Accedir al Planner del Projecte 03](https://planner.cloud.microsoft/webui/v1/plan/tAuHFPLAlUi8kZC4X1uHhJYAFCHP?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)
- 📂 **Carpeta P01 (Kanban):** [`./Producte01`](./Producte01)
- 📂 **Carpeta P02 (Repositori):** [`./Producte02`](./Producte02)
- 📂 **Carpeta P03 (Rèplica web):** [`./Producte03`](./Producte03)
- 📂 **Carpeta P04 (Documentació DNS):** [`./Producte04`](./Producte04)
- 📂 **Carpeta P05 (Presentació emmagatzematge):** [`./Producte05`](./Producte05)
- 📂 **Carpeta P06 (Vídeo DNS):** [`./Producte06`](./Producte06)
- 📂 **Carpeta P07 (Infografia ASG):** [`./Producte07`](./Producte07)

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Curs 2025-2026

---

*Aquest projecte demostra que sobreviure en una empresa IT no és només qüestió de tècnica: cal saber gestionar la pressió, comunicar solucions i documentar cada pas. EverPia 2 m’ha ensenyat que el professional no neix, es forja a base d’incidències i commits ben documentats.*
