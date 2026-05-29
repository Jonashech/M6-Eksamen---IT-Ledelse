# Retrospective — YUUMI

Eksamensprojekt · IT-Ledelse (M6) · Jonas Andersen & Jonas Hechmann · 2026

---

## Overordnet vurdering

Projektet har overordnet set forløbet godt. Vi nåede i mål med en fungerende, statisk hjemmeside der dækker alle de planlagte sider, og vi har undervejs arbejdet struktureret med Git og GitHub som omdrejningspunkt. Produktet er bevidst simpelt da fokus har ligget på processen frem for på et teknisk komplekst slutprodukt.

---

## Hvad gik godt

**Versionsstyring og branch-strategi**
Vi fik tidligt oprettet en struktur med branches til de forskellige arbejdsområder. Det betød, at vi kunne arbejde parallelt uden at overskrive hinandens arbejde, og at vi løbende kunne samle arbejdet via pull requests. Det virkede godt i praksis og gav os begge en fornemmelse for, hvordan man kan samarbejde i et team igennem brugen af Git.

**Arbejdsdeling og overblik**
Kanban-boardet i GitHub Projects hjalp os med at holde styr på hvem der arbejdede på hvad. Det var nyttigt at have et fælles sted at følge opgavernes status, og vi undgik i store træk at sidde og løse de samme opgaver parallelt.

**Design og struktur**
Hjemmesiden endte med at have et gennemgående og konsistent visuelt udtryk på tværs af alle sider. CSS-variablerne i `main.css` og den fælles `pages.css` gjorde det nemt at ændre ting ét sted og få det til at slå igennem overalt.

**Afgrænsning**
Vi holdt os til den afgrænsning vi satte fra start, med at fokus ikke skulle være på et teknisk komplekst system. Det var et bevidst valg, og det frigjorde tid til at fokusere på det vi egentlig ville lære.

---

## Hvad var svært

**Database-branchen**
Undervejs forsøgte vi at implementere en simpel database-løsning — tanken var at gøre booking-funktionaliteten mere reel. Vi oprettede en separat branch til det (`database-test`), men det lykkedes aldrig at få det til at fungere ordentligt. Branchen blev aldrig merget ind i `main`.

Set i bakspejlet var det faktisk en god demonstration af, præcis hvad branches er lavet til: at holde eksperimenter isoleret fra den fungerende kodebase. Havde vi arbejdet direkte i `main`, kunne det her forsøg have rodet rundt med, og potentielt ødelagt det vi allerede havde bygget. Nu kunne vi bare lade branchen ligge og fortsætte uden.

**Commits i bunker**
Der var perioder, særligt i starten, hvor vi glemte at committe løbende og i stedet lavede store commits med mange ændringer på én gang. Det gør det sværere at følge historikken og forstå hvad der skete hvornår. Det er noget vi ville gøre anderledes fra dag ét i et fremtidigt projekt.

**Deadlines**
Noget vi kunne have gjort bedre ville have været at sætte flere deadlines for os selv, evt gennem "target date" funktionen på githubs Kanban board. Vi havde bevidst valgt at være meget frie omkring at vi hver især bare lige kunne lave det der passede, når det passede. Det gav en frihed, men resulterede i at det blev lidt flyvsk med hvornår tingene lige blev lavet.

**Git-læringskurven**
Ingen af os kendte til Git før projektet, og der gik en del tid i starten med bare at forstå hvad der egentlig skete. Hvad en commit er, hvad der sker når man pusher, og hvornår man skulle lave en ny branch. Det føltes til tider som at overkomplicere arbejdet. Vi snakkede faktisk flere gange om at når projektet kun bestod af HTML- og CSS-filer, kunne man nærmest lige så godt have skrevet dem direkte i GitHub. Vi kan godt se ideen giver mening, men det er nemmere at se når man kigger på større og mere komplekse systemer, hvor man virkelig ville mærke værdien af det.

---

## Hvad vi ville gøre anderledes

- Sætte commit-regler fast fra start: korte, hyppige commits med beskrivende beskeder
- Bruge pull request-beskrivelser mere aktivt til at forklare hvad en branch indeholder, ikke bare hvad der er ændret
- Frihed er fedt, men var lidt på bekostning af struktur. Lidt flere deadlines kunne have været godt.

---

## Hvad vi tager med videre

Projektet har givet os en praktisk forståelse for, hvordan versionsstyring fungerer i et samarbejde, og ikke som en abstrakt teori, men som noget vi rent faktisk har brugt. Vi ved nu hvorfor man laver branches, hvad en merge-konflikt er, og hvordan et Kanban-board kan holde et lille team koordineret.

Database-branchen, der aldrig blev merget, er måske det bedste eksempel på hvad vi har lært: at det er okay at eksperimentere, at fejle og at lade noget ligge, så længe det sker et sted der ikke ødelægger resten.

---
