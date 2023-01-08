<!DOCTYPE html>
<html>
<head>
 <title>Sito di scrittura di temi con intelligenza artificiale</title>
 <meta charset="utf-8">
 <style>
  * {
   box-sizing: border-box;
  }
  body {
   font-family: Arial, sans-serif;
   margin: 0;
   padding: 0;
   background-color: #f4f4f4;
  }
  header {
   background-color: #333;
   color: #fff;
   padding: 20px;
   text-align: center;
  }
  header h1 {
   margin: 0;
   font-size: 36px;
  }
  .container {
   max-width: 1200px;
   margin: 0 auto;
   padding: 20px;
  }
  .topic-form {
   display: flex;
   align-items: center;
   margin-bottom: 20px;
  }
  .topic-form input {
   border: 1px solid #ccc;
   padding: 10px;
   font-size: 16px;
   width: 75%;
   border-radius: 5px 0 0 5px;
  }
  .topic-form button {
   background-color: #333;
   color: #fff;
   border: 0;
   padding: 10px 20px;
   font-size: 16px;
   border-radius: 0 5px 5px 0;
   cursor: pointer;
  }
  .topics {
   display: flex;
   flex-wrap: wrap;
   margin-bottom: 20px;
  }
  .topics .topic {
   background-color: #fff;
   border: 1px solid #ccc;
   padding: 20px;
   margin-right: 20px;
   margin-bottom: 20px;
   width: calc(33.333% - 20px);
   box-sizing: border-box;
   text-align: center;
   cursor: pointer;
   transition: all 0.2s ease-in-out;
   box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .topics .topic:hover {
   transform: scale(1.1);
   box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  .topics .topic h2 {
   margin: 0;
   font-size: 24px;
   color: #333;
  }
  .selected-topic {
   display: none;
  }
    </form>
  </div>
</body>
</html>
