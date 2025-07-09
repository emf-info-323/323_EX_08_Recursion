<h1><code>Module 323</code> - Programmer de manière fonctionnelle</h1>

# 😅 Exercice 08 - Récursion

## Objectifs

- Entraîner la récursion, les méthodes récursives.

## Rapports à produire

## R1 - Reconstitution de l'arbre des généalogique des animaux

Créez une méthode récursive qui, sur la base de `bdAnimaux`, produise récursivement le JSON ci-dessous :

```json
{
   "animal": {
      "vertébré": {
         "à sang chaud": {
            "mammifère": {
               "cochon": {},
               "tigre": {},
               "lapin": {},
               "ours": {},
               "humain": {
                  "motard": {}
               }
            },
            "oiseau": {
               "manchot": {},
               "corbeau": {},
               "autruche": {},
               "perroquet": {}
            }
         },
         "à sang froid": {
            "poisson": {
               "poisson clown": {},
               "requin": {},
               "poisson-globe": {},
               "poisson-papillon": {}
            },
            "amphibien": {
               "grenouille": {},
               "crapaud": {},
               "salamandre": {},
               "néobatrachia": {}
            },
            "reptile": {
               "python": {},
               "caméléon": {},
               "tortue": {},
               "crocodile": {}
            }
         }
      },
      "invertébré": {
         "avec articulations": {
            "insecte": {
               "mante religieuse": {},
               "fourmi": {}
            },
            "arachnide": {
               "mygale": {},
               "scorpion": {}
            },
            "crustacés": {
               "crabe": {},
               "décapodes": {}
            }
         },
         "sans articulations": {
            "mollusque": {
               "gastéropodes": {},
               "pieuvre": {}
            },
            "annélides": {
               "ver": {},
               "sangsue": {}
            },
            "échinodermes": {
               "étoile de mer": {},
               "concombre de mer": {}
            }
         }
      }
   }
}
```

## R2 - Calculer la taille totale d'un volume

Créez une méthode récursive qui, sur la base des données `userFilesystem` qui représente le contenu d'un volume, calcule récursivement la taille de l'ensemble des dossiers et fichiers qui s'y trouvent.

Vous devez obtenir le résultat suivant :

```json
20660497
```

## R3 - Vérifier si ce dossier contient, à un endroit ou un autre, un fichier d'un certain genre

Créez une méthode récursive qui, sur la base des données `userFilesystem` qui représente le contenu d'un volume, vérifie si ce volume contient un ou plusieurs fichiers d'une certaine extension, à un endroit ou un autre dans sa hiérarchie.

Lorsque appelée avec l'extension `.mp3`, vous devez obtenir ceci :

```json
true
```

Lorsque appelée avec l'extension `.mp4`, vous devez obtenir ceci :

```json
false
```

## R4 - xxx

Blabla :

```json
```

## R5 - xxx

Blabla :

```json
```

---

<img src="res/EMF_logo_RVB_Info_long.png" width="25%" style="margin-left:-20px;">
