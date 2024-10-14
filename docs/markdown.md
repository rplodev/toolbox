# Markdown

## Syntaxe

### Les titres

```markdown
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

### Paragraphes
#### Sans retour chariot
!!! info

    Chaque paragraphe est délimité par une ligne vide.

```markdown title="paragraphes_sans_retour_chariot.md" linenums="1"
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
```
<u>Rendu:</u>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

#### Avec retour chariot
!!! info

    Un retour chariot dans un paragraphe ne produit pas un changement de ligne dans le rendu.

```markdown title="paragraphes_avec_retour_chariot.md" linenums="1"
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
```
<u>Rendu:</u>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

### Retour chariot
!!! info

    Un changement de ligne est produit lorque le retour chariot est précédé de deux espaces.

```markdown title="paragraphes_avec_retour_chariot.md" linenums="1"
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.  
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.  
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
```
<u>Rendu:</u>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.  
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.  
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.
### Mise en forme du texte
#### Italique
!!! info

    Il est nécessaire d'encadrer le \**texte*\* par des \* afin qu'il soit rendu en italique.
```markdown title="texte_italique.md" linenums="1"
Lorem ipsum *dolor* sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

Lorem ipsum *dolor* sit amet, consectetur adipiscing elit.

#### Gras
!!! info

    Il est nécessaire d'encadrer le \*\***texte**\*\* par des \*\* afin qu'il soit rendu en gras.
```markdown title="texte_gras.md" linenums="1"
Lorem ipsum **dolor** sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

Lorem ipsum **dolor** sit amet, consectetur adipiscing elit.

#### Rayé
!!! info

    Il est nécessaire d'encadrer le ~~<del>texte</del>~~ par des ~~ afin qu'il soit rendu en rayé.
```markdown title="texte_rayé.md" linenums="1"
Lorem ipsum ~~dolor~~ sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

Lorem ipsum ~~dolor~~ sit amet, consectetur adipiscing elit.

#### Souligné
!!! info

    Il est nécessaire d'encadrer le &lt;u&gt;<u>texte</u>&lt;/u&gt; par des balises html &lt;u&gt;&lt;/u&gt; afin qu'il soit rendu en rayé.
```markdown title="texte_souligné.md" linenums="1"
Lorem ipsum <u>dolor</u> sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

Lorem ipsum <u>dolor</u> sit amet, consectetur adipiscing elit.

### Citations
!!! info

    Il est nécessaire de commencer un paragraphe par le caractère > afin qu'il soit rendu comme un bloc de citation.
```markdown title="bloc_de_citation.md" linenums="1"
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Les lignes de séparation
!!! info

    Il est nécessaire de placer les caractères --- encadrés par deux lignes vides.
```markdown title="ligne_de_separation.md" linenums="1"
⠀
---
⠀
```
<u>Rendu:</u>

---

### Bloc de code
#### Bloc de code inline
!!! info

    Il est nécessaire d'encadrer le code par les ` afin qu'il soit rendu comme un bloc de code inline.
~~~title="bloc_de_code_inline.py" linenums="1"
`Ceci est un bloc de code inline.`
~~~
<u>Rendu:</u>

`Ceci est un bloc de code inline.`
#### Bloc de code simple
!!! info

    Il est nécessaire d'encadrer le code par les caractères ```  afin qu'il soit rendu comme un bloc de code.
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

    Il est nécessaire d'ajouter l'attribut title="<filename\>.<extension\>" après ouverture du bloc de code.
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

    Il est nécessaire d'ajouter l'attribut linenums="<numéro de la première ligne\>" après ouverture du bloc de code.
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

    Il est nécessaire d'ajouter le caractère * au début de chaque item.  
    Afin d'ajouter des niveaux de profondeur à la liste, il est nécéssaire d'ajouter une ou plusieurs tabulation avant le caractère * qui précède chaque item.
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
    Il est nécessaire d'ajouter les caractères - [ ] avant chaque item non sélectionné.  
    Il est nécessaire d'ajouter les caractères - [X] avant chaque item sélectionné.
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
### Les liens hypertexte
!!! info
    La syntaxe permettant d'afficher un lien hypertexte est la suivante \[nom du lien affiché](url du lien)
```markdown title="lien_hypertexte.md" linenums="1"
[Link](http://example.com)
```
<u>Rendu:</u>

[Link](http://example.com)