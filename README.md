*ScabbLibrary* (v1.2)
===================

*Scabblibrary*, es una pequeña libreria de funciones escritas en bash que nos facilita diversas tareas a la hora de escribir nuestros scripts.
El archivo `template_script.tar.gz` contiene un template de script bash basado en *Scabblibrary*, junto con su correspondiente archivo de configuracion el cual se carga automaticamente el invocar el script (el archivo .config, debe tener el mismo nombre que el archivo del script). 

## Indice
- [Funciones][funciones]
	- [chkPath();][funciones.chkPath]
	- [chkProcess();][funciones.chkProcess]
	- [chkScriptIntegrity();][funciones.chkScriptIntegrity]
	- [chkScriptVersion();][funciones.chkScriptVersion]
	- [chkSsh();][funciones.chkSsh]
	- [chkSum();][funciones.chkSum]
	- [debug();][funciones.debug]
	- [doQuestionAndReadAnswer();][funciones.doQuestionAndReadAnswer]
	- [doQuestionAndReadSimpleAnswer();][funciones.doQuestionAndReadSimpleAnswer]
	- [getEnvironment();][funciones.getEnvironment]
	- [getHour();][funciones.getHour]
	- [getSubstring();][funciones.getSubstring]
	- [gotConnected();][funciones.gotConnected]
	- [linexy();][funciones.linexy]
	- [log();][funciones.log]
	- [remplaceString();][funciones.remplaceString]
	- [rotateFile();][funciones.rotateFile]
	- [sendMail();][funciones.sendMail]
	- [toLower();][funciones.toLower]
	- [toUpper();][funciones.toUpper]
- [Variables][var]
	- [Generales][var.gral]
		- [LIBRARY_VERSION][var.gral.library_version]
		- [LIBRARY_FILE][var.gral.library_file]
		- [LIBRARY_PATH][var.gral.library_path]
		- [SCRIPT_FILE][var.gral.script_file]
		- [SCRIPT_PATH][var.gral.script_path]
		- [SCRIPT_CFG_FILE][var.gral.script_cfg_file]
		- [SCRIPT_TITLE][var.gral.script_title]
		- [TEMP_PATH][var.gral.temp_path]
		- [DATE][var.gral.date]
		- [HOST_NAME][var.gral.host_name]
	- [Tipograficas][var.fonts]
		- [ESC_CHAR][var.fonts.esc_char]
		- [FONT_TP][var.fonts.font_tp]
		- [FONT_FG][var.fonts.font_fg]
		- [FONT_BG][var.fonts.font_bg]
	- [Conectividad][var.connection]
		- [CHKCONNECTION][var.connection.chkconnection]
		- [GOTCONNECTED][var.connection.gotconnected]
	- [Notificaciones][var.notification]
		- [SEND_MAIL_NOTIFICATION][var.notification.send_mail_notification]
	- [Logging][var.logging]
		- [STDOUT_ENABLE][var.logging.stdout_enable]
		- [DEBUG_ENABLE][var.logging.debug_enable]
		- [LOG_ENABLE][var.logging.log_enable]
		- [LOG_PATH][var.logging.log_path]
		- [LOG_FILE][var.logging.log_file]
	- [Otros][var.other]
		- [VERSION_CHECK][var.other.version_check]
		- [WGET_TRIES][var.other.wget_tries]
		- [WGET_TIMEOUT][var.other.wget_timeout]
		- [WGET_OPTIONS][var.other.wget_options]
		- [WGET_DEBUG][var.other.wget_debug]

-----------------------------------------------------------------------------------------------

## Funciones
- <a name="chkPath"></a>*chkPath();*
		
	Chequea que el path indicado exista(1), tenga permisos de escritura(2) y permisos de lectura(3)
	# Uso / chkPath "<path>"
	# Ej: chkPath "/mnt/releases"

- <a name="chkProcess"></a>*chkProcess();*
- <a name="chkScriptIntegrity"></a>*chkScriptIntegrity();*
- <a name="chkScriptVersion"></a>*chkScriptVersion();*
- <a name="chkSsh"></a>*chkSsh();*
- <a name="chkSum"></a>*chkSum();*
- <a name="debug"></a>*debug();*
- <a name="doQuestionAndReadAnswer"></a>*doQuestionAndReadAnswer();*
- <a name="doQuestionAndReadSimpleAnswer"></a>*doQuestionAndReadSimpleAnswer();*
- <a name="getEnvironment"></a>*getEnvironment();*
- <a name="getHour"></a>*getHour();*
- <a name="getSubstring"></a>*getSubstring();*
- <a name="gotConnected"></a>*gotConnected();*
- <a name="linexy"></a>*linexy();*
- <a name="log"></a>*log();*
- <a name="remplaceString"></a>*remplaceString();*
- <a name="rotateFile"></a>*rotateFile();*
- <a name="sendMail"></a>*sendMail();*
- <a name="toLower"></a>*toLower();*
- <a name="toUpper"></a>*toUpper();*

## Variables
#### Generales
- <a name="library_version"></a>*LIBRARY_VERSION (string)*
- <a name="library_file"></a>*LIBRARY_FILE (string)*
- <a name="library_path"></a>*LIBRARY_PATH (string)*
- <a name="script_file"></a>*SCRIPT_FILE (string)*
- <a name="script_path"></a>*SCRIPT_PATH (string)*
- <a name="script_cfg_file"></a>*SCRIPT_CFG_FILE (string)*
- <a name="script_title"></a>*SCRIPT_TITLE (string)*
- <a name="temp_path"></a>*TEMP_PATH (string)*
- <a name="date"></a>*DATE (string)*
- <a name="host_name"></a>*HOST_NAME (string)*

