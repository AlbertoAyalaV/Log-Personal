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
  CLOCK: [2025-03-09 Sun 13:29:30]--[2025-03-09 Sun 13:29:30] =>  00:00:00
  :END:
	- TODO [[Reunión con [[nombre]] - <%today%> - <%time%>]]
	  SCHEDULED: <2025-03-09 Sun 14:13>
	  título:: [[Reunión con [[nombre]] - <%today%> - <%time%>]]
	  participantes:: [[Alberto Ayala]],
	  duración::
	  lugar::
	  URL:: 
	  descripción::
	  proyecto::
	  tipo:: [[Reuniones]]
	  etiquetas::
- ## Ejemplos de Uso
	-