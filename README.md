# Anleitung-Crontroll-PC-Raspberry-with-Smart-Home-Device
Anleitung: PC/Raspberry steuern mit Smart-Home-Devices(Amazon/Google)

*Benötigten Programme/Datein* 
Setup Anleitung mit allen benötigten programmen zum Starten: https://www.push2run.com/setup.html

-https://ifttt.com 
-Erstelle ein Applet wähle den trigger *"Say a phrase with text ingredient"* [Wichtig]
-Applet muss mit PUSHBULLET verknüpft werden hierzu ist der Acess Token nötig. 

diesen findest du auf:
-https://www.pushbullet.com/ [Account nötig] [Settings/Account/Create Acess Token]

-http://www.push2run.com/Push2RunSetup.exe [Direct Download]

Folge der Push2Run Setup Anleitung bis alle nötigen Schirtte vollendet sind.

Applet erstellen überspringen[Download only Google Home]
-https://ifttt.com/applets/91909795d-if-you-say-computer-then-push-a-note/edit

Sprachbefehle [$ = Geben Sie ein $ ein, an dem Sie die Textzutat sagen]

variante.1		-If You say "Computer $", then Push a note  

variante.2		-befehl an computer $

variante.3		-Nutze computer für $

variante.4		-befehl an PC $

Assistent antwort:	-Sende befehl auf den computer

Language:		-German

-------------------------APPLET--CONFIG---------------

*WICHTIG Title muss SSIDHARTH*¹ sein* 

Push a note
This Action will push a new note to your Pushbullet inbox.

Title (optional)
SSIDHARTH*¹

Message (optional)
-Leer-
								
Nun kannst du Push2Run mit deinen wunsch Funktionen konfigurieren examples findest du auf
-https://www.push2run.com/examplecards.html


*¹WICHTIG DER TITLE[SSIDHARTH] IN DER APPLET MUSS IDENTISCH MIT DEN TITLE FILTER IN P2R[OPTIONS/PUSHBULLET/TITLE FILTER= SSIDHARTH]SEIN*
