# T06 — Configuració del domini (Active Directory) 🧩👥

## Introducció

Un cop el **domini ja està creat i operatiu** (tasca T05), el següent pas és desplegar-lo correctament. Això implica crear i organitzar els **objectes principals del domini**: unitats organitzatives (OU), grups, usuaris i equips.

Aquesta tasca té com a objectiu entendre i aplicar una **estructura lògica i escalable** dins d’Active Directory, tal com es faria en un entorn professional real. També permet validar el funcionament del domini mitjançant l’accés d’usuaris reals des d’un equip client.

---

## Objectiu de la tasca

En finalitzar la T06, l’alumne ha de ser capaç de:
- Organitzar un domini mitjançant **Unitats Organitzatives (OU)**.
- Definir una **estructura de grups** coherent.
- Crear **plantilles d’usuari** per estandarditzar altes.
- Crear usuaris reals a partir d’aquestes plantilles.
- Integrar un **equip client Windows** dins del domini.
- Verificar el correcte funcionament del domini amb inicis de sessió reals.

---

## Procediment pràctic

### 1️⃣ Creació de les Unitats Organitzatives (OU)

Crear una estructura d’OU que permeti una gestió clara dels objectes del domini.  
Com a mínim, s’ha de contemplar la separació de:
- Usuaris
- Grups
- Equips

📌 L’objectiu de les OU és facilitar:
- L’organització.
- L’aplicació de polítiques.
- L’escalabilitat futura del domini.

---

### 2️⃣ Definició de l’estructura de grups

Crear els següents **grups de seguretat**:

- `gestio`
- `magatzem`
- `gerencia`
- `personal`

🔗 **Relació entre grups**  
Tots els grups (`gestio`, `magatzem` i `gerencia`) **han de ser membres del grup `personal`**.

Aquesta estructura permet:
- Assignar permisos comuns al grup `personal`.
- Afegir permisos específics per departament.

---

### 3️⃣ Creació de plantilles d’usuari

Crear una **plantilla d’usuari** per a cada grup següent:
- Gestio
- Magatzem
- Gerencia

Cada plantilla ha de tenir configurat:
- La **pertinença automàtica al grup corresponent**.
- La **creació de la carpeta personal** de l’usuari.

Les plantilles permeten:
- Estandarditzar la creació d’usuaris.
- Evitar errors de configuració.
- Estalviar temps en entorns amb moltes altes.

---

### 4️⃣ Creació d’usuaris de prova

A partir de cada plantilla:
- Crear **un usuari de prova** per a:
  - Gestio
  - Magatzem
  - Gerencia

Aquests usuaris serviran per validar:
- La pertinença als grups.
- L’accés al domini.
- La correcta creació del perfil i carpeta personal.

---

### 5️⃣ Aprovisionament d’un equip client

#### PC1 — Equip del domini

- Crear un objecte equip anomenat:

