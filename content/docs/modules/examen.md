---
title: "Examens"
bookIcon: examen
weight: 6
---

# Examens

<p>Le cours INF 1220 est évalué au moyen de <strong>deux examens en ligne télésurveillés</strong>. Il n'y a aucun travail noté à remettre et aucun entretien de suivi. L&rsquo;objectif des examens est de valider le savoir-faire que vous avez intégré tout au long du cours.</p>

| Évaluation  | Sujets                | Moment           | Durée     | Pondération |
|-------------|-----------------------|------------------|-----------|-------------|
| Examen 1    | Modules 1 et 2        | semaine 7        | 3 heures  | 30&nbsp;%   |
| Examen 2    | L'ensemble du cours   | fin du cours     | 3 heures  | 70&nbsp;%   |

Le premier examen a lieu à la septième semaine du cours et porte uniquement sur les deux premiers modules&nbsp;:
les algorithmes et le pseudocode, puis les bases du langage Java (types, opérateurs, variables, méthodes,
classes et instances). Comme la question revient sans cesse, soyons clair sur le second examen&nbsp;:
**l'examen 2 couvre toute la matière du cours**, y compris celle du premier examen.

{{% hint danger %}}

## Conditions d'examen

Les deux examens sont télésurveillés. Dans les deux cas&nbsp;:

- vous n'avez droit à **aucune note** (ni notes personnelles, ni aide-mémoire, ni manuel, ni documentation)&nbsp;;
- vous n'avez **pas accès à Internet** (ni le site du cours, ni un moteur de recherche, ni l'intelligence artificielle)&nbsp;;
- vous n'avez **pas accès à un compilateur Java ni à un environnement de programmation**.

Vous devez donc écrire votre code Java de mémoire, sans le compiler ni l'exécuter.

{{% /hint %}}

<p>Si vous ne maîtrisez pas la matière du cours, vous ne réussirez probablement pas les examens. Prenez le temps d'étudier, de réviser et de poser des questions le cas échéant. Pratiquez-vous à programmer.</p>

<p>Quand il s'agit de programmer, plusieurs étudiants remettent du code qui n'est pas fonctionnel, qui ne peut en aucun cas répondre à la question. Comme vous ne pouvez pas exécuter votre code pendant l'examen, vous devez le relire et l'exécuter dans votre esprit, en traçant la valeur des variables. Comme vous devez de toute manière toujours expliquer vos solutions, vous pouvez en profiter pour y inclure une séquence d'exécution de votre programme. Un programmeur doit toujours se relire. Il est facile de se tromper complètement en écrivant même du code simple si on ne se relit pas avec soin.</p>

## Mise en forme de votre examen

Même écrit sans l'aide d'un environnement de développement, votre code Java doit être lisible. Veillez à aligner les accolades ouvrantes et fermantes, à indenter votre code de manière cohérente, à espacer les opérateurs et les virgules de manière uniforme, et à limiter la longueur des lignes à environ 100 caractères. N'oubliez pas d'ajouter des commentaires clairs et concis pour expliquer les parties complexes, en les plaçant au-dessus des blocs de code concernés plutôt qu'en fin de ligne. Un code illisible est difficile à corriger et vous désavantage.

## Se préparer

Les étudiants qui passent un examen en ligne télésurveillé doivent s'assurer d'avoir un environnement adéquat. Il est de votre responsabilité d'avoir un ordinateur fiable, avec un bon clavier, une caméra fonctionnelle et une connexion Internet stable permettant la télésurveillance. Si vous travaillez sur un ordinateur portable, gardez-le sous tension. Prévoyez au besoin une solution de rechange pour votre connexion (par exemple, un branchement par l'entremise de votre téléphone cellulaire).

Nous comprenons que la vie vous réserve des surprises. Parfois un logiciel plante. Parfois il faut redémarrer un ordinateur et ainsi de suite. Néanmoins, vous êtes responsable d'être bien préparé.

