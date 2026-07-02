# ERM
Game ERM by Rocketree Studios:

Breakdown of file contents:

- In folder "Content", "Interaction":

AC_Interaction_Trace: Detects the distance of a players vision trace (exactly where they're looking). Created a framework for interaction between either another player or an interactable object. The skeleton of all interaction systems within the game. 

BI_Interaction: A blueprint interface applicable to all interactable objects to provide a floating widget that shows what the interaction will do (ie. "E to interact"), along with other uses.

WBP_Interaction: The floating widget that is edited by BI_Interaction. Shows the control (typically E), along with a short description for what they're doing. Again, "E" would be the control and "Interact" would be the short description.

- In folder "Content", "Interaction", "Interaction Area":

BP_InteractionArea: A physical area that can be added into any actor as the physical boundaries that can be found by the trace. If the trace hits this actor inside another actor (a machine for example), it will flag the trace as seeing an object. 

- In folder "Content", "Game", "Resources", "Images":

eyes and mouth: Contain all mouths and eye textures in a sprite sheet. This sheet can be cycled as players switch their cosmetics

characterface: a texture for cosmetic previews in widgets and in the customization menu, where the eyes and mouth will be laid over

spacebg: a texture for the customization menu that goes behind the preview, simply cosmetic


