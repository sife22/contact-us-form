<p align="center"><a href="https://www.php.net/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Webysther_20160423_-_Elephpant.svg/2560px-Webysther_20160423_-_Elephpant.svg.png" width="400" alt="PHP Logo"></a></p>

# Form Submit to Send Email
La page index.php permet d'envoyer un email à partir d'un formulaire de contact.

## Fonctionnalités
- Formulaire de contact avec champs nom, email, téléphone et message
- Validation des champs obligatoires
- Envoi de l'email au destinataire défini
- Affichage d'un message de succès ou d'erreur après l'envoi

## Configuration requise
- PHP 5.3 ou supérieur
- Serveur web (Apache, Nginx, etc.)

## Installation
1. Clonez le dépôt Git :
   git clone https://github.com/sife22/contact-us-form.git
2. Accédez au répertoire du projet :
   cd contact-us-form
3. Ouvrez le fichier 'index.php' et modifiez l'adresse email du destinataire ('$toEmail') selon vos besoins.
4. Copiez les fichiers dans le répertoire web de votre serveur.
5. Accédez à l'application dans votre navigateur.

## Utilisation
1. Remplissez le formulaire avec vos informations.
2. Cliquez sur le bouton "Submit" pour envoyer le message.
3. Un message de succès ou d'erreur s'affichera en fonction du résultat de l'envoi de l'email.
