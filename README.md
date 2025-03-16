<p align= "right">
<img  width="90" height="90" src="https://github.com/LucyAGOU/OC_DA_Project5/blob/main/bottleneck.jpg/" > 
<h1 aling="left">  $\textbf{\color{#8D073A} {Optimiser\ la\ gestion\ des\ données\ d'une\ boutique\ de\ vin\ en\ Python\ }}$  </h1>
</p>
<br>

### **Mission avec Bottlenec -le marchand de vin très prestigieux -**

Actuellement, pour gérer les ressources, les clients, etc., s’utilise un ERP qui n’est absolument pas relié au site de vente en ligne.
Pour être tout à fait honnête, les outils en place sont vraiment artisanaux et dans ces conditions, la gestion des stocks est vraiment 
complexe et la visibilité en termes d’analyse des ventes sur le Net est vraiment réduite, car très peu de personnes ont accès au back-office.
En attendant une solution plus centralisée, un rapprochement entre les 2 bases, même manuel, pourrait être très utile…

**La mission va se dérouler en 3 points :**
<ol>
<li> <strong>Rapprocher 2 exports :</strong> un export de l’ERP contenant les références produit, leur prix de vente et leur état de stock, et un export d’une
     table de l’outil de CMS contenant les informations des produits commercialisés en ligne (nom, description, nombre de ventes...) <br>    
  L’export issu de la boutique en ligne contient le nombre de ventes pour chaque produit depuis sa mise en ligne, il ne permet pas 
  d’analyser l'évolution des ventes dans le temps. <br>    
  En plus de ces 2 exports, tu vas bénéficier d’une aide précieuse car l’ancienne stagiaire, a réalisé un travail de fourmi. Elle a
  créé un tableau Excel qui permet d’établir le lien entre la référence du produit dans l’ERP (product_id) et la référence du même 
  produit dans la base de la boutique en ligne (SKU); </li>

<li><strong>Chiffre d’affaires à calculer : </strong>  une fois le rapprochement effectué, je souhaiterais avoir le chiffre d’affaires par produit, ainsi que
     le total du chiffre d’affaires réalisé en ligne.</li>

<li><strong>Détecter et corriger des erreurs de saisie dans certains prix des produits:</strong> Effectuer une analyse sur cette variable afin de détecter 
     d’éventuelles valeurs aberrantes, de les lister et d’en faire une représentation graphique pour plus de lisibilité.</li>

</ol>
  
Présenter tes résultats lors de la prochaine réunion de COPIL, les résultats vont se présenter sur le Notebook .

## Compétences 
  * Gérer les erreurs et les incohérences présentes sur des données stockées 
  * Classifier différents types de données 
  * Réaliser une analyse univariée pour interpréter des données

## Langages et softwares
  - ipython==7.6.1
  - matplotlib==3.4.3
  - numpy==1.20.3
  - pandas==1.3.4
  - scikit-learn==0.24.2
  - scipy==1.7.1
  - seaborn==0.11.2
  - statsmodels==0.12.2

* JupyterLab==3.2.1

