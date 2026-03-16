# Git
- Para usar git en Logseq tenemos varias opciones:
	- Crear un nuevo repositorio y clonarlo en nuestro equipo.
	- Clonar un repositorio existente donde tengamos permisos para escribir.
	- Hacer un _fork_ de un repositorio existente y _clonarlo_.
- ## Clonar un repositorio existente para colaborar en equipo
	- Para este ejercicio vamos a hacer un fork y clonar el [repositorio con este grafo de logseq](https://github.com/atfornes/CursoSoftwareLibreUAM) que está alojado en github:
		- Haz login en tu cuenta de github.
		  logseq.order-list-type:: number
		- Visita la web del repositorio y haz un fork.
		  logseq.order-list-type:: number
		  ![Screenshot_20260312_114043.png](../assets/Screenshot_20260312_114043_1773312065052_0.png)
		- Clona tu fork del repositorio en tu equipo. Para ello, sigue las instrucciones de clonado de un repositorio con token de autenticación que viste en la lección sobre git.
		  logseq.order-list-type:: number
-
- ## Habilitar git en Logseq
	- En las opciones de configuración de Logseq, habilita **Git** y el **auto commit** para que los cambios se envíen automáticamente a vuestro repositorio en github.
	  ![Screenshot_20260312_115055.png](../assets/Screenshot_20260312_115055_1773312846264_0.png)
	  Después, puedes poner un nombre y email para la configuración local del repositorio. _No tienen que coincidir con los que usaste para registrarte en github ni ser emails reales_
	- Una vez hayas configurado estas opciones, los cambios que hagas se enviarán a github cada 60 segundos.
-
- # Zotero
	- Para usar Zotero en logseq, debes tenerlo instalado en tu equipo.
	- ## Bibliotecas compartidas
	- Para poder compartir nuestra bibliografía, usaremos [una biblioteca de grupo en zotero.org](https://www.zotero.org/groups/6464350/software_libre_uam)
	- ## Configurar Zotero en Logseq
	- LATER En los ajustes de Logseq, podemos habilitar Zotero desde la pestaña de características
	  ![Screenshot_20260316_090810.png](../assets/Screenshot_20260316_090810_1773648534024_0.png)
	  Usaremos la información de nuestro usuario en logseq.org, con una nueva clave, generada en [https://www.zotero.org/settings/keys](https://www.zotero.org/settings/keys) para conectar logseq a nuestra biblioteca. Cuando generemos la clave, podremos indicar que también tiene permisos para acceder a nuestros grupos, para poder hacer uso de la biblioteca compartida. El User ID podéis encontrarlo en vuestra configuración de seguridad de logseq.org, bajo el botón para generar una nueva clave:
	  ![Screenshot_20260316_093908.png](../assets/Screenshot_20260316_093908_1773650489015_0.png)
	- Una vez tenemos configurado Logseq, podemos añadir una referencia escribiendo `/Logseq` y ejecutando dicho comando. Se abrirá una búsqueda en nuestra biblioteca y la refencia quedará vinculada
	- /zotero
-