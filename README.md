# Ahmad Alkhatib

> Portfolio voor de minor Data science


<details><summary>Research project</summary>
<p>

## Task definition
<br />
Het doel van dit project, uitgevoerd voor Cofano Software Solutions, is om de processen bij containerterminals te optimaliseren door het verkorten van de tijd dat schepen aan de kade liggen voor het in- en uitladen van containers. Dit moet geautomatiseerd worden en het onderzoek zal zich richten op het vinden van een optimale aanpak om deze uitdaging aan te pakken. Dit is belangrijk voor de efficiëntie van containeroverslag in de haven en voor het verminderen van kosten.<br />
<br />
Hoofdvraag :<br />
Hoe kan ervoor gezorgd worden dat containers op de kade op een efficiënte manier opgestapeld kunnen worden, zodat de afnemer van de containers hier makkelijk bij kan.<br /> 
<br /> 
Deelvragen 
 <br />
•	Hoe ziet de lay-out van de desbetreffende kade eruit? <br />
•	Welke reinforcement learning modellen en methodes zijn relevant om dit optimalisatieprobleem aan te pakken? <br />
<br />

## Evaluation:
<br />
 uiteindelijk gefocust op een Reinforcement learning model als oplossing voor ons probleem. Hoewel we ook een lineair programmeer model hebben geprobeerd, heb ik mij hier niet verder mee bezig gehouden omdat ik geen expertise heb in lineair programmeren. Maar dankzij deze experimenten heb ik een dieper begrip verkregen van hoe Reinforcement learning werkt en hoe we het konden toepassen op ons specifieke geval. Dit heeft ons geholpen bij het maken van een betere keuze voor de oplossing van ons probleem.

## Conclusions: 
 <br />
In dit project is gekeken naar manieren om containers op een efficiënte manier op te stapelen op een kade, zodat de afnemer van de containers hier gemakkelijk bij kan. Door het probleemdomein in kaart te brengen, bleek dat de huidige containerplaatsing op een kade handmatig verloopt, wat tijd en geld kost. Door gebruik te maken van Reinforcement Learning (RL) en twee verschillende agents (PPO en A2C) die interacties voerden met een environment, kwam de PPO-agent als de beste naar voren. Door de PPO-agent te trainen met optimale waarden en hyperparameters, is er een efficiënte containerplaatsing ontstaan, waarbij rekening wordt gehouden met de bestemming van aangrenzende containers. Dit is een grote doorbraak voor de logistieke sector en een goed voorbeeld van hoe technologie/AI de internationale handel bevordert.
 
## Planning:
<br />
Als groep hebben we afgesproken om een planning te maken en te werken met Scrum methodologie. Hierbij maakten we gebruik van een tool genaamd Trello waar we alle taken bijhouden, de verantwoordelijken aangeven en de deadlines noteren. We hebben alles ook kunnen indelen in afgeronde taken en werk in uitvoering.<br />
 <br />
Verder hebben we ons gehouden aan de volgende planning:<br />
 <br />
 • Elke maandag om 11:00 bespreken we met docent Karin de Smidt. <br />
 • Op vrijdag om 10:00 in Delft hebben we begeleidingsgesprekken met docenten Tony Andrioli en Jeroen Vuurens waar we al onze vragen kunnen stellen die we niet konden beantwoorden tijdens de week. <br />
 • Als groep hebben we afgesproken om op wisselende dagen via Teams te communiceren, aangezien we andere verplichtingen hadden. <br />
 
 
</p>
</details>


<details><summary>Domain knowledge</summary>
<p>

## Introduction of the subject field

### Data science cursus:
<br />
Data Science is een multidisciplinair veld dat zich richt op het verkrijgen van inzicht en kennis uit gegevens. Het omvat verschillende stappen zoals het verzamelen, opschonen, analyseren en visualiseren van gegevens. Met behulp van methoden uit de statistiek, wiskunde, informatica en machine learning, ontdekken data wetenschappers patronen in de gegevens en maken zij voorspellingen.
Data Science wordt vaak toegepast in verschillende industrieën, zoals financiën, gezondheidszorg, marketing en retail om beslissingen te nemen gebaseerd op data. In de financiële sector wordt bijvoorbeeld gebruik gemaakt van data science om fraude te detecteren en risico's te bepalen. In de gezondheidszorg wordt data science ingezet om patiëntendossiers te analyseren en zo behandelingsopties te bepalen. In marketing en retail worden klantprofielen opgebouwd en voorspellingen gedaan over klantgedrag.<br />
<br />
Data Science is een snel groeiend veld en wordt vaak beschouwd als een van de belangrijkste vaardigheden voor de toekomst van werk. Er zijn steeds meer organisaties die grote hoeveelheden gegevens verzamelen, zoals sociale media, sensoren en internet-verbonden apparaten. Deze gegevens moeten worden geanalyseerd en geïnterpreteerd om waardevolle inzichten te verkrijgen.<br />
 <br />
