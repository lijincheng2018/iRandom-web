# iRandom-web
简易的网页抽号器



## 展示图

![展示图](https://github.com/lijincheng2018/iRandom-web/blob/main/img/展示图.png)



## 用法

打开`data.js`配置数据

打开后是这样的：

```js
function getData() {
    let data = [
        {
            name: '李锦成'
        }, {
            name: '测试者1'
        }, {
            name: '测试者2'
        }
    ];
    return data;
}

```

其中data为JSON数组，你可以将里面的{name: ' '}修改成抽取的姓名

name字段是必须的

#### 配置完数据后，双击运行`index.html`即可
注意，index.html和data.js需要在同一目录下！
