# T03 — Serveis de transferència de fitxers 📂🔐

## Introducció a la tasca

Durant la vostra etapa a **EverPia** heu configurat serveis fonamentals com **DHCP**, **DNS** i la **connexió i administració remota** dels equips. Aquests serveis són la base de qualsevol infraestructura IT funcional.

Ara, en el vostre camí cap a una major autonomia tècnica, cal **ampliar coneixements** i dominar altres serveis clau. Tot i que avui dia plataformes cloud com **Dropbox**, **Google Drive** o similars són habituals per compartir arxius, com a professionals IT és imprescindible **entendre i saber implementar els protocols fonamentals de transferència de fitxers**.

Per aquest motiu, aquesta tasca es planteja com una **formació pràctica** per convertir-vos en experts en serveis de transferència de dades, amb especial èmfasi en la **seguretat**.

---

## Objectius de la formació

En acabar la T03, haureu de ser capaços de **respondre amb fets, configuracions reals i criteri tècnic** a les següents qüestions:

- Com funciona el **protocol FTP**?
- Quina diferència hi ha entre el **mode actiu** i el **mode passiu**?
- Com s’implementa un **servidor FTP segur**?
- Què és el **protocol sFTP** i per què és una alternativa al FTP tradicional?
- Com es pot **engabiar (chroot)** usuaris en connexions sFTP?
- Quins **altres mètodes alternatius** existeixen per a la transferència de fitxers?

---

## Pla de treball: què farem?

Aquesta formació es divideix en **dues parts clarament diferenciades**: teoria i pràctica real.

### 1️⃣ Fonaments teòrics i seguretat

Estudi dels protocols **FTP** i **sFTP**, amb especial atenció a:
- Funcionament general del protocol FTP.
- Diferències entre **mode actiu** i **mode passiu**.
- Ports utilitzats.
- Riscos de seguretat del FTP tradicional.
- sFTP com a solució segura basada en **SSH**.
- Engabiament d’usuaris (chroot) per evitar fuites de seguretat.

---

### 2️⃣ Laboratori pràctic — *The Real World*

És el moment de posar les mans al teclat. Es treballarà amb **màquines virtuals** per simular entorns reals.

#### 🔹 Activitat A — Servidor FTP
Configuració d’un servidor FTP estàndard:
- Creació d’usuaris.
- Assignació de permisos de lectura i escriptura.
- Engabiament (chroot) d’usuaris.
- Verificació de connexions des d’un client extern.
- Observació de la transferència de dades **en clar (sense xifrar)**.

Objectiu: entendre els riscos reals del FTP tradicional.

---

#### 🔹 Activitat B — Servidor sFTP (Secure FTP)
Implementació d’un servidor sFTP:
- Transferència de fitxers sobre **SSH**.
- Configuració segura d’usuaris.
- Engabiament d’usuaris per limitar l’accés al sistema.
- Validació de la connexió segura des d’un client extern.

Objectiu: aplicar bones pràctiques de seguretat en entorns professionals.

📌 **Nota important**  
Com a administradors de sistemes, la seguretat **no és una opció, és una obligació**. Entendre la diferència entre FTP i sFTP és vital per al vostre futur professional.

---

## Sistema d’avaluació

Per superar la T03, haureu de demostrar la vostra competència en **dos formats**:

### 📝 Prova escrita (40%)
Preguntes sobre:
- Protocols de transferència.
- Ports utilitzats.
- Modes de connexió (actiu/passiu).
- Conceptes clau de seguretat.

### 🛠️ Examen pràctic (60%)
Repte de configuració cronometrat:
- Crear **des de zero** un servidor FTP i un servidor sFTP.
- Configurar usuaris amb permisos específics.
- Aplicar engabiament (chroot).
- Verificar la connexió i la transferència des d’un client extern.

---

## Resultat esperat

En finalitzar aquesta tasca, l’alumne ha de ser capaç de:
- Implementar serveis de transferència de fitxers funcionals.
- Identificar riscos de seguretat en protocols no xifrats.
- Aplicar solucions segures com sFTP en entorns reals.
- Justificar tècnicament les decisions preses.

Aquesta tasca reforça una competència clau per a qualsevol perfil IT orientat a **xarxes, sistemes i seguretat**.

---

## Materials i recursos de suport 📚

- **Materials de l’assignatura**  
  Moodle — *Serveis de Xarxa*

Prepareu les vostres màquines virtuals.  
**Comencem a transferir dades.**

