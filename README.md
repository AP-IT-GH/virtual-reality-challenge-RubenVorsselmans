Vorsselmans Ruben

TAKEN:
- In het canvas component van "Canvas_Pedestal" heb ik de render mode van Screen space naar World Space
veranderd.
- De input van de RightRay en LeftHand heb ik moeten veranderen. Deze stonden namelijk omgedraaid.
- In de XR Grab Interactable component van de Paintbrush heb ik bij de Interactable Events de "On Activate"
en de "On Deactivate" events moeten aanpassen. Bij het "On Activate" event stond er CreateTrail.EndTrail
maar dit moest CreateTrail.StartTrail zijn. Bij het "On Deactivate" event moest ik dit ook aanpassen maar
dan andersom.
- In het Button component van de medium button moest de Pressed Color aangepast worden. Deze zorgde ervoor 
dat de knop onzichtbaar werd wanneer er op gedrukt werd. In hetzelfde component moest ook bij het 
OnClick event de dikte van de lijn aangepast worden. Dit heb ik gedaan door de dikte van 0.25 naar 0.03
te veranderen.
- Voor het sound effect van de Paintbrush te verbeteren heb ik enkele aanpassingen moeten doen in de
Audio Source component, namelijk bij het deel van 3D Sound Settings. Hier heb ik de Min Distance van 1
naar 0.1 veranderd en de Max Distance van 500 naar 1 veranderd. 