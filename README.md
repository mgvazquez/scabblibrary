*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Funciones
- *chkPath();*<br/>
- *chkProcess();*<br/>
- *chkScriptIntegrity();*<br/>
- *chkScriptVersion();*<br/>
- *chkSsh();*<br/>
- *chkSum();*<br/>
- *debug();*<br/>
- *doQuestionAndReadAnswer();*<br/>
- *doQuestionAndReadSimpleAnswer();*<br/>
- *getEnvironment();*<br/>
- *getHour();*<br/>
- *getSubstring();*<br/>
- *gotConnected();*<br/>
- *linexy();*<br/>
- *log();*<br/>
- *remplaceString();*<br/>
- *rotateFile();*<br/>
- *sendMail();*<br/>
- *toLower();*<br/>
- *toUpper();*<br/>

## Variables
#### Generales
- *LIBRARY_VERSION (string)*<br/>Contiene la version actual de la Libreria
- *LIBRARY_FILE (string)*<br/>
- *LIBRARY_PATH (string)*<br/>
- *LIBRARY (string)*<br/>
- *SCRIPT_FILE (string)*<br/>
- *SCRIPT_PATH (string)*<br/>
- *SCRIPT_CFG_FILE (string)*<br/>
- *SCRIPT_TITLE (string)*<br/>
- *TEMP_PATH (string)*<br/>
- *DATE (string)*<br/>
- *HOST_NAME (string)*<br/>

#### Tipograficas
- *ESC_CHAR (string)*<br/>
- *FONT_TP (array - String)*<br/>
- *FONT_FG (array - String)*<br/>
- *FONT_BG (array - String)*<br/>

#### Conectividad
- *CHKCONNECTION (boolean)*<br/> # Devuelve si se comprobo la conexion
- *GOTCONNECTED (boolean)*<br/> # Devuelve el estado actual de la conexion

#### Notificaciones (Mail)
- *SEND_MAIL_NOTIFICATION (boolean)*<br/>Al setear los valores true/false en esta variable, se habilita o deshabilita la funion sendMail();

#### Logging
- *STDOUT_ENABLE (boolean)*<br/>
- *DEBUG_ENABLE (boolean)*<br/>
- *LOG_ENABLE (boolean)*<br/>
- *LOG_PATH (string)*<br/>
- *LOG_FILE (string)*<br/>
- *LOG (string)*<br/>

#### Otros
- *VERSION_CHECK (boolean)*<br/>
- *WGET_TRIES (int)*<br/>
- *WGET_TIMEOUT (int)*<br/>
- *WGET_OPTIONS (string)*<br/>
- *WGET_DEBUG (sting)*<br/>