Puisque vous n'aurez ni notes, ni manuel, ni compilateur, ni accès à Internet, la préparation ne consiste pas à rassembler de la documentation&nbsp;: elle consiste à pratiquer.

- Écrivez du code Java à la main, sur papier ou dans un simple éditeur de texte, sans le compiler. Vérifiez ensuite votre code en le compilant. Vous découvrirez vos erreurs habituelles.
- Apprenez par cœur la structure d'un programme Java&nbsp;: déclaration de classe, méthode `main`, déclaration de méthode, boucles, conditions.
- Refaites les exercices et les activités d'autoévaluation de chaque module jusqu'à ce que vous puissiez les résoudre sans aide.
- Faites les examens factices ci-dessous en conditions réelles&nbsp;: trois heures, sans notes, sans Internet et sans compilateur.

**Nous vous suggérons de prévoir au moins 4 heures pour vous préparer à chaque examen.**

## Gestion du temps à l'examen

Chaque examen peut comporter plusieurs questions de programmation. Vous devez donc pouvoir fournir en quelques minutes du code fonctionnel ainsi que des explications précises. Vous devez pouvoir écrire un programme Java correct et l'expliquer en une trentaine de minutes. Vous devez arriver bien entraîné et bien préparé.

La durée de chaque examen est de trois heures. Vous devez joindre l'Université si vous avez des questions concernant la durée de votre examen. La personne qui vous encadre ne contrôle pas la durée de l'examen.

## Examen factice — préparation à l'examen 1 (modules 1 et 2)

<p>Pour vous pratiquer pour le premier examen, prenez un maximum de trois heures pour répondre aux six questions suivantes, sans notes, sans Internet et sans compilateur :</p>
<ol>
<li>Écrivez, en pseudocode, un algorithme qui lit une suite de nombres entiers terminée par la valeur 0 et qui affiche le plus grand nombre lu (la valeur 0 servant uniquement de marqueur de fin). Précisez les entrées, les sorties et le comportement de votre algorithme lorsque la suite est vide.</li>
<li>Deux algorithmes résolvent le même problème : le premier effectue environ n&sup2; opérations, le second environ 100n opérations, où n est la taille de l'entrée. Expliquez ce que signifie la notation grand-O, donnez la complexité de chacun des deux algorithmes et indiquez à partir de quelle taille d'entrée le second devient préférable.</li>
<li>Donnez la valeur et le type de chacune des expressions Java suivantes, et expliquez brièvement chaque résultat : <code>7 / 2</code>, <code>7 % 2</code>, <code>7.0 / 2</code>, <code>(int) 3.9</code>, <code>"3" + 4</code>, <code>(char) 65</code>.</li>
<li>Écrivez une méthode Java <code>static boolean estBissextile(int annee)</code> qui retourne <code>true</code> si l'année passée en paramètre est bissextile. Une année est bissextile si elle est divisible par 4, sauf si elle est divisible par 100, à moins qu'elle ne soit aussi divisible par 400. Expliquez votre solution et donnez quelques exemples de valeurs de retour.</li>
<li>Écrivez une classe <code>Compteur</code> comportant une variable d'instance et une variable de classe (<code>static</code>). Expliquez, en français, la différence entre une variable de classe, une variable d'instance et une variable locale, en indiquant la portée et la durée de vie de chacune.</li>
<li>Créez une classe <code>Rectangle</code> munie d'un constructeur prenant une largeur et une hauteur, ainsi que de deux méthodes <code>aire</code> et <code>perimetre</code>. Ajoutez une méthode <code>main</code> qui crée deux rectangles et affiche leur aire et leur périmètre. Expliquez la différence entre une classe et une instance de classe.</li>
</ol>
<p>Dans tous les cas, vous devez expliquer vos solutions et produire du code valable.</p>

## Examen factice 1 — préparation à l'examen 2

