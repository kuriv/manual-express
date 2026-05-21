# 安装 Express

安装 Express 框架前，请先安装好 Node.js ，然后执行下面的命令。

```
npm install express --save
```

执行下面的代码，创建第一个示例。

```javascript
const express = require('express');
const app = express();
app.get('/', (req, res) => {
    res.send('Hello World!');
});
app.listen(9000, () => console.log('Server is running.'));
```

