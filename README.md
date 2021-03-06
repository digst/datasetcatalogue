# FDA Datasætkataloget

FDA Datasætkataloget er en løsning der tilbyder et fællesoffentligt katalog over datasæt samt understøttelse af direktivet om åbne data og den offentlige sektors informationer (PSI-direktivet). 

## FDA Datasætkataloget 1.0

FDA Datasætkatalogets primære applikationskomponent udgøres i version 1.0 af en open-source dataportalplatform, CKAN, som i sin standardimplementering med en tilhørende CKAN-database udstiller en brugergrænseflade (CKAN GUI) samt et programmeringsinterface (CKAN API) (se: https://ckan.org/). Brugergrænsefladen er også tilpasset dansk anvendelse og løsningen integrerer med NemLog-in ifm. brugerrettighedsstyring.

Standardudgaven er i den danske løsning udvidet med en række såkaldte extensions med plugins, som tilføjer ny funktionalitet til løsningen, fx. en række høstere der gør det muligt at hente metadatabeskrivelser fra eksempelvis andre CKAN-instanser, geodataportaler (ISO19139) eller fra et DCAT-AP-kompatible datadump. Den danske tilpasning er også implementeret via en custom extension. Yderligere extensions som dog ikke er illustereret herunder er hentet fra https://extensions.ckan.org/.

Datasætkataloget understøtter via udvidelsen ckanext-dcat DCAT-AP. DCAT-AP er EU-Kommissionens anvendelsesprofil til beskrivelse af datasæt i datakataloger, og specifikationen har til formål at standardisere og etablere sammenhæng mellem dataportaler i de europæiske medlemslande. Udvidelsen ckanext-dcat understøtter pt. DCAT-AP 1.1. DCAT-AP 1.1 er også blevet profileret til anvendelse i dansk administrativ kontekst i DCAT-AP-DK 1.1, som indfører enkelte danske tilføjelser og begrænsninger.

### Datamodellen DCAT-AP-DK 1.1 (UDKAST)
DCAT-AP-DK er en anvendelsesprofil til beskrivelse af datasæt i det fællesoffentlige datasætkatalog.
Se: https://github.com/digst/DCAT-AP-DK/

### Overordnet arkitekturbeskrivelse  (UDKAST)
![Overordnet arkitektur](https://github.com/digst/datasetcatalogue/blob/master/FDADatasætkataloget-v1.1(ArchiMate).png "ArchiMate Diagram")

### Sammenhænge med andre kataloger (UDKAST)
![Sammenhænge](https://github.com/digst/datasetcatalogue/blob/master/FDADatasætkataloget-v1.1sammenhænge(ArchiMate).png "ArchiMate Diagram")