<p>Pour vous pratiquer pour l'examen final, prenez un maximum de trois heures pour répondre aux six questions suivantes, sans notes, sans Internet et sans compilateur :</p>
<ol>
<li>Écrivez une fonction Java qui, étant donné une chaîne de caractères, retourne la même chaîne de caractères mais inversée. Par exemple, la fonction doit transformer la chaîne "un chien" en la chaîne "neihc nu". Vous pouvez faire l'hypothèse que les caractères de la chaîne originale se représentent tous en 2 octets selon la norme UTF-16.</li>
<li>Écrivez une fonction Java qui prend un tableau d'entier et compte le nombre d'entiers négatifs.</li>
<li>Écrivez une classe qui va lire, dans son constructeur, les chaînes de caractères trouvées dans un fichier texte. Le constructeur doit prendre le nom du fichier en argument. La classe doit être munie d'une méthode enregistre prenant un nom de fichier en paramètre. Lorsque la méthode enregistre est invoquée, les chaînes de caractères chargées par le constructeur sont écrites dans un fichier texte prenant le nom de fichier fourni à la méthode enregistre. Il doit être possible, en appelant la méthode enregistre ainsi qu'un constructeur de dupliquer une instance de classe. </li>
<li>Écrivez une fonction Java qui, étant donné un tableau d'entier, calcule la moyenne des valeurs, sous la forme d'un nombre à virgule flottante.</li>
<li>Mettez en oeuvre le jeu Fizz Buzz à l'aide d'une fonction Java, affichant les nombre de un à cent, en y ajoutant Fizz quand le nombre est divisible par trois et Buzz quand le nombre est divisible par cinq.</li>
<li>Écrivez un programme Java qui utilise FileOutputStream et FileInputStream pour écrire une séquence de nombres entiers dans un fichier binaire, puis la relire. Gérez les exceptions.</li>
</ol>
<p>Dans tous les cas, vous devez expliquer vos solutions et produire du code valable.</p>
<p>Vous devriez arrivez sans mal à produire les solutions attendues en moins de 3 heures. Si vous n'y arrivez pas, c'est que vous manquez de pratique.</p>

## Examen factice 2 — préparation à l'examen 2

<p>Pour vous pratiquer pour l'examen final, prenez un maximum de trois heures pour répondre aux six questions suivantes, sans notes, sans Internet et sans compilateur :</p>
<ol>
<li>Écrivez une classe «&nbsp;Tableau&nbsp;» munie d'une fonction «&nbsp;unique&nbsp;» qui prend comme paramètre un tableau (String[] t). La fonction doit trouver le nombre de valeurs répétées consécutivement dans le tableau. Une valeur est répétée si la valeur précédente lui est identique. Ainsi donc, étant donné le tableau {"bah", "bah", "be", "bo", "bo", "bo"}, votre fonction doit retourner l’entier 3 puisqu’il y a trois valeurs répétées.</li>
<li>Écrivez une fonction occurrences(String s, char c) qui prend deux paramètres : une chaine de caractères et un caractère. Elle doit retourner un tableau comprenant les indices correspondant aux occurrences du caractère (second paramètre) dans la chaîne (premier paramètre). Les indices doivent être des entiers de 1 à s.length() inclusivement.</li>
<li>Écrivez un programme qui demande à l’utilisateur de fournir un entier positif. Le programme doit vérifier si l’entier en question est un nombre premier. Un nombre premier n’est divisible que par lui-même et par le nombre 1.</li> 
<li>Écrivez un programme Java qui demande à l'utilisateur de choisir un nombre impair entre 0 et 100. Le programme doit ensuite offrir à l'utilisateur un nombre impair entre 0 et 100 et demander à celui-ci si le nombre choisi est (a) plus petit (b) plus grand ou (c) identique au nombre offert par le programme. Le programme doit continuer tant que la bonne valeur n'est pas trouvée par le programme informatique. Votre mise en œuvre doit être efficace pour obtenir tous les points. Vous devez pleinement expliquer votre solution.</li>
<li>Créez une classe «&nbsp;Fruit&nbsp;» dotée de deux méthodes non-statiques nommées «&nbsp;mange&nbsp;» et «&nbsp;jette&nbsp;». Les méthodes ne doivent prendre aucun paramètre et ne retourner qu’un entier. La méthode «&nbsp;mange&nbsp;» doit retourner le nombre de fois qu'elle a été appelée pendant la vie de l'objet (instance de classe) courante. La méthode «&nbsp;jette&nbsp;» doit retourner le nombre de fois qu'elle a été appelée, toutes instances confondues. Votre code doit inclure une méthode «&nbsp;main&nbsp;» qui démontre que le code répond bien à la question. Vous devez par ailleurs expliquer (en prose française) votre solution. Si votre explication est manquante ou peu claire, une note de zéro pourra être attribuée.</li>
<li>Décrivez l’utilisation de la classe RandomAccessFile pour manipuler un fichier à adressage relatif. Donnez-un exemple de code.</li>
</ol>