#### Tipograficas
- <a name="esc_char"></a>*ESC_CHAR (string)*
- <a name="font_tp"></a>*FONT_TP (array - String)*
- <a name="font_fg"></a>*FONT_FG (array - String)*
- <a name="font_bg"></a>*FONT_BG (array - String)*

#### Conectividad
- <a name="chkconnection"></a>*CHKCONNECTION (boolean)*
- <a name="gotconnected"></a>*GOTCONNECTED (boolean)*

#### Notificaciones (Mail)
- <a name="send_mail_notification"></a>*SEND_MAIL_NOTIFICATION (boolean)*

#### Logging
- <a name="stdout_enable"></a>*STDOUT_ENABLE (boolean)*
- <a name="debug_enable"></a>*DEBUG_ENABLE (boolean)*
- <a name="log_enable"></a>*LOG_ENABLE (boolean)*
- <a name="log_path"></a>*LOG_PATH (string)*
- <a name="log_file"></a>*LOG_FILE (string)*

#### Otros
- <a name="version_check"></a>*VERSION_CHECK (boolean)*
- <a name="wget_tries"></a>*WGET_TRIES (int)*
- <a name="wget_timeout"></a>*WGET_TIMEOUT (int)*
- <a name="wget_options"></a>*WGET_OPTIONS (string)*
- <a name="wget_debug"></a>*WGET_DEBUG (sting)*

-----------------------------------------------------------------------------------------------

[funciones]: #funciones "Funciones"
[funciones.chkPath]: #chkPath "chkPath Function"
[funciones.chkProcess]: #chkProcess "chkProcess Function"
[funciones.chkScriptIntegrity]: #chkScriptIntegrity "chkScriptIntegrity Function"
[funciones.chkScriptVersion]: #chkScriptVersion "chkScriptVersion Function"
[funciones.chkSsh]: #chkSsh "chkSsh Function"
[funciones.chkSum]: #chkSum "chkSum Function"
[funciones.debug]: #debug "debug Function"
[funciones.doQuestionAndReadAnswer]: #doQuestionAndReadAnswer "doQuestionAndReadAnswer Function"
[funciones.doQuestionAndReadSimpleAnswer]: #doQuestionAndReadSimpleAnswer "doQuestionAndReadSimpleAnswer Function"
[funciones.getEnvironment]: #getEnvironment "getEnvironment Function"
[funciones.getHour]: #getHour "getHour Function"
[funciones.getSubstring]: #getSubstring "getSubstring Function"
[funciones.gotConnected]: #gotConnected "gotConnected Function"
[funciones.linexy]: #linexy "linexy Function"
[funciones.log]: #log "log Function"
[funciones.remplaceString]: #remplaceString "remplaceString Function"
[funciones.rotateFile]: #rotateFile "rotateFile Function"
[funciones.sendMail]: #sendMail "sendMail Function"
[funciones.toLower]: #toLower "toLower Function"
[funciones.toUpper]: #toUpper "toUpper Function"
[var]: #variables "Variables"
[var.gral]: #generales "General Variables"
[var.gral.library_version]: #library_version "Library Version Variable"
[var.gral.library_file]: #library_file "Library File Variable"
[var.gral.library_path]: #library_path "Library Path Variable"
[var.gral.script_file]: #script_file "Script File Variable"
[var.gral.script_path]: #script_path "Script Path Variable"
[var.gral.script_cfg_file]: #script_cfg_file "Script Config File Variable"
[var.gral.script_title]: #script_title "Script Title Variable"
[var.gral.temp_path]: #temp_path "Temp Path Variable"
[var.gral.date]: #date "Date Variable"
[var.gral.host_name]: #host_name "Hostname Variable"
[var.fonts]: #tipograficas "Fonts Variables"
[var.fonts.esc_char]: #esc_char "Character Escape Variable"
[var.fonts.font_tp]: #font_tp "Font Type Variable"
[var.fonts.font_fg]: #font_fg "Font Foregorund Variable"
[var.fonts.font_bg]: #font_bg "Font Background Variable"
[var.connection]: #conectividad "Connection Variables"
[var.connection.chkconnection]: #chkconnection "Chacking Connection Variable"
[var.connection.gotconnected]: #gotconnected "Got Connected Variable"
[var.notification]: #notificaciones "Notification Variables"
[var.notification.send_mail_notification]: #send_mail_notification "Send Mail Notification Variable"
[var.logging]: #logging "Logging Variables"
[var.logging.stdout_enable]: #stdout_enable "Standard Out Control Variable"
[var.logging.debug_enable]: #debug_enable "Debug Control Variable"
[var.logging.log_enable]: #log_enable "Log Control Variable"
[var.logging.log_path]: #log_path "Log Path Variable"
[var.logging.log_file]: #log_file "Log File Variable"
[var.other]: #otros "Others Variables"
[var.other.version_check]: #version_check "Version Control Variable"
[var.other.wget_tries]: #wget_tries "WGet tries Variable"
[var.other.wget_timeout]: #wget_timeout "WGet Timeout Variable"
[var.other.wget_options]: #wget_options "WGet extra Options Variable"
[var.other.wget_debug]: #wget_debug "WGet Debung control Variable"