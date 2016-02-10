# Titres

Comme nous écrivons un document en markdown, nous devons ajouter un titre et quelques sous-titres.

Markdown supporte deux types de titres, Setext et atx.

Les titres Setext sont “soulignés" en utilisant le signe égale (Pour les titres de 1er niveau) et avec des pointillés (Pour les titres de 2nd niveau). Par exemple :

```
Ceci est un titre 1
=============

Ceci est un titre 2
-------------
```

N'importe quel nombre de = ou - va fonctionner.

Les titres Atx utilisent entre 1 et 6 dièses au début de la ligne, correspondant au titres de niveau 1 à 6. Par exemple:

```
# Ceci est un titre 1

## Ceci est un titre 2

###### Ceci est un titre 6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---
