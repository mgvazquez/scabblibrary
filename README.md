*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Funciones
- *chkPath();*<dd>Texto de Prueba</dd><br/>
- *chkProcess();*<dd>Texto de Prueba</dd><br/>
- *chkScriptIntegrity();*<dd>Texto de Prueba</dd><br/>
- *chkScriptVersion();*<dd>Texto de Prueba</dd><br/>
- *chkSsh();*<dd>Texto de Prueba</dd><br/>
- *chkSum();*<dd>Texto de Prueba</dd><br/>
- *debug();*<dd>Texto de Prueba</dd><br/>
- *doQuestionAndReadAnswer();*<dd>Texto de Prueba</dd><br/>
- *doQuestionAndReadSimpleAnswer();<dd>Texto de Prueba</dd><br/>
- *getEnvironment();*<dd>Texto de Prueba</dd><br/>
- *getHour();*<dd>Texto de Prueba</dd><br/>
- *getSubstring();*<dd>Texto de Prueba</dd><br/>
- *gotConnected();*<dd>Texto de Prueba</dd><br/>
- *linexy();*<dd>Texto de Prueba</dd><br/>
- *log();*<dd>Texto de Prueba</dd><br/>
- *remplaceString();*<dd>Texto de Prueba</dd><br/>
- *rotateFile();*<dd>Texto de Prueba</dd><br/>
- *sendMail();*<dd>Texto de Prueba</dd><br/>
- *toLower();*<dd>Texto de Prueba</dd><br/>
- *toUpper();*<dd>Texto de Prueba</dd><br/>

## Variables
#### Generales
- *LIBRARY_VERSION (string)*<dd>Contiene la version actual de la Libreria</dd><br/>
- *LIBRARY_FILE (string)*<dd>Contiene el nombre del archivo de la libreria, 'scabblibrary.lib'</dd><br/>
- *LIBRARY_PATH (string)*<dd>Path en donde vive la libreria. Por defecto es `/usr/lib`<br/>Puede setearse desde el archivo de configuracion del script</dd><br/>
- *SCRIPT_FILE (string)*<dd>Nombre del Script que importa la Librería</dd><br/>
- *SCRIPT_PATH (string)*<dd>Texto de Prueba</dd><br/>
- *SCRIPT_CFG_FILE (string)*<dd>Texto de Prueba</dd><br/>
- *SCRIPT_TITLE (string)*<dd>Texto de Prueba</dd><br/>
- *TEMP_PATH (string)*<dd>Texto de Prueba</dd><br/>
- *DATE (string)*<dd>Texto de Prueba</dd><br/>
- *HOST_NAME (string)*<dd>Texto de Prueba</dd><br/>

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

<hr/>

sasa