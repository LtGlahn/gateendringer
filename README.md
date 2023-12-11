# gateendringer
Python-kode for å generere endringsett med gatenavn. Rekonstruert fra arkiv fra Kartverket. Ikke helt stø på 
kodens funksjon, jobber med å trenge inn i hva som skjer versus hva som egentlig burde skje. 

Overordnet så skal koden sammenligne data fra objekttypen GATE fra NVDB api LES med Kartverkets manus og finne 
hva som bør oppdateres (korrigeres eller registreres?). Sluttresultatet er innsending av endringsett til NVDB api  SKRIV.  

Via angitt YAML konfigurasjonsfil (p.t. `config_prod_v3.yml` ) så konfigurees både generiske python-funksjoner (f.eks logging) og en del variabler som brukes av scriptet `crawl_V2.py`, så som mappenavn, filnavn, lenke til NVDB api og en del andre ting. 

