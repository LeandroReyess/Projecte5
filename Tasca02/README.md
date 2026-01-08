# T02 — Control de versions: Treballant amb Git 🧩🔧

## Descripció de la tasca

Fins ara, el control de versions del projecte s’ha gestionat principalment mitjançant l’editor web de GitHub. Tot i que aquesta opció ha permès resoldre situacions bàsiques, presenta diverses **limitacions importants**:

- 🐢 **Lentitud i poca comoditat** a l’hora d’editar fitxers.
- ✍️ Editors web menys versàtils que eines locals com **Visual Studio Code** o editors específics de Markdown.
- 📁 **Gestió poc eficient del repositori**, especialment en afegir carpetes, estructurar arxius o fer canvis repetitius.

Per aquest motiu, amb la tasca **T02** es comença a treballar amb el **flux de treball real utilitzat en entorns professionals**, combinant:
- **Git en local** (control de versions descentralitzat)
- **GitHub com a repositori remot**

---

## Objectiu de la T02

L’objectiu d’aquesta tasca és aprendre a **treballar correctament amb Git en local**, utilitzant-lo conjuntament amb GitHub, tal com es fa en el món professional.

Això implica:
- Editar sempre els fitxers en local.
- Fer servir Git per registrar els canvis.
- Sincronitzar el treball amb el repositori remot de GitHub.

La T02 no consisteix només a “fer funcionar Git”, sinó a **interioritzar una metodologia de treball ordenada, eficient i escalable**.

---

## Context: Git i GitHub

- **Git** és un sistema de control de versions **descentralitzat**, creat per **Linus Torvalds**, el creador de Linux.
- Git va aparèixer **abans que GitHub** i va suposar una ruptura amb els sistemes de control de versions centralitzats que predominaven fins aquell moment.
- **GitHub** és un gestor de repositoris remots que utilitza Git, però **no és l’única opció** (també existeixen GitLab, Bitbucket, etc.).

En aquest projecte s’utilitzarà **GitHub** com a repositori remot per centralitzar el treball de l’equip.

---

## Metodologia de treball

El flux de treball que seguirem és el següent:

1. **Repositori base a GitHub**  
   El projecte sempre parteix d’un repositori existent a GitHub.

2. **Clonar el repositori en local**  
   Es crea una còpia sincronitzada al disc dur de l’ordinador (PC de classe o de casa).

3. **Treballar sempre en local**  
   - Edició de fitxers amb editors locals (VS Code, editors Markdown, etc.).
   - Creació i modificació d’arxius i carpetes de manera eficient.

4. **Registrar els canvis amb Git**
   - `git add` → seleccionar els canvis.
   - `git commit` → guardar un punt de control amb missatge clar.

5. **Pujar els canvis a GitHub**
   - `git push` → sincronitzar el treball local amb el repositori remot.

6. **Baixar canvis abans de començar**
   - `git pull` → assegurar que el repositori local està actualitzat.
   - Especialment important quan es treballa des de diferents ordinadors.

Aquest flux garanteix:
- Historial de canvis clar.
- Possibilitat de recuperar versions anteriors.
- Treball coherent en equip.

---

## Bones pràctiques esperades

Durant la T02 s’espera que:
- Els commits siguin **freqüents i amb missatges clars**.
- No es treballi directament des de l’editor web de GitHub.
- El repositori tingui una **estructura ordenada**.
- Es faci `pull` abans de començar a treballar i `push` en acabar.

Aquesta disciplina és clau per a projectes col·laboratius i entorns professionals.

---

## Materials i recursos de suport 📚

- **Introducció a GitHub**  
  👉 https://github.com/SMX2n/IntroGitHub

- **Guia de Control de Versions**  
  👉 https://github.com/SMX2n/ControlVersions

Aquests materials serveixen com a base per entendre els conceptes i resoldre dubtes durant la tasca.

---

## Resultat esperat

En acabar la T02, l’alumne ha de ser capaç de:
- Treballar amb Git en local amb seguretat.
- Sincronitzar correctament un projecte amb GitHub.
- Entendre i aplicar un flux de treball real de control de versions.

Aquesta tasca és fonamental per al desenvolupament correcte de la resta del projecte i per acostumar-se a les eines que s’utilitzen en el sector professional IT.

