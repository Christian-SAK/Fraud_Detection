CONTEXT
Il est très important que les entreprises établissant des cartes de crédits puissent avoir des mécanismes de détection de transactions frauduleuses afin d'éviter à leurs clients d'être facturés pour des achats qu'ils n'ont pas effecté.

CONTENT
Les données correspondent à des transactions effectuées en Septembre2013 par des utilisateurs de cartes bancaires européennes. Ces données contiennent les transactions effectuées pendant 2 jours, où il a été constaté 492 cas de fraudes sur 284.807 transactions. Nous sommes donc dans un cas de données déséquilibrées (umbalanced data) de la classe des  fraudeurs, qui représentent un taux de 0.172 %.
Les variables sont toutes numériques et sont les résultantes d'une analyse en commposante principale (ACP). Pour des raisons de confidentialité, les données ont été anonyminisées. Les variables V1, V2,..., V28 sont les principales composantes obtenues après l'ACP et seules les variables "Times" et "Amoun" n'ont pas été transformées et anonyminisées. La variables "Class" est notre variable cible et prend la valeur 1 en cas de fraude et 0 sinon.
