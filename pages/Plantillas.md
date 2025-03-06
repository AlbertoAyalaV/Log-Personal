## Persona
template:: Persona
template-including-parent:: false
	- tipo:: [[Personas]]
	  nombre-completo:: 
	  descripción::
	  link::
	  correo::
	  etiqueta::
- ## Congreso
  template:: Congreso
  template-including-parent:: false
	- tipo:: [[Congresos]]
	  URL::
	  etiquetas::
	  descripción::
	  fecha-de-celebración::
	  lugar::
	  deadline::
	-
- ## Diario
  template:: Diario
  template-including-parent:: false
  collapsed:: true
	- ← <% yesterday %> | <% tomorrow %> →
	- ## Tareas pendientes
		- {{query [[TODO]]}}
		  collapsed:: true
	- ## Nuevas tareas
	- ## Objetivos del día
		- TODO Mirar tareas pendientes
	- ## Reuniones
	- ## Notas rápidas
- ## Reunión
	- tipo:: [[Reuniones]] 
	  URL::
	  descripción::
	  fecha-hora::
	  lugar::
	  URL::
	  etiquetas::
- ## Ejemplos de Uso