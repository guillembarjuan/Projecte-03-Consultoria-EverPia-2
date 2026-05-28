
# P04 – Documentació servidor DNS

## 📌 Descripció del producte

Aquest producte consisteix a **publicar al repositori GitHub la configuració completa d’un servidor DNS** (BIND9) que es va implementar com a prova de concepte per al client **Digicore**. La configuració original es troba en una màquina virtual Ubuntu Server; l’objectiu és extreure els fitxers clau i pujar‑los al repositori perquè qualsevol altre tècnic pugui **replicar la configuració** de manera ràpida, només descarregant els arxius i reiniciant el servei.

Aquest producte garanteix la **repetibilitat** de la infraestructura i facilita la recuperació davant d’incidències o la creació d’entorns idèntics en altres servidors.

---

## 🎯 Objectius específics

- **Extreure els fitxers de configuració** del servidor DNS de la màquina virtual mitjançant **SCP** (Secure Copy Protocol).
- **Organitzar els fitxers** dins del repositori GitHub seguint l’estructura estàndard (carpeta `tasca04` amb subcarpeta `zones`).
- **Documentar el procés** amb un `README.md` que expliqui el contingut i els passos seguits.
- **Permetre la replicació** ràpida de la configuració en qualsevol altre servidor Linux.

---

## 🔧 Passos realitzats

### Fase 1 – Preparació de la connectivitat i extracció dels fitxers

1. **Configuració de la interfície Host‑Only** a la màquina virtual Ubuntu Server per permetre la comunicació amb l’amfitrió (màquina física).
2. **Verificació de la connectivitat** (ping entre la VM i l’amfitrió).
3. **Ús del protocol SCP** per copiar els fitxers clau des de la VM a l’amfitrió:
   - `/etc/bind/named.conf.options`
   - `/etc/bind/named.conf.local`
   - Tots els arxius de zones ubicats a `/etc/bind/zones/`

Exemple de comanda:
```bash
scp usuari@ip_vm:/etc/bind/named.conf.options .
````

### Fase 2 – Integració a GitHub

1. **Creació de la carpeta `tasca04`** al repositori (on s’allotja tota la documentació de la tasca DNS).
2. **Creació d’un `README.md` dins de `tasca04`** explicant el funcionament del servidor i la configuració.
3. **Pujada dels fitxers de configuració**:
   - `named.conf.options`
   - `named.conf.local`
   - Subcarpeta `zones/` amb els arxius de zona corresponents (ex: `db.digicore.local`, `db.192.168.x`, etc.)
4. **Documentació addicional** (captures de pantalla, comprovacions amb `dig` i `nslookup`).

> Tota aquesta documentació es troba a la carpeta [`tasca04`](/./tasca04) d’aquest repositori.

---

## 📁 Contingut lliurat

- **Carpeta `producte04/`** amb aquest `README.md` explicatiu.
- **Carpeta `tasca04/`** que conté:
  - `README.md` (descripció detallada de la configuració DNS).
  - `named.conf.options`
  - `named.conf.local`
  - `zones/` (arxius de zona)
  - Captures de pantalla a `img/` (opcional).

---

## 🔗 Enllaç a la documentació completa

> 📂 Tota la configuració i explicació pas a pas del servidor DNS es troba a:  
> [`./tasca04` – Documentació servidor DNS](/./tasca04)

---

## 💡 Aprenentatges clau

- **Ús de SCP** per transferir fitxers de configuració entre màquines virtuals i l’amfitrió de manera segura.
- **Organització de fitxers tècnics** dins d’un repositori GitHub per mantenir la traçabilitat.
- **Repetibilitat de configuracions:** la possibilitat de reconstruir un servidor DNS en pocs minuts només descarregant els fitxers i reiniciant el servei.
- **Importància de documentar** no només les comandes, sinó també l’estructura de zones i les decisions de configuració.

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Projecte 03 – Consultoria EverPia 2  
Data de realització: segon trimestre del curs 2025-2026

---

*Aquest producte demostra que la documentació tècnica ben estructurada i emmagatzemada en un repositori de control de versions és una eina fonamental per a la gestió professional d’infraestructures IT.*



