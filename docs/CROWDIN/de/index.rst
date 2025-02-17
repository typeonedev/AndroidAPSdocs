Willkommen zur AndroidAPS-Dokumentation
==================================================

AndroidAPS ist eine Open Source App für Google Android Smartphones, die bei insulinabhängigem Diabetes als künstliche Bauchspeicheldrüse (sog. artificial pancreas system - APS) dient. Hauptkomponenten sind verschiedene OpenAPS-Softwarealgorithmen, die genau das zu tun sollen, was eine gesunde Bauchspeicheldrüse auch tut: den Blutzuckerspiegel durch automatisierte Insulindosierung (AID) in gesunden Grenzen halten.  Zusätzlich werden zumindest eine unterstützte Insulin-Pumpe und ein CGM benötigt, die eine CE-Kennzeichnung haben. 

Die App hat KEINE selbstlernende künstliche Intelligenz. Stattdessen basieren die Berechnungen von AndroidAPS auf den individuellen Therapiefaktoren und Kohlenhydratmengen, die der Benutzer manuell in sein Behandlungsprofil eingibt. Diese Eingaben werden aber aus Sicherheitsgründen vom System verifiziert. 

Die App wird nicht in Google Play angeboten - du musst sie aus rechtlichen Gründen selbst aus dem Quellcode erstellen.

Die Hauptkomponenten sind:

.. image:: images/modules-female.png
  :alt: Komponenten

Für weitere Details lies bitte hier weiter.

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Sprache wechseln

   Sprache wechseln <./changelanguage.rst>

.. _getting-started:

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Erste Schritte

   Sicherheitshinweise <./Getting-Started/Safety-first.rst>
   Was ist ein Closed Loop System <./Getting-Started/ClosedLoop.rst>
   Was ist ein Closed Loop System mit AndroidAPS <./Getting-Started/WhatisAndroidAPS.rst>  
   Insulinpumpen <./Getting-Started/Pump-Choices.md>
   Docs Updates & Änderungen <./Getting-Started/WikiUpdate.rst>

.. _what-do-i-need:

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Was brauche ich? 

   Module <./Module/module.rst>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Wie man AndroidAPS installiert

   App aus Quellcode erstellen <./Installing-AndroidAPS/Building-APK.md>
   Update auf neue Version oder Branch <./Installing-AndroidAPS/Update-to-new-version.md>
   Hinweise und Prüfungen nach dem Update auf AAPS 3.0<./Installing-AndroidAPS/update3_0.md>
   Notwendige Überprüfungen nach Aktualisierung auf AndroidAPS 2.7 <./Installing-AndroidAPS/update2_7.rst>
   Installation git <./Installing-AndroidAPS/git-install.rst>
   Fehlerbehebung Android Studio <./Installing-AndroidAPS/troubleshooting_androidstudio.md>
   Release Notes <./Installing-AndroidAPS/Releasenotes.rst>
   Dev branch (nur für Entwickler) <./Installing-AndroidAPS/Dev_branch.md>

.. _component-setup:

.. toctree::
   :maxdepth: 1
    
   :caption: Komponenten-Setup

   CGM/FGM <./Configuration/BG-Source.rst>
   xDrip Einstellungen <./Configuration/xdrip.md>
   Pumpen <./Hardware/pumps.rst>
   Smartphones <./Hardware/Phoneconfig.rst>
   Nightscout Installation <./Installing-AndroidAPS/Nightscout.md>
   Smartwatch  <./Hardware/Smartwatch.rst>

.. _configuration:

