## Beauté algorithmée

### Fonctionnement général
Chacun·e peut poster son contenu sur les médias sociaux, mais la visibilé de celui-ci ne repose pas sur un système égalitaire. Face à la profusion du flux d'informations,
il serait devenu nécessaire d'éditorialiser les contenus[^edit]. C'est là qu'algorithmes et intelligences artificielles interviennent et
obéissent, pour décider de ce qui sera mis en avant dans nos *feed*.
Chaque plateforme en possède des spécifiques qui coordonnent et modèrent nos affichages et recommandations.

La définition d'un algorithme est «&#8239;la description d'une suite d'étapes permettant d'obtenir un résultat à partir d'éléments fournis en
entrée&#8239;»[^algo]. Les données en jeu pour établir une mise en forme prétendument
pertinente sont nombreuses. Ces systèmes analysent entre autres nos interactions entre utilisateur·rice·s, les publications aimées et/ou sauvegardées, les vidéos visionnées et le temps que l'on y a consacré. Le but de ces stratégies est toujours le même&#8239;: créer de _l'engagement_. Le temps que nous passons à scroller vient remplir l'objectif des éditeur·rice·s&#8239;; «&#8239;monétiser (notre) présence et (notre) activité&#8239;»[^monet].

Mais ces pages de recommandation _pour nous_, sont aussi soumises à des logiques algorithmiques qui vont au-delà de notre simple interaction avec l'environnement en ligne. Évidemment les contenus sensibles, à caractère raciste, violent, pornographique, etc sont censurés. Mais parfois l'éthique et la moralité de ces motions dépassent les conditions générales d'utilisation. Pendant que certains contenus sont mis en avant, d'autres sont bêtement censurés. TikTok par exemple va, en fonction du pays où il est utilisé, censurer les contenus identifiés comme LGBTQ+ ou bloquer des «&#8239;messages de justice sociale&#8239;»[^justice]. Instagram encore, bien connu pour sa [politique binaire en matière de téton](https://www.ladn.eu/media-mutants/reseaux-sociaux/instagram-ou-le-defi-du-teton/), offre des passe-droits à la nudité aux personnes minces mais signale celleux en surpoids. L'algorithme est biaisé puisque, la nudité (ou non) est identifiée par une intelligence artificielle qui va calculer le «&#8239;pourcentage de peau&#8239;» de la personne photographiée[^peau]. Ces exemples, pourtant offciellement identifiés comme des _bugs_, sont venus mettre en lumière les limites de ces mécanismes qui rappelons-le, sont le fruit d'une logique humaine imputée aux machines. «&#8239;Nous avons des préjugés, et l'IA les apprend&#8239;»[^joannastar], et quand on sait que ce «&#8239;nous&#8239;» est une large majorité d'hommes confortables dans notre système patriarcal, il est peu étonnant de voir poindre ces biais algorithmiques.
<br><br>
C'est là une des failles des plateformes dominantes en terme de
«&#8239;représentations culturelles collectives&#8239;». Nos suggestions ne sont pas le fruit de nos interactions uniquement&#8239;; le «&#8239;déterminisme algorithmique (est) lui même contraint par un déterminisme culturel&#8239;»[^cul]. Dans l'univers de la beauté en ligne, cette notion est centrale et il apparaît que TikTok en particulier s'arme d'un outil supplémentaire pour hiérarchiser ses contenus.

[^edit]: https://ateliers.esad-pyrenees.fr/web/pages/culturenum/mediaqueries/ <br><br>
[^algo]: cnil.fr <br><br>
[^monet]: _Thèque 1, Mes années Tiktok_. Marlewe Granados, 2022. <br><br>
[^justice]:_Thèque 1, Mes années Tiktok_. Marlewe Granados, 2022. <br><br>
[^peau]: _Les personnes en surpoids plus susceptibles d'être censurées par Instagram_, Ophélie Surcouf, 2019. <br><br>
[^joannastar]: Joanna Bryson, _There is no AI ethics&#8239;: The human origins of machine prejudice_, 2017. <br><br>
[^cul]: _L'appétit des géants_, Olivier Ertzscheid, 2017.<br><br>

### _Online beauty privilege_
Si la plateforme offre des débats sur l’hégémonie ambiante des standards en ligne, force est de constater qu’en «&#8239;vitrine&#8239;», dans les _feed_ et publications suggérées, il est rare de voir la diversité se côtoyer. TikTok, dont l’algorithme est l’un des plus compliqué à percer, collectionne de nombreuses accusations de «&#8239;racisme et de censure&#8239;» à ce sujet. Le _privilège de la beauté_ se transpose en ligne et les vidéos mises en avant sont celles d’utilisateur·rice·s qui correspondent aux normes de beauté établies. Critères découlant des standards occidentaux mais aussi d’un algorithme beauté bien particulier.

