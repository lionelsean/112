<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>资源列表</title>
    <style>
        /* 通用样式 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f6f8;
            color: #333;
        }
        header {
            background-color: #0078D4;
            color: white;
            text-align: center;
            padding: 1rem;
            font-size: 1.8rem;
        }
        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1.5rem;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h2 {
            color: #0078D4;
            text-align: center;
            margin-bottom: 1rem;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 0.8rem 0;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 6px;
            background-color: #f9f9f9;
            transition: all 0.3s ease;
        }
        li:hover {
            background-color: #eef6ff;
            border-color: #0078D4;
        }
        a {
            text-decoration: none;
            color: #0078D4;
            font-size: 1rem;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        /* 特别提示样式 */
        .highlight {
            margin: 2rem 0;
            text-align: center;
            padding: 1rem;
            font-size: 1.2rem;
            font-weight: bold;
            color: #0078D4;
            background-color: #e8f4ff;
            border: 2px solid #0078D4;
            border-radius: 6px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% {
                box-shadow: 0 0 10px rgba(0, 120, 212, 0.5);
            }
            50% {
                box-shadow: 0 0 15px rgba(0, 120, 212, 0.7);
            }
            100% {
                box-shadow: 0 0 10px rgba(0, 120, 212, 0.5);
            }
        }
    </style>
</head>
<body>
    <!-- 顶部标题 -->
    <header>资源列表</header>

    <!-- 页面主体 -->
    <main>
        <h2>设计资源导航</h2>
        <ul>
            <li>
                <a href="https://mastergo.com/goto/FuUvneXS?file=128862103934092" target="_blank">PC端组件库</a>
            </li>
            <li>
                <a href="https://mastergo.com/goto/FuUocFQ8?file=122968394889071" target="_blank">移动端组件库</a>
            </li>
            <li>
                <a href="https://mastergo.com/goto/FuUtOpcL?file=61833409762430" target="_blank">图标库</a>
            </li>
        </ul>

        <!-- 特别提示 -->
        <div class="highlight">
            体验小助手，请点击右下角进行对话。
        </div>
    </main>

    <!-- 集成 Coze Web SDK 并默认展开 -->
    <script src="https://lf-cdn.coze.cn/obj/unpkg/flow-platform/chat-app-sdk/1.0.0-beta.4/libs/cn/index.js"></script>
    <script>
        new CozeWebSDK.WebChatClient({
            config: {
                bot_id: '7442536183781244965',
            },
            componentProps: {
                title: 'Coze',
                defaultOpen: true, // 聊天窗口默认展开
            },
        });
    </script>
</body>
</html>
