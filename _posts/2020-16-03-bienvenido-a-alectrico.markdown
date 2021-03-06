---
layout: post
title:  "Bienvenido a CoronaVid!"
date:   2019-12-03 06:18:58 -0300
categories: corona virus
---
Los síntomas de una infección viral son bien conocidas por los médicos. El virus COVID-19 no ha sido una gran sorpresa en ese sentido. Lo que ha resultado realmente sorprendente para todos en el planeta, es la gran contagiosidad que ha demostrado. Conviene tratar tempranamente a las personas infectadas antes de que la progresión geométrica de los contagiados haga colapsar las capacidades de atención de salud.

Conavid actua como una detector temprano de síntomas de COVID-19 permitiendo a los consumidores de sus datos, hecho a través de una api, la toma de acción rápida. El frontend también puede ser usado para realizar las internaciones, las que serán autorizadas por un macarrón en un microservicio aparte.

Conavid no puede hacer milagros, las personas solo dirán públicamente que se sienten mal si confían que los consumidores de datos harán algo al respecto. Si Ud. es un consultorio que consume los datos de sus pacientes crónicos a los que previamente inscribió, debe actuar pensando en ello. Si no lo hace, los pacientes irán a pie hasta el lugar físico de atención generando un foco de contagio adicional.

{% highlight ruby %}
def hay_síntomas?(paciente)
  puts "Envíe a apoyo a, #{direccion}"
end
no_hay_camas?('Hospital')
#=> prints 'Aislar en infraestructura municipal' to STDOUT.
{% endhighlight %}

La api usa una metáfora de circuito, tipo de circuito y carga. Donde las cargas son síntomas agregados por el paciente a un circuito hospitalario de un tipo dado. 

De esta forma se puede manejar la idea de que los pacientes no deben estar mucho tiempo en los hospitales sino que deben moverse si fuera necesario en un circuito determinado de infraestructura hospitalaria con capacidad adhoc al tipo de síntoma. Si el personal que atiende el backend de Coronavid entiende eso entonces les será más fácil usar la interface de internación desde el propio celular del paciente, teniendo a la vista los síntomas.  

Esto permite una especie de drive-in donde cada paciente al muestrar su celular a un asesor podrá ser redirigido ipso facto. Conavid usa un sistema de microservicios con autenticación basada en jwt y macarrones de autorización. Uno de esos macarrones permitirá en una ventana de tiempo la internación del paciente, esa forma el analizador en terreno solo necesitará operar el celular del paciente haciendo la internación. El macarrón se atenuará en una ventana de tiempo, haciendo imposible el mal uso de funcionarios corruptos con acceso al backend. Es importante que haya un funcionario menos corrupto a cargo de activar los macarrones.

La operación de la interfaz del celular del paciente debe hacerse con un lápiz esteril o descartable, o el propio usuario puede hacer la selección de acuerdo a indicaciones del analizador.


Una vez que se realice la internación, la cuenta del usuario será eliminada irrevocablemente para evitar distracciones y falsos positivos.

