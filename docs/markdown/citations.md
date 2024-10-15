# Les blocs de citation

## Simples
!!! info

    Pour créer un bloc de citation, il est nécessaire d'ajouter le caractère `>` suivi d'un espace devant un mot ou une phrase.

```markdown title="bloc_citation_simple.md" linenums="1"
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.

## Avec paragraphes
!!! info

    Pour créer un bloc de citation contenant plusieurs paragraphes, il est nécessaire d'ajouter le caractère `>` au début des lignes vides.

```markdown title="bloc_citation_avec_paragraphes.md" linenums="1"
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.

## Imbriqués
!!! info

    Pour créer un bloc de citation imbriqué, il est nécessaire d'ajouter des caractères `>` supplémentaires en début de bloc nécessitant l'imbrication.  
    Le nombre de caractères à utiliser correspond au niveau d'imbrication.

```markdown title="bloc_citation_imbrique.md" linenums="1"
> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>>> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
<u>Rendu:</u>

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
>>> Lorem ipsum dolor sit amet, consectetur adipiscing elit.