.. toctree::
   :maxdepth: 1
       
   :caption: AndroidAPS einrichten

   Konfigurations-Generator <./Configuration/Config-Builder.md>
   Einstellungen im Drei-Punkte-Menü <./Configuration/Preferences.rst>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: AndroidAPS Nutzung

   AndroidAPS-Bildschirme <./Getting-Started/Screenshots.md>
   Objectives (Ziele) <./Usage/Objectives.rst>
   OpenAPS-Funktionen <./Usage/Open-APS-features.md>   
   Berechnung der aktiven Kohlenhydrate (COB) <../Usage/COB-calculation.rst>
   Empfindlichkeitserkennung <./Configuration/Sensitivity-detection-and-COB.md>
   Profil Wechsel <./Usage/Profiles.md>
   Temporäre Ziele <./Usage/temptarget.md>   
   Verzögerte Kohlenhydrate (eCarbs) <./Usage/Extended-Carbs.rst>
   Automatisierungen <./Usage/Automation.rst>
   Careportal (eingestellt) <./Usage/CPbefore26.rst>
   Open Humans Uploader <./Configuration/OpenHumans.rst>
   Automation mit Drittanbieter-Apps <./Usage/automationwithapp.md>
   Android Auto <./Usage/Android-auto.md>  

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Allgemeine Hinweise 

   Zeitzonenwechsel auf Reisen <./Usage/Timezone-traveling.md>
   Logfiles erhalten <./Usage/Accessing-logfiles.md>
   Accu Chek Combo - Tipps <./Usage/Accu-Chek-Combo-Tips-for-Basic-usage.md> 
   Export/Import von Einstellungen <./Usage/ExportImportSettings.rst>
   xDrip+ engineering mode <./Usage/Enabling-Engineering-Mode-in-xDrip.md>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: AndroidAPS für Kinder

   Kontrolle aus der Ferne <./Children/Children.rst>
   SMS-Befehle <./Children/SMS-Commands.rst>
   Profile helper <./Configuration/profilehelper.rst>
   
.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Problembehandlung

   Problembehandlung <./Usage/troubleshooting.rst>
   Nightscout Client <./Usage/Troubleshooting-NSClient.html>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: FAQ

   FAQ <./Getting-Started/FAQ.md>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Glossar

   Glossar <./Getting-Started/Glossary.md>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Hilfe durch die Community 

   Nützliche Informationsquellen vor dem Start <./Where-To-Go-For-Help/Background-reading.md>
   Hilfe <./Where-To-Go-For-Help/Connect-with-other-users.md>
   Docs Updates & Änderungen <./Getting-Started/WikiUpdate.rst>

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Für Mediziner & Fachpersonal

   Für Mediziner & Fachpersonal <./Resources/clinician-guide-to-AndroidAPS>


.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Mithelfen in der Community

   Wie ich helfen kann <./Getting-Started/How-can-I-help.md>
   App oder Docs übersetzen <./translations.md>
   An den Docs mitschreiben <./make-a-PR>


.. note:: 
	**Disclaimer und Warnung**

	* Sämtliche Informationen, Gedanken und der Quellcode sind nur für informatorische und wissenschaftliche Zwecke. Nightscout erfüllt keinerlei Anforderungen des Datenschutzes im Gesundheitswesen. Verwenden Sie Nightscout und AndroidAPS auf eigenes Risiko und setzen Sie es nicht ein, um Behandlungsentscheidungen zu treffen.

	* Bei Nutzung des Quellcodes von github.com bestehen keinerlei Gewährleistungs- und Garantieansprüche. Es gibt keinen Support. Im Übrigen wird auf die Lizenz verwiesen, die im Repository abgerufen werden kann.

	* Sämtliche Produkt- und Herstellernamen, Handelsmarken, Dienstleistungsmarken, Warenzeichen und eingetragene Dienstleistungsmarken sind Eigentum ihrer jeweiligen Inhaber und werden nur zu Informationszwecken genutzt und nicht für Werbung oder Marketing. Ihre Verwendung dient nur zur Information und bedeutet weder, dass AAPS zu ihnen gehört, noch dass sie unterstützt werden.

	Bitte beachten: Dieses Projekt steht in keinerlei Verbindung mit `SOOIL <https://www.sooil.com/eng/>`_, `Dexcom <https://www.dexcom.com/>`_, `Accu-Chek, Roche Diabetes Care <https://www.accu-chek.com/>`_ oder `Medtronic <https://www.medtronic.com/>`_
