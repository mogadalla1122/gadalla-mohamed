<html>
  <head>
    <meta charset="utf-8">
    <title>App per la generazione dei temi di italiano</title>
  </head>
  <body>
    <h1>App per la generazione dei temi di italiano</h1>
    <p>Benvenuto nell'app per la generazione dei temi di italiano. Utilizza il modulo sottostante per ottenere un tema scelto a caso.</p>
    <form>
      <label for="difficulty-level">Scegli il livello di difficoltà:</label><br>
      <select id="difficulty-level" name="difficulty-level">
        <option value="easy">Facile</option>
        <option value="medium">Medio</option>
        <option value="difficult">Difficile</option>
      </select><br><br>
      <button type="submit">Genera tema</button>
    </form> 
    <div id="generated-theme"></div>
  </body>
</html>
