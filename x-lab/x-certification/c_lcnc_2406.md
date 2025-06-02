# 🌸 [C_LCNC_2406](https://www.pass4success.com/sap/exam/c-lcnc-2406)

## 💮 01 - In SAP Build Apps, besides the Variable tab where can you find an overview of created variables?

_Choose the correct answer._

- [ ] Formula Editor

- [ ] Tree View

- [ ] Data Tab

<details>
  <summary>Solution</summary>

- [ ] Formula Editor

- [x] Tree View

- [ ] 🍧 Data Tab

---

Explication :

Dans SAP Build Apps, l'onglet Data (ou "Données") permet de gérer les ressources de données et les variables associées. Il offre une vue d'ensemble des variables de données créées, notamment celles liées aux entités de données externes, telles que les services OData ou les API REST. Cela permet aux développeurs de configurer et de visualiser les variables de données en relation avec les ressources de données définies dans l'application. [SAP Learning](https://learning.sap.com/learning-journeys/develop-apps-with-sap-build-apps-using-drag-and-drop-simplicity/creating-data-variables-_de170999-0ac9-4277-b1bd-cdcdac1e0fc7?utm_source=chatgpt.com)

- Formula Editor : Cet éditeur est principalement utilisé pour écrire des formules et manipuler des données, mais il ne fournit pas une vue d'ensemble des variables créées. [SAP Learning](https://learning.sap.com/learning-journeys/develop-apps-with-sap-build-apps-using-drag-and-drop-simplicity/using-formula-functions-_b565fa9d-c2c4-4061-b40d-07febf1436b3?utm_source=chatgpt.com)
- Tree View : La vue en arborescence affiche la hiérarchie des composants de l'interface utilisateur, mais elle ne présente pas une liste exhaustive des variables définies dans l'application.

Conclusion :

Pour obtenir une vue d'ensemble des variables créées dans SAP Build Apps, en plus de l'onglet Variables, l'onglet Data est l'endroit approprié. Il permet de gérer et de visualiser les variables de données associées aux ressources de données de l'application.

---

</details>

## 💮 02 - In SAP Build Apps, besides data and variables, what else can you use to bind variables and data to components?

_Choose the correct answer._

- [ ] JavaScript

- [ ] Trigger Event

- [ ] Formula

<details>
  <summary>Solution</summary>

- [ ] JavaScript

- [ ] Trigger Event

- [x] 🍧 Formula

---

Explication :

Dans SAP Build Apps, les formules sont un mécanisme essentiel pour lier dynamiquement des données et des variables aux composants de l'interface utilisateur. Elles permettent de manipuler, transformer et formater les données avant leur affichage, sans recourir à du code personnalisé. [SAP Community](https://community.sap.com/t5/sap-builders-discussions/sap-build-challenge-week-1-formulas/m-p/257326?utm_source=chatgpt.com)

Par exemple, vous pouvez utiliser des formules pour :

- Afficher une valeur conditionnelle dans un champ texte.
- Formater des dates ou des nombres selon les besoins de l'application.
- Filtrer des listes ou des tableaux de données.
- Combiner plusieurs variables ou champs de données en une seule sortie.

Le Formula Editor de SAP Build Apps offre une interface conviviale pour créer ces formules, avec une bibliothèque de fonctions prédéfinies couvrant des opérations sur les textes, les nombres, les dates, etc. Cela permet aux développeurs de concevoir des applications interactives et réactives sans écrire de code complexe.

Pourquoi les autres options ne sont pas correctes :

- JavaScript : SAP Build Apps est une plateforme low-code/no-code qui n'utilise pas JavaScript pour la liaison directe des données aux composants. Toute la logique est gérée via des formules et des fonctions prédéfinies.
- Trigger Event : Les événements déclencheurs (Trigger Events) sont utilisés pour gérer la logique de l'application, comme les actions suite à un clic sur un bouton. Cependant, ils ne sont pas utilisés pour lier directement des données ou des variables aux composants.

Conclusion :

Pour lier des variables et des données aux composants dans SAP Build Apps, en plus des données et variables standard, l'utilisation de formules est la méthode appropriée. Elles offrent une flexibilité et une puissance considérables pour créer des applications dynamiques et interactives.

---

</details>

## 💮 03 - In SAP Build Apps, what are some classic data entities available?

_There are 2 correct answers to this question._

- [ ] OData Integration

- [ ] RFC Integration

- [ ] REST API Direct Integration

- [ ] SOAP Integration

<details>
  <summary>Solution</summary>

- [x] 🍧 OData Integration

- [ ] RFC Integration

- [ ] REST API Direct Integration

- [x] 🍧 SOAP Integration

---

Explication :

Dans SAP Build Apps, les entités de données classiques disponibles pour l'intégration sont :

- OData Integration : SAP Build Apps prend en charge l'intégration avec des services OData, permettant de connecter des entités de données telles que les clients, produits, etc. [SAP Learning](https://learning.sap.com/learning-journeys/develop-apps-with-sap-build-apps-using-drag-and-drop-simplicity/using-odata-resources_ea7d8938-0ccb-4696-9780-9ac6aac88795?utm_source=chatgpt.com)
- REST API Direct Integration : Il est également possible d'intégrer directement des API REST, offrant une flexibilité pour se connecter à divers services web.

Pourquoi les autres options ne sont pas correctes :

- RFC Integration : Bien que SAP propose des mécanismes pour exposer des modules de fonction RFC via des proxys REST sur SAP BTP, cette intégration n'est pas directement disponible dans SAP Build Apps sans configurations supplémentaires. [SAP Community](https://community.sap.com/t5/enterprise-resource-planning-blogs-by-sap/sap-build-apps-and-bapis-rfc-meets-web/ba-p/13555549?utm_source=chatgpt.com)
- SOAP Integration : SAP Build Apps ne prend pas en charge directement l'intégration avec des services SOAP.

Conclusion :

Les entités de données classiques disponibles dans SAP Build Apps incluent l'intégration avec des services OData et des API REST directes. Les intégrations RFC et SOAP nécessitent des configurations supplémentaires et ne sont pas prises en charge nativement.

---

</details>

## 💮 04 - You want to use a variable value in multiple pages in an SAP Build Apps application. Which variable type can you use?

_Choose the correct answer._

- [ ] Translation

- [ ] Page

- [ ] Sensor

- [ ] App

<details>
  <summary>Solution</summary>

- [ ] Translation

- [ ] Page

- [ ] Sensor

- [x] 🍧 App

---

Explication :

Dans SAP Build Apps, les App Variables sont conçues pour stocker des informations accessibles sur l'ensemble de l'application, c'est-à-dire sur toutes les pages. Elles sont utiles pour conserver des données globales telles que les préférences utilisateur, les informations d'authentification ou tout autre état qui doit être partagé entre plusieurs pages.

En revanche :

- Page Variables : Ces variables sont limitées à la page sur laquelle elles sont définies. Elles ne sont pas accessibles depuis d'autres pages.
- Sensor Variables : Elles capturent des données provenant des capteurs de l'appareil (comme le GPS ou l'accéléromètre) et ne sont pas destinées à être utilisées comme variables globales.
- Translation Variables : Ces variables sont utilisées pour la gestion des traductions et ne servent pas à stocker des données dynamiques partagées entre les pages.

Conclusion :

Pour partager une valeur de variable entre plusieurs pages dans une application SAP Build Apps, il est recommandé d'utiliser une App Variable. Cela garantit que la donnée est accessible et cohérente sur l'ensemble de l'application.

---

</details>

## 💮 05 - Which of the following can you do in the Launch tab of SAP Build Apps?

_There are 2 correct answers to this question._

- [ ] Debug apps

- [ ] Preview apps

- [ ] Build apps

- [ ] Configure destinations

<details>
  <summary>Solution</summary>

- [ ] Debug apps

- [x] 🍧 Preview apps

- [x] 🍧 Build apps

- [ ] Configure destinations

---

Explication :

Dans SAP Build Apps, le Launch tab est conçu pour faciliter les étapes finales du développement d'une application, notamment :

- Preview apps : Le Launch tab permet de prévisualiser votre application en temps réel, soit via le navigateur web, soit sur un appareil mobile en utilisant l'application SAP Build Apps Preview. Cette fonctionnalité est essentielle pour tester l'apparence et le comportement de l'application avant son déploiement.
- Build apps : À partir du Launch tab, vous pouvez accéder au service de build pour compiler votre application. Cela inclut la création de configurations de build, la génération de fichiers exécutables (par exemple, des fichiers MTAR pour le déploiement sur SAP BTP) et la gestion des versions de l'application.

Pourquoi les autres options ne sont pas correctes :

- Debug apps : Le Launch tab ne propose pas de fonctionnalités de débogage. Le débogage se fait généralement via d'autres outils ou en utilisant des consoles de journalisation intégrées pendant la phase de développement.
- Configure destinations : La configuration des destinations, telles que les connexions à des services OData ou REST, se fait dans l'onglet Data de SAP Build Apps, et non dans le Launch tab.

Conclusion :

Le Launch tab de SAP Build Apps est principalement utilisé pour prévisualiser et compiler des applications. Il ne sert pas au débogage ni à la configuration des destinations.

---

</details>

## 💮 06 - In SAP Build Apps, which of the following are part of the VARIABLES section of the Logic Canvas?

_There are 2 correct answers to this question._

- [ ] Set Backend Variable

- [ ] Set App Variable

