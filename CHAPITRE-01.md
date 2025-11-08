# **Introduction à HTML et à la création du Web**

## **1. Aux origines de l’informatique**

L’histoire du **Web** et du **HTML** commence bien avant Internet.
Pour comprendre comment on en est arrivé aux pages web que nous créons aujourd’hui, il faut remonter aux **fondements de l’informatique**.

### **1.1 Les premiers ordinateurs**

* **1940–1950 :** Les premiers ordinateurs, comme **ENIAC** (1946) ou **UNIVAC I** (1951), étaient d’immenses machines électroniques remplies de tubes à vide.
  Ces ordinateurs n’avaient **ni clavier, ni écran** : les programmes étaient introduits via des **cartes perforées**.
* Ils étaient conçus pour des calculs scientifiques et militaires, et non pour communiquer entre eux.

### **1.2 L’apparition du transistor et des microprocesseurs**

* En **1947**, l’invention du **transistor** au Bell Labs révolutionne l’électronique : les ordinateurs deviennent plus petits, plus fiables et plus rapides.
* En **1971**, Intel lance le **premier microprocesseur** (Intel 4004).
  → C’est le début de l’ère des **ordinateurs personnels (PC)**.

### **1.3 L’avènement des réseaux**

Dans les années **1960**, plusieurs laboratoires de recherche américains cherchent à **faire communiquer les ordinateurs entre eux** :

* En **1969**, naît **ARPANET**, un projet financé par le département américain de la Défense.
  Il s’agit du **premier réseau d’ordinateurs interconnectés**, ancêtre d’Internet.
* Dans les années **1970**, les chercheurs créent les **protocoles TCP/IP**, toujours utilisés aujourd’hui.
  → Ces protocoles permettent aux ordinateurs de “se comprendre” à travers le réseau.

---

## **2. De l’Internet au World Wide Web**

### **2.1 Internet ≠ Web**

Il est essentiel de distinguer :

* **Internet** : le **réseau** physique et logique reliant les ordinateurs du monde entier.
* **Le Web (World Wide Web)** : un **service** qui fonctionne *sur* Internet, permettant de consulter des pages via un navigateur.

Autrement dit :

> Internet est l’autoroute, et le Web en est une des voitures.

### **2.2 L’idée de Tim Berners-Lee**

En **1989**, **Tim Berners-Lee**, chercheur au **CERN** (Centre Européen de Recherche Nucléaire), cherche un moyen simple de **partager des documents scientifiques** entre chercheurs.

Il imagine :

1. Un **langage de description** des documents : **HTML** (*HyperText Markup Language*).
2. Un **système d’adressage universel** : **URL** (*Uniform Resource Locator*).
3. Un **protocole de communication** : **HTTP** (*HyperText Transfer Protocol*).
4. Et un **logiciel pour afficher les pages** : le premier **navigateur web**, appelé **WorldWideWeb** (puis renommé Nexus).

Cette invention marque la **naissance du Web**, en **1990**.

---

## **3. La naissance du HTML**

### **3.1 Qu’est-ce que le HTML ?**

Le **HTML** (HyperText Markup Language) est un **langage de balisage** conçu pour structurer le contenu d’une page web.

* Il ne s’agit **pas d’un langage de programmation** (comme JavaScript ou Python),
  mais d’un **langage descriptif** : il décrit la nature et la hiérarchie du contenu.
* Les **balises** (ou *tags*) permettent de définir des titres, paragraphes, liens, images, formulaires, etc.

Exemple minimal d’une page HTML :

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Ma première page web</title>
  </head>
<body>
  <header>
    <h1>Bonjour, monde !</h1>
  </header>
  <main>
<p>Voici ma première page en HTML.</p>
  </main>
  <footer>
  </footer>
</body>
</html>
```

### **3.2 Le concept d’hypertexte**

Le mot “**hypertexte**” vient de la capacité du HTML à **lier plusieurs documents entre eux** grâce à des liens (`<a href="...">`).

C’est cette idée de **navigation entre documents** qui a donné son nom au **World Wide Web** : une “toile mondiale” de documents reliés.

---

## **4. Évolution du Web et des standards HTML**

### **4.1 Les premières versions**

* **HTML 1.0 (1993)** : version expérimentale, très limitée (textes, liens, images).
* **HTML 2.0 (1995)** : première normalisation officielle par l’IETF.
* **HTML 3.2 / 4.0 (1997–1999)** : introduction des tableaux, formulaires, CSS et JavaScript.

### **4.2 L’apparition du CSS et de JavaScript**

Dans les années **1990**, le Web devient visuel et interactif :

* Le **CSS (Cascading Style Sheets)** permet de séparer la **mise en forme** du contenu.
* Le **JavaScript** ajoute l’**interactivité** : formulaires dynamiques, animations, requêtes asynchrones…

### **4.3 HTML5 (depuis 2014)**

Le **HTML5**, normalisé par le **W3C** et le **WHATWG**, modernise totalement le langage :

* Balises sémantiques (`<header>`, `<article>`, `<footer>`, etc.).
* Intégration native des **vidéos**, **sons**, **canvas**.
* Meilleure compatibilité mobile et SEO.
* API intégrées (géolocalisation, stockage local, etc.).

Aujourd’hui, **HTML5 est la norme universelle du Web moderne**.

---

## **5. Le rôle du HTML dans un site web**

Un site web moderne repose sur **trois piliers fondamentaux** :

| Couche    | Langage        | Rôle principal           |
| --------- | -------------- | ------------------------ |
| Structure | **HTML**       | Contenu et organisation  |
| Apparence | **CSS**        | Mise en forme et design  |
| Dynamisme | **JavaScript** | Interactivité et logique |

> HTML fournit la **structure**,
> CSS fournit le **style**,
> JavaScript apporte le **comportement**.
