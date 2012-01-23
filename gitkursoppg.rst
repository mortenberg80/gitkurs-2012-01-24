Scenario:
=========

Du har fått i oppgave å lage en rapport om favoritthobbyen din, vedhogst.
For å ha kontroll på arbeidet ditt, velger du å lagre rapporten i et
Git-repository på Github-kontoen din.

Oppgave 1
---------
Lag et nytt repository på Github-kontoen din, "vedhogst".

Klon ned dette repoet til lokal disk.

Lag ei ny fil, `README.txt`, og skriv kort hva dette prosjektet omhandler.
Legg til fila, commit og push.


Oppgave 2
---------
Din første versjon av rapporten skal inneholde følgende tekst::

  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat
  lorem vitae nulla volutpat vehicula. Vestibulum ante ipsum primis in faucibus
  orci luctus et ultrices posuere cubilia Curae; Sed rutrum vestibulum
  consectetur. Nulla malesuada, ante dapibus convallis facilisis, ipsum orci
  pulvinar dui, in euismod mauris enim ac metus. Nulla facilisi. Vivamus a
  dolor ut leo consequat lobortis. Ut nec urna neque. Maecenas ligula velit,
  pretium vitae tristique vitae, dignissim vehicula dui. Vivamus ultrices orci
  nisi. Donec porttitor aliquam tempus. Mauris augue sem, condimentum eu luctus
  pharetra, interdum scelerisque nisi. Praesent ornare tellus vitae magna
  molestie rutrum. Curabitur suscipit laoreet orci, vitae porta libero pretium
  sit amet. Aenean interdum, elit nec cursus venenatis, lorem velit dapibus
  neque, ut ultrices felis purus nec sapien. Nulla facilisi.

Legg til dette i ei fil kalt *ditt_navn-1*, commit, og push.


Oppgave 3
---------
Du begynner å jobbe på kapittel 2, med følgende tekst::

  Fusce odio justo, congue vel sodales vel, posuere nec ligula. Curabitur arcu
  dui, vulputate eu viverra a, sagittis sit amet diam.

Plutselig kommer du på at du har glemt noe viktig i kapittel 1, og legger til
følgende i *ditt_navn-1*-fila::

  Nam bibendum, magna at tincidunt tincidunt, dui turpis eleifend urna, a
  viverra elit nisl at tellus. Curabitur tincidunt placerat egestas.

For ikke å blande ulike konsepter i samme commit, ønsker vi å ha en naturlig
separasjon i disse. Legg derfor til og commit endringene dine i kapittel
1-fila, men **ikke** den nye fila *ditt_navn-2*.


Oppgave 4
---------
Du ser nå (kanskje) verdien i å kunne uforstyrret jobbe med et kapittel om
gangen, og velger derfor å branche ut kapittel 2 i en egen branch.

Lag en branch som heter `kapittel_2`, bytt til denne, og commit *ditt_navn-2*.


Oppgave 5
---------
Du får lyst til å legg til et bilde i kapittel 1.

Bytt tilbake til kapittel 1, i form av `master`-branchen.

Finn et bilde på Internett, og kopier inn i working directory, og legg det til
i index.

Akkurat idet du skal til å commite, får du en epost fra sjefen din om at
kopibeskyttede bilder ikke har noe å gjøre i rapporter.

Fjern bildet fra indeksen igjen.


Oppgave 6
---------
Du ble litt irritert av å måtte fjerne det fine bildet du fant, og bestemmer
deg derfor for å skrive litt videre på *ditt_navn-1*::

  Mauris sit amet ipsum erat, nec ultrices felis. Donec scelerisque faucibus
  orci quis dignissim. Nullam lacinia consequat sapien ut commodo. Etiam velit
  elit, cursus vel tempor eget, venenatis et urna.

Lagre filen.

Etter å ha tenkt deg litt om, skjønner du at du kanskje ikke var i riktig
sinnsstemning da du skrev forrige avsnitt, og bestemmer deg for å forkaste
endringene.

Forkast endringene ved å hente ut filens nåværende tilstand i repositoryet.


Oppgave 7
---------
Sjefen din ringer deg, og forteller at din kollega (personen ved siden av deg)
har jobbet på en annen del av samme rapport.
Heldigvis har din kollega har også lagret arbeidet sitt på Github.

Dere setter dere sammen, og bestemmer dere for å slå i sammen repositoryene
deres til ett felles ett.

Legg til din kollegas repo som en remote, og merge inn endringer fra denne, og
push tilbake til ditt prosjekt på Github.


Oppgave 8
---------
Utforsk samarbeidsmuligheter ved å dele et prosjekt på Github.

  1. Hva er **pull requests**?
  2. Kan **issues** eller **wiki** brukes til noe fornuftig?