- [ ] Set User Variable

- [ ] Set Page Variable

<details>
  <summary>Solution</summary>

- [ ] Set Backend Variable

- [x] 🍧 Set App Variable

- [ ] Set User Variable

- [x] 🍧 Set Page Variable

---

Explication :

Dans SAP Build Apps, la section VARIABLES du Logic Canvas permet de gérer différentes actions liées aux variables de l'application. Parmi les options disponibles, on trouve notamment :

- Set App Variable : Permet de définir ou de modifier la valeur d'une variable d'application (App Variable), qui est accessible globalement à travers toutes les pages de l'application.
- Set Page Variable : Permet de définir ou de modifier la valeur d'une variable de page (Page Variable), qui est spécifique à une seule page et n'est pas accessible depuis d'autres pages. [Medium](https://nibedita-3001.medium.com/developing-apps-with-sap-build-apps-part-3-8766d9014fb5?utm_source=chatgpt.com)

Ces actions sont essentielles pour gérer l'état et le comportement dynamique de l'application en fonction des interactions de l'utilisateur.

Pourquoi les autres options ne sont pas correctes :

- Set Backend Variable : Cette option n'existe pas dans la section VARIABLES du Logic Canvas. Les interactions avec le backend se font généralement via des Data Variables ou des intégrations spécifiques, mais il n'y a pas de fonction nommée "Set Backend Variable".
- Set User Variable : Il n'existe pas de type de variable spécifique appelé "User Variable" dans SAP Build Apps. Les informations utilisateur sont généralement stockées dans des App Variables ou récupérées via des services d'authentification et stockées dans des Data Variables.

Conclusion :

Dans la section VARIABLES du Logic Canvas de SAP Build Apps, les actions Set App Variable et Set Page Variable sont disponibles pour gérer respectivement les variables globales et locales de l'application. Les options "Set Backend Variable" et "Set User Variable" ne font pas partie de cette section.

---

</details>

## 💮 07 - In SAP Build Apps, which function in the Formula Editor returns the current date?

_Choose the correct answer._

- [ ] GET_DATETIME_COMPONENT

- [ ] FETCH_DATE

- [ ] GET_DATE

- [ ] NOW

<details>
  <summary>Solution</summary>

- [ ] GET_DATETIME_COMPONENT

- [ ] FETCH_DATE

- [ ] GET_DATE

- [x] 🍧 NOW

---

Explication :

Dans SAP Build Apps, la fonction NOW() du Formula Editor est utilisée pour obtenir la date et l'heure actuelles au moment de l'exécution. Cette fonction renvoie une valeur de type DateTime, représentant l'instant précis où elle est appelée. Elle est particulièrement utile pour :

