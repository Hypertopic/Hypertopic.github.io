---
layout: splash
---

# Interopérabilité

## Primitives du modèle

Le modèle 

## Interopérabilité entre logiciels

<table>

<thead>
<th>Lecteurs (lignes) x Créateurs (colonnes)</th>
<th>Steatite</th>
<th>Cassandre</th>
<th>Porphyry (dans Argos)</th>
<th>LaSuli (dans Argos)</th>
<th>Agorae (dans Argos)</th>
</thead>
<tbody>
 
<tr>
<th>Porphyry</th>

<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>vignette d'item</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>fragment (correspondant à un marqueur) [FUTUR]</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>IDEM</ul></td>

<td><ul>
<li>portfolio</li>
<li>corpus</li>
<li>point de vue</li>
<li>attribut d'item</li>
<li>catégorie d'item</li>
<li>fragment [FUTUR]</li>
<li>catégorie de fragment [FUTUR]</li>
</ul></td>

<td><ul>
<li>portfolio</li>
<li>corpus</li>
<li>point de vue</li>
<li>attribut d'item (dont vignette et ressource)</li>
<li>catégorie d'item</li>
</ul></td>

</tr>
<tr>
<th>LaSuli</th>
 
<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>
<li>portfolio</li>
<li>point de vue</li>
<li>attribut d'item</li>
<li>catégorie d'item</li>
</ul></td>

<td><ul>IDEM</ul></td>

<td><ul>
<li>portfolio</li>
<li>corpus</li>
<li>point de vue</li>
<li>attribut d'item (dont vignette et ressource)</li>
<li>catégorie d'item</li>
</ul></td> 

</tr>
<tr>
<th>Agorae</th>

<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>vignette d'item</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>
<li>corpus</li>
<li>nom d'item</li>
<li>ressource d'item</li>
</ul></td>

<td><ul>
<li>portfolio</li>
<li>point de vue</li>
<li>attribut d'item</li>
<li>catégorie d'item</li>
</ul></td>

<td><ul>
<li>portfolio</li>
<li>corpus</li>
<li>point de vue</li>
<li>attribut d'item (dont ressource)</li>
<li>catégorie d'item</li>
</ul></td>

<td><ul>IDEM</ul></td>

</tr>
</tbody>
</table>

## Développement de logiciels sur mesure

### Adaptateur

Dans le cas où l'on souhaite décrire avec Hypertopic des items présents dans une source de données externe (base de données, entrepôt RDF, annuaire LDAP, etc.), il est possible de développer un logiciel sur mesure appelé "adaptateur".

Exemple : https://github.com/Hypertopic/ldap2hypertopic

### Client spécifique

Dans le cas où les traitements proposés par les clients du collectif (Porphyry, LaSuli, Agorae) sont trop génériques, il est possible de développer des clients plus adaptés à vos données. Le développement est grandement facilité par la réutilisation de la blibliothèque logicielle "[Hypertopic Node Library](https://www.npmjs.com/package/hypertopic)".

