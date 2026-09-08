Pokédex React

Objetivo del Proyecto
Desarrollar una aplicación en React que permite consumir datos de la PokéAPI externa y gestionar un equipo Pokémon local utilizando un CRUD completo.

Tecnologías Utilizadas

React + Vite
JavaScript 
JSON Server 
CSS

Arquitectura de APIs

PokéAPI: Utilizada como fuente de datos externa para consultar información y estadísticas de Pokémon mediante solicitudes GET.

JSON Server: Configurada localmente para persistir y administrar el equipo Pokémon mediante las operaciones del CRUD.

Operaciones CRUD y Métodos HTTP

CREATE (POST): Agrega un nuevo Pokémon consultado al equipo guardado.

READ (GET): Consulta los datos desde la PokéAPI y muestra la lista actual del equipo.

UPDATE (PATCH): Modifica atributos específicos de los Pokémon en el equipo, como subir de nivel o alternar el estado de favorito.

DELETE (DELETE): Libera y elimina un Pokémon registrado en el equipo.
