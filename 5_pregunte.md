# Respostes de les preguntes

## 5. XML o Markdown?

### a) Quina opció és més ràpida d'escriure i més fàcil de llegir?

Per mi la B, la de Markdown. És molt més curta, només has d'escriure un guionet i els claudàtors, i no cal repetir etiquetes com `<tasca>` o `<descripcio>` cada vegada. Si obres el fitxer amb el Bloc de notes o amb VS Code sense previsualització s'entén bé què hi ha. L'XML en canvi té moltes etiquetes i costa més de llegir, tot i que està més ben organitzat.

### b) Per què un sistema informàtic preferiria XML?

Perquè l'XML està fet per a màquines. Cada dada té la seva etiqueta, tot està en una jerarquia i pots afegir atributs com `estat="completada"`. Així un programa pot llegir el fitxer i comprovar que està ben fet, per exemple amb un XSD o una DTD, i agafar les dades sense problemes. Markdown serveix més per donar format a un text i no té regles tan estrictes, així que a un programa li costaria més treballar-hi.

## 6. Per què Markdown és l'estàndard dels README.md?

Penso que és perquè és molt fàcil d'escriure i de llegir. GitHub el mostra directament a la pàgina del repositori amb els títols, les llistes i els blocs de codi ja formatats, i no has de descarregar res. A més és text pla, així que el pots editar amb qualsevol editor i Git et deixa veure bé què ha canviat. Per a un README no necessites res més complicat.

## 7. Quins avantatges té un README.md a la portada del repositori?

Quan busco una llibreria a GitHub, el primer que miro és el README. Si està ben fet, en un parell de minuts ja sé què fa, com s'instal·la i com s'utilitza. Això és més còmode que haver de descarregar un PDF o obrir un XML.

Els avantatges que veig són que el pots veure directament a GitHub sense instal·lar res, que amb els títols i les llistes es llegeix més ràpid, i que els exemples de codi els pots copiar directament. També, com que és text, Git guarda l'historial i es poden veure els canvis. I si el README està bé, et dona més confiança per decidir si la llibreria et serveix.

Un PDF pesa més, no el pots editar fàcilment i al mòbil es veu malament. Un XML ple d'etiquetes és pesat de llegir per a una persona.

## 8. XML o Markdown en cada cas?

Cas 1 (apunts i guia d'instal·lació): Markdown. És text per a persones i amb Markdown l'escric ràpid i el puc llegir sense renderitzar. També el puc pujar a GitHub i si després he de canviar alguna cosa és fàcil.

Cas 2 (configuració de l'aplicació): XML. Les dades les ha de llegir un programa, així que necessito una estructura clara amb etiquetes que diguin què és cada cosa, i si pot ser un esquema per comprovar que el fitxer està bé. Amb Markdown no es podria fer això.
