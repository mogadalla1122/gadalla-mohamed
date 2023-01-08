<!DOCTYPE html>
<html>
<head>
  <title>Temi di Italiano</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
    }
    h1 {
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      text-align: left;
      padding: 20px;
    }
    form {
      display: inline-block;
      margin: 0 auto;
      text-align: left;
    }
    select {
      font-size: 16px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      width: 200px;
      margin: 10px;
    }
    textarea {
      font-size: 16px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      width: 50%;
      height: 300px;
      margin: 10px;
      resize: none;
    }
    button {
      font-size: 16px;
      padding: 10px 20px;
      border: 1px solid #333;
      border-radius: 4px;
      background-color: #333;
      color: #fff;
      cursor: pointer;
    }
    button:hover {
      background-color: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Temi di Italiano</h1>
    <p>Scegli un tema dalla lista qui sotto e inizia a scrivere:</p>
    <form>
      <label for="temi">Temi:</label><br>
      <select id="temi" name="temi">
        <option value="amore">Amore</option>
        <option value="amicizia">Amicizia</option>
        <option value="viaggi">Viaggi</option>
        <option value="famiglia">Famiglia</option>
        <option value="lavoro">Lavoro</option>
      </select>
      <br><br>
      <textarea rows="10" cols="50" placeholder="Inizia a scrivere il tuo tema qui..."></textarea>
      <br><br>
      <button type="submit">Invia il tuo tema</button>
    </form>
  </div>
</body>
</html>
