!doctype html>
<html lang="fr"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Formulaire d'inscription - Banque</title> 
  <link rel="stylesheet" href="styles.css"> 
 </head> 
 <body> 
  <header> 
   <h1>Bienvenue à Kévin Shop</h1> 
   <div class="welcome-message"> <marquee behavior="scroll" direction="left">
     Inscrivez-vous dès aujourd'hui pour profiter de nos services exclusifs !
    </marquee> 
   </div> 
  </header> 
  <main> 
   <form action="#" method="post"> 
    <h2>Formulaire d'inscription</h2> 
    <div class="form-group"> <label for="nom">Nom :</label> 
     <input type="text" id="nom" name="nom" required> 
    </div> 
    <div class="form-group"> <label for="prenom">Prénom :</label> 
     <input type="text" id="prenom" name="prenom" required> 
    </div> 
    <div class="form-group"> <label for="email">Email :</label> 
     <input type="email" id="email" name="email" required> 
    </div> 
    <div class="form-group"> <label for="telephone">Téléphone :</label> 
     <input type="tel" id="telephone" name="telephone" required> 
    </div> 
    <div class="form-group"> <label for="adresse">Adresse :</label> 
     <input type="text" id="adresse" name="adresse" required> 
    </div> 
    <div class="form-group"> <label for="password">Mot de passe :</label> 
     <input type="password" id="password" name="password" required> 
    </div> 
    <div class="form-group"> <label for="confirm-password">Confirmer le mot de passe :</label> 
     <input type="password" id="confirm-password" name="confirm-password" required> 
    </div> <button type="submit">S'inscrire</button> 
   </form> 
  </main> 
  <footer> 
   <p>© 2025 Kévin Shop. Tous droits réservés.</p> 
  </footer> 
 </body>
</html>
