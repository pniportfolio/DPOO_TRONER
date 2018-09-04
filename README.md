# DPOO_TRONER

Aquest projecte està relacionat amb l'assignatura Disseny i Programació Orientat a Objectes. Consisteix en un joc multijugador del popular joc online Troner. La carpeta programari conté dos projectes de Java, un és el client i l'altra el servidor. En el joc, els jugadors necesiten connectar-se al servidor per poder jugar amb altres jugadors. 
Les instruccions per el correcte funcionament de Troner son les seguents:
	1.- Primerament instalarem el sistema gestor de bases de dades MySQL i en desactivem l'opció de "Safe Updates" situada a "Preferences -> SQL Editor.
 	2.- Un cop instalat, obrirem Mysql i executarem el arxiu BBDD.sql per tal de crear la base de dades necessaria.
	3.- A continuació introduirem les dades de la Base de Dades al fitxer config.json del programa Servidor i podrem començar l'execució.
	4.- Amb els 3 passos previs realitzats ja podrem procedir a registrar usuaris pel joc.
	5.- Per tal de registrar usuaris ho podrem fer a traves de dos medis:
		5.1.- A traves del programa servidor, nomès es necessari omplir els camps i premer el boto registrar.
		5.2.- A traves del programa client, en aquest cas haurem d'obrir el servidor i conectar-nos amb el 
		      client a traves de la IP i port correctes, despres omplirem el camps necesaris com en el servidor.
	6.- Si es desitja, els usuaris poden confiugurar els controls del joc clicant al boto de configuració del menú
	    de selecció de partida.
	7.- Un cop els usuaris estiguin registrats i conectats al servidor, podran procedir a jugar. Per fer-ho simplement
	    haurem de clicar el mode de joc desitjat i esperar a que hi hagi el nombre de jugadors requerit.
	8.- Dintre de la partida el jugador anira jugant partides, i podrar triar un altre tipus de partida clicant el
	    botó abandona i triant el nou mode.
	9.- Si el jugador desitja conectar-se a un altre servidor o iniciar sessio com un altre usuari o pot fer clicant al
	    botó tancar sessió, que el portara a la pàgina de conexió.
	10.- Si es desitja eliminar un usuari del la base de dades, ho podrem fer desde la pestaña gestiona del servidor.
	11.- Podrem consultar el ranquing i grafics del jugador a las seves pestanyes amb el mateix nom del servidor.
