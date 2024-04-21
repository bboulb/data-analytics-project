Bilal Boulbarss
bilalboulbarss@gmail.com
31-01-2024


----------------------------------


WERKLOOSHEID EN DOODSOORZAKEN IN DE VERENIGDE STATEN

In dit project zal ik onderzoeken of er verbanden zitten tussen bepaalde doodsoorzaken en werkloosheid in de VS. Dit zal ik doen door eerst twee datasets klaar te maken in een Jupyter Notebook, en daarna zal ik visualiseren in Power BI



VEREISTEN

Gemaakt in python versie: 3.9.7

Om het notebook te runnen zul je eerst de twee bijgevoegde bestanden in dezelfde directory moeten zetten:
- leading_cause_death.csv
- Unemployment in America Per US State.csv

Als je beslist de notebook te runnen in google colab, dien je zelf de code toe te voegen om de bestanden te importeren. 

Om het notebook te runnen zul je ook de 'pandas' module moeten installeren voor python. 



GEGEVENSBRONNEN EN DATASETS

De twee csv bestanden bovengenoemd zijn twee 'rauwe' datasets van Kaggle:
- https://www.kaggle.com/datasets/kingburrito666/leading-causes-of-death-usa/data
- https://www.kaggle.com/code/ilyai332/unemployment-in-america-per-us-state/input

Het derde inbegrepen csv bestand is het bestand dat je krijgt na het runnen van de Jupyter Notebook, waar alle data cleaning is toegepast. Dus het pbix bestand maakt gebruik van het volgende csv bestand:
- death_work.csv



NAVIGATIEGIDS EN DASHBOARD FUNCTIES

Bij het openen van het pbix bestand begin je op pagina 1. Op deze pagina heb je meerdere visualisaties, slicers en cards:

- Slicers: Met de twee slicers 'State' en 'Year' kan je de grafieken aanpassen om verschillende states of jaren te laten zien. (Alleen de twee line-plots worden niet beïnvloed door de slicer 'Year'.)

- 'Reset' Bookmark: Deze kan je gebruiken om alle toegepaste filters te verwijderen.

- Donut diagram: Deze laat alle doodsoorzaken zien.

- Maps: De twee kaarten van de VS laten 'Unemployment' en 'Death (all causes)' zien.

- Cards: Deze twee kaarten laten de twee staten zien met de meeste en de minste werkloosheid in percentages.

- Line plots: Deze twee lineplots zijn apart gekozen om interessante ontwikkelingen te laten zien over de tijd heen. 

Op pagina 2 heb je een aparte visualisatie die de hele pagina overneemt. Deze visualisatie laat zien wat de doodsoorzaken zijn die een relatie hebben met werkloosheid. LET OP: Dit zijn geen correlaties, maar relaties. Er worden GEEN conclusies getrokken wat betreft veroorzaken. 
# data-analytics-project
