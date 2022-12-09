## Programme Combats de Poneys

// nom/age/couleurs => attributs du poney
// Autre manière d'exporter une classe => export default {NomDeLaClasse} à mettre en bas du fichier
// L'attribut age() se transforme en dateNaissance() pour plus de logique
// L'attribut pv() se tranforme en pvMax() et pv() pour plus de logique
// On ajoute l'attribut couleur()
// pv va définir pv() et pvMax()
// "?" devant un paramètre ==> paramètre facultatif ==> Si param précisé, niveau sinon niv 1
// "!" devant un paramètre => tkt gros ça arrive plus tard
// this.nom => permet d'accéder au getter/setter de nom
// this.dateNaissance => permet d'accéder au getter/setter de dateNaissance
// Faire appel à un attribut qui n'existe pas (attribut qui ne bougera jamais) ==> encapsulation
// .join => Mettre tous les éléments du tableau côte à côte

// Implements => fleche pointille "- - - >"

// Une classe est Abstraite quand on va mettre bcp de logique dedans
// permet aussi d'être implémenter

attaque Puissante => return le nombre de dégats
attaqueMagique => a besoin d'un certains nombres de PM pour les attaques magiques
// Si valeur par défaut, on ne met pas dans le constructeur
