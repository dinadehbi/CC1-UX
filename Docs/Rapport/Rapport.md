# Rapport : Analyse & Conception Soli-lms

## Gestion des tâches





## Chapitre 1 : Introduction

Dans le cadre du développement de l'application **Soli-LMS**, le package `pkg_QCM-Apprenant` joue un rôle essentiel en fournissant une interface dédiée aux apprenants pour interagir avec les QCM (Questions à Choix Multiples). Ce module est conçu pour répondre aux besoins des utilisateurs en termes d'évaluation continue, de suivi des performances et d'amélioration de l'expérience d'apprentissage.

L'objectif principal de ce package est de permettre aux apprenants d'accéder facilement aux QCM créés par les formateurs, de soumettre leurs réponses et de recevoir un feedback instantané sur leurs performances. Ce système offre une manière efficace de renforcer les compétences et de mesurer les progrès dans un cadre pédagogique interactif.

---

## Chapitre 2 : Besoin

Voici le besoin pour le rapport dans la section correspondante :

---

## Chapitre 2 : Besoin

Le besoin principal dans le cadre de l'application **Soli-LMS** est de mettre en place un système d'évaluation interactif et efficace pour les apprenants. Le package `pkg_QCM-Apprenant` doit permettre aux utilisateurs d'accéder facilement aux QCM créés par les formateurs, de répondre aux questions, et de recevoir un retour immédiat sur leurs performances.

L'application doit répondre aux objectifs suivants :

1. **Facilité d'accès** : Offrir une interface intuitive et simple pour les apprenants afin de consulter les QCM disponibles.
2. **Évaluation continue** : Permettre un suivi des performances des apprenants au fur et à mesure qu'ils passent les QCM.
3. **Feedback instantané** : Fournir un retour immédiat sur les réponses données, permettant ainsi aux utilisateurs de connaître leurs progrès.
4. **Suivi des progrès** : Mesurer les progrès des apprenants dans leur parcours d'apprentissage en offrant des statistiques détaillées sur leurs résultats.

Cela permettra d'améliorer l'expérience d'apprentissage tout en assurant une évaluation continue et une adaptation aux besoins des apprenants.

---
---



## Chapitre 3 : Design Thinking

Le **Design Thinking** est une méthode créative centrée sur l'utilisateur pour résoudre des problèmes complexes. Elle se compose de cinq étapes clés :

1. **Empathie** : Comprendre les besoins et défis des utilisateurs par des recherches qualitatives.
2. **Définition** : Analyser les informations recueillies pour définir clairement le problème à résoudre.
3. **Idéation** : Générer un large éventail d'idées sans restrictions.
4. **Prototype** : Créer des prototypes simples pour tester les solutions.
5. **Test** : Tester les prototypes auprès des utilisateurs et affiner les solutions en fonction des retours.


---

## Chapitre 4 : L'empathie

 phase, l'objectif est de comprendre les besoins, les comportements et les émotions des utilisateurs, afin de mieux adapter le système **Soli-LMS** aux attentes des apprenants.

### 1. **Ce qu'il dit**  
L'apprenant exprime :  
"Je veux tester mes connaissances sur ce sujet. Où est le QCM que mon formateur a créé ?"

### 2. **Ce qu'il fait**  
L'apprenant se connecte à l'application **Soli-LMS**, accède au package `pkg_QCM-Apprenant`, et navigue jusqu'au QCM. Ensuite, il commence à répondre aux questions.

### 3. **Ce qu'il ressent**  
L'apprenant peut ressentir de la **curiosité** et de la **motivation** à réussir le QCM, mais aussi un peu **d'anxiété** s'il souhaite bien performer et obtenir des résultats satisfaisants.

### 4. **Ce dont il a besoin**  
L'apprenant a besoin d'un **accès fluide** au QCM, d'un **feedback clair** après chaque réponse, et d'un **résumé final** de ses résultats pour évaluer ses progrès et ses compétences.