Een data scientist is vaak verantwoordelijk voor het bedenken van de juiste vragen, het verzamelen en opschonen van gegevens, het bouwen van modellen en het communiceren van resultaten. Het vereist vaak een combinatie van vaardigheden in statistiek, programmeren, communicatie en domain-kennis. Veel data wetenschappers hebben een achtergrond in wiskunde, informatica of statistiek, maar er zijn ook steeds meer professionals die een overstap maken naar data science vanuit andere achtergronden zoals economie, natuurkunde, of zelfs filosofie.<br />
<br />
In samenvatting, Data Science is een veld dat zich richt op het verkrijgen van inzicht en kennis uit gegevens door middel van het verzamelen, opschonen, analyseren en visualiseren van gegevens met behulp van methoden uit de statistiek, wiskunde, informatica en machine learning. Het wordt veelvuldig toegepast in verschillende industrieën, zoals financiën, gezondheidszorg, marketing en retail, om beslissingen te nemen gebaseerd op data. Het is een snel groeiend veld en wordt vaak beschouwd als een van de belangrijkste vaardigheden voor de toekomst van het werk. Data wetenschappers hebben vaak een achtergrond in wiskunde, informatica of statistiek, maar er zijn ook steeds meer professionals die een overstap maken naar data science vanuit andere achtergronden, zoals economie of natuurkunde.
<br />
 <br />
 
### Het project:
<br />
In de logistieke wereld is de scheepvaart een cruciale sector. Goederen worden eerst in containers geladen en vervolgens naar een terminal vervoerd, waar ze op een containerschip gezet worden. Voordat de containers op het schip geplaatst worden, staan ze eerst op de container yard van de terminal. Hier worden de containers die meegaan met het schip, met behulp van een reachstacker op het schip gezet.

Het doel is om de containers zo efficiënt mogelijk te plaatsen en op te stapelen, zodat er zo min mogelijk stappen nodig zijn om de containers op elk schip te laden. Dit bespaart tijd en geld, en vermindert vertragingen. Cofano wil onderzoeken welke methode(s) geschikt zijn om het container stacking probleem op te lossen en het container stacken te automatiseren. Eén van de oplossingsrichtingen is om het probleem als een optimalisatieprobleem te formuleren, bestaande uit decision variables, objective function en constraints, en vervolgens een heuristiek toe te passen. Het is interessant om meerdere heuristieken toe te passen en deze met elkaar te vergelijken op basis van hun resultaten.
 
<br />

## Literature research:
Ik heb tijdens het project gezocht naar literatuur om begrip te krijgen over hoe machine learning-modellen werken en om oplossingen te vinden die voorspellende modellen opleveren.<br />
<br />
https://www.ibm.com/topics/machine-learning<br />
https://en.wikipedia.org/wiki/Machine_learning<br />
https://www.sap.com/insights/what-is-machine-learning.html<br />
https://www.geeksforgeeks.org/what-is-reinforcement-learning/<br />
https://en.wikipedia.org/wiki/Reinforcement_learning<br />
https://www.ifaamas.org/Proceedings/aamas2019/pdfs/p2250.pdf<br />
https://www.geeksforgeeks.org/ml-reinforcement-learning-algorithm-python-implementation-using-q-learning/?ref=rp<br />


## Explanation of Terminology, jargon and definitions:<br />
 
Data science is een interdisciplinaire veld dat zich richt op het verzamelen, analyseren en interpreteren van grote hoeveelheden gegevens (big data) met behulp van methoden uit de statistiek, wiskunde, informatica en andere gerelateerde velden. Hieronder worden enkele belangrijke termen, jargon en definities behandeld die vaak worden gebruikt in de context van data science.<br />