Dans une note interne **(voir annexe)**, récupérée en 2020 par le magazine d’investigation en ligne _The Intercept_, une partie de la stratégie de TikTok est détaillée. Il y est demandé aux modérateur·rices·s du média, pour selon eux «&#8239;prévenir du harcèlement&#8239;», de supprimer tout contenu présentant des «&#8239;visages laids&#8239;»,
des personnes «&#8239;trop ridées&#8239;» ou même celleux atteint de «&#8239;nanisme&#8239;»[^ti]. Si l’entreprise a depuis répondu que cette note était aujourd’hui obsolète, les enquêtes sur l’algorithme beauté TikTok se sont
multipliées. La théorie avancée serait que chaque vidéo, soumise à l‘analyse d‘une intelligence artificielle, noterait notre «&#8239;beauté&#8239;» sur cinq. Angelina Jolie, désignée comme l’une des «&#8239;plus belle
femme du monde&#8239;»[^vanity] obtiendrait par exemple la note de 4.7/5. En 2021, le tiktokeur @benthamite a
même récupéré dans la documentation de ByteDance, société qui produit TikTok, les lignes de codes qui régissent l’algorithme. Il a produit avec celles-ci un site, tiktokbeautiful.com où chacun·e pouvait noter sa «&#8239;beauté&#8239;» sur cinq&thinsp;; Tiktok a exigé la fermeture du site quelques temps après.

Modelé sur une base de données nommée [SCUT-FB5500](https://github.com/HCIILAB/SCUT-FBP5500-Database-Release), cet algorithme calcule via des «&#8239;points clefs&#8239;», logiques de symétrie et de ratio, l’attractivité de nos visages(imagenote: content/images/point.png caption: Exemple de logiques de calcul class: printright). Les données en question sont les photos de «&#8239;5500 visages avec diverses propriétés&#8239;», qui prises de manière frontales se sont vues attribuer une note entre un et cinq. Le problème est que les «&#8239;diverses propriétés&#8239;» s’arrête à la différence entre genre «&#8239;masculin ou féminin&#8239;», et «&#8239;caucasien ou asiatique&#8239;» **(voir annexe)**. Aucune données donc, n’est présente pour les autres «&#8239;couleur de peau&#8239;» ou les «&#8239;particularités physiques&#8239;» par exemple. Difficile donc de ne pas standardiser la beauté quand l’unité de mesure de celle-ci ne connaît pas la diversité.
<br><br>
Mais s’il est logique de blâmer l’algorithme pour ses failles éthiques, il faut aussi comprendre la responsabilité de l’utilisateur·rice dans celui-ci. Comme nous l’avons déjà mentionné, le but premier du média est de générer du profit, profit auquel nous participons via notre engagement. Il s’avère que mettre en avant des «&#8239;visages attractifs&#8239;» donne de meilleurs résultats. Nous nourrissons l’application avec «&#8239;nos propres idéaux de beauté toxiques&#8239;»[^toxiques]. La plateforme nous donne du contenu que nous l’avons aidé à identifier comme séduisant. Nous tenir pour responsable du système serait pourtant fallacieux. Mais il faut admettre qu’il est le reflet d’une société abusée et fascinée par la beauté. On comprend
peut-être mieux ainsi le succès de la _cleangirl_, malgré son manque évident de diversité.
<br><br>
L’impact sur le _tutoriel beauté 2.0_ et sa (re)définition de la beauté est mesurable. L’affluence du format
TikTok au-delà même de sa plateforme, vient peu à peu lisser le paysage de la beauté en ligne. Au-delà d’une performance ritualisée, les visages se confondent, répondant à un modèle donné et laissant de moins en moins de place à la diversité. Mais quand on voit que la stratégie est efficace, on peut se demander si nous sommes vraiment prêt·e·s à se défaire du poids des standards relatifs à nos apparences&#8239;? Comme le dit Olivier Ertzscheid, sans volonté de comprendre et démystifier ces mécanismes, «&#8239;le futur technologique sera rempli de stéréotypes&#8239;»[^techno].

[^ti]: _TikTok Told Moderators to Suppress Posts by “&#8239;Ugly&#8239;” People and the Poor to Attract New Users_, The Intercept, 2020. <br><br>
[^vanity]: Selon [Vanity Fair](https://www.vanityfair.com/news/2009/04/angelina-jolie-is-the-most-beautiful-woman-in-the-world) en 2009. <br><br>
[^toxiques]: Priya Melonio, _TikTok’s Non -Inclusive Beauty Algorithm &
Why We Should Care_, 2022. <br><br>
[^techno]: _L'appétit des géants_, Olivier Ertzscheid, 2017. <br><br>

<!-- <br class="breakpage"> -->