# Test


<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image responsive</title>

  <style>
    /* --- Mise en page simple et centrée --- */
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background-color: #f5f5f5;
    }

    /* --- Image responsive --- */
    img {
      max-width: 100%;   /* ne dépasse jamais la largeur de l'écran */
      height: auto;      /* garde les proportions */
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
  </style>
</head>

<body>
  <img 
    src="https://github.com/user-attachments/assets/0480379e-0507-41ca-a736-ffc528856ef1"
    alt="9fc046d9-d713-462e-b6ad-0e832036a5a5">
</body>
</html>

