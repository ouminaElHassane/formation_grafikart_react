# Introduction :(2 min)
## Formation_grafikart_react
La formation React 2023 est en ligne ! GRAFIKART

## Partie une : les bases de react 
1. IO
2. Syestem de fonction 

## Partie2: Ecosystem : outils
1. Gestion des formulaires
2. Gestion des Routers
3. Cas pratiques : cas diffciles à modéliser avec React !

## Partie3: Tests, configurer les tests pour tester le code fait avec react
----------------------------------------------------------------------------------------
# Introduction :(5 min 37 secondes)

## React c'est quoi ?

React : libraririe pour faire des interfaces web et des ineterfaces utilisateur native

## React c'est pourquoi ?
Une librairie est là pour resoudre un probleme : creons une page de todoList :

![image](https://github.com/user-attachments/assets/92eb6cf3-9e78-47cc-bcb2-dc608689aa26)

 Il est difficle de synchroniser notre etat (les taches de liste a faire) et notre vue (dom) ==>Tour de Jinga assez difficile à maintenir

 ==>React intervient : separe le systeme en plusieurs parties :
 
1. une partie representant l'éta de notre composant
2. notre vue en focntion de l'etat

   ![image](https://github.com/user-attachments/assets/b16125c8-b267-463c-bc06-80a591d02246)

React gere la synchronisation

## Pourquoi React plutôt que "Vue.js" , "Svelte" , "Angular" , "SolidJs" et autre ?

selon les situation, y'a des avantages et les inconvenients de chaque librairie ==>Different != Meilleur, chacune ont des approches differentes :

1. Réact est simple (en surface) : moins de fonctions et methodes
2. Ecosystème : outils, bibliotheques (animation, formulaires, requetes serveurs), react native(applications natives), react motion(videos a partir de react : adaptateur ou outil), bcp d'adaptatuers
3. JSX (syntaxe un peu particuliere un peu proche de js, moins de chose à apprender pour connaitre cette syntaxe)
4. Préférences personnelles : tester bcp de librariries, faire son opinion, et voir si ça vous plait ou non

## Prérequis
1. (()=>"Etre à l'aise avec le javascript")()
   * Portée des variables : une variable definie dans une fonction n'existe que dans ce context là
   * Fontions flechées : Arrow function
   * map(), filter() et reduce() qui permettent de travaillr sur les tableaux

## Ce que l'on va voir :
 * Les bases de React : installation + voir comment trvailler avec, quelques fonctionnalités dessus
 * Les concepts avancés
 * l'Ecosystème : certains librairies
 * Cas pratiques : developpés une petite application ==>le fonctionnement de React, organiation du projets, utilisation de queleques librairies

   ----------------------------------------------------------------------------------------
# Apprendre React : Installation de React :(4 min 12 secondes) :
## Deux approche :
 * Utilisation dans le navigateur :https://react.dev/----> Learn React--->Installation ---->Fork--->codesandbox (https://codesandbox.io/s/pxtpj8?file=/src/App.js&utm_medium=sandpack)
   ![image](https://github.com/user-attachments/assets/b2c1962b-0a32-4557-adea-58bd3e54e956)

 * Creation des fichiers dans notre Ordinateur,il nous faut un outil pour comprendre l'installation de react, le JSX, ils existe plusieurs outils, mais on va choisir "Vite"

![image](https://github.com/user-attachments/assets/f1af3578-8856-4a9b-a5d0-a4460df266bd)

Pour installer "Vite", il est imperatif que vous installiez "NodeJs"

![image](https://github.com/user-attachments/assets/7c4e2afa-d325-4662-a204-4f07eb440dba)

![image](https://github.com/user-attachments/assets/91f69eda-eeb3-4b2e-b73c-4d1f776e65ce)

On selectionne la variation "Javascript classic" 

![image](https://github.com/user-attachments/assets/80e0dc30-d844-46e4-9f26-915516225f74)


* >>>>> npm install : pour telecharger l'ensemble de dependances
  >>>>>  npm run dev : demarrer un serveur web sous le port 5173

   ![image](https://github.com/user-attachments/assets/a875bcea-0092-4686-a93c-b57965442a55)
  ![image](https://github.com/user-attachments/assets/d45740ef-b92a-43d7-acd2-1f9150b5e182)

  ![image](https://github.com/user-attachments/assets/3dfcda24-2978-4c6c-8239-d7ded4045f00)

pour aller sur les bases Saines, on doit nettoyer ce qu'il a proposer par default (dossier assets, app.css, index.css)

dans App.jsx : on efface tout le code , on laisse seulement :  

![image](https://github.com/user-attachments/assets/12b9c8de-6cc9-4577-93f7-4bd8109ffb9e)

au niveau de main supprimer l'import : import './index.css'



