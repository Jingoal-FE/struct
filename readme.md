
#####`目录结构描述`
> `README.md` // 帮助文档
> `dep` // 第三方 js 组件
>> `zepto.js`
>> `[.].js`
> `doc` // 项目相关文档
> `mock` // Mock 后端数据文件夹
>> `api.js`
>> `1000.json`
>> `[.].json`
> `src` // 项目源文件
>> `common` // 公共目录
>>> `css` // 样式目录
>>> `img` // 图片目录
>>> `ui` // ui 交互目录
>>>>> `sticky` // sticky
>>>>>> `sticky.js`
>>>>> `...` // 其他交互组件
>>> `page.js` // page 基类
>>> `util.js` // 工具包 基类
>>> `[.].js` // 基类
>> `index` // 首页 入口目录
>>> `index.js` // 首页js 入口
>>> `index.scss`
>>> `index.tpl`
>> `detail` // 详情 入口目录
>>> `[module folder]` // 如果页面复杂，可以在目录下建立单独的文件夹来存放各种小的业务 js
>>> `detail.js` // detail js 入口
>> `config.js` // js 相关的基础配置
> `tool` // 构建相关等与开发无关的工具包
> `config.js` // 构建配置文件
> `gulpfile.js`
> `make.webpack-config.js` // webpack 配置
> `package.json`