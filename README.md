# CircuLeather – Beheersysteem

## 1. Over het project
CircuLeather is een webapplicatie waarmee leerpartijen en opslaglocaties beheerd kunnen worden. Het systeem is ontwikkeld om gegevens overzichtelijk op te slaan en eenvoudig terug te vinden.

## 2. Gebruikte technologieën
- PHP – voor de werking van de applicatie.
- MySQL – voor het opslaan van gegevens.
- HTML – voor de structuur van de webpagina's.
- CSS – voor de vormgeving.
- XAMPP – om de applicatie lokaal te draaien.

## 3. Benodigdheden
Om het project te installeren heb je nodig:
- XAMPP
- Een webbrowser
- De projectbestanden van CircuLeather

## 4. Installatie-instructies

### Stap 1: XAMPP installeren
Download en installeer XAMPP via https://www.apachefriends.org/.

### Stap 2: Projectbestanden plaatsen
1. Download of kloon dit GitHub-project.
2. Plaats de projectmap in de map `htdocs` van XAMPP.
3. Zorg dat de projectmap bijvoorbeeld `CircuLeather_website` heet.

### Stap 3: Apache en MySQL starten
1. Open het XAMPP Control Panel.
2. Start Apache.
3. Start MySQL.

### Stap 4: Database instellen
1. Open http://localhost/phpmyadmin.
2. Maak de database aan die in `config.php` wordt gebruikt.
3. Importeer het bestand `install.sql` om de benodigde tabellen aan te maken.

### Stap 5: Verbinding controleren
Controleer of de databasegegevens in `config.php` overeenkomen met jouw lokale MySQL-instellingen.

### Stap 6: Applicatie openen
Open de browser en ga naar:

http://localhost/CircuLeather_website/

## 5. Screenshot van de werkende applicatie





## 6. Functionaliteiten
- Leerpartijen beheren.
- Opslaglocaties beheren.
- Gegevens toevoegen, bekijken, wijzigen en verwijderen.
- Zoeken naar leerpartijen.
- Foto's toevoegen aan leerpartijen.
- Inloggen in de applicatie.

## 7. Projectstructuur
- `config.php` – instellingen voor de databaseverbinding.
- `login.php` – inloggen.
- `auth.php` – controleren of een gebruiker is ingelogd.
- `functions.php` – gedeelde functies.
- `leerpartijen.php` – overzicht en beheer van leerpartijen.
- `partij_toevoegen.php` – een leerpartij toevoegen.
- `locaties.php` – opslaglocaties bekijken en beheren.
- `install.sql` – database en tabellen installeren.
- `style.css` – vormgeving van de applicatie.

## 8. Auteur
CircuLeather – schoolproject.

