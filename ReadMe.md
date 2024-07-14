- Télécharger le dernier Arefact sur le lien ci-dessous (Prendre le dernier en date et non les Latest)
https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/
- Placer tout l'artefact dans le dossier "FiveM_Template"
==============================================================================================================================
- Changer le dossier de destination du fichier "cmd.bat"
Ex: on ne change que cette ligne "C:\Users\nomdupc\Desktop\FiveM_Template"
==============================================================================================================================
cd /d C:\Users\nomdupc\Desktop\FiveM_Template
C:\Users\nomdupc\Desktop\FiveM_Template\FXServer.exe +exec server.cfg
==============================================================================================================================
- Mettre une clé de licence keymaster à la ligne 15 sinon le serveur ne pourra pas démarrer la clé steam estoptionnel
set sv_licenseKey "ici"
https://keymaster.fivem.net/
==============================================================================================================================
- Vous pouvez lancer le 'cmd.bat"
==============================================================================================================================
PS: si vous souhaitez renommé votre dossier "FiveM_Template" n'oublié pas de changer les chemin de répertoire dans "cmd.bat"