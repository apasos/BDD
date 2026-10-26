### Ejercicio

Se quiere modelar una base de datos de información histórico-política e histórico-administrativa de las 
calles de una ciudad, así como información sobre los hospitales y canchas de fútbol sobre las mismas. 
La información histórico-política de interés se refiera al año en que fue inaugurada la calle así como el 
nombre del intendente en ejercicio. 

La información histórico- administrativa que se desea mantener es la identificación del plano de 
construcción de la calle en cuestión, así como la empresa constructora que estuvo a cargo del diseño de 
dicho plano. El plano de construcción de la calle consiste del diseño de la misma y el identificador del 
plano es una referencia que se utiliza a fin de ubicarlo en el archivo de planos que mantiene la 
intendencia. Desde ahora al plano de construcción lo llamaremos simplemente plano de la calle. Se 
sabe que una calle tiene tanto un número de calle como un nombre y que cada uno identifica a la calle. 
El número de calle determina en forma única tanto el nombre de la calle como el identificador del plano 
de la calle y la empresa constructora. 

A su vez el número de la calle y la identificación del plano de la calle y la empresa constructora son 
únicos dado el nombre de la calle. El nombre de la calle fue elegido durante el ejercicio de un 
intendente, es decir que el nombre del intendente queda determinado por el nombre de la calle. Dado el 
nombre y el número de la calle y el nombre del intendente queda determinado el año de inauguración de 
la calle. 

Se sabe que una identificación del plano de una calle puede describir a distintas calles, pero un plano es 
diseñado por una única empresa constructora. Las mismas empresas que se encargaron de diseñar los 
planos de las calles, construyeron hospitales y canchas de fútbol. En la construcción de un hospital ó de 
una cancha de fútbol designa un único ingeniero responsable. A su vez dichos ingenieros trabajan en 
una única empresa constructora. 


a. Deducir las dependencias funcionales que se cumplen, justificando a partir de la letra. 
Se sugieren los siguientes nombres para los atributos: 
- (NC) Nombre Calle (EC) Empresa Constructora 
- (NRO) Número Calle (HO) Hospital 
- (IP) Identificación Plano (CF) Cancha Fútbol 
- (NI) Nombre Intendente (ING) Ingeniero 
- (AI) Año de inauguración de la calle 

b. Hallar todas las claves. Justificar la respuesta. 

c. Hallar un cubrimiento minimal. Justificar la respuesta. 

d. Llevar a 3NF con join sin pérdida y preservando dependencias. Indicar las dependencias 
funcionales que se proyectan en cada esquema y las claves de cada uno de éstos. 

e. Llevar a BCNF con join sin pérdida. Indicar las dependencias funcionales que se proyectan en 
cada uno de éstos. Indicar si se perdieron dependencias funcionales y cuales. 