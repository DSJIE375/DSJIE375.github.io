<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>DSJIE_个人主页</title>
</head>
<body>
    <script>
        // 设置跳转的目标URL
        const targetUrl = "http://dsjie375.cn:375";

        // 设置延迟时间（毫秒）
        const delay = 0; // 3秒

        // 使用 setTimeout 在延迟后跳转
        setTimeout(() => {
            window.location.href = targetUrl;
        }, delay);

        // 获取按钮元素
        const button = document.getElementById("jumpButton");

        // 绑定点击事件
        button.addEventListener("click", () => {
            window.location.href = targetUrl;
        });
    </script>
</body>
</html>
![](https://dsjie375.github.io/dsjie-logo-%E6%95%B4%E4%BD%93.svg)
