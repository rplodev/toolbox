# Markdown

## Syntaxe



### Bloc de code

#### Bloc de code inline
!!! info

    Il est nécessaire d'encadrer le code par les `` ` `` afin qu'il soit rendu comme un bloc de code inline.
~~~title="bloc_de_code_inline.py" linenums="1"
`Ceci est un bloc de code inline.`
~~~
<u>Rendu:</u>

`Ceci est un bloc de code inline.`

#### Bloc de code simple
!!! info

    Il est nécessaire d'encadrer le code par les caractères ` ``` `  afin qu'il soit rendu comme un bloc de code.
~~~title="bloc_de_code_simple.py" linenums="1"
```
Ceci est du code.
```
~~~
<u>Rendu:</u>

```
Ceci est du code.
```

#### Bloc de code avec coloration syntaxique
!!! info

    Il est nécessaire d'indiquer le langage utilisé après ouverture du bloc de code.
~~~title="bloc_de_code_avec_coloration_syntaxique.py" linenums="1"
```python
def fonction():
    pass
```
~~~
<u>Rendu:</u>

```python
def fonction():
    pass
```

#### Bloc de code avec titre
!!! info

    Il est nécessaire d'ajouter l'attribut `title="<filename>.<extension>"` après ouverture du bloc de code.
~~~title="bloc_de_code_avec_titre.md" linenums="1"
```python title="snippets.py"
def fonction():
    pass
```
~~~
<u>Rendu:</u>

```python title="snippets.py"
def fonction():
    pass
```

#### Bloc de code avec numérotation des lignes
!!! info

    Il est nécessaire d'ajouter l'attribut `linenums="<numéro de la première ligne>"` après ouverture du bloc de code.
~~~title="bloc_de_code_avec_numérotation_des_lignes.md" linenums="1"
```python linenums="1"
def fonction():
    pass
```
~~~
<u>Rendu:</u>

```python linenums="1"
def fonction():
    pass
```

### Les listes

#### Les listes non ordonnées
!!! info

    Il est nécessaire d'ajouter le caractère `*` au début de chaque item.  
    Afin d'ajouter des niveaux de profondeur à la liste, il est nécéssaire d'ajouter une ou plusieurs tabulation avant le caractère `*` qui précède chaque item.
```markdown title="liste_non_ordonnée.md" linenums="1"
* Item 1
* Item 2
    * Item 2.1
    * Item 2.2
        * Item 2.2.1
* Item 3
```
<u>Rendu:</u>

* Item 1
* Item 2
    * Item 2.1
    * Item 2.2
        * Item 2.2.1
* Item 3

#### Les listes ordonées
!!! info

    Il est nécessaire d'ajouter le caractère indiquant le numéro d'ordre.  
    Afin d'ajouter des niveaux de profondeur à la liste, il est nécéssaire d'ajouter une ou plusieurs tabulation avant le caractère indiquant le numéro d'ordre qui précède chaque item.
```markdown title="liste_ordonnée.md" linenums="1"
1. Item 1
2. Item 2
    1. Item 2.1
    2. Item 2.2
        1. Item 2.2.1
3. Item 3
```
<u>Rendu:</u>

1. Item 1
2. Item 2
    1. Item 2.1
    2. Item 2.2
        1. Item 2.2.1
3. Item 3

#### Les check lists
!!! info
    Il est nécessaire d'ajouter les caractères `- [ ]` avant chaque item non sélectionné.  
    Il est nécessaire d'ajouter les caractères `- [X]` avant chaque item sélectionné.
```markdown title="check_list.md" linenums="1"
- [ ] Task 1
- [X] Task 2
- [X] Task 3
- [ ] Task 4
```
<u>Rendu:</u>

- [ ] Task 1
- [X] Task 2
- [X] Task 3
- [ ] Task 4

### Les images

#### Les images simples
!!! info
    La syntaxe permettant d'afficher une image est la suivante : `[texte_alternatif](url_de_l'image "titre_de_l'image")`
```markdown title="image_simple.md" linenums="1"
![Logo Markdown](./assets/images/markdown/markdown.png "Logo Markdown")
```
<u>Rendu:</u>

![Logo Markdown](./assets/images/markdown/markdown.png "Logo Markdown")

#### Les liens hypertexte images
!!! info
    La syntaxe permettant d'afficher une image comme lien hypertexte est la suivante : `[![texte_alternatif](url_de_l'image "titre_de_l'image")](url du lien)`
[![Logo Markdown](./assets/images/markdown/markdown.png "Logo Markdown")](https://www.markdownguide.org/)
