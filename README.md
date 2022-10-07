# ENTREGA_1_Estadistica_2

## Miembros del grupo:
 + Joel B. Huamani (20196510)
 + Jose Rios (20181496)
 
Tema de investigacion: El desempleo de jovenes y su relacion con el desarrollo estatal [Desempleo.csv](https://github.com/20181496/Trabajo-final-Estadistica-2/files/9539852/Desempleo.csv)


Variable dependiente: Desempleo de jovenes de 15 a 22 años (CIA) 
 + -Da el porcentaje del resultado total de la mano de obra de jovenes que se encuentran en la edad de 15 a 22 años
  Extraido de https://www.cia.gov/the-world-factbook/field/unemployment-youth-ages-15-24/country-comparison

El desempleo es un problema economico, estructural por el cual miles de personas tienen que sobrevivir dia a dia. Consideramos que algunos factores socioeconomicos explicarán su incremento o disminución en el mundo. En ese sentido, consideraremos las siguientes variables:


### Base de Datos 1:

4 Variables independients y su Metadata
 + Infraestructura de Carreteras(CIA)[RoadW.csv](https://github.com/20181496/Trabajo-final-Estadistica-2/files/9539836/RoadW.csv)
 + -Revisa los kilometros de Carreteras pavimentadas y no pavimentadas y las suma.
   Extraido de https://www.cia.gov/the-world-factbook/field/roadways/country-comparison
   - Consideramos la importancia de los kilometros de carretera dentro del desempleo ya que una ausencia de carreteras dentro de un Estado puede terminar disminuyendo el area en la que un individuo puede trabajar, limitando sus opciones y por ende la posibilidad que este pueda o no trabajar.


 + Libertad Civica (Democracy Index Wikipedia)
 + - Revisa la Libertad civica, es decir, la libertad de los ciudadanos dentro del Estado en el que se encuentran residiendo
   Extraido de https://en.wikipedia.org/wiki/Democracy_Index en el xpath "/html/body/div[3]/div[3]/div[5]/div[1]/table[6]"
   - Dentro de lo que se espera de la libertad civil podemos ver si los ciudadanos pueden o no tener acceso a un trabajo otorgado por el Estado o si les ayuda a conseguir uno mediante un intermediario. Horst Feldman (2010) considera que el desempleo tiene un efecto directo en la economias como reviso enel caso del Reino Unido y observa regiones y las tasas de dempleo que estas tienen al recolectar informacion de medios como la organizacion internacional del trabajo con el objetivo de legitimar su investigacion.


 + Gastos en Educacion(CIA)[GastosEdu.csv](https://github.com/20181496/Trabajo-final-Estadistica-2/files/9539839/GastosEdu.csv)
 + -Los gastos de educacion compara el gasto publico en educacion como porcentaje al PIB
   Extraido de https://www.cia.gov/the-world-factbook/field/education-expenditures/country-comparison
    - Consideramos que los gastos en eduacion influyen dentro del desempleo cuando consideramos que mientras mayor nivel educativo se puede alcanzar en un individuo, mas posibilidades de trabajo o de opciones de trabajo puede tener. Cesar Calvo (2012) considera tambien que los niveles educativos alcanzados tienen un efecto sobre los ingresos laborales dentro del Perú, por lo que podriamos extrapolar este pensamiento al resto de paises una vez asumido estas constantes.
   
   
 + Obesidad (CIA)
 + - Considera el porcentaje de ciudadanos que son considerados obesos en un pais
   Extraido de https://www.cia.gov/the-world-factbook/field/obesity-adult-prevalence-rate/country-comparison
  La obesidad es un desorden que constituye un sobrepeso al punto de generar problemas psicologicos y fisicos de un individuo y puede tener efecto en la capacidad de una persona de mantener un empleo estable. Veronica Espinoza (2014) nos explica dentro del portal de la organizacion psico.org que la obesidad puede generar inseguridad y problemas a la hora de encontrar un empleo ya que se considera a la persona obesa fuera del parametro de una persona exitosa, lo que puede colaborar dentro del desempleo de las personas que se encuentran con este problema
   
   
Bibliografía:
Calvo, C. (2012) "La educacion como factor determinante de los ingresos laborales en el Perú"
https://repositorio.upch.edu.pe/bitstream/handle/20.500.12866/9686/Educaci%C3%B3n_CalvoRamirez_Cesar.pdf?sequence=3&isAllowed=y Fecha de consulta: 7 de octubre de 2022

Espinoza, V. (2014) "¿Es la obesidad una barrera para conseguir empleo?" Quito, Ecuador https://www.psico.org/articulos/obesidad-una-barrera-para-conseguir-empleo Fecha de consulta 6 de octubre de 2022

Feldman, H. (2010) "Capitulo 5: Libertad económica y desempleo" en Libertad Economica en el mundo: informe anual 2010
https://www.elcato.org/pdf_files/efw2010/efw-capitulo5-2010.pdf fecha de consulta 6 de octubre de 2022


### Base de Datos 2 (joel)

4 Variables independientes:

 + Tasa de crecimiento de la producción industrial (CIA)
 + - Compara el aumento porcentual anual de la producción industrial (incluye manufactura, minería y construcción). Queremos conocer si contribuye signifcativamente en un posible modelo y afecte a nuestra variable dependiente o si existen otros factores más influyentes. En los paises desarrollados ha permitido mejorar el nivel de vida de sus miembros y una reactivación económica a corto plazo, pero queremos saber si influye aún si tomamos en cuenta los demás países.
 
[proindustrial.csv](https://github.com/20181496/Trabajo-final-Estadistica-2/files/9539625/proindustrial.csv)

 
+ Crecimiento del PIB (% anual)
Tasa de crecimiento anual porcentual del PIB a precios de mercado en moneda local, a precios constantes. Los agregados están expresados en dólares de los Estados Unidos a precios constantes del año 2010. El PIB es la suma del valor agregado bruto de todos los productores residentes en la economía más todo impuesto a los productos, menos todo subsidio no incluido en el valor de los productos. Se calcula sin hacer deducciones por depreciación de bienes manufacturados o por agotamiento y degradación de recursos naturales.

https://datos.bancomundial.org/indicador/NY.GDP.MKTP.KD.ZG


+ Promedio grupal de gestión económica de la CPIA (1=bajo a 6=alto)
El grupo de gestión económica incluye la gestión macroeconómica, la política fiscal y las políticas de deuda.

https://datos.bancomundial.org/indicador/IQ.CPA.ECON.XQ?view=chart


+ Población que vive en barrios de tugurios (% de la población urbana)
La población que vive en barrios marginales es la proporción de la población urbana que vive en hogares de barrios marginales. Un hogar de tugurios se define como un grupo de personas que viven bajo el mismo techo y carecen de una o más de las siguientes condiciones: acceso a agua mejorada, acceso a saneamiento mejorado, espacio suficiente para vivir y durabilidad de la vivienda. 

https://datos.bancomundial.org/indicador/EN.POP.SLUM.UR.ZS?view=chart












