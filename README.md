# mock-db

## 初衷
 1. 直接简单使用mockjs并不易于管理
 2. 如果使用yapi、yii2之类的可视化管理工具，管理较为繁琐
 3. 如果用node端代理有比较复杂还需要配置node后端
 4. 如果我们有一个包，直接import xxx，然后在一个固定的目录或者配置文件中进行配置即可catch到所有url并且对齐进行定制化的mock同时这些mock配置文件都是在我们前端项目中进行管理的，这样感觉会更加舒服 hook-ajax

