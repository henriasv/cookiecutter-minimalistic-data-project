# cookiecutter-minimalistic-data-project 

Denne filstrukturen er laget for å passe i HON2200 - Data-drevne prosjekter. Den er en nedstrippet variant av cookiecutter-data-science. Målet er å ha med litt mindre enn dere trenger, slik at det ikke ligger en masse forvirrende filer rundt og flyter. 

Filstrukturen er som følger:

``` 
my_project
    │ 
    ├── data        <- Her legger vi data som skal brukes
    │               i prosjektet. Om det er lite data kan
    │               vi legge det på Github, men om det er
    │               mye kan vi kun lagre det lokalt.       
    │
    ├── notebooks   <- Her legger vi notebooks som vi bruker 
    │               i utforskning av data. Bruk navnekonvensjon 
    │               med tall-initialer-beskrivelse.ipynb, eks. 
    │               002-has-utforske-iris-data.ipynb
    │    
    ├── report      <- Her skriver vi den ferdige rapporten som en jupyter-book 
    │               (nettside som autogenereres fra jupyter notebooks). 
    │ 
    ├── my_module   <- Her legger vi større deler kode som ikke passer inn i notebooks. 
    │               En god måte å jobbe på er å prøve seg fram 
    │               i en notebook, men når analysen blir klar, 
    │               legges den i en egen funksjon eller klasse og 
    │               importeres i notebook'en.
    │               Navner på denne trenger ikke være "my_module". 
    │
    ├── setup.py    <- Spesiell fil som lar oss installere "my_module" med "pip install ."
    │
    └── requirements.txt <- Fil som lister opp hvilke python-pakker vi trenger i prosjektet. 


```

Du kan lage deg en mappe med denne filstrukturen ved å skrive `cookiecutter https://github.com/henriasv/cookiecutter-minimalistic-data-project` i terminalen, og følge instruksjonene. 

Det er mer informasjon om hvordan å bruke denne filstrukturen på nettsidene til HON2200. 
