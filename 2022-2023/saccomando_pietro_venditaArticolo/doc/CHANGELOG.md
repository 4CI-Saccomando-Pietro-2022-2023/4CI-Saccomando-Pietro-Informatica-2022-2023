# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0] 2022-11-17
## Added
Creo le classi Articolo e VenditaArticolo, e il programma ApplicazioneArticolo.

Classe Articolo
Method                Visibility                Purpose
setNome               public                    Da un valore alla variabile di istanza nome.
getNome               public                    Resistuisce il valore della variabile di istanza nome.
setPrezzo             public                    Da un valore alla variabile di istanza prezzo.
getPrezzo             public                    Resistuisce il valore della variabile di istanza prezzo.
setQuantita           public                    Da un valore alla variabile di istanza quantita che descrive quanti pezzi comprare.
getQuantita           public                    Resistuisce il valore della variabile di istanza quantita.

Classe ApplicazioneArticolo
Method                Visibility                Purpose
start                 public                    Serve per chiamare i metodi che utilizza il programma.
describeProgram       public                    Serve per dare una breve descrizione del programma.
displayOut            public                    Serve per visualizzare a schermo i dati presi in ingresso.
getInput              public                    Serve per prendere in ingresso i dati.
