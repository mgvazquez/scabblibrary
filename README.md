*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Funciones
- *chkPath();*
		
		Texto de Prueba</dd><br/>

- *chkProcess();*

Texto de Prueba</dd><br/>

- *chkScriptIntegrity();*

Texto de Prueba</dd><br/>

- *chkScriptVersion();*

Texto de Prueba</dd><br/>

- *chkSsh();*

Texto de Prueba</dd><br/>

- *chkSum();*

Texto de Prueba</dd><br/>

- *debug();*

Texto de Prueba</dd><br/>

- *doQuestionAndReadAnswer();*

Texto de Prueba</dd><br/>

- *doQuestionAndReadSimpleAnswer();

Texto de Prueba</dd><br/>

- *getEnvironment();*

Texto de Prueba</dd><br/>

- *getHour();*

Texto de Prueba</dd><br/>

- *getSubstring();*

Texto de Prueba</dd><br/>

- *gotConnected();*

Texto de Prueba</dd><br/>

- *linexy();*

Texto de Prueba</dd><br/>

- *log();*

Texto de Prueba</dd><br/>

- *remplaceString();*

Texto de Prueba</dd><br/>

- *rotateFile();*

Texto de Prueba</dd><br/>

- *sendMail();*

Texto de Prueba</dd><br/>

- *toLower();*

Texto de Prueba</dd><br/>

- *toUpper();*

Texto de Prueba</dd><br/>

## Variables
#### Generales
- *LIBRARY_VERSION (string)*

		Contiene la version actual de la Libreria

- *LIBRARY_FILE (string)*

		Contiene el nombre del archivo de la libreria, 'scabblibrary.lib'

- *LIBRARY_PATH (string)*

		Path en donde vive la libreria. Por defecto es `/usr/lib`
		Puede setearse desde el archivo de configuracion del script

- *SCRIPT_FILE (string)*

		Nombre del Script que importa la Librería

- *SCRIPT_PATH (string)*

		Texto de Prueba

- *SCRIPT_CFG_FILE (string)*

		Texto de Prueba

- *SCRIPT_TITLE (string)*

		Texto de Prueba

- *TEMP_PATH (string)*

		Texto de Prueba

- *DATE (string)*

		Texto de Prueba

- *HOST_NAME (string)*

		Texto de Prueba

#### Tipograficas
- *ESC_CHAR (string)*<dd>Texto de Prueba</dd><br/>
- *FONT_TP (array - String)*<dd>Texto de Prueba foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa </dd><br/>
- *FONT_FG (array - String)*<dd>Texto de Prueba</dd><br/>
- *FONT_BG (array - String)*<dd>Texto de Prueba</dd><br/>

#### Conectividad
- *CHKCONNECTION (boolean)*<dd>Texto de Prueba</dd><br/> # Devuelve si se comprobo la conexion
- *GOTCONNECTED (boolean)*<dd>Texto de Prueba</dd><br/> # Devuelve el estado actual de la conexion

#### Notificaciones (Mail)
- *SEND_MAIL_NOTIFICATION (boolean)*<dd>Texto de Prueba</dd><br/>Al setear los valores true/false en esta variable, se habilita o deshabilita la funion sendMail();

#### Logging
- *STDOUT_ENABLE (boolean)*<dd>Texto de Prueba</dd><br/>
- *DEBUG_ENABLE (boolean)*<dd>Texto de Prueba</dd><br/>
- *LOG_ENABLE (boolean)*<dd>Texto de Prueba</dd><br/>
- *LOG_PATH (string)*<dd>Texto de Prueba</dd><br/>
- *LOG_FILE (string)*<dd>Texto de Prueba</dd><br/>
- *LOG (string)*<dd>Texto de Prueba</dd><br/>

#### Otros
- *VERSION_CHECK (boolean)*<dd>Texto de Prueba</dd><br/>
- *WGET_TRIES (int)*<dd>Texto de Prueba</dd><br/>
- *WGET_TIMEOUT (int)*<dd>Texto de Prueba</dd><br/>
- *WGET_OPTIONS (string)*<dd>Texto de Prueba</dd><br/>
- *WGET_DEBUG (sting)*<dd>Texto de Prueba</dd><br/>

-----------------------------------------------------------------------------------------------

sasa