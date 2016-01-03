# jeuRuby
Environnement windows
http://railsinstaller.org/fr-FR
Faire l’installation à la racine du C:\

Dans le dossier Rubyxxxxcréer un dossier DevKit

Téléchargerle Development Kitun peu plus bas sur la page, en prenant le soinde bien prendre la version qui va avec votre ruby.

Installer dans le dossier DevKit.

Ouvrir une fenêtre dos et ce positionner à l’intérieur du dossier devKit

Lancer cette suite de commande

ruby dk.rb init

ruby dk.rb install

gem install json --platform=ruby

ruby -rubygems -e "require 'json'; puts JSON.load('[42]').inspect"

Sortir du dossier devKit

Ce position dans le dossier ruby et dans le terminal cmd lancer
