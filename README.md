<html>
  <body>
    <h2>--</h2>
    <p>0-0</p>
    <p id="error_message"></p>
    <script>
      try {
        alert("WARNING! your devices data is corrupted! press ok to ignore and risk data corruption!");
      }
      catch(err) {
        document.getElementById("error_message").innerHTML = err.message;
      }
    </script>
  </body>
</html>
