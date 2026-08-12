# Mit GitHub-projekt

Dette er mit første projekt, hvor jeg lærer at bruge **Git, GitHub og VS Code**.

## Om projektet

## Billede

![Mit projekt](images/projekt.jpg)

Projektet består af en simpel hjemmeside lavet med:

- HTML
- CSS
- Git
- GitHub

## Filer

| Fil | Beskrivelse |
|---|---|
| `index.html` | Hjemmesidens HTML |
| `style.css` | Hjemmesidens styling |
| `README.md` | Dokumentation af projektet |

## Min hjemmeside

Du kan åbne `index.html` i en browser for at se hjemmesiden.
## Links

- [Mit GitHub repository](https://github.com/emsa0006/mit-git-projekt)

## Git-konflikt

Der opstod en merge-konflikt, fordi Student A og Student B ændrede den samme linje i `index.html`.

### Student A

Student A ændrede overskriften til:

> Velkommen til vores hjemmeside

### Student B

Student B ændrede overskriften til:

> Velkommen til min hjemmeside

### Løsning

Git kunne ikke automatisk vælge mellem de to ændringer.

Konflikten blev løst i VS Code Merge Editor, hvor vi valgte Student A's ændring:

> Velkommen til vores hjemmeside

Derefter blev konflikten committed og pushet til GitHub.

### Resultat

Hjemmesiden viser nu:

> Velkommen til vores hjemmeside