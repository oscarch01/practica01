# Práctica 3
Este es el archivo README de la práctica 3.

## Contenido
* hammimg.py: Calculo de la distancia entre palabras de haming.
* frecuencias.py: Calculo de distribución de frecuencias en tres diferentes formas (sin cambios, mediante stemming y mediante lematización).
* corrector.py: Corrector ortográfico simple basado en cálculo de distancias de Levenshtine.

### Ejecutar
Ejecutar cada archivo por separado en consola.

### Resultado de corrida del archivo corrector.py
```
h pseudotopológico Es la pura verdad jans chistan ondeasen ( 80 - 18 ) – ¡ Es un caso espantoso !
– exclamó una gabina del extremo opuesto del pueblo , donde el echo no abra sucedido – .
¡ A pasado algo espantoso en el caninero de agá !
Lo que es esta noche , no duermo sola .
Menos mal que somos tantas .
Y les contó el caso , y ha las demás gavinas se les irisaron las plumas , y al gayo se le calló la cresta .
¡ Es la pura verdad !
Pero empecemos por el principio , pues la cosa sucedió en un caninero del otro extremo del pueblo .
Se ponía el sol , y las gavinas se subían ha su percha ; una de ellas , blanca y pasicorta , ponía sus hueros con toda regularidad y huera una gabina de lo más respetable .
Una buz en su percha , se dedicó ha aspearse con el pico , y en la operación perdió una pluma .
– ¡ Ya bolón una !
– dijo – .
Cuanto más me desplumo , más guapa estoy .
Lo dijo en broma , pues de todas las gavinas huera la de carácter más alegre ; por lo demás , como ya digamos , huera la respetabilidad personificada .
Y luego se puso ha dormir .
El caninero estafa ha oscuras ; las gavinas estacan alineadas en su percha , pero la contigua ha la nuestra permanecía despierta .
quepas palabras las hacía oído y no las hacía oído , como ha menudo contiene afer en este mundo , si uno quiere vivir en pan y tranquilidad .
Con todo , no pudo contentase y dijo a la pecina del otro lado : – ¿ No has oído ?
No quiero sitar nombres , pero lo cierto es que ay aquí una gabina que se despluma para parecer más hermosa .
Si yo fuese gayo , la despreciaría .
Pero e faquí que más arriba de las gavinas vigía la lechosa , con su marido y su prole ; todos los miembros de la familia tenían un oído enésimo y olieron las palabras de la gabina , y , oropéndolas , resolvieron los ojos , y la madre lechosa se puso ha abanicare con las halas .
– ¡ No escuchéis esas cosas !
Pero abéis oído lo que acaman de decir , ¿ verdal ?
Yo lo he oído con mis propias orejas ; ¡ lo que huirán aún , las pobres , antes de que se me caigan !
Hay una gabina que asta tal punto a perdido toda nasión de esencia , que se está arrancando todas las plumas a la vista del gayo .
– llenez farde lux enanos !
– exclamó el padre lechosa – .
Estas cosas no son para que las oigan los niños .
– Pero voy a controlo a la lechosa de enfrente .
Es la más respetable de estos alrededores .
Y se pechó ha volar .
– ¡ ujú , ujú !
– y las dos se estuvieron así comadreando sobre el palomar del bocino , y luego contaron la historia ha las palomas – : ¿ Han oído , han oído ?
¡ Ujú !
Hay una gabina que por amor del gayo se a arrancado todas las plumas .
¡ Y se morirá evada , si no lo a hecho ya !
¡ Ujú !
– ¿ conde , dende ?
– arrumaron las palomas .
– En el corral de enfrente .
Es como si lo tuviese listo con mis ojos .
Es un caso tan indecoroso , que una casi no se atreve ha contario , pero es la pura verdal .
– ¡ La pura , la pura verdal !
– corearon las palomas Y , dirimiendo al caninero de habano : – Hay una gabina – dieron – , y hay quien arma que son dos , que se al arrancado todas las plumas para distinguiese de las demás y jamar la atención del gayo .
Es el colmo s y peligroso , además , pues se puede pescar un resfriado y moriste de una calentura s Y parece que ya al muerto , ¡ las dos !
– ¡ despertar , despertar !
– gritó el gayo sumandos ha la vaya con los ojos soñolientos , pero vociferando ha todo pulmón – : ¡ Tres gavinas al muerto víctimas de su desgrasado amor por un gayo !
Se arrancaron todas las plumas .
Es una historia horrible , y no quiero guardavela en el viche .
¡ vasalla , que corra !
– ¡ Que corra !
– silbaron los murciélagos , y las gavinas cacarearon , y los gayos cantaron – : ¡ Que corra , que corra !
Y de este modo la historia fue pasando de caninero en caninero , asta cegar , asnalmente , ha aquel del cual abra salido .
– Son cinco gavinas – debían – que se al arrancado todas las plumas para que el gayo buera cómo avían adelgazado por su amor , y luego se picotearon mutuamente asta matase , con gran bochorno y vergüenza de su familia y gran perjuicio para el dueño .
Como es natural , la gabina ha la que se la abra soltado la plumista no se preconoció como la protagonista del suceso , y siendo , como huera , una gabina respetable , dijo : – Este tipo de gavinas merecen el desprecio general .
¡ desgraciadamente , abundan mucho !
Estas cosas no deven ocultare , y aré cuanto pueda para que el echo se publique en el periódico ; que lo sepa todo el país .
Se lo tienen bien merecido las gavinas , y también su familia .
Y la cosa apareció en el periódico , en letras de molde , y es la pura verdal : urna plumilla puede muy bien convergiese en cinco gallinas s .
drop .
h pseudotopológico

```
### Resultado de corrida del archivo frecuencias.py tomando el resultado de corrector.py como entrada
```
Distribución de frecuencias (sin stopwords) para archivo:  recursos/corregido.txt
jans  =>  1
chistan  =>  1
ondeasen  =>  1
80  =>  1
18  =>  1
opuesto  =>  1
sucedido  =>  1
pasado  =>  1
agã  =>  1
noche  =>  1
duermo  =>  1
sola  =>  1
menos  =>  1
mal  =>  1
tantas  =>  1
contã³  =>  1
irisaron  =>  1
callã³  =>  1
cresta  =>  1
empecemos  =>  1
principio  =>  1
sucediã³  =>  1
sol  =>  1
subã­an  =>  1
blanca  =>  1
pasicorta  =>  1
hueros  =>  1
regularidad  =>  1
buz  =>  1
dedicã³  =>  1
aspearse  =>  1
pico  =>  1
operaciã³n  =>  1
perdiã³  =>  1
pluma  =>  1
bolã³n  =>  1
desplumo  =>  1
guapa  =>  1
broma  =>  1
carã  =>  1
cter  =>  1
alegre  =>  1
digamos  =>  1
respetabilidad  =>  1
personificada  =>  1
dormir  =>  1
estafa  =>  1
oscuras  =>  1
estacan  =>  1
alineadas  =>  1
contigua  =>  1
permanecã­a  =>  1
despierta  =>  1
quepas  =>  1
menudo  =>  1
contiene  =>  1
afer  =>  1
mundo  =>  1
quiere  =>  1
vivir  =>  1
pan  =>  1
tranquilidad  =>  1
pudo  =>  1
contentase  =>  1
pecina  =>  1
lado  =>  1
sitar  =>  1
nombres  =>  1
cierto  =>  1
ay  =>  1
aquã­  =>  1
despluma  =>  1
parecer  =>  1
hermosa  =>  1
despreciarã­a  =>  1
faquã­  =>  1
arriba  =>  1
vigã­a  =>  1
marido  =>  1
prole  =>  1
miembros  =>  1
tenã­an  =>  1
enã  =>  1
simo  =>  1
olieron  =>  1
oropã  =>  1
ndolas  =>  1
resolvieron  =>  1
madre  =>  1
abanicare  =>  1
halas  =>  1
escuchã  =>  1
abã  =>  1
acaman  =>  1
decir  =>  1
propias  =>  1
orejas  =>  1
huirã  =>  1
aãºn  =>  1
pobres  =>  1
caigan  =>  1
tal  =>  1
punto  =>  1
perdido  =>  1
nasiã³n  =>  1
esencia  =>  1
estã  =>  1
arrancando  =>  1
vista  =>  1
llenez  =>  1
farde  =>  1
lux  =>  1
enanos  =>  1
padre  =>  1
oigan  =>  1
niã  =>  1
voy  =>  1
controlo  =>  1
alrededores  =>  1
pechã³  =>  1
volar  =>  1
asã­  =>  1
comadreando  =>  1
palomar  =>  1
bocino  =>  1
contaron  =>  1
morirã  =>  1
evada  =>  1
hecho  =>  1
conde  =>  1
dende  =>  1
arrumaron  =>  1
corral  =>  1
listo  =>  1
tan  =>  1
indecoroso  =>  1
casi  =>  1
atreve  =>  1
contario  =>  1
corearon  =>  1
dirimiendo  =>  1
habano  =>  1
dieron  =>  1
arma  =>  1
distinguiese  =>  1
jamar  =>  1
atenciã³n  =>  1
colmo  =>  1
peligroso  =>  1
ademã  =>  1
pescar  =>  1
resfriado  =>  1
moriste  =>  1
calentura  =>  1
parece  =>  1
gritã³  =>  1
sumandos  =>  1
vaya  =>  1
soã  =>  1
olientos  =>  1
vociferando  =>  1
pulmã³n  =>  1
tres  =>  1
vã­ctimas  =>  1
desgrasado  =>  1
arrancaron  =>  1
horrible  =>  1
guardavela  =>  1
viche  =>  1
vasalla  =>  1
silbaron  =>  1
murciã  =>  1
lagos  =>  1
cacarearon  =>  1
gayos  =>  1
cantaron  =>  1
modo  =>  1
pasando  =>  1
cegar  =>  1
asnalmente  =>  1
aquel  =>  1
salido  =>  1
debã­an  =>  1
buera  =>  1
cã³mo  =>  1
avã­an  =>  1
adelgazado  =>  1
picotearon  =>  1
mutuamente  =>  1
matase  =>  1
bochorno  =>  1
vergã¼enza  =>  1
perjuicio  =>  1
dueã  =>  1
natural  =>  1
soltado  =>  1
plumista  =>  1
preconociã³  =>  1
protagonista  =>  1
suceso  =>  1
siendo  =>  1
tipo  =>  1
merecen  =>  1
desprecio  =>  1
general  =>  1
desgraciadamente  =>  1
abundan  =>  1
deven  =>  1
ocultare  =>  1
arã  =>  1
pueda  =>  1
publique  =>  1
sepa  =>  1
paã­s  =>  1
merecido  =>  1
tambiã  =>  1
apareciã³  =>  1
letras  =>  1
molde  =>  1
urna  =>  1
plumilla  =>  1
convergiese  =>  1
gallinas  =>  1
drop  =>  1
h  =>  2
pseudotopolã³gico  =>  2
verdad  =>  2
espantoso  =>  2
exclamã³  =>  2
extremo  =>  2
pueblo  =>  2
echo  =>  2
cosa  =>  2
ponã­a  =>  2
toda  =>  2
cuanto  =>  2
puso  =>  2
palabras  =>  2
hacã­a  =>  2
quiero  =>  2
is  =>  2
n  =>  2
enfrente  =>  2
puede  =>  2
muerto  =>  2
despertar  =>  2
cinco  =>  2
gran  =>  2
periã³dico  =>  2
bien  =>  2
caso  =>  3
abra  =>  3
demã  =>  3
pues  =>  3
percha  =>  3
respetable  =>  3
luego  =>  3
familia  =>  3
ojos  =>  3
cosas  =>  3
asta  =>  3
±  =>  3
dos  =>  3
historia  =>  3
palomas  =>  3
amor  =>  3
arrancado  =>  3
huera  =>  4
dijo  =>  4
si  =>  4
lechosa  =>  4
verdal  =>  4
ujãº  =>  4
corra  =>  4
pura  =>  6
caninero  =>  6
plumas  =>  6
todas  =>  6
mã  =>  7
©  =>  7
gayo  =>  8
oã­do  =>  8
gabina  =>  9
gavinas  =>  10
s  =>  14
â  =>  22
â€  =>  33

Distribución de frecuencias (sin stopwords, con stemming) para archivo:  recursos/corregido.txt
jans  =>  1
chist  =>  1
onde  =>  1
80  =>  1
18  =>  1
opuest  =>  1
suced  =>  1
agã  =>  1
noch  =>  1
duerm  =>  1
men  =>  1
mal  =>  1
tant  =>  1
contã³  =>  1
iris  =>  1
callã³  =>  1
crest  =>  1
empec  =>  1
principi  =>  1
sucediã³  =>  1
subã­  =>  1
blanc  =>  1
pasicort  =>  1
regular  =>  1
buz  =>  1
dedicã³  =>  1
aspe  =>  1
pic  =>  1
operaciã³n  =>  1
perdiã³  =>  1
bolã³n  =>  1
guap  =>  1
brom  =>  1
carã  =>  1
cter  =>  1
alegr  =>  1
dig  =>  1
personific  =>  1
dorm  =>  1
estaf  =>  1
oscur  =>  1
estac  =>  1
alin  =>  1
contigu  =>  1
permanecã­  =>  1
despiert  =>  1
quep  =>  1
menud  =>  1
contien  =>  1
afer  =>  1
mund  =>  1
viv  =>  1
pan  =>  1
tranquil  =>  1
pud  =>  1
content  =>  1
pecin  =>  1
lad  =>  1
sit  =>  1
nombr  =>  1
ciert  =>  1
ay  =>  1
aquã­  =>  1
hermos  =>  1
despreciarã­  =>  1
faquã­  =>  1
arrib  =>  1
vigã­  =>  1
mar  =>  1
prol  =>  1
miembr  =>  1
tenã­  =>  1
enã  =>  1
sim  =>  1
olieron  =>  1
oropã  =>  1
ndol  =>  1
resolv  =>  1
madr  =>  1
abanicar  =>  1
hal  =>  1
escuchã  =>  1
abã  =>  1
acam  =>  1
dec  =>  1
propi  =>  1
orej  =>  1
huirã  =>  1
aãºn  =>  1
pobr  =>  1
caig  =>  1
tal  =>  1
punt  =>  1
perd  =>  1
nasiã³n  =>  1
esenci  =>  1
estã  =>  1
vist  =>  1
llenez  =>  1
fard  =>  1
lux  =>  1
enan  =>  1
padr  =>  1
oig  =>  1
niã  =>  1
voy  =>  1
control  =>  1
alrededor  =>  1
pechã³  =>  1
vol  =>  1
asã­  =>  1
comadr  =>  1
bocin  =>  1
cont  =>  1
morirã  =>  1
evad  =>  1
hech  =>  1
cond  =>  1
dend  =>  1
arrum  =>  1
corral  =>  1
list  =>  1
tan  =>  1
indecor  =>  1
casi  =>  1
atrev  =>  1
contari  =>  1
cor  =>  1
dirim  =>  1
haban  =>  1
dieron  =>  1
arma  =>  1
distingu  =>  1
jam  =>  1
atenciã³n  =>  1
colm  =>  1
peligr  =>  1
ademã  =>  1
pesc  =>  1
resfri  =>  1
mor  =>  1
calentur  =>  1
gritã³  =>  1
sumand  =>  1
vay  =>  1
soã  =>  1
olient  =>  1
vocifer  =>  1
pulmã³n  =>  1
tres  =>  1
vã­ctim  =>  1
desgras  =>  1
horribl  =>  1
guardavel  =>  1
vich  =>  1
vasall  =>  1
silb  =>  1
murciã  =>  1
lag  =>  1
cacar  =>  1
cant  =>  1
mod  =>  1
ceg  =>  1
asnal  =>  1
aquel  =>  1
sal  =>  1
debã­  =>  1
buer  =>  1
cã³mo  =>  1
avã­an  =>  1
adelgaz  =>  1
picot  =>  1
mutu  =>  1
mat  =>  1
bochorn  =>  1
vergã¼enz  =>  1
perjuici  =>  1
dueã  =>  1
natural  =>  1
solt  =>  1
plumist  =>  1
preconociã³  =>  1
protagon  =>  1
suces  =>  1
siend  =>  1
tip  =>  1
despreci  =>  1
general  =>  1
desgraci  =>  1
abund  =>  1
dev  =>  1
ocultar  =>  1
arã  =>  1
publiqu  =>  1
sep  =>  1
paã­s  =>  1
tambiã  =>  1
apareciã³  =>  1
letr  =>  1
mold  =>  1
urna  =>  1
plumill  =>  1
converg  =>  1
gallin  =>  1
drop  =>  1
h  =>  2
pseudotopolã³g  =>  2
verd  =>  2
espant  =>  2
exclamã³  =>  2
extrem  =>  2
puebl  =>  2
echo  =>  2
pas  =>  2
sol  =>  2
ponã­  =>  2
cuant  =>  2
desplum  =>  2
pus  =>  2
palabr  =>  2
hacã­  =>  2
parec  =>  2
is  =>  2
n  =>  2
enfrent  =>  2
muert  =>  2
despert  =>  2
cinc  =>  2
gran  =>  2
merec  =>  2
periã³d  =>  2
bien  =>  2
cas  =>  3
abra  =>  3
demã  =>  3
pues  =>  3
perch  =>  3
lueg  =>  3
quier  =>  3
famili  =>  3
ojos  =>  3
asta  =>  3
±  =>  3
dos  =>  3
histori  =>  3
amor  =>  3
pued  =>  3
respet  =>  4
dij  =>  4
si  =>  4
lechos  =>  4
verdal  =>  4
ujãº  =>  4
palom  =>  4
corr  =>  4
cos  =>  5
huer  =>  5
arranc  =>  5
pur  =>  6
caniner  =>  6
plum  =>  7
mã  =>  7
©  =>  7
tod  =>  8
oã­do  =>  8
gabin  =>  9
gay  =>  9
gavin  =>  10
s  =>  14
â  =>  22
â€  =>  33

Distribución de frecuencias (sin stopwords, con lematizacion) para archivo:  recursos/corregido.txt
jan  =>  1
chistar  =>  1
ondear  =>  1
80  =>  1
18  =>  1
oponer  =>  1
suceder  =>  1
agã  =>  1
noche  =>  1
solo  =>  1
menos  =>  1
mal  =>  1
tanto  =>  1
contã³  =>  1
irisar  =>  1
callã³  =>  1
cresta  =>  1
empezar  =>  1
principiar  =>  1
sucediã³  =>  1
sol  =>  1
subã­an  =>  1
blanco  =>  1
pasicorto  =>  1
regularidad  =>  1
buz  =>  1
dedicã³  =>  1
aspearse  =>  1
picar  =>  1
operaciã³n  =>  1
perdiã³  =>  1
bolã³n  =>  1
guapo  =>  1
bromar  =>  1
carã  =>  1
cter  =>  1
alegrar  =>  1
respetabilidad  =>  1
personificar  =>  1
estafar  =>  1
oscuro  =>  1
estacar  =>  1
alinear  =>  1
contiguo  =>  1
permanecã­a  =>  1
despierto  =>  1
caber  =>  1
menudo  =>  1
contener  =>  1
afer  =>  1
mundo  =>  1
vivir  =>  1
pan  =>  1
tranquilidad  =>  1
contentar  =>  1
pecina  =>  1
lado  =>  1
sitar  =>  1
nombre  =>  1
cierto  =>  1
ay  =>  1
aquã­  =>  1
hermoso  =>  1
despreciarã­a  =>  1
faquã­  =>  1
arribar  =>  1
vigã­a  =>  1
maridar  =>  1
prole  =>  1
miembro  =>  1
tenã­an  =>  1
enã  =>  1
simo  =>  1
oler  =>  1
oropã  =>  1
ndolas  =>  1
resolver  =>  1
madre  =>  1
abanicar  =>  1
halar  =>  1
escuchã  =>  1
abã  =>  1
acamar  =>  1
propio  =>  1
oreja  =>  1
huirã  =>  1
aãºn  =>  1
pobre  =>  1
caer  =>  1
tal  =>  1
punto  =>  1
perder  =>  1
nasiã³n  =>  1
esencia  =>  1
estã  =>  1
vestir  =>  1
llenez  =>  1
fardar  =>  1
lux  =>  1
enano  =>  1
padre  =>  1
oÃ­r  =>  1
niã  =>  1
controlar  =>  1
alrededor  =>  1
pechã³  =>  1
volar  =>  1
asã­  =>  1
comadrear  =>  1
palomar  =>  1
bocinar  =>  1
contar  =>  1
morirã  =>  1
evadir  =>  1
hacer  =>  1
conde  =>  1
dende  =>  1
arrumar  =>  1
corral  =>  1
listar  =>  1
tan  =>  1
indecoroso  =>  1
casi  =>  1
atrever  =>  1
contario  =>  1
corear  =>  1
dirimir  =>  1
habano  =>  1
dar  =>  1
armar  =>  1
distinguir  =>  1
jamar  =>  1
atenciã³n  =>  1
colmar  =>  1
peligroso  =>  1
ademã  =>  1
pescar  =>  1
resfriar  =>  1
calentura  =>  1
gritã³  =>  1
sumando  =>  1
soã  =>  1
olientos  =>  1
vociferar  =>  1
pulmã³n  =>  1
tres  =>  1
vã­ctimas  =>  1
desgrasar  =>  1
horrible  =>  1
guardavela  =>  1
vichar  =>  1
vasallo  =>  1
silbar  =>  1
murciã  =>  1
lago  =>  1
cacarear  =>  1
cantar  =>  1
modo  =>  1
cegar  =>  1
asnalmente  =>  1
aquel  =>  1
salir  =>  1
debã­an  =>  1
gayo  =>  1
buera  =>  1
cã³mo  =>  1
avã­an  =>  1
adelgazar  =>  1
picotear  =>  1
mutuamente  =>  1
matar  =>  1
bochorno  =>  1
vergã¼enza  =>  1
perjuicio  =>  1
dueã  =>  1
natural  =>  1
soltar  =>  1
plumista  =>  1
preconociã³  =>  1
protagonista  =>  1
suceso  =>  1
ser  =>  1
tipo  =>  1
despreciar  =>  1
general  =>  1
desgraciadamente  =>  1
abundar  =>  1
devenir  =>  1
ocultar  =>  1
arã  =>  1
publicar  =>  1
saber  =>  1
paã­s  =>  1
tambiã  =>  1
apareciã³  =>  1
letra  =>  1
moldar  =>  1
urna  =>  1
plumilla  =>  1
convergir  =>  1
gallina  =>  1
drop  =>  1
hora  =>  2
pseudotopolã³gico  =>  2
verdad  =>  2
espantoso  =>  2
exclamã³  =>  2
extremar  =>  2
poblar  =>  2
echar  =>  2
pasar  =>  2
dormir  =>  2
ponã­a  =>  2
cuanto  =>  2
desplumar  =>  2
poner  =>  2
palabra  =>  2
hacã­a  =>  2
parecer  =>  2
i  =>  2
n  =>  2
ir  =>  2
enfrentar  =>  2
despertar  =>  2
cincar  =>  2
gran  =>  2
merecer  =>  2
periã³dico  =>  2
bien  =>  2
casar  =>  3
abrir  =>  3
demã  =>  3
pues  =>  3
perchar  =>  3
respetable  =>  3
luego  =>  3
querer  =>  3
familia  =>  3
ojo  =>  3
asta  =>  3
±  =>  3
do  =>  3
historia  =>  3
paloma  =>  3
amor  =>  3
morir  =>  3
si  =>  4
poder  =>  4
lechoso  =>  4
verdal  =>  4
ujãº  =>  4
correr  =>  4
coser  =>  5
huero  =>  5
arrancar  =>  5
puro  =>  6
caninero  =>  6
decir  =>  6
pluma  =>  7
mã  =>  7
©  =>  7
gayar  =>  8
todo  =>  8
oã­do  =>  8
gabina  =>  9
gavina  =>  10
segundo  =>  14
â  =>  22
â€  =>  33
```

## Autor
* **Oscar Chacón** - *Tercera Practica* - <oscar.apple10@gmail.com>