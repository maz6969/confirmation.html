<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Confirmation Page</title>
</head>
<body>
  <h1>Thank you for completing the questionnaire!</h1>
  <div id="dynamicContent"></div>

  <script>
    // Extract response parameter from the URL
    const urlParams = new URLSearchParams(window.location.search);
    const response = urlParams.get('response');

    // Update the content dynamically
    document.getElementById('dynamicContent').innerHTML = response;
  </script>
</body>
</html>
