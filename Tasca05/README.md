# T05 — Instal·lació del domini (Active Directory) 🏢🔐

## Introducció

Aquesta tasca és la continuació directa de la **T04 — Instal·lació de Windows Server 2025**. En aquest punt, el següent pas lògic és desplegar el **Directori Actiu (Active Directory Domain Services)** sobre la màquina virtual creada prèviament.

L’objectiu és doble:
- Practicar el procediment complet d’instal·lació i configuració d’un **domini Windows**.
- Generar una **Prova de Concepte (PoC)** que pugui ser presentada als responsables de **TransLògic S.A.**, permetent validar i ajustar la configuració abans del desplegament en producció.

Aquesta tasca reprodueix un escenari real on una empresa IT ha de documentar, justificar i automatitzar la configuració d’un entorn de domini.

---

## Objectiu de la tasca

En finalitzar la T05, l’alumne ha de ser capaç de:
- Instal·lar els **rols necessaris** per a un controlador de domini.
- Crear un **domini nou en un bosc nou** amb una nomenclatura definida.
- Establir el **nivell funcional** adequat.
- Promocionar el servidor a **Controlador de Domini (DC)**.
- Automatitzar el procés mitjançant **PowerShell**.
- Documentar tot el procediment de manera clara i reutilitzable.

---

## Procediment a documentar

La documentació ha d’estar escrita en **Markdown** i incloure captures de pantalla i explicacions clares.

### 1️⃣ Instal·lació de rols

- Instal·lació del rol:
  - **Active Directory Domain Services (AD DS)**
- Instal·lació automàtica de les característiques necessàries associades.

---

### 2️⃣ Creació del domini

- Crear un **domini nou en un bosc nou** amb el nom:

