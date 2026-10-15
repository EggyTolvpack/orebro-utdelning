# Örebro – Utdelningskarta

https://eggytolvpack.github.io/orebro-utdelning/

GPS-app för Adolfsberg, Marieberg, Gamla Vintrosavägen och Sörby. Totalt 1526 gatbitar. Områdesurvalen är praktiska karturval, inte officiella områdesgränser.

## Körning och utdelning

- Grönt: kört. Under en ny runda visas tidigare körda gatbitar streckat gröna.
- Gult: delvis kört. Tidigare delvis körda sträckor ligger också kvar.
- Lila: reklam utdelad, alltid markerad manuellt.
- Rött: inte markerad körd. Turkost: den visade rundans sparade GPS-körspår.
- Tryck på en gatbit för att markera körning eller utdelning separat. Den ena markeringen är inte automatiskt bevis för den andra.
- Tona ned utdelat gör markeringarna svagare, men inga körda gator döljs helt.

## Rundor

Starta runda + GPS skapar eller återupptar en runda. Pausa stoppar GPS och tidtagning. Avsluta runda sparar den i historiken. Ny runda raderar aldrig äldre körhistorik. Sparade rundor kan väljas under Rundor och säkerhetskopia. Tid, körd sträcka, gatmarkeringar och körspår sparas. Vid omladdning återställs en pågående runda pausad; återuppta GPS med Fortsätt runda.

GPS markerar gatbitar efter minst 75 procent täckning av provpunkter inom 18 meter och uppgiven noggrannhet högst 35 meter. För svag GPS och orimliga GPS-hopp registreras inte som körning. Körspåret bryts vid paus, dålig signal eller mer än 30 sekunder mellan användbara positioner. Avstånd är en GPS-baserad uppskattning, inte en exakt vägmätare.

## Skärm och GPS

Starta GPS aktiverar följning och gatunivå. Färdriktningen visas som en pil när du rör dig. Dra kartan för fri vy, tryck Följ mig för att följa igen. Dölj meny ger full kartvy med Visa meny, Följ mig och GPS-status kvar. GPS-status visar god, svag eller förlorad signal.

Håll skärmen vaken används under en aktiv runda när webbläsaren stöder Screen Wake Lock. Appen visar om det misslyckas. Skärmlåset släpps vid paus eller avslut. Safari kan fortfarande pausa GPS i bakgrunden eller med låst skärm. Håll appen synlig under registrering.

## Lagring och säkerhetskopior

All historik och exakta körspår sparas lokalt i webbläsaren på enheten, inte i GitHub. Exportera regelbundet. Om lagringen är full visas en bestående varning; export använder även den ännu osparade historiken. Import lägger till markeringar och unika rundor utan att radera befintliga. Gamla säkerhetskopior fungerar.

Befintliga körmarkeringar från tidigare appversioner bevaras med samma lagringsnyckel. Vid första öppningen hämtas även markeringar från de ursprungliga områdeskartorna om de finns i samma webbläsare på eggytolvpack.github.io. Apparna synkroniserar inte efter detta.

Kräver internet för kartbakgrund och Leaflet. Öppna i Safari på iPhone och välj Dela → Lägg till på hemskärmen för en appgenväg.

© OpenStreetMap contributors, ODbL: https://www.openstreetmap.org/copyright . Leaflet 1.9.4. Följ lokala skyltar. Grönt är körning, inte bekräftad utdelning. Detta är en täckningskarta, inte optimerad sväng-för-sväng-navigering.
