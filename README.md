<!DOCTYPE html>
<html>
<head>
  <title>Fiche d'inscription</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .container {
      width: 500px;
      margin: 40px auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    label {
      display: block;
      margin-bottom: 10px;
    }
    input[type="text"], input[type="email"], input[type="password"] {
      width: 100%;
      height: 40px;
      margin-bottom: 20px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    input[type="submit"] {
      width: 100%;
      height: 40px;
      background-color: #4CAF50;
      color: #fff;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #3e8e41;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Fiche d'inscription</h2>
    <form>
      <label for="nom">Nom :</label>
      <input type="text" id="nom" name="nom" required>

      <label for="prenom">Prénom :</label>
      <input type="text" id="prenom" name="prenom" required>

      <label for="email">Adresse e-mail :</label>
      <input type="email" id="email" name="email" required>

      <label for="password">Mot de passe :</label>
      <input type="password" id="password" name="password" required>

      <label for="confirmation">Confirmer le mot de passe :</label>
      <input type="password" id="confirmation" name="confirmation" required>

      <input type="submit" value="S'inscrire">
    </form>
  </div>
</body>
</html>