---

Ce chapitre met en évidence l'importance de comprendre les attentes et émotions des apprenants pour offrir une expérience utilisateur optimale dans le cadre de l'application **Soli-LMS**.
---

Voici un texte pour le **Chapitre 5 : Définition du problème** :

---

## Chapitre 5 : Définition du problème

### **Définition du problème :**

L'apprenant rencontre des difficultés pour naviguer de manière fluide et efficace dans le package `pkg_QCM-Apprenant`. De plus, l'absence de feedback clair après chaque réponse limite sa capacité à évaluer ses connaissances de façon autonome et à suivre ses progrès en temps réel.

---

Ce chapitre définit clairement le problème que l'application doit résoudre pour améliorer l'expérience de l'utilisateur et faciliter l'apprentissage.
---

## Chapitre 5 : Définition du problème

D'accord, je vais expliquer de manière plus claire le diagramme de cas d'utilisation en texte et comment il se relie à l'idéation.

### **Idéation du Mode d’Apprentissage Adaptatif :**

L'idée du mode d'apprentissage adaptatif pour le package `pkg_QCM-Apprenant` consiste à personnaliser l'expérience d'apprentissage de l'apprenant. En fonction des réponses de l'apprenant, les questions du QCM s'ajustent à son niveau. Si l'apprenant répond incorrectement à une question, il reçoit immédiatement une explication et des ressources supplémentaires pour l'aider à progresser.

### **Diagramme de Cas d'Utilisation (en texte) :**

1. **Acteur : Apprenant**
   L’acteur principal est l’apprenant qui interagit avec le système.

2. **Cas d’utilisation :**
   - **Consulter les QCM disponibles**  
     L'apprenant peut accéder à une liste de QCM créés par le formateur.
   - **Répondre à un QCM**  
     L'apprenant peut répondre aux questions d'un QCM.
   - **Recevoir un feedback**  
     Après chaque réponse, l'apprenant reçoit un feedback qui lui indique si la réponse est correcte ou incorrecte.
   - **Visualiser les résultats**  
     L'apprenant peut consulter ses résultats après avoir terminé un QCM.
   - **Mode d’apprentissage adaptatif**  
     Ce cas d’utilisation ajoute un mode où les questions du QCM s’adaptent en fonction des réponses de l'apprenant. Si l'apprenant répond mal, il reçoit une explication et des ressources pour améliorer ses connaissances.

### **Relations :**

- L'apprenant interagit avec tous les cas d'utilisation :
  - **Consulter les QCM disponibles**  
  - **Répondre à un QCM**  
  - **Recevoir un feedback**  
  - **Visualiser les résultats**  
  - **Mode d’apprentissage adaptatif** : Ce cas s’ajoute comme une fonctionnalité supplémentaire qui améliore l’expérience d'apprentissage.

### **Comment l’idéation se reflète dans le cas d’utilisation :**

- **Mode d’apprentissage adaptatif** : 
   Ce cas d’utilisation fait partie de l'idéation. Il montre que les questions du QCM ne sont pas fixes, mais ajustées dynamiquement en fonction des performances de l'apprenant. Par exemple, si l'apprenant commet des erreurs dans un domaine particulier, les prochaines questions seront liées à ce domaine, avec des explications et des ressources pour aider l'apprenant à progresser.

### Conclusion

L'idéation consiste à améliorer l'expérience de l'apprenant en rendant l'interaction avec le QCM plus personnalisée et dynamique. Le diagramme de cas d'utilisation montre les différentes interactions de l'apprenant avec le système, y compris le **mode d’apprentissage adaptatif** qui ajustera les questions et fournira des ressources en fonction des besoins de l'apprenant.

## Chapitre 7 : Prototype
## Conclusion



### Réalisé par

Dehbi Dina

### Supervisé par

Monsieur Fouad ESSARRAJ
