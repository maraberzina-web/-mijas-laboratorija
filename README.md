# Ķīmijas laboratorija
## Projekta ideja

Ķīmijas laboratorijas uzskaites sistēma paredzēta skolas
laboratorijā pieejamo vielu un inventāra apskatei.

## Problēma

Ja vielu un inventāra uzskaite ir tikai papīra sarakstos,
vajadzīgās informācijas atrašana var aizņemt laiku.
Šo problēmu var risināt ar pārskatāmu elektronisku sarakstu.

## Projekta mērķis

Izveidot mājaslapu, kurā var apskatīt laboratorijas vielas
un inventāru, meklēt pēc nosaukuma un atlasīt ierakstus.

## Programmas prasības

- Parādīt vielu un inventāra sarakstu.
- Meklēt ierakstus pēc nosaukuma.
- Atsevišķi parādīt vielas vai inventāru.
- Ielādēt datus no JSON failiem.
- Parādīt paziņojumu, ja nekas nav atrasts.
## Izstrādes metode

Izvēlējos iteratīvo izstrādes metodi. Tas nozīmē, ka
programmu veidoju pa daļām un pēc katras daļas pārbaudu,
vai tā darbojas. Šī metode ir piemērota, jo kļūdas var
pamanīt un izlabot pakāpeniski.

## Darba plāns

1. Noteikt problēmu un programmas mērķi.
2. Noskaidrot lietotāju vajadzības.
3. Izveidot sākumlapas un datu tabulas izskatu.
4. Pievienot vielu un inventāra datus JSON failos.
5. Izveidot datu ielādi, meklēšanu un filtrus.
6. Pārbaudīt programmu un izlabot atrastās kļūdas.
7. Sagatavot lietošanas instrukciju.

## Izmantotās tehnoloģijas

- HTML — lapu saturs un uzbūve.
- CSS — krāsas, izkārtojums un pielāgošana ekrāna izmēram.
- JavaScript — datu ielāde, meklēšana un filtrēšana.
- JSON — vielu un inventāra datu glabāšana.
- GitHub — projekta failu un izmaiņu glabāšana.
## Lietošanas instrukcija

1. Atver projekta mājaslapu.
2. Sākumlapā nospied “Piekļūt publiskiem datiem”.
3. Tabulā apskati vielu un inventāra sarakstu.
4. Meklēšanas laukā ieraksti vajadzīgo nosaukumu vai tā daļu.
5. Nospied “Rādīt vielas”, lai apskatītu tikai vielas.
6. Nospied “Rādīt inventāru”, lai apskatītu tikai inventāru.
7. Lai atkal redzētu visus ierakstus, iztīri meklēšanas
   lauku un nospied “Rādīt visu”.
8. Lai atgrieztos sākumlapā, nospied
   “Atpakaļ uz sākumlapu”.

## Autore

Vārds, uzvārds: [Māra Bērziņa]
Klase: 11.
## Testēšana

Pārbaudīju mājaslapas darbību.

| Pārbaude | Rezultāts |
| --- | --- |
| Atvērt publisko datubāzi | Vielu un inventāra tabula parādās. |
| Meklēšanā ierakstīt “svari” | Parādās divi svaru ieraksti. |
| Izvēlēties “Rādīt vielas” | Tabulā redzamas tikai vielas. |
| Izvēlēties “Rādīt inventāru” | Tabulā redzami pieci inventāra ieraksti. |
| Meklēšanā ierakstīt “zzzz” | Parādās paziņojums, ka neviens ieraksts nav atrasts. |
## Risinājumu salīdzinājums

Salīdzinot iespējamos risinājumus, papīra saraksts ir
vienkāršs, bet tajā vajadzīgais ieraksts jāmeklē manuāli.
Excel tabulā var meklēt un filtrēt datus, tomēr šajā
projektā izvēlēta mājaslapa, lai izveidotu vienkāršu
saskarni ar meklēšanas lauku un atlases pogām.

Mērķauditorija ir skolēni un ķīmijas skolotāji.
Mājaslapas iespējamais ieguvums ir ātrāka informācijas
atrašana par laboratorijas vielām un inventāru.
Lietotāju pieprasījums pagaidām nav pārbaudīts aptaujā.

Izskatam izvēlēts balts fons un zilas pogas. Informācija
sakārtota tabulā, lai ierakstus būtu viegli salīdzināt.

## Tehniskā specifikācija

### Lapas un faili

- index.html — sākumlapa ar saitēm uz pārējām lapām.
- forma2.html — pieslēgšanās lapa.
- forma3.html — publiskais vielu un inventāra saraksts.
- inventars.json — inventāra dati.
- vielas.json — vielu dati.
- README.md — projekta apraksts un lietošanas instrukcija.

### Datu struktūra

Inventāra ierakstā ir ID, nosaukums, tips, apakštips,
skaits un komentāri. Vielu attēlošanai programma paredz
arī daudzumu un mērvienību.

### Programmas darbība

Atverot publisko datubāzi, JavaScript ielādē abus JSON
failus un izveido tabulas rindas. Meklēšana atlasa
ierakstus pēc nosaukuma, neņemot vērā lielos un mazos
burtus. Filtri ļauj apskatīt visus ierakstus, tikai
vielas vai tikai inventāru.

Ja nekas nav atrasts, parādās paziņojums. Ja datu
ielāde neizdodas, programma parāda kļūdas paziņojumu.

### Darbināšana

Programmu lieto interneta pārlūkā, atverot GitHub Pages
mājaslapu. JavaScript jābūt ieslēgtam.

### Ierobežojumi

Šajā versijā publiskajā lapā datus var apskatīt,
meklēt un filtrēt. Datu papildināšana notiek, rediģējot
JSON failus. Pieslēgšanās funkcija nav iekļauta
dokumentētajos testos. Pogai “Ziņot par kļūdu”
vēl nav pievienota darbība.

## Darba organizēšana

Projektu veicu individuāli. Par lapu izveidi, datu
pievienošanu, pārbaudīšanu un dokumentāciju atbildu pati.

## Turpmākie uzlabojumi

Turpmāk varētu pievienot datu rediģēšanu mājaslapā,
lietotāju autentifikāciju un kļūdu ziņošanas iespēju.
