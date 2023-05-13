# 待实现
- 把class名重新定义，减小css体积
- 把相同属性内容的css合并为同一个，减小css体积
- 提取公用内容，减小css体积
- 编写代码提示插件
- 兼容unocss的预设
- 配置文件改变自动更新
- 实现伪类
- 实现深度选择
- 使用单独的配置文件
- 在页面内直接写style样式，然后插件转换为class样式
- 提供自定义css规则的网页工具，生成自己css规则

# 已实现
- 不需要手动导入css，css文件默认不需要引入 
- 触发css的修改，内容生成在app.vue文件中
- 把每次修改文件输出css，改为虚拟的内容
- 添加一个css生成成功的提示
- 可以生成css作为预览