# Decisiones de Modelado

### Primera Iteración

Decidí utilizar las entidades:

- FuenteDeLuz
- Cuerpo
- Superficie
- Posición
- Reflejo
- Perspectiva

Tomé en cuenta que siempre para generar una sombra, debe existir una fuente de iluminación y un cuerpo el cual está siendo iluminado.

Este cuerpo debe estar ubicado en una posición **(aúnque aún no sé si posición podría pasar a ser un atributo)**, y genera un **reflejo**.

Este reflejo es lo que escencialmente conocemos como sombra, y aunque la iluminación del cuerpo no rebota, considero que la silueta del mismo provoca el rebote de la umbra del cuerpo, más no de la luz, pero puede ser una forma equivocada de verlo, considerando que la umbra en realidad es simplemente el espacio del objeto al cual no le llego luz.

Este reflejo/sombra tiene una perspectiva, ya que si yo posiciono el objeto de una u otra forma, el reflejo adquiere una nueva perspectiva, pero diferente o no, sigue siendo una perspectiva concreta.

Finalmente, este reflejo se sitúa en una superficie la cual proyecta la umbra de la sombra o mejor dicho el espacio donde los fotones de luz no pudieron llegar.