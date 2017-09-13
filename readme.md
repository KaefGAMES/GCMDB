#############################################################################
#####                                                                   #####
#####        GGGGGGGG	  CCCCC   MM      MM     DDDDDDD    BBBBBBB 	#####
#####       GG      	 CC       M M    M M     D     DD   B      B   	#####
#####      GG    GGG	CC        M  M  M  M     D      D   BBBBBBB    	#####
#####       GG     GG	 CC       M   MM   M     D     DD   B      B   	#####
#####        GGGGGGG	  CCCCC   M        M     DDDDDDD    BBBBBBB    	#####
#####                                  for tbc-db, based on GMDB 0.7    #####
#############################################################################

Milestone 0.7.1:

Wir bieten euch mit jedem Milestone zwei M�glichkeiten eure Datenbank zu patchen!

1. Ersetzen der englischen DB-Eintr�ge: (GMDB_ver_0.7.1 _template.sql)
---------------------------------------
	Jeder englischer DB-Eintrag wird durch einen deutschen ersetzt.
	Die englische Sprache ist nach dem Patchvorgang nicht mehr verf�gbar.
	Auch Spieler, die z. B. mit einem englischen Client connecten, finden nur die deutsche Sprache vor.
	

2. Nutzung der "locales_*" Tabellen: (GMDB_ver_0.7.1 locales_.sql)
------------------------------------------
	Hierbei werden die "locales_*" Tabellen gef�llt!
	Nach dem Patchvorgang ist es Clientabh�ngig welche Sprache euch angezeigt wird!
	Z.B. wenn ihr einen englischen Client habt, wird euch alles in englischer Sprache angezeigt, 
	     habt ihr jedoch einen deutschen Client werden euch die Texte in deutscher Sprache angezeigt!
	INFO: Weitere Sprachen (wie Franz�sisch oder Spanisch) sind nur verf�gbar wenn ihr euch die entsprechenden 
	      Patchfiles besorgt (wir sind nur das Projekt f�r die deutsche Sprache).



Die Extra-�bersetzungen ("areatrigger_tavern", "areatrigger_teleport", "command", "transports") findet ihr in einer 
extra Datei (GMCDB_ver_0.7.1 extras.sql). Keine dieser �bersetzungen hat multilanguagesupport. 
Es werden also beim patchen alle englischen Eintr�ge �berschrieben!

Der Datei "GMDB_ver_0.7.1 scriptdev2.sql" �bersetzt die Texte von Bossen und NPCs, die von SD2 bzw. ACID gescripted wurden.
Solltet ihr auch diese Texte �bersetzt haben wollen, so m�sst ihr die Datei in eure ScriptDev2 Datenbank patchen!
(Hier ist die sp�tere Anzeige auf Deutsch clientabh�ngig: 
Englischer Client = englische Sprache, deutscher Client = deutsche Sprache)


#############################################################################
#####                                                                   #####
#####        GGGGGGGG	  CCCCC   MM      MM     DDDDDDD    BBBBBBB 	#####
#####       GG      	 CC       M M    M M     D     DD   B      B   	#####
#####      GG    GGG	CC        M  M  M  M     D      D   BBBBBBB    	#####
#####       GG     GG	 CC       M   MM   M     D     DD   B      B   	#####
#####        GGGGGGG	  CCCCC   M        M     DDDDDDD    BBBBBBB    	#####
#####                                  for tbc-db, based on GMDB 0.7    #####
#############################################################################