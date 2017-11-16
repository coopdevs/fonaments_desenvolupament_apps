# Notes de la presentació

## Com funcionen les apps a internet?

Metàfora de la ceba. Que es quedin amb aquesta imatge al cap.

Preguntar a l'audiència: Algú que hagi programat algun cop o algú que tingui
estudis tècnics?

## Client/Servidor

Model d'aplicacions distribuides que particiona una tasca entre dues parts.
Comunicació a través de la xarxa.

Base de moltes tecnologies que fem servir durant el dia.

## Client/Servidor

Servidor arrenca un procés de vida indefinida escoltant en un procés

## Frontend

Fins ara hem vist el model. Concepte aplicat a apps web.

En aplicacions web a grans trets el frontend està a la banda de client,


## Frontend

El "codi" frontend s'executa al navegador. Podem associar al que apareix al
navegador.

Botons, diàlegs, camps de text, animacions, etc.

Fer menció de l'h2 i de ser estàtic Fer menció de les crides a funcions show,
hide i de ser dinàmic


## Backend

Tenim imatge mental de data center. Molts ordinadors sense pantalla.

Business Logic o Domain Logic no exclusiu de backend en segons quines
arquitectures, però backend sempre en té. Ara ho veurem.

Les dades també s'emmagatzemen al darrere. Base de dades

## Aplicació

Implementa la lògica de negoci. Traducció a codi del que hem definit amb
diagrames, requeriments, etc.

Web app clàssica retorna HTML, CSS i JS

Remarcar `valid?` i `find_by_id`. App interacciona amb les dades.

## Base de dades

Sense dades no hi ha app. En la gran majoria dels casos l'app haurà de persistir
dades.

Aquestes quatre operacions s'anomenen CRUD. No es limita a DB.

## I els mòbils què?

Fem comparació respecte a web app clàssica

## App Nativa

Concepte natiu fa referència a tecnologia del fabricant: Android, iPhone, etc.

Tecnologies multiplataforma fan ús de tecnologies web d'ampli ús i que no
depenen dels fabricants

## API

Application Programming Interface. Comparar amb interfície d'usuari. Implementa
la mateixa lògica de negoci.

Dades per a que les processi el frontend-client. Elements d'una llista.

Ensenyar exemple a https://jsonplaceholder.typicode.com/posts

## Com es fa tot això?

Preguntar a l'audiència

## No reinventis la roda

Quelcom ja inventat, que no té errors coneguts de funcionament, i un intent de
reinvent-ho no tindria sentit no hi afegiria valor. Malgastar el temps mentre et
podries centrar en coses que aportin més valor.

Moltes vegades no és conscient.

## Reusant codi

Metàfora que ens porta a les nostres cebes. Per això incideix-ho tant en les
cebes perquè vull que reuseu.

A quina capa de la ceba desenvolupem.

Llibreria: implementa funcionalitats espcífiques. Nivell de granularitat
variable. Lligat a un domini o una utilitat. Exemple de llibreries de xarxa.
Ensenyar Gemfile.

Framework: conjunt de llibreries per construir quelcom. Molts components. No
lligat a un domini.  Implementa algun disseny de sofware. Has d'inserir el teu
codi, lligat a un domini, per veure'l funcionar. Parlar de Rails.

## Git

Per poder reusar codi i fer codi de manera col·laborativa cal emmagatzemar-lo
fora del nostre ordinador i fer-lo accessible.

Gestió de canvis en arxius i directoris en el temps.

Commit: foto
Branca: Línia de temps indepent de la central. Conjunt de commits. Sempre hi ha
una principal.
Repositori: Estructura de les metadades del projecte usades per git. `.git/`

## Github

Social coding: Vell moto de github. Fer codi amb altres té una gran dimensió
social que s'amplia en el cas de l'open source. Com més open source faig, més
descobreixo aquest dimensió.

## Anatomia

Pull Request. Demanar ajuntar la branca que t'havies fet per
implementar/arreglar un error.

Merge: ajuntar aquestes dues branques.
