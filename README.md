## 自用PPT
### 使用方法
body 末尾添加 ppt.js，引用 ppt.css 样式，按照如下格式写html

    <html>
    <head></head>
    <body>
        <div class="index">
            <ul>
            </ul>
        </div>
        <div class="view">
            <div class="page" data-title="title of page1">
                <div class="page-container">
                    <h1>Page1</h1>
                </div>
            </div>
            <div class="page" data-title="title of page2">
                <div class="page-container">
                    <h1>Page2</h1>
                </div>
            </div>
        </div>
    <body>
    <script src="ppt.js"></script>
    </html>
