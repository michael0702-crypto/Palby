
<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <title>Chat med os</title>
</head>
<body>
    <h1>Velkommen til Palby chat. Snak med os via Chatboksen herunder.</h1>

    <script type="text/javascript">
        const scriptElement = document.createElement("script");
        scriptElement.async = true;
        scriptElement.src = "https://magicwidget.socialboards.com/magic-widget.js";
        document.body.appendChild(scriptElement);
    </script>
    <script>
        const options = {
            community: 'palbymarine',
            widgetId: 2394,
        }
        window.magicWidgetAsyncInit = function () {
            magicWidget.initializeAsync(options)
        }
    </script>
</body>
</html>
