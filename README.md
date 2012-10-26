*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Funciones
- *chkPath();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *chkProcess();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *chkScriptIntegrity();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *chkScriptVersion();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *chkSsh();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *chkSum();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *debug();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *doQuestionAndReadAnswer();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *doQuestionAndReadSimpleAnswer();
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *getEnvironment();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *getHour();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *getSubstring();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *gotConnected();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *linexy();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *log();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *remplaceString();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *rotateFile();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *sendMail();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *toLower();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

- *toUpper();*
	- Uso:
			
				Uso
	- Nota:
			
				Nota

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

		Texto de Prueba

- *DEBUG_ENABLE (boolean)*

		Texto de Prueba

- *LOG_ENABLE (boolean)*

		Texto de Prueba

- *LOG_PATH (string)*

		Texto de Prueba

- *LOG_FILE (string)*

		Texto de Prueba

- *LOG (string)*

		Texto de Prueba

#### Otros
- *VERSION_CHECK (boolean)*

		Texto de Prueba

- *WGET_TRIES (int)*

		Texto de Prueba

- *WGET_TIMEOUT (int)*

		Texto de Prueba

- *WGET_OPTIONS (string)*

		Texto de Prueba

- *WGET_DEBUG (sting)*

		Texto de Prueba

-----------------------------------------------------------------------------------------------

sasa