<p>Dans tous les cas, vous devez expliquer vos solutions et produire du code valable.</p>
<p>Vous devriez arrivez sans mal à produire les solutions attendues en moins de 3 heures. Si vous n'y arrivez pas, c'est que vous manquez de pratique.</p>

## Pour se pratiquer à programmer

<p>Si vous avez fait toutes les lectures, les examens factices et tous les exercices du cours honnêtement, alors vous êtes prêt pour les examens. Certains étudiants souhaitent se pratiquer davantage. </p>

<p>Voici quelques suggestions de problèmes supplémentaires pour réviser:</p>
<ol>
<li>Écrivez un programme qui lit un fichier contenant un mot par ligne et qui affiche les mots en question dans le sens inverse (en commençant par le dernier mot).</li>
<li>Écrivez un programme qui calcule la somme des 100 premiers entiers divisibles par 3.</li>
<li>Écrivez une fonction qui trouve dans une liste la valeur de tous les éléments répétés (par exemple dans 1,2,2,3,4, le nombre 2 est répété).</li>
<li>Expliquez la différence entre une variable (attribute) statique (static) et une variable normale.</li>
<li>Est-ce qu'une classe peut avoir plus d'un constructeur?</li>
<li>Étant donné deux variables entières, i et j, je peux toujours calculer i/j? (vrai ou faux, expliquez)</li>
<li>Combien de bits utilise le type double en Java?</li>

</ol>

<p>N'oubliez pas de <strong>tester vos solutions</strong> pendant vos révisions. S'il s'agit de produire du code Java, alors exécutez le code Java et passez du temps avec le programme pour vous assurez qu'il fait ce qu'il doit faire. C'est une erreur commune chez les étudiants d'aller trop rapidement et de supposer que parce que le programme a l'air correct, il doit être correct. Non! Testez et testez encore. Vous ne pourrez pas tester votre code pendant l'examen : c'est pendant vos révisions qu'il faut acquérir ce réflexe de vérification.</p>

<p><a href="https://projecteuler.net/archives">Le projet Euler offre des centaines de problèmes</a> similaires à ceux qui sont utilisés dans le cours.</p>

<p>Certains étudiants apprécient <a href="https://www.jetbrains.com/academy/">JetBrains Academy</a> (en anglais) qui offre certaines formations élémentaires en Java. Il y a aussi plusieurs manuels (en anglais) dédiés aux exercices que vous pouvez acquérir :</p>
<ol>
<li><a href="https://www.amazon.ca/Java-Coding-Problems-Programming-real-world/dp/1789801419/">Java Coding Problems: Improve your Java Programming skills by solving real-world coding challenges</a></li>
<li><a href="https://www.amazon.ca/Java-Cookbook-Problems-Solutions-Developers/dp/1492072583/">Java Cookbook: Problems and Solutions for Java Developers</a> </li>
</ol>

## Les reports de la date de fin de cours

<p><strong>Rappel</strong>: L'enseignant ne peut modifier votre date de fin de cours  peu importe votre situation. Le moment après la date de fin de cours où votre dossier est fermé et où vous recevez (éventuellement) un incomplet est géré par l'Université. Il est de votre responsabilité de bien planifier votre temps.  Si vous avez des problèmes personnels qui limitent vos progrès (maladie, deuil, etc.), il faut voir avec l'Université: les enseignants n'ont aucune prise sur les dates de fin, sur les dates d'examen, etc.</p>


