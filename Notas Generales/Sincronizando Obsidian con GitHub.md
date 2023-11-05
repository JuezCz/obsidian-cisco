Sincronizar Obsidian con repositorio de GitHub.

**1 - Crear repositorio en GiitHub:**
	"Perfil de usuario"
		+Your repositories
			+New 
				+Configurar  repositorio (Propietario, nombre, estado...)


**2 - Generar token:**
		+Setting
			+<> Developer settings
				+ Personal access tokens
					+ Tokens (classic)
						+ Generate new token


**3 - Configurar obsidian**
		+ Preferencias
			+ Complementos comunitarios
				+ Buscar  (Buscamos BRAT, sirve para instalar plugins en fase beta). 
					+ ctrl + p (en la pantalla principal). Buscamos "add beta plugins"
						+ Instalamos "Obsidian42 BRAT Plugins Add a beta for testing".
							+En ventana emergente ponemos direccion de github
							"https://github.com/oscarspalk/obsidian-git-sync"

**4 - Vincular repositorio personal de guithub con Obsidian**
	+ Preferencias
		+Complementos comunitarios (abajo del todo)
			+Click en Git Sync
				+Rellenamos los 3 campos con:
					  -Nombre del repositorio
					  -Dueño del repositorio
					  -Token de acceso (que creamos anteriormente).




**Sincronizando la bóveda de obsidian con repositorio de github.**

Mientras estamos en la ventana principal de obsidian presionamos "ctrl+p". Escribimos Git Sync y veremos las opciones disponibles.

>**Git Sync push**: Sube al repositorio la bóveda actual en la que estamos. Es la opción que usaremos habitualmente.

>**Git Sync pull**: Arrastramos los archivos de nuestro repositorio a nuestra bóveda de obsidian.+

>[!note] CUIDADO  
>Cuidado, con PULL se sobrescribirán los datos de nuestra bóveda de obsidian local.

