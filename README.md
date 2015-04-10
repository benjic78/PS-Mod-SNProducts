# PS-Mod-SNProducts
Prestashop Module SerialNumber Products

Bonjour,

Nous recherchons un développeur pour le projet suivant :

Création d'un module dans la fiche produit en BO permettant d'ajouter/editer/supprimer un numéros de séries de tous mes produits selectionnés (boutique vente informatique)

Les numéros de séries seront identifier par un champ "SerialNumber :" d'une longueur de 6 à 32 caractères, et être visibles par l'administrateur pour chaque produit.

Ces numéros de séries doivent être placés ensuite sur les factures des produits concernés sous la description du produit.

Les numéros de séries déjà utilisés devront devenir obsolètes et donc ne pas réapparaître sur une autre facture.

Si le client achète 2x le même produit, il doit y avoir 2 références différentes sous chaque description.

L'idée globale serait de générer par exemple 20 numéros de série pour un produit en BO, et que ces numéros se placent automatiquement sous la description du produit quand un client achète ce produit. Chaque numéro de série utilisé ne pourra plus l'être.

Concernant le paiement : 30% avant la réalisation, le reste à la livraison.

Informations ajoutées le 10 avril 2015 12:11:18 :

Bonjour, ci dessous un complément d'information : 
Je ne souhaite pas un générateur de numéro de série mais enregistrer ceux existant des constructeurs (Samsung, intel, DELL par exemple) pour une traçabilité et une utilisation après-vente : Garantie constructeur, retour SAV ou bien Assurance en cas de sinistre chez le client. Cette "variable" devra être stocker en base SQL afin que je puisse au cas ou faire une requête sur celle-ci. 
J'aurais aimez avoir un onglet dans la page BO du produit afin d'ajouter autant de produit disponible que de numéro de série (une sorte de Mini-inventaire par produit). Ces numéros de série que je rentre aléatoirement seront entre 6 et 32 caractères et devront être supprimer des lorsque le client fait sa commande.

