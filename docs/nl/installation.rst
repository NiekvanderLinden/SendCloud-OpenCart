***********
Installatie
***********

**Opmerking!** Een SendCloud is nodig om deze extensie te gebruiken. Je kunt `hier <https://www.sendcloud.nl/aanmelden/?r=OpenCartDocs>`_ een account aanvragen.

1.  De SendCloud Extensie downloaden.
=====================================
De gemakklijkste manier om de extensie te bemachtigen is via de OpenCart Extensie Winkel

.. include:: ../../README.rst
	:start-after: Extension Store:
	:end-before: SendCloud

2.  De SendCloud Extensie uitpakken
===================================
Pak het zip bestand uit op een locatie naar keuze op je computer.

.. image:: ../images/unzip.png
 
3.  vQmod Installeren
=====================
Als je vQmod al geïnstalleerd hebt kun je deze stap overstaan. Ga verder met :ref:`stap 4 <step-four>`.

1. Download de laatste versie van vQmod voor OpenCart vanaf GitHub:
	https://github.com/vqmod/vqmod/releases

2. 	De makkelijkste manier op vQmod te installeren is aan de hand van deze video:
	http://youtu.be/ezS1jWoMmjc

3.	Of je kunt deze handleiding volgen:
	https://github.com/vqmod/vqmod/wiki/Installing-vQmod-on-OpenCart

.. _step-four:

4.  De SendCloud Extensie uploaden
==================================
Verbind met je webwinkel middels je favoriete FTP client. Als je nog geen FTP client hebt kun je `FileZilla <https://filezilla-project.org/>`_ gebruiken.

Upload de bestanden uit de ``upload`` in de extensie map naar je webwinkel.

.. image:: ../images/upload.png
 
5.  De SendCloud API sleutels bemachtigen
=========================================
Login in het `SendCloud Panel <https://panel.sendcloud.nl>`_  met je SendCloud account.  Kies ``Instellingen -> API``.

.. image:: ../images/api_keys.png
 
Kopieer de public en secret key.
 
 
6.  Activeren van de SendCloud Extensie
=======================================
Login in de OpenCart admin. Ga naar ``Extensies -> Modules`` en klik op de groene knop bij de SendCloud Extensie. 

.. image:: ../images/extension_install.png
 
De SendCloud extensie is nu geïnstalleerd. 

7.  De SendCloud Extensie instellen
===================================
Klik op de blauwe "edit" knop. 

.. image:: ../images/extension_edit.png
 
Voer je API public & secret key in. Kies de order status die je wilt instellen na het exporteren en sla de instellingen op.