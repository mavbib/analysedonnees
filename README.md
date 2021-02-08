# analysedonnees
Après quelques essais réussis et intéressants avec la librairie Python MNL et les EEG. Nous pensons être insuffisamment informés sur la matière entourant les EEG pour entamer un tel projet d'analyse pour l'instant.

L'électroencéphalographie est une méthode utilisée dans plusieurs domaines. Nous tenterons de savoir à quel sujet nous la retrouvons le plus souvent. Pour ce faire nous utiliserons une matière que nous connaissons mieux : les publications. Nous avons un bagage en science de l'information.

L'exercice sera pratiqué avec la base de données Pubmed et les termes MESH. Il serait pertinent d'effectuer un exercice semblable avec d'autres bases de données telles que PyscInfo ou Clinical Key. Non seulement elles disposent de sources différentes. Elles utilisent d'autres ensembles de mots-clés et une approche de classement différente.

Évidemment, ceci est d'abord et avant tout un exercice formatif. Nous inférons "l'usage" d'une méthode en considérant des publications, une terminologie et une pratique de classement. 

Pubmed peut exporter jusqu'à 10 000 notices directement en format CSV. Cette option n'inclut pas les termes MESH. Nous avons téléchargé le format nbib pour les logiciels de gestions bibliographiques. Nous avons effectué une recherche simple avec le mot-clé "EEG" dans la base et filtrée cette recherche pour une année et un type de publication: "Journal Article". Nous avons importé ces notices.

Bien entendu, nous pouvons importer les notices dans un logiciel de gestion bibliographique. Puis, les exporter en CSV. Nous pouvons aussi travailler directement avec le fichier nbib dans un Jupyter Notebook avec le module metaknowledge.

En plus des modules que nous voyons souvent Pandas, Matplotlib, etc. Nous pourrons apprendre de nouveaux modules de Python : metaknowledge, stop_words, networkx et nltk.tokenize.




