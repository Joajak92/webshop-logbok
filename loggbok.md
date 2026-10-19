LOGGBOK

Fram till sprint 4:

Jag har skrivit koden i payment-service där vi använde oss av stripe som betalmetod.
Jag har ansvarat för utseendet på produktsidan samt mycket av produkthanteringen då jag hade det som backend-service. Efter ett tag så insåg vi att vi inte kan ta allt som vi tidigare har ansvarat för i backend service även i frontend då det blir ojämnt fördelat då.

Sprint 4:

Sprinten började med sprint planning på måndagen där vi satte upp sprintmål, spelade poker för att se vad alla tyckte om svårighetsgrad på varje kort i backloggen och om något behövde delas upp. Vi ansåg att det inte behövde delas upp i mindre kort så vi skapade checklistor i korten som vi delade upp. Vi började med en punkt i checklistan var att utgå ifrån.

Jag fick i uppgift att sätta upp docker miljön så jag skapade en dockerfile, lade till relevant kod i maven.yml för att automatiskt bygga, logga in och pusha till docker hub. Jag gav sedan över docker imagen till Cecilia som hade ansvar för att driftsätta gateway-service på render.

Vi har haft daily scrum möten varje dag klockan 10.00 där vi har planerat dagen. Det har blivit mycket gemensamt arbete denna vecka där vi har turats om att koda när resten av gruppen sökt information.

På fredagen började vi med ett daily scrum möte då vi ville hinna klart med det sista inför demo. Klockan 13.00 hade vi ett till möte där vi filade på det sista och förberedde os för demon. Ca klockan 14.30 hade vi ett retrospektiv möte där vi körde start, stop, continue och reflekterade över sprinten som varit.

Jag har fokuserat en del på att söka LIA under denna sprint och har därför inte kunnat vara lika delaktig som resten av gruppen. Jag skötte mitt ansvarsområde som var dockermiljö samt skrev en del kod för jwt-cookie i frontend.

Sprint 5:

19/10
Sprint planering där vi körde planning poker för att avgöra svårighet på varje uppgift i product backlog. Vi ansåg inte att något behövde brytas ner i mindre uppgifter. Vi satte även sprintmål för denna sprint.

Jag kodade i gateway-service för att implementera en get metod för /auth/me som vi använder för att hantera jwt token i cookies istället för sessionstorage.
Jag hjälpte även till att söka information i implementeringen av jwt i cookies för frontend delen tills vi körde fast. Vi avvaktar till 20/10 för att fråga Håkan om hjälp.