<p>Votre date de fin de cours est inscrite dans votre dossier et vous pouvez la trouver sur le portail étudiant et sur la documentation qu'on vous a remise lors de votre inscription. Il est possible que votre examen final ait lieu des semaines ou même des mois après votre date de fin de cours: cela ne constitue pas une extension de votre date de fin de cours.</p>

## Déroulement et le jour de l'examen

L'enseignant ne peut changer la date, la durée, le lieu ou l'heure de vos examens. Il ne contrôle pas l'environnement technologique lors des examens. Un service distinct et indépendant au sein de l'Université gère les examens et la télésurveillance.


### Pour les personnes inscrites aux trimestres d'automne 2025 et d'hiver 2026

Le déroulement des examens, incluant leur date et leur heure, est géré par l'Université. Il est inutile d'écrire à l'enseignant pour savoir quand vos examens auront lieu ou pour en changer la date. Si vous avez des questions au sujet de la plateforme technologique ou au sujet de l'heure d'un examen, il faut voir avec l'Université et au sein du portail étudiant. Par exemple, dans le portail étudiant, sous Dossier administratif, il est possible que vous trouviez une option pour modifier une date d’examen.


### Plate-forme d'examen

-[Accédez à vos examens directement dans l'environnement Moodle](https://m2.teluq.ca/mod/quiz/view.php?id=172628). Vous y trouverez davantage d'information. Les examens sont gérés par l'Université. Il est inutile de joindre la personne qui vous encadre à ce sujet avec vos questions, il faut joindre l'Université.

## Résultat et rétroaction sur les examens

<p>Une fois un examen corrigé, vous trouverez votre note dans le portail étudiant. L'enseignant ne transmet jamais les examens (corrigés ou pas) par courriel. Si vous avez des questions suite à un examen, nous nous ferons un plaisir d'en discuter avec vous. Nous ne transmettons toutefois jamais le corrigé d'un examen (à quiconque, et il n'y a pas d'exception).</p>

{{% hint danger %}}


Les deux examens sont obligatoires et il n'y a aucune possibilité de reprise. Il est de votre responsabilité de vous assurer de vous présenter aux deux examens.

{{% /hint  %}}

## Rétroaction sur le cours

N'oubliez pas que nous tenons compte de votre opinion. Si vous avez des critiques
constructives, [remplissez le formulaire à cet effet]({{< relref "docs/erreurs.md" >}}).



## Vous avez aimé le cours ?

Si vous avez aimé le cours...

- Parlez du cours autour de vous, laissez des remarques positives en ligne.
- [Consultez la page professeur](https://www.teluq.ca/siteweb/univ/dlemire.html) et les autres cours qu'il a conçus.
- Si vous avez un compte sur GitHub, [suivez-y le professeur](https://github.com/lemire). (Bouton  *follow*.)
- Si vous lisez l'anglais, [abonnez-vous au blog du professeur](https://lemire.me/blog/).
- Vous pouvez suivre le professeur sur [X](https://x.com/lemire).
- [Laissez une évaluation positive sur la page du manuel chez Amazon](https://www.amazon.ca/Java-pas-Introduction-programmation-langage/dp/B0CR7RW87Y/).
- [Consultez les autres livres écrits par le professeur](https://www.amazon.ca/stores/Daniel-Lemire/author/B0CR7YMZT2)




<div style="margin: 40px auto; padding: 30px; max-width: 680px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 16px; box-shadow: 0 10px 30px rgba(0,0,0,0.2); font-family: 'Segoe UI', Arial, sans-serif; color: white; text-align: center;">
  <p style="font-size: 18px; line-height: 1.6; margin: 0 0 24px 0; opacity: 0.95;">
    Si  vous avez acheté le manuel sur Amazon, et que le manuel vous a été utile, si une explication vous a fait gagner du temps ou si un exercice vous a enfin fait comprendre un concept difficile…
  </p>
  <p style="font-size: 20px; font-weight: 600; margin: 20px 0;">
    Votre avis compte énormément ❤️
  </p>
  <p style="font-size: 17px; line-height: 1.6; margin: 0 0 30px 0; opacity: 0.95;">
    Prendre 30 secondes pour laisser 5 étoiles et quelques mots gentils sur Amazon fait une différence énorme : 
    cela permet à d’autres étudiants de trouver plus facilement ce livre et me motive à continuer à créer du contenu de qualité.
  </p>
  <a href="https://www.amazon.ca/dp/B0CR7RW87Y/#customerReviews" 
     style="display: inline-block; background: #fff; color: #764ba2; font-size: 18px; font-weight: bold; padding: 14px 36px; border-radius: 50px; text-decoration: none; box-shadow: 0 6px 20px rgba(0,0,0,0.2); transition: all 0.3s;"
     onmouseover="this.style.background='#f0e6ff'; this.style.transform='translateY(-2px)'; this.style.boxShadow='0 8px 25px rgba(0,0,0,0.3)';"
     onmouseout="this.style.background='#fff'; this.style.transform='none'; this.style.boxShadow='0 6px 20px rgba(0,0,0,0.2)';">
    ⭐ Laisser un avis sur Amazon (30 secondes)
  </a>
  <p style="margin: 24px 0 0 0; font-size: 14px; opacity: 0.8;">
    Merci infiniment pour votre soutien !<br>
  </p>
</div>


## Vous voulez continuer votre apprentissage ?

Je vous recommande les cours suivants.

- Au sein du cours [INF 2007 Programmation avancée](https://www.teluq.ca/site/etudes/offre/cours/TELUQ/INF%202007/), vous approfondirez vos compétences en développement logiciel avec des concepts avancés comme les tests et l'optimisation des performances en utilisant le langage Go. Ce cours de programmation avancée est une suite naturelle au cours INF 1220. Plusieurs des mêmes notions y sont approfondies.
- Au sein du cours [INF 2020 Programmation d'applications avec Python : des jeux au Web](https://www.teluq.ca/site/etudes/offre/cours/TELUQ/INF%202020/), vous apprendrez à créer des applications dynamiques, allant des jeux interactifs aux interfaces web, en maîtrisant Python et ses bibliothèques. Ce cours est aussi une suite naturelle au cours INF 1220.
- Au sein du cours [INF 6450 Gestion de l'information avec XML](https://www.teluq.ca/site/etudes/offre/cours/TELUQ/INF%206450/), vous explorerez les techniques de structuration, de stockage et de transformation des données à l’aide du langage XML et de ses technologies associées. Ces techniques sont importantes pour développer des applications web.
- Au sein du cours [INF 6460 Recherche et filtrage d'informations](https://www.teluq.ca/site/etudes/offre/cours/TELUQ/INF%206460/), vous développerez des compétences pour concevoir et utiliser des systèmes de recherche et de filtrage d'informations, en exploitant des techniques avancées d'indexation et d'analyse de données. Vous y apprendrez comment fonctionnent les moteurs de recherche.
- Au sein du cours [INF 9004 Informatique des entrepôts de données](https://www.teluq.ca/site/etudes/offre/cours/teluq/inf%209004), vous développerez des compétences en conception, gestion et analyse d’entrepôts de données pour soutenir la prise de décision stratégique. Vous y apprendrez à faire des requêtes sophistiquées au sein de bases de données avec des langages comme MDX et le SQL.


### INF 2007

{{< youtube id="Of7vbY4eAGI" >}}

### INF 2020

{{< youtube id="F6fI-1dtxxw" >}}

### INF 6450

{{< youtube id="VpxyCuuTInA" >}}

[Le contenu du cours INF 6450 est en accès libre](https://lemire.github.io/inf6450-hugo/). Il s'agit d'une
excellente suite au cours INF 1220.

### INF 6460

{{< youtube id="xh_l-2qhe48" >}}

### INF 9004

{{< youtube id="Qq3W6OUfrc0" >}}
