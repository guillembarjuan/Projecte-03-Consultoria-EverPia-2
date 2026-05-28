# P05 – Presentació sistemes emmagatzematge

## 📌 Descripció del producte

Aquest producte consisteix en una **presentació oral i visual** realitzada davant d’un client simulat (una empresa de disseny que necessita modernitzar els seus servidors de fitxers). L’objectiu és comparar de manera exhaustiva dues tecnologies líders per a la gestió d’emmagatzematge en servidors:

- **LVM (Logical Volume Manager)** – solució estàndard per a entorns Linux.
- **Storage Spaces (Espais d’Emmagatzematge)** – eina nativa de Microsoft per a servidors Windows.

La presentació ha de servir per **educar el client** i **justificar la nostra elecció tecnològica**, de manera que s’aprovi el pressupost per a la implementació dels nous servidors de fitxers.

---

## 🎯 Objectius específics

- Explicar les **característiques principals** i beneficis de LVM i Storage Spaces.
- Establir **paral·lelismes clars** entre la terminologia de cada tecnologia:
  - LVM: Grups de Volums (VG), Volums Lògics (LV), Extents Físics (PE).
  - Storage Spaces: Storage Pool, Virtual Disk, Physical Disk.
- Analitzar **semblances i diferències** en escalabilitat, rendiment i costos.
- **Defensar els avantatges** d’emprar aquestes tecnologies en servidors de fitxers, segons el perfil del client.
- Transmetre la informació de manera **clara, tècnica però accessible** per a un públic no necessariament expert.

---

## 📊 Contingut de la presentació

La presentació es va estructurar en els següents blocs:

1. **Introducció al repte del client**  
   - Necessitat de modernitzar els servidors de fitxers.  
   - Requisits: flexibilitat, escalabilitat, tolerància a fallades.

2. **Què és LVM?**  
   - Funcionament, flexibilitat (redimensionament en calent), snapshots.  
   - Terminologia: PV, VG, LV, PE.  
   - Entorns d’ús típics (Linux).

3. **Què és Storage Spaces?**  
   - Funcionament, perfils de residència (mirror, parity, simple).  
   - Terminologia: Storage Pool, Virtual Disk, Physical Disk.  
   - Integració amb Windows Server.

4. **Taula comparativa**  
   - Semblances: ambdues virtualitzen l’emmagatzematge, permeten redundància i creixement dinàmic.  
   - Diferències: entorn (Linux vs Windows), eines de gestió (línia de comandes vs GUI + PowerShell), maduresa, rendiment en determinats escenaris.

5. **Avantatges per al client**  
   - **LVM**: ideal si l’empresa té majoritàriament servidors Linux, cost zero de llicències, gran comunitat.  
   - **Storage Spaces**: millor integració si ja usen Active Directory i Windows Server, gestió centralitzada.  
   - Recomanació final basada en l’entorn actual del client.

6. **Conclusió**  
   - Resum de la millor opció i justificació del pressupost.

---

## 🛠️ Eines utilitzades

- **PowerPoint / Google Slides** – suport visual.
- **Gràfics i esquemes** per explicar l’arquitectura de LVM i Storage Spaces.
- **Exemples pràctics** de comandes (Linux) i de la interfície de Storage Spaces (Windows).

---

## 💡 Aprenentatges clau

- **Capacitat de síntesi i comparació** entre tecnologies de diferents entorns (Linux vs Windows).
- **Comunicació oral tècnica**: adaptar el llenguatge a un públic mixt (direcció i tècnics).
- **Ús de paral·lelismes** per facilitar la comprensió de conceptes equivalents.
- **Argumentació basada en necessitats reals del client**, no només en especificacions tècniques.
- **Preparació de materials visuals** que reforcin el missatge i facilitin la presa de decisions.

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Projecte 03 – Consultoria EverPia 2  
Data de realització: segon trimestre del curs 2025-2026

---

*Aquesta presentació demostra la capacitat d’analitzar, comparar i defensar solucions tecnològiques complexes davant d’un client, una habilitat essencial per a qualsevol consultor d’infraestructura IT.*
