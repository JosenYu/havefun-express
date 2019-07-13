# havefun-express

## mongoose

[mongoose 官方文档](https://cn.mongoosedoc.top/docs/index.html)

1. 链接 mongodb 需要通过 mongoose 插件
   > npm i mongoose --save
2. 创建 schema 对象

   ```js
   const Schema = mongoose.Schema;
   ```

3. 创建 model 实例化 schema

    ```js
    let data = mongoose.model("official", dataSchema);
    ```
