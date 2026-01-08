# T04 — Instal·lació de Windows Server 2025 🪟🖥️

## Introducció al cas

Després del nostre assessorament tècnic, l’empresa **TransLògic S.A.** ens encarrega el **desplegament dels seus servidors amb Windows Server 2025**.

Abans de realitzar la implantació definitiva en entorns productius, és necessari dur a terme una **instal·lació de prova** en màquines virtuals. Aquesta instal·lació servirà per a dos objectius clau:

- Aprendre i interioritzar correctament els **procediments d’instal·lació**.
- Elaborar una **guia d’instal·lació documentada**, que actuarà com a base per a futurs desplegaments als sistemes del client.

Aquesta tasca simula una situació real en què una empresa IT ha de preparar documentació tècnica clara, reutilitzable i defensable.

---

## Objectiu de la tasca

L’objectiu principal de la T04 és:
- Realitzar una **instal·lació correcta i coherent de Windows Server 2025** en una màquina virtual.
- Documentar tot el procés en **format Markdown**, amb captures de pantalla i observacions tècniques.
- Validar que la configuració de la màquina virtual compleix els **requisits oficials de Microsoft**.

El resultat final ha de ser una **guia d’instal·lació clara**, útil tant per a l’equip tècnic com per a futurs desplegaments en entorns reals.

---

## Procediment d’instal·lació

### 1️⃣ Creació de la màquina virtual

Cal crear una màquina virtual amb les següents característiques:

- **Memòria RAM:** 8 GB  
- **Processadors:** 2 CPU  
- **Discos:**
  - Disc principal: 32 GB (instal·lació del sistema operatiu)
  - Disc secundari: 10 GB
- **Xarxa:**
  - 1 interfície en xarxa **NAT (o no NAT segons configuració del centre)**
  - 1 interfície en xarxa **Host-only**

Aquesta configuració està pensada per simular un servidor real amb separació de recursos.

---

### 2️⃣ Instal·lació de Windows Server 2025

Durant la instal·lació s’han de complir els següents requisits:

- Sistema operatiu: **Windows Server 2025**
- Mode: **GUI**
- Idioma del sistema: **English (US)**
- Configuració regional i teclat: **Espanyol**
- Nom de l’equip:  

