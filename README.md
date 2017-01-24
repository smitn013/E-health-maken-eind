# E-health-maken-eind


<b>Mijn uitdaging:</b> 
Mijn uitdaging voor het vak maken is meer kennis verkrijgen wat er mogelijk is in Code/ Javascript. Ik ben zelf niet goed in het schrijven van Code/Javascript maar als ik het uitgewerkt zie snap ik dit meestal wel. Ik wil gaan of het mij lukt om javascipt en uitgebruide CSS kan toepassen in mijn eigen code en wat voor gave dingen je nog meer kan doen. Als designer is het handig om te weten wat de mogelijkheden zijn van code, zodat je altijd iets ontwerpt wat ook daadwerkelijk kan en niet pas erachter komt dat het niet kan als het ontwerp al definitief is. Dit wil ik in het project voornamelijk doen door veel onderzoek en wellicht als het lukt in de praktijk toepassen.

<b>Begin, POC:</b>

Deelvraag: Hoe kunnen wij met notificaties het dagelijks gebruik stimuleren bij de gebruiker van de applicatie?

Inleiding, wat wil ik weten? Tijdens het onderzoek bij BDD patiënten kwam naar voren dat zij ons idee over notificaties toepassen in de applicatie fijn zouden vinden. Dat zij als gebruiker een reminder krijgen. Dit is voornamelijk handig tijdens de therapie. Een voorbeeld van een melding die toegepast kan worden: De patiënten schrijven in een “witboek” hun positieve ervaringen bij en ze zouden dit fijn vinden om het in de applicatie te doen en dan een melding krijgen dat zij het nog niet gedaan hebben. Wij willen nog meerdere positieve notificaties toepassen, zodat de patiënt nog vaker naar de applicatie gaan om het dagelijks gebruik te stimuleren.

In dit onderzoek wil ik het technische gedeelte onderzoeken van notificaties. Hoe kunnen we push notificaties gebruiken in een native applicatie en wat voor notificaties zijn er daar mogelijk. Als laatst wil ik kijken wat voor Code je ongeveer hiervoor nodig hebt.

Hoe heb ik dit onderzoek aangepakt? Ik begon mijn onderzoek op het internet met artikelen zoeken over notificaties op het internet. Als eerste kwam ik bij de bron Kony, over hoe je notificaties wel en niet moet gebruiken. Daarna ben ik opzoek gegaan naar soorten notificaties en kwam ik op de bron (developer)/ Bij deze site ben ik gaan kijken hoe je die notificaties toe zou kunnen passen met code. In de resultaten vertel ik wat ik ondervonden heb van deze artikelen.

Ik heb ook een github account gevonden die laat zien hoe je push notificaties kan toepassen dan wel op een ios applicatie. Voor mij was deze code iets te ingewikkeld. PushNotificationIOS

Resultaten De meeste telefoon gebruikers zijn weten goed hoe hun mobiel werkt en hoe ze notificaties uit kunnen zetten. Dit is niet fijn voor de bedrijven en ook erg nadelig.Kony, In dit artikel wordt verteld over push notificaties die gebruiker niet uit zouden willen zetten. Dit zijn een aantal manieren hoe je er voor kan zorgen dat de gebruiker het niet uit zou willen zetten:

Feedback: Wanneer de gebruiker de applicatie installeert vraag aan de gebruiker wat voor notificatie ze wel en niet willen. Op deze manier kiest de gebruiker de notificaties die bij hen persoonlijk passen. Ook kan de maken de data analyseren welke notificaties wel en niet aantrekken bij de meeste gebruikers. Als laatst maak het niet te moeilijk om de notificaties uit te zetten, gebruikers willen niet zoeken ze verwijderen liever de applicatie zelf.

Zo min mogelijk informatie: Denk aan hoe irritant het is als je meerdere notificaties per uur krijgt, dan zet je het graag uit nietwaar. Hou hier rekening mee, applicaties die te veel meldingen sturen en irritant gevonden worden, worden vaak verwijderd of uitgezet. Ook houd de informatie interessant, als op dat moment niet relevant is om die notificatie te krijgen stuur hem dan niet. Voorbeeld hiervan is om s nachts een notificatie te sturen naar de gebruiker terwijl ze liggen te slapen.

Op een mobiel zijn er verschillende notificaties mogelijk: Notifications on the Quick Panel (developer) Dit is in het weergavegebied voor snelle meldingen en hierin heb je twee verschillende vormen namelijk :

Het notificatiegebied: hierin staan alle meldingen die de gebruiker krijgt behalve de lopende meldingen. Deze melding vind je door het tapje op je mobiel naar beneden te halen. Deze notificatie hebben nog verschillende layouts namelijk: NOTIFICATION_LY_NOTI_EVENT_SINGLE elke notificatie apart. Dit wordt ook toegepast door bijv. facebook. Elke melding die je krijgt heeft zijn eigen notificatie.

