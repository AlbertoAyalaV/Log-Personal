## Persona
template:: Persona
template-including-parent:: false
	- nombre-completo:: 
	  descripción::
	  link::
	  correo::
	  etiqueta::
	  tipo:: [[Personas]]
- ## Congreso
  template:: Congreso
  template-including-parent:: false
	- URL::
	  descripción::
	  fecha-de-celebración::
	  lugar::
	  deadline::
	  etiquetas::
	  tipo:: [[Congresos]]
	-
- ## Diario
  template:: Diario
  template-including-parent:: false
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
  template:: Reunión
  template-including-parent:: false
  :LOGBOOK:
  CLOCK: [2025-03-09 Sun 13:00:57]--[2025-03-09 Sun 13:00:58] =>  00:00:01
  :END:
	- Título:: [[Reunión con [[{{nombre}}]] - {{fecha}}]] 
	  :LOGBOOK:
	  CLOCK: [2025-03-09 Sun 13:00:57]--[2025-03-09 Sun 13:00:58] =>  00:00:01
	  :END:
	  participantes:: [[Alberto Ayala]],   
	  descripción::
	  fecha-hora:: 
	  duración::
	  lugar::
	  URL::
	  tipo:: [[Reuniones]] 
	  etiquetas::
- ## Ejemplos de Uso