<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coze Web SDK</title>
</head>
<body>
    <h1>欢迎访问 Coze Chat</h1>
    <div id="chat-container"></div>

    <script src="https://lf-cdn.coze.cn/obj/unpkg/flow-platform/chat-app-sdk/1.0.0-beta.4/libs/cn/index.js"></script>
    <script>
        new CozeWebSDK.WebChatClient({
            config: {
                bot_id: '7442536183781244965',
            },
            componentProps: {
                title: 'Coze',
            },
        });
    </script>
</body>
</html>