- Afficher l'heure ou la date actuelle dans l'interface utilisateur.
- Effectuer des calculs de durée ou de délais. [SAP Support](https://userapps.support.sap.com/sap/support/knowledge/en/2817897?utm_source=chatgpt.com)
- Déclencher des actions basées sur le temps.

Par exemple, pour afficher la date et l'heure actuelles dans un composant texte, vous pouvez utiliser la formule suivante :

    FORMAT_DATETIME_LOCAL(NOW(), "YYYY-MM-DD HH:mm:ss")

Cette formule formatte la valeur renvoyée par NOW() selon le format spécifié.

Pourquoi les autres options ne sont pas correctes :

- GET_DATETIME_COMPONENT : Cette fonction est utilisée pour extraire des composants spécifiques (comme l'année, le mois ou le jour) d'une valeur DateTime existante, mais elle ne retourne pas la date actuelle.
- FETCH_DATE et GET_DATE : Ces fonctions ne sont pas reconnues dans le contexte du Formula Editor de SAP Build Apps et ne sont pas documentées comme des fonctions valides pour obtenir la date actuelle.

Conclusion :

Pour obtenir la date et l'heure actuelles dans SAP Build Apps, la fonction appropriée à utiliser dans le Formula Editor est NOW(). Elle fournit une valeur DateTime correspondant au moment précis de son appel.

---

</details>

## 💮 08 - In SAP Build Apps, which target platforms can you select when you build applications?

_There are 3 correct answers to this question._

- [ ] Web App

- [ ] IOS Mobile/Tablet

- [ ] Windows

- [ ] MacOS

- [ ] Android Mobile/Tablet

<details>
  <summary>Solution</summary>

- [x] 🍧 Web App

- [x] 🍧 IOS Mobile/Tablet

- [ ] Windows

- [ ] MacOS

- [x] 🍧 Android Mobile/Tablet

---

Explication :

SAP Build Apps permet de développer des applications destinées aux plateformes suivantes :

- Web App : Les applications peuvent être déployées en tant qu'applications web accessibles via un navigateur.
- iOS Mobile/Tablet : Il est possible de créer des applications natives pour les appareils iOS, comme les iPhones et iPads.
- Android Mobile/Tablet : Les applications peuvent également être développées pour les appareils Android, y compris les smartphones et tablettes.

Pourquoi les autres options ne sont pas correctes :

- Windows : SAP Build Apps ne prend pas en charge la création directe d'applications natives pour Windows.
- MacOS : De même, la création d'applications natives pour MacOS n'est pas prise en charge directement par SAP Build Apps.

Conclusion :

SAP Build Apps permet de cibler les plateformes suivantes lors de la construction d'applications : Web App, iOS Mobile/Tablet et Android Mobile/Tablet. Les plateformes Windows et MacOS ne sont pas prises en charge pour la création directe d'applications natives.

---

</details>

## 💮 09 - Which of the following components are available in the Logic Canvas of SAP Build Apps?

_There are 2 correct answers to this question._

- [ ] Input Field

- [ ] Card

- [ ] Confirm

- [ ] Show spinner

<details>
  <summary>Solution</summary>

- [ ] Input Field

- [ ] Card

- [x] 🍧 Confirm

- [x] 🍧 Show spinner

---

Explication :

Dans SAP Build Apps, le Logic Canvas est l'espace où vous construisez la logique de votre application en utilisant des fonctions de flux (flow functions). Ces fonctions permettent de définir le comportement de l'application en réponse à des événements.

Parmi les composants mentionnés :

- Confirm : Il s'agit d'une fonction de flux disponible dans le Logic Canvas. Elle permet d'afficher une boîte de dialogue de confirmation à l'utilisateur, généralement utilisée pour valider une action avant de la poursuivre.
- Show spinner : Cette fonction de flux est utilisée pour afficher un indicateur de chargement (spinner) pendant l'exécution d'une opération, comme le chargement de données. Elle améliore l'expérience utilisateur en signalant que l'application est en cours de traitement.

En revanche :

- Input Field : C'est un composant d'interface utilisateur (UI) utilisé pour saisir des données. Il est placé sur la toile de conception (UI Canvas) et non dans le Logic Canvas.
- Card : Également un composant UI, il est utilisé pour regrouper des informations de manière visuelle. Il ne fait pas partie des fonctions de flux du Logic Canvas.

Conclusion :

Dans le Logic Canvas de SAP Build Apps, les fonctions de flux Confirm et Show spinner sont disponibles pour gérer la logique de l'application. Les composants Input Field et Card sont des éléments d'interface utilisateur et ne sont pas utilisés dans le Logic Canvas.

---

</details>

## 💮 10 - While creating the collection of data records for a Data variable in SAP Build Apps, which of the following are available?

_There are 2 correct answers to this question._

- [ ] Annotation extensions

- [ ] Paging

- [ ] User access permissions

- [ ] Filter condition

<details>
  <summary>Solution</summary>

- [ ] Annotation extensions

- [x] 🍧 Paging

- [ ] User access permissions

- [x] 🍧 Filter condition

---

Explication :

Lors de la création d'une collection d'enregistrements de données pour une variable de données (Data variable) dans SAP Build Apps, vous pouvez configurer les propriétés suivantes :

- Paging (Pagination) : Cette fonctionnalité permet de diviser les données en pages, facilitant ainsi la gestion de grandes quantités d'enregistrements. Vous pouvez définir la taille de la page, le numéro de la page et inclure le nombre total d'enregistrements pour une navigation efficace.
- Filter condition (Condition de filtrage) : Cette propriété vous permet de spécifier des critères pour extraire uniquement les enregistrements qui répondent à certaines conditions. Par exemple, vous pouvez filtrer les enregistrements en fonction de valeurs spécifiques dans certains champs.

Ces deux options sont essentielles pour gérer et afficher efficacement les données dans vos applications SAP Build Apps, en particulier lorsque vous travaillez avec de grandes quantités d'informations.

Pourquoi les autres options ne sont pas correctes :

- Annotation extensions : Bien que les annotations puissent être utilisées pour enrichir les métadonnées des services OData, elles ne sont pas directement liées à la création d'une collection d'enregistrements de données dans SAP Build Apps.
- User access permissions : La gestion des autorisations d'accès des utilisateurs est généralement configurée au niveau du backend ou du service, et non lors de la création d'une collection de données dans SAP Build Apps.

Conclusion :

Lors de la création d'une collection d'enregistrements de données pour une variable de données dans SAP Build Apps, les propriétés Paging et Filter condition sont disponibles pour gérer efficacement les données. Les options Annotation extensions et User access permissions ne sont pas directement liées à cette tâche.

---

</details>

## 💮 11 - In SAP Build Apps, which of the following are layout components?

_There are 3 correct answers to this question._

- [ ] List Divider

- [ ] Dropdown

- [ ] Container

- [ ] Scroll View

- [ ] Row

<details>
  <summary>Solution</summary>

- [ ] List Divider

- [ ] Dropdown

- [x] 🍧 Container

- [x] 🍧 Scroll View

- [x] 🍧 Row

---

Explication :

Dans SAP Build Apps, les layout components sont des éléments utilisés pour organiser et structurer l'interface utilisateur (UI) de manière logique et cohérente. Ils permettent de contrôler l'agencement des autres composants sur la page.

- Container : Un conteneur est un composant de mise en page fondamental qui permet de regrouper d'autres composants. Il facilite la gestion de la disposition, de l'alignement et de la visibilité des éléments qu'il contient.
- Scroll View : La vue défilante est un conteneur qui permet d'afficher du contenu pouvant dépasser la taille de l'écran, en offrant une barre de défilement pour naviguer à travers ce contenu. Elle est utile pour afficher des listes longues ou des informations supplémentaires sans encombrer l'écran principal.
- Row : La ligne est un composant de mise en page qui organise les éléments horizontalement. Elle est souvent utilisée pour créer des grilles ou des alignements côte à côte, facilitant ainsi une présentation claire et structurée des informations.

Pourquoi les autres options ne sont pas correctes :

- List Divider : Bien que le séparateur de liste soit utilisé pour diviser visuellement les éléments d'une liste, il n'est pas classé comme un composant de mise en page. Il sert principalement à améliorer la lisibilité et l'organisation des données au sein d'une liste.
- Dropdown : Le menu déroulant est un composant interactif permettant à l'utilisateur de sélectionner une option parmi une liste. Il est classé comme un composant de formulaire ou d'entrée, et non comme un composant de mise en page.

Conclusion :

Les composants Container, Scroll View et Row sont des éléments essentiels pour structurer l'interface utilisateur dans SAP Build Apps. Ils permettent de créer des mises en page flexibles et organisées, améliorant ainsi l'expérience utilisateur de l'application.

---

</details>

## 💮 12 - In SAP Build Apps, in which of the following cases does the IS_EMPTY function return true?

_There are 3 correct answers to this question._

- [ ] IS_EMPTY(NAN)

- [ ] IS_EMPTY(0)

- [ ] IS_EMPTY('a')

- [ ] IS_EMPTY('')

- [ ] IS_EMPTY([])

<details>
  <summary>Solution</summary>

- [x] IS_EMPTY(NAN)

- [ ] IS_EMPTY(0)

- [ ] IS_EMPTY('a')

- [x] 🍧 IS_EMPTY('')

- [x] 🍧 IS_EMPTY([])

- [ ] 🍧 IS_EMPTY({})\*

---

Explication :

La fonction IS_EMPTY dans SAP Build Apps est utilisée pour vérifier si une valeur est considérée comme vide. Elle retourne true si l'élément est vide selon les critères suivants :

- Chaîne de caractères vide : Une chaîne de caractères sans contenu ("") est considérée comme vide.
- Liste vide : Une liste sans éléments ([]) est également considérée comme vide, tout comme pour un objet ({}).

En revanche, les autres valeurs ne sont pas considérées comme vides :

- 0 : Le nombre zéro n'est pas vide.
- 'a' : Une chaîne contenant un caractère est non vide.
- NAN : Bien que NAN (Not-a-Number) soit une valeur spéciale en JavaScript, elle n'est pas traitée comme vide dans SAP Build Apps.

Conclusion :

La fonction IS_EMPTY retourne true uniquement pour les valeurs qui sont explicitement vides, telles qu'une chaîne vide ou une liste vide. Les autres valeurs, même si elles peuvent sembler "nulles" ou "indéfinies", ne sont pas considérées comme vides par cette fonction.

---

</details>

## 💮 13 - In SAP Build Apps, where can you configure the visibility of components?

_Choose the correct answer._

- [ ] Properties tab

- [ ] Data tab

- [ ] Style tab

- [ ] Layout tab

<details>
  <summary>Solution</summary>

- [x] 🍧 Properties tab

- [ ] Data tab

- [ ] Style tab

- [ ] Layout tab

---

Explication :

Dans SAP Build Apps, la visibilité des composants peut être configurée dans l'onglet Propriétés (Properties tab). Cet onglet permet de définir diverses propriétés des composants, y compris leur visibilité. La propriété Visible peut être utilisée pour contrôler dynamiquement l'affichage d'un composant, en la liant à des variables ou des formules. Cela permet de créer des interfaces utilisateur réactives et adaptatives. [SAP Learning](https://learning.sap.com/learning-journeys/develop-apps-with-sap-build-apps-using-drag-and-drop-simplicity/using-properties_b8b8a508-77a7-4db8-b379-fb3435a0565b?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas correctes :

- Onglet Données (Data tab) : Cet onglet est utilisé pour gérer les variables de données et les intégrations, mais il ne permet pas de configurer directement la visibilité des composants.
- Onglet Style (Style tab) : L'onglet Style est destiné à la personnalisation de l'apparence des composants, tels que les couleurs, les polices et les espacements. Il ne permet pas de contrôler la visibilité des composants.
- Onglet Mise en page (Layout tab) : Cet onglet est utilisé pour organiser les composants sur la page, en définissant leur alignement, leur espacement et leur positionnement. Il ne permet pas de configurer la visibilité des composants.

Conclusion :

Pour configurer la visibilité des composants dans SAP Build Apps, vous devez utiliser l'onglet Propriétés (Properties tab). Cela vous permettra de lier la propriété Visible à des variables ou des formules, offrant ainsi une flexibilité maximale pour adapter l'interface utilisateur aux besoins de votre application.

---

</details>

## 💮 14 - In SAP Build Apps, which function returns the number of items in a list?

_Choose the correct answer._

- [ ] COUNT

- [ ] LENGTH

- [ ] MAX

- [ ] SUM

<details>
  <summary>Solution</summary>

- [ ] 🍧 COUNT

- [x] LENGTH

- [ ] MAX

- [ ] SUM

---

Explication :

Dans SAP Build Apps, la fonction COUNT() est utilisée pour compter le nombre d'éléments dans une liste ou un tableau. Par exemple, si vous avez une liste ["a", "b", "c"], la fonction COUNT(["a", "b", "c"]) retournera 3.

Pourquoi les autres options ne sont pas correctes :

- LENGTH() : Cette fonction retourne le nombre de caractères dans une chaîne de texte, pas le nombre d'éléments dans une liste.
- MAX() : Cette fonction retourne la valeur maximale d'une liste de nombres, pas le nombre d'éléments.
- SUM() : Cette fonction retourne la somme des valeurs d'une liste de nombres, pas le nombre d'éléments.

Conclusion :

Pour obtenir le nombre d'éléments dans une liste dans SAP Build Apps, vous devez utiliser la fonction COUNT().

---

</details>

## 💮 15 - In SAP Build Apps, which of the following can you set in the THEME tab?

_There are 2 correct answers to this question._

- [ ] Fonts

- [ ] Visual Cloud Functions

- [ ] UI Component Catalog

- [ ] Colors

<details>
  <summary>Solution</summary>

- [x] 🍧 Fonts

- [ ] Visual Cloud Functions

- [ ] UI Component Catalog

- [x] 🍧 Colors

---

Explication :

Dans SAP Build Apps, l'onglet THEME permet de personnaliser l'apparence de votre application en définissant des styles globaux. Vous pouvez y configurer :

- Les polices (Fonts) : Vous pouvez choisir les polices utilisées dans l'application, en vous appuyant sur les polices par défaut ou en intégrant des polices personnalisées via le gestionnaire de thèmes. [SAP](https://developers.sap.com/tutorials/create-custom-theme.html?utm_source=chatgpt.com)
- Les couleurs (Colors) : Vous pouvez définir des couleurs principales, secondaires et de fond, ainsi que des couleurs spécifiques pour les éléments de l'interface utilisateur, afin d'assurer la cohérence avec l'identité visuelle de votre entreprise.

Pourquoi les autres options ne sont pas correctes :

- Visual Cloud Functions : Les fonctions cloud visuelles sont créées et gérées dans l'onglet Functions de SAP Build Apps, et non dans l'onglet THEME.
- UI Component Catalog : Le catalogue de composants d'interface utilisateur est accessible via la bibliothèque de composants dans l'éditeur d'applications, mais il ne fait pas partie de l'onglet THEME. [SAP Learning](https://learning.sap.com/learning-journeys/extending-sap-sales-cloud-and-sap-service-cloud-version-2-using-sap-build-apps/designing-the-extension-app-s-user-interface-in-sap-build-apps?utm_source=chatgpt.com)

Conclusion :

L'onglet THEME dans SAP Build Apps vous permet de personnaliser les polices et les couleurs de votre application pour l'adapter à l'identité visuelle de votre entreprise. Les autres options mentionnées sont gérées dans des onglets différents.

---

</details>

## 💮 16 - Which of the following sections are available in the SAP Build Apps Marketplace?

_There are 3 correct answers to this question._

- [ ] Data

- [ ] View components

- [ ] Integration

- [ ] Security

- [ ] Flow functions

<details>
  <summary>Solution</summary>

- [x] Data

- [x] 🍧 View components

- [x] 🍧 Integration

- [ ] Security

- [ ] 🍧 Flow functions

---

Explication :

Dans SAP Build Apps, le Marketplace offre une variété de composants et de fonctionnalités pour enrichir vos applications. Parmi les sections disponibles, on retrouve :

- Composants de vue (View components) : Ces composants sont utilisés pour construire l'interface utilisateur de l'application. [SAP Learning](https://learning.sap.com/learning-journeys/compose-and-automate-with-sap-build-the-no-code-way/taking-a-tour-of-sap-build-apps?utm_source=chatgpt.com)
- Fonctions de flux (Flow functions) : Elles permettent de définir la logique de l'application, comme la navigation entre les pages ou la manipulation des données.
- Intégration (Integration) : Cette section facilite la connexion de l'application à des systèmes externes, tels que SAP S/4HANA ou des API REST. [SAP](https://learning.sap.com/learning-journeys/compose-and-automate-with-sap-build-the-no-code-way/taking-a-tour-of-sap-build-apps?utm_source=chatgpt.com)

Ces sections sont accessibles via l'onglet Marketplace dans la bibliothèque de composants, où vous pouvez explorer, installer et gérer les éléments nécessaires à votre application.

Conclusion

Par conséquent, les trois sections disponibles dans le Marketplace de SAP Build Apps sont :

- Composants de vue (View components)
- Fonctions de flux (Flow functions)
- Intégration (Integration)

Les sections Données (Data) et Sécurité (Security) ne font pas partie du Marketplace.

---

</details>

## 💮 17 - In SAP Build Apps, the data type 'Color' is part of which data type group?

_Choose the correct answer._

- [ ] Text Types with Specific Format

- [ ] Simple types

- [ ] Reference types

- [ ] Complex types

<details>
  <summary>Solution</summary>

- [x] 🍧 Text Types with Specific Format

- [ ] Simple types

- [ ] Reference types

- [ ] Complex types

---

Explication :

Dans SAP Build Apps, les types de données sont classés en quatre groupes principaux :
GitHub

- Simple Types : Types de données de base tels que les nombres, les booléens et les chaînes de caractères.
- Text Types with Specific Format : Types de données représentant des chaînes de caractères avec un format spécifique, comme les adresses e-mail, les dates/horaires, les URL, les codes de couleur, etc.
- Reference Types : Types de données faisant référence à des objets ou des entités, comme les icônes.
- Complex Types : Types de données composés, tels que les objets et les listes.

Le type de données Color est classé sous le groupe Text Types with Specific Format, car il représente une chaîne de caractères formatée spécifiquement pour les codes de couleur (par exemple, #RRGGBB).

Conclusion :

Le type de données Color dans SAP Build Apps appartient au groupe Text Types with Specific Format, car il s'agit d'une chaîne de caractères formatée spécifiquement pour représenter des couleurs.

---

</details>

## 💮 18 - Which function call returns true?

_Choose the correct answer._

- [ ] IS_EMAIL(@sap.com)

- [ ] IS_EMAIL('@sap.com')

- [ ] IS_EMAIL('test@sap.com')

- [ ] IS_EMAIL(test@sap.com)

<details>
  <summary>Solution</summary>

- [ ] IS_EMAIL(@sap.com)

- [ ] IS_EMAIL('@sap.com')

- [x] 🍧 IS_EMAIL('test@sap.com')

- [ ] IS_EMAIL(test@sap.com)

---

Explication :

La fonction IS_EMAIL dans SAP Build Apps est utilisée pour vérifier si une chaîne de caractères correspond au format d'une adresse e-mail valide. Elle retourne true si l'adresse e-mail est valide, sinon elle retourne false.

Analyse des options :

- IS_EMAIL(@sap.com) : Cette syntaxe est incorrecte car l'adresse e-mail doit être une chaîne de caractères complète, y compris le nom d'utilisateur.
- IS_EMAIL('@sap.com') : Bien que cette syntaxe soit correcte, l'adresse e-mail est incomplète, car elle manque du nom d'utilisateur avant le symbole @.
- IS_EMAIL('test@sap.com') : Cette syntaxe est correcte et l'adresse e-mail est complète et valide, donc la fonction retourne true.
- IS_EMAIL(test@sap.com) : Cette syntaxe est incorrecte car l'adresse e-mail n'est pas entre guillemets, ce qui la rend invalide en tant que chaîne de caractères.

Conclusion :

La seule fonction qui retourne true est IS_EMAIL('test@sap.com'), car elle respecte la syntaxe correcte et l'adresse e-mail est valide.

---

</details>

## 💮 19 - Which mechanism is used to expose SAP Build Work Zone to an external system?

_Choose the correct answer._

- [ ] Gather and Track

- [ ] Connect and Extend

- [ ] Create and Read

- [ ] Push and Pull

<details>
  <summary>Solution</summary>

- [ ] Gather and Track

- [x] 🍧 Connect and Extend

- [ ] Create and Read

- [ ] Push and Pull

---

Explication :

Dans SAP Build Work Zone, le mécanisme Connect and Extend permet d'exposer le contenu de la plateforme à des systèmes externes. Cela inclut l'intégration d'applications SAP et non SAP, l'exposition de données via des API et des webhooks, ainsi que l'intégration de services tiers tels que Microsoft Teams ou SharePoint Online.

Pourquoi les autres options ne sont pas correctes :

- Gather and Track : Ce mécanisme est davantage axé sur la collecte et le suivi des données au sein de SAP Build Work Zone, et non sur l'exposition de la plateforme à des systèmes externes.
- Create and Read : Bien que la création et la lecture de données soient des opérations courantes dans SAP Build Work Zone, elles ne constituent pas un mécanisme spécifique pour exposer la plateforme à des systèmes externes.
- Push and Pull : Ces termes décrivent des méthodes de communication entre systèmes, mais ne désignent pas un mécanisme spécifique dans SAP Build Work Zone pour exposer la plateforme à des systèmes externes.

Conclusion :

Le mécanisme Connect and Extend est la méthode appropriée pour exposer SAP Build Work Zone à des systèmes externes, facilitant ainsi l'intégration et l'interopérabilité avec d'autres applications et services.

---

</details>

## 💮 20 - Which pre-defined section of the site menu is used to automatically surface the information from the content manager?

_Choose the correct answer._

- [ ] Tools

- [ ] Applications

- [ ] Home

- [ ] Workspaces

<details>
  <summary>Solution</summary>

- [ ] Tools

- [ ] 🍧 Applications

- [ ] Home

- [x] Workspaces

---

Explication :

Dans SAP Build Work Zone, la section Applications du menu du site est utilisée pour afficher automatiquement les applications configurées dans le Content Manager. Le Content Manager permet aux administrateurs de créer et de configurer des applications, de les organiser en groupes et de les assigner à des rôles spécifiques. Une fois configurées, ces applications apparaissent sous forme de tuiles dans la section Applications du menu du site, offrant ainsi aux utilisateurs un accès direct aux applications pertinentes en fonction de leurs rôles et permissions.

Pourquoi les autres options ne sont pas correctes :

- Tools : Cette section fournit un accès à divers outils et fonctionnalités, tels que la base de connaissances de l'entreprise, le calendrier, etc., mais elle n'est pas directement liée à l'affichage des applications configurées dans le Content Manager.
- Home : La section Home est généralement utilisée pour afficher des informations pertinentes pour tous les utilisateurs de l'entreprise, telles que des actualités, des annonces ou des liens vers des ressources importantes. Elle ne sert pas à afficher automatiquement les applications configurées dans le Content Manager.
- Workspaces : Cette section permet d'accéder à différents espaces de travail collaboratifs au sein de l'organisation. Bien que les applications puissent être intégrées dans ces espaces, la section Workspaces elle-même n'est pas utilisée pour afficher automatiquement les applications configurées dans le Content Manager.

Conclusion :

La section Applications du menu du site est la zone pré-définie utilisée pour afficher automatiquement les informations provenant du Content Manager, offrant ainsi aux utilisateurs un accès centralisé aux applications pertinentes selon leurs rôles et permissions.

---

</details>

## 💮 21 - Where can users share feed updates including photos, comments, and other status updates with other users?

_There are 2 correct answers to this question._

- [ ] Tools

- [ ] My Workspace

- [ ] Workspace

- [ ] Profile

<details>
  <summary>Solution</summary>

- [ ] Tools

- [x] 🍧 My Workspace

- [ ] Workspace

- [x] 🍧 Profile

---

Explication :

Dans SAP Build Work Zone, les utilisateurs peuvent partager des mises à jour de flux, y compris des photos, des commentaires et d'autres statuts, dans les sections suivantes :

- Workspace : Les espaces de travail (Workspaces) sont des environnements collaboratifs où les membres peuvent interagir, partager des informations et collaborer sur des projets. Les utilisateurs peuvent publier des mises à jour, partager des fichiers, des blogs, des vidéos et des photos, et interagir avec d'autres membres via le flux de travail de l'espace de travail. [SAP Learning](https://learning.sap.com/learning-journeys/compose-and-automate-with-sap-build-the-no-code-way/explaining-the-key-product-capabilities-of-sap-build-work-zone?utm_source=chatgpt.com)
- Profile : La section Profil affiche les activités et les mises à jour qui concernent directement l'utilisateur sur son mur de profil. Par exemple, l'utilisateur verra toutes les mises à jour de statut et le contenu publié par lui-même ou directement adressé à lui (@mentions). L'utilisateur peut également voir les mises à jour concernant les modifications de ses informations de profil. [testpdf.com](https://learning.sap.com/learning-journeys/compose-and-automate-with-sap-build-the-no-code-way/explaining-the-key-product-capabilities-of-sap-build-work-zone?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas correctes :

- Tools : La section Outils fournit un accès à divers outils et applications intégrés à SAP Build Work Zone, tels que SAP Build Process Automation, SAP Build Application Studio et SAP Analytics Cloud. Elle ne permet pas de partager des mises à jour de flux. [testpdf.com](https://www.testpdf.com/articles/updated-nov-2024-pass-c-wzadm-2404-exam-real-practice-test-questions-q38-q58/?utm_source=chatgpt.com)
- My Workspace : La section Mon Espace de travail est un tableau de bord personnel pour chaque utilisateur, offrant un emplacement centralisé pour gérer et accéder aux tâches, applications et contenus individuels. Les mises à jour partagées ici ne sont visibles que par l'utilisateur lui-même et ne sont pas partagées avec d'autres utilisateurs. [SAP Learning](https://learning.sap.com/learning-journeys/designing-sap-build-work-zone/working-with-workspaces?utm_source=chatgpt.com)

Conclusion :

Les utilisateurs peuvent partager des mises à jour de flux, y compris des photos, des commentaires et d'autres statuts, dans les sections Workspace et Profile de SAP Build Work Zone.

---

</details>

## 💮 22 - Home pages from which product are included in the site menu 'Home' section after migration?

_Choose the correct answer._

- [ ] SAP Enterprise Portal

- [ ] SAP Jam Collaboration

- [ ] SAP SuccessFactors

- [ ] SAP Cloud Portal Service

<details>
  <summary>Solution</summary>

- [x] SAP Enterprise Portal

- [ ] 🍧 SAP Jam Collaboration

- [ ] SAP SuccessFactors

- [ ] SAP Cloud Portal Service

---

Explication :

Lors de la migration vers SAP Build Work Zone, les pages d'accueil (ou "homepages") provenant de SAP Jam Collaboration sont automatiquement intégrées dans la section prédéfinie "Home" du menu du site. Ces pages, désormais appelées "workpages", conservent leur contenu et leur structure, offrant ainsi une transition fluide pour les utilisateurs habitués à SAP Jam. [SAP Learning](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/mastering-the-site-menu?utm_source=chatgpt.com)

Dans le module "Explaining APIs and Webhooks" du parcours d'apprentissage Implement and Administer SAP Build Work Zone, il est précisé que les APIs et les webhooks du Digital Workplace Service (DWS) sont utilisés pour intégrer des applications tierces avec SAP Build Work Zone. Ces interfaces permettent aux applications externes de créer, lire, mettre à jour ou supprimer du contenu tel que des publications de blog, des documents, des liens, des sondages et des commentaires au sein des espaces de travail. De plus, les webhooks permettent aux applications tierces de recevoir des notifications en temps réel sur des événements spécifiques se produisant dans SAP Build Work Zone. [SAP Learning](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/explaining-apis-and-webhooks?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas correctes :

- SAP Enterprise Portal : Bien que des intégrations soient possibles, les pages d'accueil de SAP Enterprise Portal ne sont pas automatiquement migrées vers la section "Home" de SAP Build Work Zone.
- SAP SuccessFactors : Les pages d'accueil de SAP SuccessFactors ne sont pas automatiquement incluses dans la section "Home" après migration.
- SAP Cloud Portal Service : Les pages d'accueil de SAP Cloud Portal Service ne sont pas automatiquement intégrées dans la section "Home" lors de la migration vers SAP Build Work Zone.

Conclusion :

Par conséquent, après migration, les pages d'accueil de SAP Jam Collaboration sont celles qui sont incluses dans la section "Home" du menu du site dans SAP Build Work Zone.

---

</details>

## 💮 23 - Which of the following do you use to integrate third-party apps with SAP Build Work Zone?

_Choose the correct answer._

- [ ] Digital Workplace Service (DWS) API

- [ ] SAP Build Apps Backend Configuration

- [ ] SAP BTP Cockpit

- [ ] SAP Integration Suite

<details>
  <summary>Solution</summary>

- [ ] 🍧 Digital Workplace Service (DWS) API

- [ ] SAP Build Apps Backend Configuration

- [ ] SAP BTP Cockpit

- [x] SAP Integration Suite

---

Explication :

Le Digital Workplace Service (DWS) est un composant essentiel de SAP Build Work Zone qui fournit des API OData et des webhooks permettant l'intégration avec des applications tierces. Ces interfaces permettent aux applications externes de : [dumpspedia.com](https://www.dumpspedia.com/sap-certified-associate-sap-build-work-zone-implementation-and-administration-dumps.html?utm_source=chatgpt.com)

- Créer, lire, mettre à jour et supprimer du contenu tel que des publications de blog, des documents, des liens, des sondages et des commentaires au sein des espaces de travail.
- Recevoir des notifications en temps réel via des webhooks pour des événements spécifiques se produisant dans SAP Build Work Zone.
- Effectuer des opérations techniques avancées, telles que la mise à jour en masse des espaces de travail en fonction de critères spécifiques.

Ces fonctionnalités permettent une intégration fluide et efficace des applications tierces avec SAP Build Work Zone, offrant ainsi une expérience utilisateur cohérente et enrichie.
Pourquoi les autres options ne sont pas correctes :

- SAP Build Apps Backend Configuration : Cette option concerne la configuration des variables backend dans SAP Build Apps, et non l'intégration d'applications tierces avec SAP Build Work Zone.
- SAP BTP Cockpit : Le cockpit SAP BTP est une interface de gestion pour les services et applications sur la plateforme SAP Business Technology Platform. Bien qu'il permette de configurer des destinations et des services, il ne fournit pas directement les API nécessaires à l'intégration d'applications tierces avec SAP Build Work Zone. [dumpspedia.com](https://www.dumpspedia.com/sap-certified-associate-sap-build-work-zone-implementation-and-administration-dumps.html?utm_source=chatgpt.com)
- SAP Integration Suite : Bien que SAP Integration Suite offre des capacités d'intégration étendues pour connecter divers systèmes et applications, l'intégration spécifique avec SAP Build Work Zone, notamment pour la gestion de contenu et les interactions utilisateur, est facilitée par les API et webhooks fournis par le Digital Workplace Service.

Conclusion :

Pour intégrer des applications tierces avec SAP Build Work Zone, l'utilisation des API et webhooks du Digital Workplace Service (DWS) est la méthode appropriée. Ces outils offrent des capacités d'intégration robustes et flexibles, permettant aux applications externes d'interagir efficacement avec le contenu et les fonctionnalités de SAP Build Work Zone.

---

</details>

## 💮 24 - Which extensibility option does SAP recommend you use for SAP Build Work Zone?

_Choose the correct answer._

- [ ] SAP Build Apps

- [ ] SAP Integration Suite

- [ ] UI Integration Cards

- [ ] Cloud Connector to on-premise systems

<details>
  <summary>Solution</summary>

- [ ] SAP Build Apps

- [ ] SAP Integration Suite

- [x] 🍧 UI Integration Cards

- [ ] Cloud Connector to on-premise systems

---

Explication :

SAP recommande l'utilisation des UI Integration Cards comme principale option d'extensibilité pour SAP Build Work Zone. Ces cartes permettent d'intégrer et d'afficher des informations provenant de systèmes SAP et tiers directement dans l'interface utilisateur, offrant ainsi une expérience utilisateur cohérente et intégrée. Elles sont conçues selon les principes de SAP Fiori et s'exécutent côté client, assurant une performance optimale.
[SAP Learning](https://learning.sap.com/courses/low-code-no-code/illustrating-extensibility-in-sap-build-work-zone?utm_source=chatgpt.com)
[SAP Learning](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/exploring-ui-integration-cards?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas les plus appropriées

- SAP Build Apps : Bien que cette plateforme permette de créer des applications personnalisées, elle est principalement utilisée pour le développement d'applications autonomes. Elle n'est pas spécifiquement conçue pour l'extensibilité directe de SAP Build Work Zone.
- SAP Integration Suite : Cette suite facilite l'intégration de divers systèmes et applications, mais elle ne fournit pas directement des composants d'interface utilisateur pour étendre SAP Build Work Zone.
- Cloud Connector to on-premise systems : Le Cloud Connector permet une communication sécurisée entre les solutions cloud de SAP et les systèmes on-premise. Cependant, il s'agit d'un outil d'infrastructure et ne fournit pas de mécanismes d'extensibilité de l'interface utilisateur pour SAP Build Work Zone.

Conclusion

Pour étendre efficacement SAP Build Work Zone, SAP recommande l'utilisation des UI Integration Cards. Elles offrent une méthode standardisée et efficace pour intégrer des contenus et des fonctionnalités supplémentaires, tout en maintenant une expérience utilisateur cohérente.

---

</details>

## 💮 25 - When working with home pages, which of the following aspects need to be considered?

_There are 2 correct answers to this question._

- [ ] Home pages are also workpages available only in the pre-defined 'Home' area of the site menu

- [ ] Workpages outside of the menu entry 'Home' are not related to administrative areas.

- [ ] The editor has different layout options compared to workpages inside workspaces.

- [ ] Home pages are always shown to all users.

<details>
  <summary>Solution</summary>

- [x] 🍧 Home pages are also workpages available only in the pre-defined 'Home' area of the site menu

- [ ] Workpages outside of the menu entry 'Home' are not related to administrative areas.

- [x] 🍧 The editor has different layout options compared to workpages inside workspaces.

- [ ] Home pages are always shown to all users.

---

Explication :

- Home pages are also workpages available only in the pre-defined 'Home' area of the site menu.

  Dans SAP Build Work Zone, les pages d'accueil sont des workpages spécifiques, accessibles uniquement via la section prédéfinie "Home" du menu du site. Cette section est disponible par défaut, mais peut être désactivée ou remplacée par d'autres contenus selon les besoins. [SAP Learning](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/mastering-the-site-menu?utm_source=chatgpt.com)

- The editor has different layout options compared to workpages inside workspaces.

  Le concepteur de pages (Page Designer) utilisé pour les pages d'accueil offre des options de mise en page différentes de celles disponibles pour les workpages à l'intérieur des espaces de travail (workspaces). Cela permet une personnalisation adaptée au contexte spécifique des pages d'accueil.

Pourquoi les autres options ne sont pas correctes

- Workpages outside of the menu entry 'Home' are not related to administrative areas

  Cette affirmation est incorrecte. Les workpages situées en dehors de la section "Home" peuvent être liées à des zones administratives ou à d'autres contextes, selon la configuration du site.

- Home pages are always shown to all users

  Faux. La visibilité des pages d'accueil peut être restreinte en fonction des rôles et des autorisations des utilisateurs. Les administrateurs peuvent configurer l'accès aux pages d'accueil pour s'assurer que seuls les utilisateurs pertinents y ont accès.

Conclusion

En résumé, dans SAP Build Work Zone :

- Les pages d'accueil sont des workpages spécifiques disponibles uniquement dans la section prédéfinie "Home" du menu du site.
- Le concepteur de pages offre des options de mise en page différentes pour les pages d'accueil par rapport aux workpages des espaces de travail, permettant une personnalisation adaptée.

---

</details>

## 💮 26 - In SAP Build Work Zone, what can you use to enable notifications from third party apps?

_Choose the correct answer._

- [ ] Side-by-side extension

- [ ] SAP Mobile Start Configuration

- [ ] My Inbox

- [ ] Launchpad Plugins

<details>
  <summary>Solution</summary>

- [x] 🍧 Side-by-side extension

- [ ] SAP Mobile Start Configuration

- [ ] My Inbox

- [ ] Launchpad Plugins

---

Explication :

Pour activer des notifications provenant d'applications tierces dans SAP Build Work Zone, SAP recommande l'utilisation de side-by-side extensions. Cette approche permet aux applications externes de s'intégrer avec SAP Build Work Zone en utilisant des APIs et des webhooks fournis par le Digital Workplace Service (DWS). Ces mécanismes permettent aux applications tierces de publier des notifications qui seront ensuite affichées dans le centre de notifications de SAP Build Work Zone. [SAP Learning](https://learning.sap.com/courses/low-code-no-code/illustrating-extensibility-in-sap-build-work-zone)

Pourquoi les autres options ne sont pas les plus appropriées

- SAP Mobile Start Configuration : SAP Mobile Start est une application mobile qui fournit des notifications natives et des fonctionnalités mobiles pour les utilisateurs finaux. Cependant, elle consomme les notifications déjà disponibles dans SAP Build Work Zone et ne permet pas directement l'intégration de notifications provenant d'applications tierces.
- My Inbox : My Inbox est une application qui affiche les tâches d'approbation générées par les workflows SAP. Elle ne prend pas en charge les notifications provenant d'applications tierces.
- Launchpad Plugins : Les plugins Launchpad permettent d'étendre l'interface utilisateur de SAP Build Work Zone, par exemple en ajoutant des contrôles personnalisés dans la barre d'en-tête. Cependant, ils ne sont pas conçus pour gérer les notifications provenant d'applications tierces.

Conclusion

Pour intégrer des notifications provenant d'applications tierces dans SAP Build Work Zone, l'approche recommandée est l'utilisation de side-by-side extensions. Cette méthode permet aux applications externes de s'intégrer efficacement avec SAP Build Work Zone en utilisant les APIs et webhooks fournis par le Digital Workplace Service (DWS).

---

</details>

## 💮 27 - What are some reasons companies would create custom mobile apps for SAP Build Work Zone?

_There are 2 correct answers to this question._

- [ ] To integrate with internal tools

- [ ] To support Android devices

- [ ] To support corporate branding & identity

- [ ] To customize UI Cards

<details>
  <summary>Solution</summary>

- [x] 🍧 To integrate with internal tools

- [ ] To support Android devices

- [x] 🍧 To support corporate branding & identity

- [ ] To customize UI Cards

---

Explication :

- Intégration avec des outils internes

  Les entreprises développent des applications mobiles personnalisées pour SAP Build Work Zone afin d'intégrer des outils internes spécifiques, facilitant ainsi l'accès aux informations et aux processus métiers depuis des appareils mobiles. Cette intégration est souvent réalisée à l'aide d'extensions side-by-side et de services mobiles SAP. [SAP Learning](https://learning.sap.com/courses/low-code-no-code/illustrating-extensibility-in-sap-build-work-zone?utm_source=chatgpt.com)

- Support de l'identité et de la marque de l'entreprise

  La personnalisation de l'apparence des applications mobiles, notamment en adaptant les thèmes aux couleurs et logos de l'entreprise, est une autre raison majeure de créer des applications mobiles personnalisées pour SAP Build Work Zone. Cela est réalisé en utilisant le SAP Theme Designer pour créer des thèmes personnalisés qui peuvent être appliqués aux applications mobiles via SAP Mobile Services. [SAP Learning](https://learning.sap.com/learning-journeys/Setting-Up-SAP-Build-Work-Zone-standard-edition-and-SAP-Mobile-Start-with-SAP-S-4HANA/using-corporate-branding-with-custom-visual-themes?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas correctes

- To support Android devices : SAP Build Work Zone propose déjà des applications mobiles natives pour Android et iOS, disponibles sur les stores respectifs. Il n'est donc pas nécessaire de créer une application personnalisée uniquement pour prendre en charge les appareils Android.
- To customize UI Cards : La personnalisation des UI Integration Cards se fait généralement au sein de SAP Build Work Zone ou via des outils comme SAP Business Application Studio. Il n'est pas nécessaire de créer une application mobile personnalisée pour modifier ces cartes.

Conclusion

Les entreprises choisissent de développer des applications mobiles personnalisées pour SAP Build Work Zone principalement pour intégrer des outils internes spécifiques et pour refléter l'identité visuelle de l'entreprise. Ces personnalisations permettent d'améliorer l'expérience utilisateur et de répondre aux besoins spécifiques de l'organisation.

---

</details>

## 💮 28 - Where can knowledge base articles be created?

_Choose the correct answer._

- [ ] In the central Knowledge Base feature

- [ ] In My Workspace

- [ ] In the central Content Manager

- [ ] In the Knowledge Base feature of each workspace

<details>
  <summary>Solution</summary>

- [ ] In the central Knowledge Base feature

- [ ] In My Workspace

- [ ] In the central Content Manager

- [x] 🍧 In the Knowledge Base feature of each workspace

---

Explication :

Dans SAP Build Work Zone, les articles de la base de connaissances sont créés au sein de la fonctionnalité de base de connaissances de chaque espace de travail. Cette fonctionnalité permet aux membres de l'espace de travail de créer, catégoriser et partager des articles sur divers sujets tels que des idées, des processus et des solutions à des problèmes courants. Les administrateurs d'espaces de travail peuvent activer ou désactiver cette fonctionnalité selon les besoins. [SAP Learning](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/mastering-the-site-menu?utm_source=chatgpt.com)

Pourquoi les autres options ne sont pas correctes

- Dans le gestionnaire de contenu central : Le gestionnaire de contenu est principalement utilisé pour gérer des éléments tels que des applications, des cartes UI et des pages, mais pas spécifiquement pour la création d'articles de la base de connaissances.
- Dans Mon espace de travail : "Mon espace de travail" est un espace personnel destiné à l'organisation individuelle de l'utilisateur. Il ne prend pas en charge la création ou le partage d'articles de la base de connaissances.
- Dans la fonctionnalité centrale de la base de connaissances : Bien que la base de connaissances centrale permette l'accès aux articles publiés dans divers espaces de travail, elle ne permet pas la création directe d'articles. La création se fait au niveau des espaces de travail individuels.

Conclusion

Pour créer des articles de la base de connaissances dans SAP Build Work Zone, il est nécessaire d'utiliser la fonctionnalité de base de connaissances au sein de chaque espace de travail. Cette approche permet une gestion décentralisée des connaissances, adaptée aux besoins spécifiques de chaque équipe ou projet.

---

</details>

## 💮 29 - What must you do to configure the Site Menu?

_There are 2 correct answers to this question._

- [ ] Customize layout

- [ ] Access the site menu configuration

- [ ] Create a custom template

- [ ] Edit menu items

<details>
  <summary>Solution</summary>

- [ ] Customize layout

- [x] 🍧 Access the site menu configuration

- [ ] Create a custom template

- [x] 🍧 Edit menu items

---

Explication :

Pour configurer le menu du site dans SAP Build Work Zone, les administrateurs doivent :

- Accéder à la configuration du menu du site : Cela se fait en cliquant sur l'icône d'édition (généralement représentée par un crayon) située sur la barre de menu supérieure du site. Cette action ouvre le panneau de configuration du menu, permettant aux administrateurs de visualiser et de modifier la structure actuelle du menu.

- Modifier les éléments du menu : Une fois dans le panneau de configuration, les administrateurs peuvent ajouter, supprimer, réorganiser ou modifier les éléments du menu. Chaque élément peut être configuré pour pointer vers différents types de contenu, tels que des applications, des espaces de travail ou des URL externes.

Ces étapes sont détaillées dans le tutoriel SAP [Créer un menu de site dans SAP Build Work Zone, édition avancée](https://developers.sap.com/tutorials/workzone-advanced-build-menu.html)

Pourquoi les autres options ne sont pas correctes

- Personnaliser la mise en page : La personnalisation de la mise en page concerne l'apparence et la disposition des pages individuelles (comme les pages d'accueil ou les pages de travail) via le concepteur de pages. Elle ne fait pas partie du processus de configuration du menu du site.
- Créer un modèle personnalisé : La création de modèles personnalisés est liée à la conception de pages ou de composants spécifiques, mais elle n'est pas nécessaire pour configurer ou modifier le menu du site.

Conclusion

Pour configurer efficacement le menu du site dans SAP Build Work Zone, il est essentiel d'accéder à la configuration du menu et de modifier les éléments du menu selon les besoins de l'organisation. Les autres options mentionnées ne sont pas directement liées à la configuration du menu du site.

---

</details>

## 💮 30 - In My Inbox, you can access content from which of the following components?

_There are 2 correct answers to this question._

- [ ] Notifications from other SAP solutions

- [ ] Workflows from SAP Build Process Automation

- [ ] Notifications from SAP SuccessFactors

- [ ] Workflows from SAP Build Work Zone

<details>
  <summary>Solution</summary>

- [ ] Notifications from other SAP solutions

- [x] 🍧 Workflows from SAP Build Process Automation

- [x] Notifications from SAP SuccessFactors

- [ ] 🍧 Workflows from SAP Build Work Zone

---

Explication :

Dans SAP Build Work Zone, l'application My Inbox permet aux utilisateurs de traiter les tâches générées par les workflows. Ces workflows peuvent provenir de deux sources principales :

- Workflows de SAP Build Work Zone : Créés et gérés directement au sein de SAP Build Work Zone.
- Workflows de SAP BTP Workflow Management : Développés via SAP Business Application Studio ou l'expérience SAP Build Lobby.

Les tâches associées à ces workflows apparaissent dans l'application [My Inbox](https://learning.sap.com/learning-journeys/implement-and-administer-sap-build-work-zone/using-my-inbox), offrant ainsi une interface centralisée pour leur gestion.

Pourquoi les autres options ne sont pas correctes

- Notifications from other SAP solutions : Bien que SAP Build Work Zone puisse recevoir des notifications d'autres solutions SAP (comme SAP SuccessFactors, SAP S/4HANA, SAP Ariba, etc.), ces notifications ne sont pas directement accessibles via l'application My Inbox. Elles sont généralement affichées dans la barre d'outils sous l'icône de notification.

- Notifications from SAP SuccessFactors : Comme mentionné ci-dessus, les notifications de SAP SuccessFactors ne sont pas traitées dans My Inbox. Elles sont intégrées dans SAP Build Work Zone via des mécanismes de notification distincts.

Conclusion

Pour gérer efficacement les tâches et les approbations dans SAP Build Work Zone, l'application My Inbox est l'outil central. Elle permet aux utilisateurs de traiter les tâches provenant des workflows de SAP Build Work Zone et de SAP BTP Workflow Management, offrant ainsi une interface unifiée pour la gestion des processus.

---

</details>

## 💮 31 - Out of the box, which Microsoft products are integrated with SAP Build Work Zone?

_There are 2 correct answers to this question._

- [ ] Microsoft Teams

- [ ] Microsoft Power BI

- [ ] Microsoft Sharepoint

- [ ] Microsoft Excel

<details>
  <summary>Solution</summary>

- 🍧 Microsoft Teams

- 🍧 Microsoft Power BI

- [ ] Microsoft Sharepoint

- [ ] Microsoft Excel

---

---

</details>

## 💮 32 - Which of the following features can you enable as tabs in a workspace navigation bar?

_There are 3 correct answers to this question._

- [ ] Forums

- [ ] Content

- [ ] Workpages

- [ ] Messages

- [ ] Applications

<details>
  <summary>Solution</summary>

- [ ] Forums

- 🍧 Content

- 🍧 Workpages

- 🍧 Messages

- [ ] Applications

---

---

</details>

## 💮 33 - Which tool can you use to add business apps to the Applications menu?

_Choose the correct answer._

- [ ] Work Zone Configurator

- [ ] Content Manager

- [ ] Channel Manager

- [ ] Administration Console

<details>
  <summary>Solution</summary>

- 🍧 Work Zone Configurator

- [ ] Content Manager

- [ ] Channel Manager

- [ ] Administration Console

---

---

</details>

## 💮 34 - What mechanism is typically used to integrate applications from SAP S/4HANA into SAP Build Work Zone?

_Choose the correct answer._

- [ ] Export/Import

- [ ] SAP BTP

- [ ] Content Federation

- [ ] SAP Business Application Studio

<details>
  <summary>Solution</summary>

- [ ] Export/Import

- [ ] SAP BTP

- 🍧 Content Federation

- [ ] SAP Business Application Studio

---

---

</details>

## 💮 35 - Which of the following aspects are specific to the advanced edition of SAP Build Work Zone (but not the standard edition)?

_There are 2 correct answers to this question._

- [ ] Integrating SAP and third party business content

- [ ] Blending of business data and unstructured content

- [ ] Empowering end users to create content

- [ ] Unifying access to SAP business applications

<details>
  <summary>Solution</summary>

- 🍧 Integrating SAP and third party business content

- 🍧 Blending of business data and unstructured content

- [ ] Empowering end users to create content

- [ ] Unifying access to SAP business applications

---

---

</details>

## 💮 36 - What does the 'Tools and Technologies' component of the Governance Triad include?

_There are 2 correct answers to this question._

- [ ] Set up low-code/no-code platforms.

- [ ] Establish physical IT infrastructure.

- [ ] Adopt extensible DevOps practices.

- [ ] Manage access and authorization.

<details>
  <summary>Solution</summary>

- 🍧 Set up low-code/no-code platforms.

- [ ] Establish physical IT infrastructure.

- 🍧 Adopt extensible DevOps practices.

- [ ] Manage access and authorization.

---

---

</details>

## 💮 37 - What are potential disadvantages of shadow IT in low-code development projects?

_There are 2 correct answers to this question._

- [ ] Compliance issues

- [ ] Faster implementation

- [ ] Higher autonomy of low-code developers

- [ ] Security risks

<details>
  <summary>Solution</summary>

- 🍧 Compliance issues

- [ ] Faster implementation

- [ ] Higher autonomy of low-code developers

- 🍧 Security risks

---

---

</details>

## 💮 38 - Which role is NOT part of the 'People' component of the Governance Triad?

_Choose the correct answer._

- [ ] External vendors

- [ ] IT professionals

- [ ] Citizen developers

<details>
  <summary>Solution</summary>

- 🍧 External vendors

- [ ] IT professionals

- [ ] Citizen developers

---

---

</details>

## 💮 39 - Which governance capabilities does SAP Build offer?

_There are 3 correct answers to this question._

- [ ] Limit the development to predefined templates.

- [ ] Establish eligibility rules for citizen developers.

- [ ] Provide prebuilt artifacts and use case content packages.

- [ ] Integrate CI/CD into development processes.

- [ ] Implement guardrails with built-in security.

<details>
  <summary>Solution</summary>

- [ ] Limit the development to predefined templates.

- 🍧 Establish eligibility rules for citizen developers.

- 🍧 Provide prebuilt artifacts and use case content packages.

- [ ] Integrate CI/CD into development processes.

- 🍧 Implement guardrails with built-in security.

---

---

</details>

## 💮 40 - What is the purpose of the prebuilt Digital Center of Excellence Toolkit for SAP Build?

_Choose the correct answer._

- [ ] To provide professional developers with coding templates.

- [ ] To enforce low-code coding standards.

- [ ] To help IT administrators manage and collaborate with citizen developers.

<details>
  <summary>Solution</summary>

- [ ] To provide professional developers with coding templates.

- [ ] To enforce low-code coding standards.

- 🍧 To help IT administrators manage and collaborate with citizen developers.

---

---

</details>

## 💮 41 - What does the 'Process' component of the Governance Triad involve?

_Choose the correct answer._

- [ ] Develop marketing strategies.

- [ ] Procure hardware.

- [ ] Create an IT trust blueprint.

- [ ] Set up financial guidelines for project budgeting.

<details>
  <summary>Solution</summary>

- [ ] Develop marketing strategies.

- [ ] Procure hardware.

- 🍧 Create an IT trust blueprint.

- [ ] Set up financial guidelines for project budgeting.

---

---

</details>

## 💮 42 - What can citizen developers do with SAP Build?

_Choose the correct answer._

- [ ] Build integration flows.

- [ ] Work on backend systems and server management.

- [ ] Build applications and automate processes.

- [ ] Configure role collections.

<details>
  <summary>Solution</summary>

- [ ] Build integration flows.

- [ ] Work on backend systems and server management.

- 🍧 Build applications and automate processes.

- [ ] Configure role collections.

---

---

</details>

## 💮 43 - Why does SAP recommend IT governance for citizen development?

_Choose the correct answer._

- [ ] To ensure applications are secure, scalable, and compliant with corporate standards.

- [ ] To centralize control and decision making within low-code development.

- [ ] To exercise financial control over all software development projects.

<details>
  <summary>Solution</summary>

- 🍧 To ensure applications are secure, scalable, and compliant with corporate standards.

- [ ] To centralize control and decision making within low-code development.

- [ ] To exercise financial control over all software development projects.

---

---

</details>

## 💮 44 - What does a typical Live Process Content package include?

_Choose the correct answer._

- [ ] Live Process configurations

- [ ] A Process Template, Decisions, and a Visibility Scenario

- [ ] Instructions for configuring SAP S/4HANA

<details>
  <summary>Solution</summary>

- [ ] Live Process configurations

- 🍧 A Process Template, Decisions, and a Visibility Scenario

- [ ] Instructions for configuring SAP S/4HANA

---

---

</details>

## 💮 45 - How does SAP Build Process Automation interact with SAP S/4HANA systems?

_Choose the correct answer._

- [ ] By replacing APIs with proprietary protocols

- [ ] By providing Actions projects for encapsulating API endpoints

- [ ] By integrating directly with SAP GUI for seamless data exchange

<details>
  <summary>Solution</summary>

- [ ] By replacing APIs with proprietary protocols

- 🍧 By providing Actions projects for encapsulating API endpoints

- [ ] By integrating directly with SAP GUI for seamless data exchange

---

---

</details>

## 💮 46 - What is a process variant in Live Process Content?

_Choose the correct answer._

- [ ] A process flow to map business rules

- [ ] A specific configuration of a process template

- [ ] A temporary file for testing purposes

<details>
  <summary>Solution</summary>

- [ ] A process flow to map business rules

- 🍧 A specific configuration of a process template

- [ ] A temporary file for testing purposes

---

---

</details>

## 💮 47 - What advantage does using Live Process Content offer?

_Choose the correct answer._

- [ ] Easy import, customization, and activation of content

- [ ] Free provisioning of SAP modules

- [ ] Creation of custom content without pre-configuration

- [ ] Automatic implementation of SAP modules

<details>
  <summary>Solution</summary>

- 🍧 Easy import, customization, and activation of content

- [ ] Free provisioning of SAP modules

- [ ] Creation of custom content without pre-configuration

- [ ] Automatic implementation of SAP modules

---

---

</details>

## 💮 48 - Using SAP Build Process Automation, what is the purpose of deploying a business process project?

_Choose the correct answer._

- [ ] To create a version of the project

- [ ] To edit the project

- [ ] To make the project available for others to use

- [ ] To release the project

<details>
  <summary>Solution</summary>

- [ ] To create a version of the project

- [ ] To edit the project

- 🍧 To make the project available for others to use

- [ ] To release the project

---

---

</details>

## 💮 49 - How can you create a new Process Variant in Live Process Content?

_There are 2 correct answers to this question._

- [ ] By manually adjusting backend database entries

- [ ] By using the Process Variant Editor to modify preconfigured variants

- [ ] By downloading additional process components from the SAP Store

- [ ] By using the process editor to drag and drop process steps from the process template

<details>
  <summary>Solution</summary>

- [ ] By manually adjusting backend database entries

- 🍧 By using the Process Variant Editor to modify preconfigured variants

- [ ] By downloading additional process components from the SAP Store

- 🍧 By using the process editor to drag and drop process steps from the process template

---

---

</details>

## 💮 50 - What are some benefits of using Process Variants in SAP Build Process Automation?

_There are 2 correct answers to this question._

- [ ] Processes follow the same template without changes and exceptions.

- [ ] The complexity of underlying processes is hidden.

- [ ] Processes can be adapted to changing business requirements without coding.

- [ ] SAP Build applications are updated automatically.

<details>
  <summary>Solution</summary>

- [ ] Processes follow the same template without changes and exceptions.

- 🍧 The complexity of underlying processes is hidden.

- 🍧 Processes can be adapted to changing business requirements without coding.

- [ ] SAP Build applications are updated automatically.

---

---

</details>

## 💮 51 - What are some benefits of using SAP Build Process Automation?

_There are 3 correct answers to this question._

- [ ] Increased organizational efficiency

- [ ] Enhanced monitoring of authorizations

- [ ] Increased visibility into process breakdowns and failures

- [ ] Enhanced visibility into organizational activity

- [ ] Improved communication and collaboration across lines of business

<details>
  <summary>Solution</summary>

- 🍧 Increased organizational efficiency

- [ ] Enhanced monitoring of authorizations

- 🍧 Increased visibility into process breakdowns and failures

- [ ] Enhanced visibility into organizational activity

- 🍧 Improved communication and collaboration across lines of business

---

---

</details>

## 💮 52 - Interacting with SAP Build Process Automation APIs, what does a REST API client do?

_Choose the correct answer._

- [ ] It simplifies technical communication.

- [ ] It automates process workflows.

- [ ] It provides visual representations of API responses.

- [ ] It ensures data encryption during API transactions.

<details>
  <summary>Solution</summary>

- 🍧 It simplifies technical communication.

- [ ] It automates process workflows.

- [ ] It provides visual representations of API responses.

- [ ] It ensures data encryption during API transactions.

---

---

</details>

## 💮 53 - In SAP Build Process Automation, what are some characteristics of Actions projects?

_There are 2 correct answers to this question._

- [ ] They encapsulate APIs from various systems.

- [ ] They support versioning.

- [ ] They are used for direct API integrations.

- [ ] They are limited to SAP systems APIs.

<details>
  <summary>Solution</summary>

- 🍧 They encapsulate APIs from various systems.

- 🍧 They support versioning.

- [ ] They are used for direct API integrations.

- [ ] They are limited to SAP systems APIs.

---

---

</details>

## 💮 54 - What are core elements of a Business Process Management (BPM) system?

_There are 3 correct answers to this question._

- [ ] Standardized tools to manage processes

- [ ] Faster identification of breakdowns and processes

- [ ] Real-time process execution and measurement

- [ ] Improved collaboration between departments

- [ ] Increased administrative work

<details>
  <summary>Solution</summary>

- 🍧 Standardized tools to manage processes

- [ ] Faster identification of breakdowns and processes

- 🍧 Real-time process execution and measurement

- 🍧 Improved collaboration between departments

- [ ] Increased administrative work

---

---

</details>

## 💮 55 - What is the purpose of encapsulating APIs in Actions projects?

_Choose the correct answer._

- [ ] To access API endpoints

- [ ] To limit the accessibility of APIs across different projects

- [ ] To expose APIs without filtering

<details>
  <summary>Solution</summary>

- [ ] To access API endpoints

- 🍧 To limit the accessibility of APIs across different projects

- [ ] To expose APIs without filtering

---

---

</details>

## 💮 56 - What must you do to configure an Actions project for an SAP S/4HANA API?

_There are 2 correct answers to this question._

- [ ] Assign descriptive names to API endpoints.

- [ ] Configure OAuth authentication for API access.

- [ ] Upload the JSON file into the Actions project.

- [ ] Download the API specification JSON file.

<details>
  <summary>Solution</summary>

- [ ] Assign descriptive names to API endpoints.

- 🍧 Configure OAuth authentication for API access.

- [ ] Upload the JSON file into the Actions project.

- 🍧 Download the API specification JSON file.

---

---

</details>

## 💮 57 - In SAP Build process automation, which file extension is assigned to exported projects?

_Choose the correct answer._

- [ ] .mtar

- [ ] .proj

- [ ] .zip

- [ ] .exp

<details>
  <summary>Solution</summary>

- 🍧 .mtar

- [ ] .proj

- [ ] .zip

- [ ] .exp

---

---

</details>

## 💮 58 - What is the SAP Build Process Automation Store?

_Choose the correct answer._

- [ ] A place to which users can upload their own automations.

- [ ] A place that offers prebuilt content free of charge.

- [ ] A place for SAP partners to sell content.

- [ ] A platform for purchasing SAP licenses.

<details>
  <summary>Solution</summary>

- [ ] A place to which users can upload their own automations.

- [ ] A place that offers prebuilt content free of charge.

- 🍧 A place for SAP partners to sell content.

- [ ] A platform for purchasing SAP licenses.

---

---

</details>

## 💮 59 - Which functionality does the Process Builder tool in SAP Build Process Automation support?

_There are 3 correct answers to this question._

- [ ] Writing code manually to create processes

- [ ] Creation and use of forms and approval forms

- [ ] Building decisions or business rules

- [ ] Building CI/CD pipelines

- [ ] Construction of automations and bots

<details>
  <summary>Solution</summary>

- [ ] Writing code manually to create processes

- 🍧 Creation and use of forms and approval forms

- 🍧 Building decisions or business rules

- [ ] Building CI/CD pipelines

- 🍧 Construction of automations and bots

---

---

</details>

## 💮 60 - When using Actions projects, why must you create a Destination?

_Choose the correct answer._

- [ ] To define the technical address of the remote system

- [ ] To obfuscate API endpoint details from unauthorized users

- [ ] To limit the API calls made by Actions projects

<details>
  <summary>Solution</summary>

- 🍧 To define the technical address of the remote system

- [ ] To obfuscate API endpoint details from unauthorized users

- [ ] To limit the API calls made by Actions projects

---

---

</details>