• Big data: Dit verwijst naar zeer grote hoeveelheden gegevens die te groot zijn om te worden verwerkt of opgeslagen door traditionele databases of software.<br />


• Machine learning: Dit is een subveld van kunstmatige intelligentie waarbij computerprogramma's in staat zijn om van gegevens te leren zonder expliciet geprogrammeerd te worden.<br />


• Data mining: Dit is het proces van het ontdekken van patronen en kennis in grote hoeveelheden gegevens.<br />


• Data warehousing: Dit is het proces van het opslaan van grote hoeveelheden gegevens in een centrale database voor analyse en rapportage.<br />


• Data visualization: Dit is het proces van het weergeven van gegevens in een visueel aantrekkelijke manier, zoals grafieken of kaarten.<br />


• Data cleansing: Dit is het proces van het verwijderen of corrigeren van fouten of inconsistenties in de gegevens.<br />


• Data modeling: Dit is het proces van het creëren van een logisch en fysiek model van de gegevens voor gebruik in een database of andere gegevensopslag.<br />


• Natural Language Processing (NLP): Dit is een subveld van kunstmatige intelligentie dat zich richt op het verwerken van menselijke taal door computers.<br />


• Predictive modeling: Dit is het proces van het maken van voorspellingen over toekomstige gebeurtenissen op basis van historische gegevens.<br />


• Data governance: Dit is het proces van het beheren van gegevens op een manier die voldoet aan de eisen van de organisatie en de wetgeving.<br />

• Machine learning is een belangrijk onderdeel van data science en wordt vaak gebruikt voor het analyseren van grote hoeveelheden gegevens. Het is een proces waarbij computers in staat zijn om van gegevens te leren zonder expliciet geprogrammeerd te worden. Dit kan worden gedaan door het gebruik van algoritmen die in staat zijn om patronen en relaties in de gegevens te ontdekken. Er zijn verschillende soorten machine learning, waaronder supervised learning, unsupervised learning en reinforcement learning.<br />

• Supervised learning is waarbij de computers leert met behulp van gegevens met bekende output (gelabeled data) zoals bijvoorbeeld bij het klassificeren van beelden.
• Unsupervised learning is waarbij de computer geen gekende output heeft en zelf patronen probeert te ontdekken zoals bijvoorbeeld bij het ontdekken van clusters in gegevens. <br />

• Reinforcement learning is een vorm van machine learning waarbij de computer leert door feedback te krijgen op zijn acties. Machine learning-modellen worden vaak gebruikt in toepassingen zoals voorspellingen, automatisch classificeren, beeldherkenning en natuurlijke taalverwerking.<br />


• Overfitting: Dit gebeurt wanneer een model te complex is en zich te nauwkeurig aanpast aan de training gegevens, waardoor het slecht presteert op onbekende gegevens (test gegevens). Het model leert de ruis (noise) in de training gegevens, in plaats van de echte relaties tussen de features en de output. Dit leidt tot een hoge nauwkeurigheid op de training gegevens en een slechte prestatie op de testgegevens.<br />


• Underfitting: Dit gebeurt wanneer een model te simpel is en niet in staat is om de complexiteit van de gegevens te captureren. Dit leidt tot een slechte prestatie zowel op de training gegevens als op de testgegevens.<br />

 
 </p>
</details>

<details><summary> Communication</summary>
<p>
 
## Presentations:
[Externe presentatie week 14 groep 4](https://github.com/AhmadJ98/ahmad.alkhatib/blob/main/Externe%20presentatie%20week%2014%20groep%204.pptx)<br />
[Interne presentatie week 10 groep 4](https://github.com/AhmadJ98/ahmad.alkhatib/blob/main/Interne%20presentatie%20week%2010%20groep%204.pptx)<br />


## Writing paper:
<br />
• Voor het eerste project (Food Boost) heb ik de onderstaande documenten geschreven voor onze research paper.<br />
[](https://github.com/AhmadJ98/ahmad.alkhatib/blob/main/IJzer.docx)<br />
[](https://github.com/AhmadJ98/ahmad.alkhatib/blob/main/Vitamine%20B12.docx)
<br />
• Voor het tweede project (Container) heb ik de discussie onderdeel geschreven.
 </p>
</details>
