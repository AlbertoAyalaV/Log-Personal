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
	- TODO Título:: [[Reunión con [[nombre]] - fecha]]
	  SCHEDULED: <día hora>
	  participantes:: [[Alberto Ayala]],
	  descripción::
	  fecha-hora::
	  duración::
	  lugar::
	  URL::
	  tipo:: [[Reuniones]]
	  etiquetas::
- ## Ejemplos de Uso
- TODO [[Reunión con [[Alberto Ayala]] - [[Mar 6th, 2025]] ]] SCHEDULED: <2025-03-09 Sun 13:08>
  Título:: [[Reunión con [[Alberto Ayala]] - [[Mar 6th, 2025]] ]]
  participantes:: [[Alberto Ayala]],
  descripción::
  fecha-hora::
  duración::
  lugar::
  URL::
  tipo:: [[Reuniones]]
  etiquetas::
  :LOGBOOK:
  CLOCK: [2025-03-09 Sun 13:08:12]--[2025-03-09 Sun 13:08:13] =>  00:00:01
  CLOCK: [2025-03-09 Sun 13:08:13]--[2025-03-09 Sun 13:08:14] =>  00:00:01
  CLOCK: [2025-03-09 Sun 13:08:15]--[2025-03-09 Sun 13:08:29] =>  00:00:14
  :END: