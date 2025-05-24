<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oni Event Reward</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <button onclick="openRewardWindow()">Click here to get the limited Oni event reward</button>

    <script>
        function openRewardWindow() {
            var message = "His Brawl Stars account is blocked due to you entering a malicious link. You can contact Supercell to recover this account.";
            var newWindow = window.open("", "_blank", "width=400,height=200");
            newWindow.document.write("<html><head><title>Warning</title></head><body>");
            newWindow.document.write("<p>" + message + "</p>");
            newWindow.document.write("</body></html>");
            newWindow.document.close();
        }
    </script>

</body>
</html>
