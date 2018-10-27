---
layout: default
description: "Mapa"
id: mapa
---

<div class="component">
  <div class="map">
    {% include maps/lowres_south_america.svg %}
  </div>
  <div class="info">
    <h1>Latinoamerica</h1>
    Calle 13
    <br />
    <br />
    Soy <br />
Soy lo que dejaron <br />
Soy toda la sobra de lo que te robaron <br />
Un pueblo escondido en la cima <br />
Mi piel es de cuero por eso aguanta cualquier clima <br />
Soy una fábrica de humo <br />
Mano de obra campesina para tu consumo <br />
Frente de frio en el medio del verano <br />
El amor en los tiempos del cólera, mi hermano <br />
El sol que nace y el día que muere <br />
Con los mejores atardeceres <br />
Soy el desarrollo en carne viva <br />
Un discurso político sin saliva <br />
Las caras más bonitas que he conocido <br />
Soy la fotografía de un desaparecido <br />
La sangre dentro de tus venas <br />
Soy un pedazo de tierra que vale la pena <br />
Soy una canasta con frijoles <br />
Soy maradona contra inglaterra anotándote dos goles <br />
Soy lo que sostiene mi bandera <br />
La espina dorsal del planeta es mi cordillera <br />
Soy lo que me enseño mi padre <br />
El que no quiere a su patria no quiere a su madre <br />
Soy américa latina <br />
Un pueblo sin piernas pero que camina, oye <br />

<br />

Tú no puedes comprar al viento <br />
Tú no puedes comprar al sol <br />
Tú no puedes comprar la lluvia <br />
Tú no puedes comprar el calor <br />
Tú no puedes comprar las nubes <br />
Tú no puedes comprar los colores <br />
Tú no puedes comprar mi alegría <br />
Tú no puedes comprar mis dolores <br />
Tú no puedes comprar al viento <br />
Tú no puedes comprar al sol <br />
Tú no puedes comprar la lluvia <br />
Tú no puedes comprar el calor <br />
Tú no puedes comprar las nubes <br />
Tú no puedes comprar los colores <br />
Tú no puedes comprar mi alegría <br />
Tú no puedes comprar mis dolores <br />

<br />

Tengo los lagos, tengo los ríos <br />
Tengo mis dientes pa` cuando me sonrío <br />
La nieve que maquilla mis montañas <br />
Tengo el sol que me seca y la lluvia que me baña <br />
Un desierto embriagado con bellos de un trago de pulque <br />
Para cantar con los coyotes, todo lo que necesito <br />
Tengo mis pulmones respirando azul clarito <br />
La altura que sofoca <br />
Soy las muelas de mi boca mascando coca <br />
El otoño con sus hojas desmalladas <br />
Los versos escritos bajo la noche estrellada <br />
Una viña repleta de uvas <br />
Un cañaveral bajo el sol en cuba <br />
Soy el mar caribe que vigila las casitas <br />
Haciendo rituales de agua bendita <br />
El viento que peina mi cabello <br />
Soy todos los santos que cuelgan de mi cuello <br />
El jugo de mi lucha no es artificial <br />
Porque el abono de mi tierra es natural <br />

<br />

Tú no puedes comprar al viento <br />
Tú no puedes comprar al sol <br />
Tú no puedes comprar la lluvia <br />
Tú no puedes comprar el calor <br />
Tú no puedes comprar las nubes <br />
Tú no puedes comprar los colores <br />
Tú no puedes comprar mi alegría <br />
Tú no puedes comprar mis dolores <br />
Não se pode comprar o vento <br />
Não se pode comprar o sol <br />
Não se pode comprar a chuva <br />
Não se pode comprar o calor <br />
Não se pode comprar as nuvens <br />
Não se pode comprar as cores <br />
Não se pode comprar minha'legria <br />
Não se pode comprar minhas dores <br />

<br />

No puedes comprar al sol <br />
No puedes comprar la lluvia <br />
Vamos caminando <br />
Vamos dibujando el camino <br />
No puedes comprar mi vida <br />
Mi tierra no se vende <br />
Trabajo bruto pero con orgullo <br />
Aquí se comparte, lo mío es tuyo <br />
Este pueblo no se ahoga con marullos <br />
Y si se derrumba yo lo reconstruyo <br />
Tampoco pestañeo cuando te miro <br />
Para que recuerdes mi apellido <br />
La operación cóndor invadiendo mi nido <br />
Perdono pero nunca olvido, oye <br />
Aquí se respira lucha <br />
(Vamos caminando) <br />
Yo canto porque se escucha (vamos caminando) <br />
Aquí estamos de pie <br />
Que viva la América <br />
No puedes comprar mi vida <br />

  </div>
</div>

<style>

.component {
  display: flex;
  justify-content: flex-start;
}

.info,
.map{
  padding: 3rem;
  width: 50%;
}


.info{
  text-align: center;
  background-color: #fafafa;
  color: #333;
  line-height: 1.6em;
  font-size: 0.8em;
}

svg {
  fill: #92d7ef;
}

#martinica,
#cuba,
#el-salvador,
#peru,
#venezuela,
#guyana-francesa,
#paraguay,
.amarillo {fill: #efa94a;}


#martinica:hover,
#cuba:hover,
#el-salvador:hover,
#peru:hover,
#venezuela:hover,
#guyana-francesa:hover,
#paraguay:hover,
.amarillo:hover {fill: #efa94a88;}

#haiti,
#santa-lucia,
#puerto-rico,
#honduras,
#panama,
#suriname,
#bolivia,
#uruguay,
.celeste {fill: #92d7ef;}

#haiti:hover,
#santa-lucia:hover,
#puerto-rico:hover,
#honduras:hover,
#panama:hover,
#suriname:hover,
#bolivia:hover,
#uruguay:hover,
.celeste:hover {fill: #92d7ef88;}

#trinidad,
#dominica,
#bahamas,
#guatemala,
#costa-rica,
#colombia,
#guyana,
#argentina,
.verde {fill: #a2eae0;}

#trinidad:hover,
#dominica:hover,
#bahamas:hover,
#guatemala:hover,
#costa-rica:hover,
#colombia:hover,
#guyana:hover,
#argentina:hover,
.verde:hover {fill: #a2eae088;}

#san-vicente-y-las-granadinas,
#mexico,
#guadalupe,
#republica-dominicana,
#jamaica,
#nicaragua,
#ecuador,
#chile,
#brasil,
#belice,
.rosa {fill: #f9acbb;}

#san-vicente-y-las-granadinas:hover,
#mexico:hover,
#guadalupe:hover,
#republica-dominicana:hover,
#jamaica:hover,
#nicaragua:hover,
#ecuador:hover,
#chile:hover,
#brasil:hover,
#belice:hover,
.rosa:hover {fill: #f9acbb88;}


path {
  cursor: pointer;
  pointer-events:all;
}
</style>
