*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script)

## Funciones
- chkPath();
- chkProcess();
- chkScriptIntegrity();
- chkScriptVersion();
- chkSsh();
- chkSum();
- debug();
- doQuestionAndReadAnswer();
- doQuestionAndReadSimpleAnswer();
- getEnvironment();
- getHour();
- getSubstring();
- gotConnected();
- linexy();
- log();
- remplaceString();
- rotateFile();
- sendMail();
- toLower();
- toUpper();

## Variables
#### Generales
- LIBRARY_VERSION (string)
- LIBRARY_FILE (string)
- LIBRARY_PATH (string)
- LIBRARY (string)
- SCRIPT_FILE (string)
- SCRIPT_PATH (string)
- SCRIPT_CFG_FILE (string)
- SCRIPT_TITLE (string)
- TEMP_PATH (string)
- DATE (string)
- HOST_NAME (string)

#### Tipograficas
- ESC_CHAR (string)
- FONT_TP (array - String)
- FONT_FG (array - String)
- FONT_BG (array - String)

#### Conectividad
- CHKCONNECTION (boolean) # Devuelve si se comprobo la conexion
- GOTCONNECTED (boolean) # Devuelve el estado actual de la conexion

#### Notificaciones (Mail)
- SEND_MAIL_NOTIFICATION (boolean)

#### Logging
- STDOUT_ENABLE (boolean)
- DEBUG_ENABLE (boolean)
- LOG_ENABLE (boolean)
- LOG_PATH (string)
- LOG_FILE (string)
- LOG (string)

#### Otros
- VERSION_CHECK (boolean)
- WGET_TRIES (int)
- WGET_TIMEOUT (int)
- WGET_OPTIONS (string)
- WGET_DEBUG (sting)