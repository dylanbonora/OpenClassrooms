    En résumé
    
    La technique de mise en page la plus récente et la plus puissante est Flexbox. C'est celle que vous devriez utiliser si vous en avez la possibilité.

    D'autres techniques de mise en page restent utilisées, notamment sur des sites plus anciens : le positionnement flottant et le positionnement inline-block . Il est conseillé de les connaître.

    Le positionnement flottant (avec la propriété float  ) est l'un des plus utilisés à l'heure actuelle. Il permet par exemple de placer un menu à gauche ou à droite de la page. Néanmoins, cette propriété n'a pas été initialement conçue pour cela et il est préférable, si possible, d'éviter cette technique.

    Le positionnement inline-block  consiste à affecter un type inline-block  à nos éléments grâce à la propriété display  . Ils se comporteront comme des inlines (placement de gauche à droite) mais pourront être redimensionnés comme des blocs (avec width  et height  ). Cette technique est à préférer au positionnement flottant.

    Le positionnement absolu permet de placer un élément où l'on souhaite sur la page, au pixel près.

    Le positionnement fixe est identique au positionnement absolu, mais l'élément restera toujours visible même si on descend plus bas dans la page.

    Le positionnement relatif permet de décaler un bloc par rapport à sa position normale.

    Un élément A positionné en absolu à l'intérieur d'un autre élément B (lui-même positionné en absolu, fixe ou relatif) se positionnera par rapport à l'élément B, et non par rapport au coin en haut à gauche de la page.