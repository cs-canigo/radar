# Radar CTTI
fitxers de control per al radar d'arquitectura

## Ús del fitxer:
Per a publicar el radar cal editar el fitxer a /data/radar.csv i modificar les columnes del fitxer seguint les següents regles:

### Nom ###
El nom de l'element.

### Anella ###
Especifica en quina anella s'ha de pintar l'element
- Adoptar, aquells elements que pensem que cal fer servir de forma immediata
- Provar, cal provar per acabar de tenir experiència amb el producte
- Avaluar, informar-se sobre l'element i començar a veure llocs on aplicar-lo
- Precaució, elements que han demostrat no ser tant eficients com s'esperava i que introdueixen deute tècnic a les aplicacions que els fan servir. 

Cal seguir estrictament l'ordre Adoptar/Provar/Avaluar/Precaució per a incloure els elements. Aquest ordre es reflecteix directament sobre el radar. 

### Quadrant ###
Són els quatre quadrants:
- Llenguatges i Entorns de Treball
- Eines
- Tècniques
- Plataformes

### esNou ###
TRUE si és nou i llavors apareix amb un triangle. FALSE si no ho és i surt com un cercle.

### Descripció ###
Aquesta és la descripció que surt en prèmer un dels elements del radar. Es pot fer servir html bàsic com el tag <strong>strong per enfatitzar paraules o frases</strong> i insertar <a href='http://canigo.ctti.gencat.cat'> enllaços a documentació i material de referència</a>.

Cal tenir en compte que la descripció ha d'anar delimitada per cometes dobles i que els enllaços web han d'anar delimitats per cometes simples.
