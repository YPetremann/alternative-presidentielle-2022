# L'Alternative

La france à un problème de représentation,  
au jour où seul un cinquiéme de la population est représenté,  
où les gens décident de ne plus voter parce qu'ils pensent que leur voix n'est pas exprimée.

Il existe des solutions :
- Pour garantir au moins 50% de satisfaction
- Pour garantir que le vote est bien pris en compte
- Pour éviter le vote strategique
- Pour éviter la nécéssité de voter blanc ou de s'abstenir

Pour cela il est nécéssaire de :
- moderniser la procédure de vote : Passer par un système de vote electronique couplé au vote classique
- moderniser le système de vote : Passer du Scrutin Majoritaire a deux tours au Jugement Majoritaire à 50%

## Moderniser la procedure de vote : Procédure de vote éléctronique couplé au vote classique

### Avant le Vote

Chaque personne à la possibilité d'imprimer son propre ticket de vote

### Au bureau de vote

<div class="columns">
    <div class="column buletin-graphics">
        <div class="Buletin Buletin--tilt">
            <pre class="QRcode">
██████████████    ██  ██        ██  ██████████████
██          ██  ████        ████    ██          ██
██  ██████  ██    ████      ████    ██  ██████  ██
██  ██████  ██  ██  ██  ██████      ██  ██████  ██
██  ██████  ██    ██████    ██████  ██  ██████  ██
██          ██  ██████  ████  ██    ██          ██
██████████████  ██  ██  ██  ██  ██  ██████████████
                ████████    ██                  
██████████  ████████      ██████  ██  ██  ██  ██  
██      ██    ██    ██          ██    ██    ████
████  ██████████  ██    ██  ██  ██      ████████
██    ██  ██    ██      ██  ██      ██    ██  ████
    ██  ██  ██  ██████████████████  ██  ██████  ██
██  ██    ██          ██    ██  ████        ████  
██  ██  ██  ████  ██        ████████████████████  
██  ██  ████          ██    ██████  ████          
██  ██  ████████      ████████  ████████████    ██
                ██  ████  ██  ████      ██████  ██  
██████████████  ██      ██  ██████  ██  ██        
██          ██    ████  ██      ██      ████████  
██  ██████  ██  ████      ████████████████    ████
██  ██████  ██  ████          ████  ████████    ██
██  ██████  ██  ██████  ██  ██████████          ██
██          ██  ██  ██  ██  ████    ██████        
██████████████  ██████  ████  ██  ██      ██    ██
            </pre>
            <div>
                123 456 789 123<br/>
                Mr Hercule Poireau
            </div>
        </div>
    </div>
    <div class="column">
        <p> A la place des buletins classique, nous aurions dans l'isoloir une machine electronique qui :
        <ul>
            <li> affiche un numéro unique
            <li> permettre à la personne de faire son choix 
            <li> imprimer deux buletins identiques avec à la fois écrit en clair et en clair dans un QRcode scannable facilement:
            <ul>
                <li> le numéro unique
                <li> le choix effectué
            </ul>
        </ul>
        <p> Un de ces bulletins est fait pour être mis sous plis dans l'urne, tandit que l'autre est fait pour être gardé par l'élécteur.
        <p> Ces buletins de vote peuvent avoir été imprimé à l'avance pour les personnes souhaitant faire un vote par procuration.
        <p> Lorsque l'on met dans l'urne et que l'on émarge, l'electeur ou l'agent va aussi barrer un qrcode se trouvant sur sa liste dans le but de ne plus être lisible.
    </div>
</div>

### Durant la dépouille

La dépouile reste manuelle, avec seulement une étape suplémentaire, à l'ouverture de l'enveloppe, l'agent scanne le QRcode du buletin, le scanneur indique si le vote à bien été scanné via un indicateur vert, mal scanné en orange ou déja validé en rouge. le reste est effectué de manière classique ce qui permet à la depouille manuelle et éléctronique de s'entre-valider.

Pendant ce temps un agent sera en charge de scanner la liste des electeurs des QRcodes pour y enregistrer tout élécteur ne s'étant pas présenté.

La cohérence entre les résultats par la dépouille manuelle et par la dépouille éléctronique permet de réduire la possibilité d'une manipulation lors de l'une des dépouilles

### Après la dépouille

Tout citoyen à le droit d'écceder à deux listes publiques accessible clairement.
Elles n'ont aucun lien, ne sont pas datés. En prime elle sont triés alphabétiquement par leurs données dans l'ordre.
La première liste contient seulement dans cette ordre : le numéro de département, le nom et prénom complet.
La seconde liste contient seulement les mêmes informations que les tickets dans cette ordre : le numéro unique et le choix effectué.

Un programme facilement accessible au code source libre, publique, clair et facilement reproductible est aussi fourni affin de faciliter la lecture des listes.
Il permettrait :
- de vérifier le décompte et donc le résultat éléctoral
- de vérifier que le nombre d'électeurs est égal au nombre de votes
- de verifier sa présence ou celle d'un proche sur la list des élécteurs
- de vérifier la présence et la cohérence de son vote sur la seconde

Cela permet de garantir par exemple qu'un proche n'ayant pu voter ne soit présent, que notre vote n'aie été modifié ou encore d'autres situations.

### Conclusion

Avec cette procédure de vote nous augmentons la garantie que chaque vote est vraiment exprimé.
Si en plus nous couplons cela avec un système de vote comme le jugement majoritaire à 50%, il n'y a du coup aucune raison d'abstention ou de voter blanc, et démontre clairement que l'absence d'un élécteur serait du à l'impossibilité de voter.

## Moderniser le système de vote : Jugement Majoritaire à 50%

