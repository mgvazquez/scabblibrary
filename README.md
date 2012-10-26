*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Funciones
- *chkPath();*
		
		Texto de Prueba

- *chkProcess();*

		Texto de Prueba

- *chkScriptIntegrity();*

		Texto de Prueba

- *chkScriptVersion();*

		Texto de Prueba

- *chkSsh();*

		Texto de Prueba

- *chkSum();*

		Texto de Prueba

- *debug();*

		Texto de Prueba

- *doQuestionAndReadAnswer();*

		Texto de Prueba

- *doQuestionAndReadSimpleAnswer();

		Texto de Prueba

- *getEnvironment();*

		Texto de Prueba

- *getHour();*

		Texto de Prueba

- *getSubstring();*

		Texto de Prueba

- *gotConnected();*

		Texto de Prueba

- *linexy();*

		Texto de Prueba

- *log();*

		Texto de Prueba

- *remplaceString();*

		Texto de Prueba

- *rotateFile();*

		Texto de Prueba

- *sendMail();*

		Texto de Prueba

- *toLower();*

		Texto de Prueba

- *toUpper();*

		Texto de Prueba

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
- *ESC_CHAR (string)*

		Texto de Prueba

- *FONT_TP (array - String)*
		
		Texto de Prueba foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa foo faa

- *FONT_FG (array - String)*

		Texto de Prueba

- *FONT_BG (array - String)*

		Texto de Prueba

#### Conectividad

- *CHKCONNECTION (boolean)*

		Texto de Prueba

- *GOTCONNECTED (boolean)*

		Texto de Prueba

#### Notificaciones (Mail)
- *SEND_MAIL_NOTIFICATION (boolean)*

		Al setear los valores true/false en esta variable, se habilita o deshabilita la funion sendMail();

#### Logging
- *STDOUT_ENABLE (boolean)*

		Texto de Prueba</dd><br/>

- *DEBUG_ENABLE (boolean)*

		Texto de Prueba</dd><br/>

- *LOG_ENABLE (boolean)*

		Texto de Prueba</dd><br/>

- *LOG_PATH (string)*

		Texto de Prueba</dd><br/>

- *LOG_FILE (string)*

		Texto de Prueba</dd><br/>

- *LOG (string)*

		Texto de Prueba</dd><br/>

#### Otros
- *VERSION_CHECK (boolean)*<dd>Texto de Prueba</dd><br/>
- *WGET_TRIES (int)*<dd>Texto de Prueba</dd><br/>
- *WGET_TIMEOUT (int)*<dd>Texto de Prueba</dd><br/>
- *WGET_OPTIONS (string)*<dd>Texto de Prueba</dd><br/>
- *WGET_DEBUG (sting)*<dd>Texto de Prueba</dd><br/>

-----------------------------------------------------------------------------------------------

sasa