NOTIFICATION_LY_NOTI_EVENT_MULTIPLE elke notificatie die je van die applicatie binnenkrijgt wordt samengevoegd en een cijfer ernaast gezet. Dit gebeurt bij mijn e-mail als ik meerdere e-mails binnenkrijg staat er een cijfer. Voor deze notificatie heb je de functie notification_post() nodig die je een parameter accepteert. Deze melding heeft een titel, naam en een icon.

Lopende gebied: waarin meldingen weergegeven worden die op dat moment bezig zijn. Deze meldingen zijn vaak updates of downloads. Deze notificatie is een NOTIFICATION_LY_ONGOING_PROGRESS In het lopende gebied heb je een progres balk nodig om deze aan de gang te krijgen gebruik je de code notification_create().

Active Notifications Actieve notificaties worden bovenin het scherm weergegeven wanneer de melding binnenkomt. Dit gebeurt vaak met een sms of een oproep die worden bovenin het scherm weergegeven.

Conclusie Er zijn verschillende soorten mogelijkheden om een notificatie toe te passen en wat niet veel werk kost. Het is alleen belangrijk dat we goed gaan kijken wat voor meldingen belangrijk zijn en hoe vaak er een melding naar de gebruiker toegestuurd wordt. We moeten verder gaan onderzoeken of wij de gebruiker een kans geven om bepaalde notificaties uit te zetten of dat we dit niet doen.

<b>Eindproduct:</b>
De flow van notificaties hoe ik ze wil toepassen kan alleen in een Native applicatie. Om voor ontwerpen toch iets te kunnen maken wat te maken heeft met mijn deelvraag heb ik één van mijn ontwerpen gecodeerd. Ik heb hiervoor de instellingen scherm gepakt voor de meldingen en dit scherm ben ik in code gaan uitwerken. Ik vond tijdens de lezen codepen erg handig werken en ik heb hier mijn eindscherm gaan uitwerken. In week drie hebben wij een link van de website(Css tricks,2016) gehad waarin staat uitgelegd hoe je een button maakt en deze een toggle mee geeft in javascript. Ik heb dit nog nooit gebruikt en heb dit in mijn code toegepast. 

<b>Must Have:</b>
Daarnaast heb ik geprobeerd een toggle switch toe te passen in mijn code. Dit vond ik echt een hele lastige taak en ben er uren mee bezig geweest. Ik heb hem wel kunnen aanpassen maar het is mij nog steeds niet gelukt om hem 100% goed te laten werken. Ik snap de code dat gebruikt wordt en alleen kom ik er zelf niet uit waarom hij steeds boven het menu blijft staan. Het is nog wel een must have in mijn code naar mij mening. Ik heb het wel geprobeerd en daarom heb ik een tweede link toegevoegd hieronder om te laten zien dat ik er wel mee bezig ben geweest.

<b>Mijn ontwerpen:</b>
Mijn eerste ontwerp in codepen: http://codepen.io/NikkiSmit/pen/QdMyMz
Mijn ontwerp waar ik de toggleswitch heb toegepast: http://codepen.io/NikkiSmit/pen/YNxGZV

<b>Wat heb ik geleerd:</b>
Ik ben er tijdens dit vak erachter gekomen dat ik altijd moeilijke code ontweek als in een werkende knop te gebruiken. Ik merk dat ik er ook erg lang mee bezig ben om een klein stukje code te laten werken. Ik zie andere er binnen een paar minuten klaar mee zijn terwijl ik er echt een uur mee bezig ben. Ik moet zeker mijn code gaan bijhouden en daarom wil ik binnenkort mijn eigen site gaan bouwen via Wordpress. Op deze manier houd ik de code bij en hoop ik er sneller en beter in te worden. Complexe code vind ik heel erg ingewikkeld en ik hoop dat ik uiteindelijk daarin wel beter ga worden. Wat ik erg jammer vond is dat ik op mijn Windows niet kan werken met Framer. Ik heb hier wel een klasgenoot mee geholpen na de workshop in de les. Ik was super nieuwschierig ernaar en geprobeerd om via een omweg toch op mijn computer te krijgen, helaas is dit mij gelukt en blijf ik hopen dat deze geweldige design tool ook voor Windows beschikbaar komt. 

<b>Bronnen:</b>
Kony, How to use pushnotifications: http://www.kony.com/resources/blog/how-use-push-notifications-their-full-potential Devolper, Notifications https://developer.tizen.org/development/guides/native-application/notifications-and-content-sharing/notifications PushnotificationsIOS: https://facebook.github.io/react-native/docs/pushnotificationios.html
Css Tricks, 23 November 2016, Hey designers, if you only know one thing about JavaScript, this is what I would recommend https://css-tricks.com/video-screencasts/150-hey-designers-know-one-thing-javascript-recommend/ 
W3schools, How to switch, http://www.w3schools.com/howto/howto_css_switch.asp
