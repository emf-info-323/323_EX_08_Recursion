<h1><code>Module 323</code> - Programmer de manière fonctionnelle</h1>

# 😅 Exercice 08 - Récursion / Solution

## Objectifs

-   Entraîner la récursion, les méthodes récursives.

## Rapports à produire

## R1 - Calculer la somme d'un tableau

On vous donne un tableau contenant une série de nombres. Votre tâche est de développer une fonction récursive qui calcule la somme de tous les éléments de ce tableau. La fonction devra prendre en paramètre le tableau et retourner un entier correspondant à la somme des valeurs. Par exemple, pour le tableau [2, 4, 6], la fonction devra retourner 12, et pour le tableau [5, 10, 15, 20], elle devra retourner 50.

```json
{
    "tableau": [34, 67, 23, 89, 2, 5, 8, 13],
    "resultat": 241
}
```

## R2 - Calculer la suite de Fibonacci

La suite de Fibonacci est une suite de nombres dans laquelle chaque terme correspond à la somme des deux termes précédents. Pour cet exercice, vous allez écrire une fonction récursive capable de calculer un terme de cette suite en fonction de sa position. La fonction prendra en paramètre un entier représentant le rang du terme souhaité et devra retourner la valeur correspondante dans la suite de Fibonacci. Par exemple, l’appel de la fonction avec le paramètre `n = 6` devra retourner la valeur `8`, et l’appel avec le paramètre `n = 9` devra retourner la valeur `34`.

**Exemple de la suite de Fibonacci**

> **Cas de base** : F(0) = 0, F(1) = 1
> **Calcul** :
> F(2) = F(1) + F(0) = 1 + 0 = 1
> F(3) = F(2) + F(1) = 1 + 1 = 2
> F(4) = F(3) + F(2) = 2 + 1 = 3
> F(5) = F(4) + F(3) = 3 + 2 = 5
> ...

```json
{
    "n": 9,
    "resultat": 34
}
```

## R3 - Calculer la taille totale d'un volume

Créez une méthode récursive qui, sur la base des données `userFilesystem` qui représente le contenu d'un volume, calcule récursivement la taille de l'ensemble des dossiers et fichiers qui s'y trouvent.

Vous devez obtenir le résultat suivant :

```json
20660497
```

## R4 - Vérifier si ce dossier contient, à un endroit ou un autre, un fichier d'un certain genre

Créez une méthode récursive qui, sur la base des données `userFilesystem` qui représente le contenu d'un volume, vérifie si ce volume contient un ou plusieurs fichiers d'une certaine extension, à un endroit ou un autre dans sa hiérarchie.

Lorsque appelée avec l'extension `.mp3`, vous devez obtenir ceci :

```json
true
```

Lorsque appelée avec l'extension `.mp4`, vous devez obtenir ceci :

```json
false
```

## R5 - Reconstitution de l'arbre des généalogique des animaux

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

---

<img src="res/EMF_logo_RVB_Info_long.png" width="25%" style="margin-left:-20px;">
