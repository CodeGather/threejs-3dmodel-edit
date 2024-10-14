### 🌱 基于 Three.js+Vue3+Typescript+Element-Plus 开发的 3d 模型可视化编辑系统

<a href='https://gitee.com/ZHANG_6666/Three.js3D/stargazers'><img src='https://gitee.com/ZHANG_6666/Three.js3D/badge/star.svg?theme=dark' alt='star'></img></a> <a href='https://gitee.com/ZHANG_6666/Three.js3D/members'><img src='https://gitee.com/ZHANG_6666/Three.js3D/badge/fork.svg?theme=dark' alt='fork'></img></a>

### 📦️ 分支介绍

1. master: `Vue3+Pinia+Javascript` (最新的功能 issues 和修复的 bug 都在这个分支)
2. ts-master: `Vue3+Pinia+Typescript` (master 分支的 typescript 版本)
3. develop: `Vue3+Pinia+Javascript` (一些不确定的功能和代码重构会在这个分支开发)
4. gh-pages: `git-pages 线上包分支` (忽略即可)

### 🌐 安装/启动/打包(详见 package.json)

```
 yarn  / yarn serve  / yarn build(yarn build:pro)

```

### 🎨 预览

- 1.注意:部分模型文件较大,首次加载需要等待较长时间
- 2.线上访问:[https://zhangbo126.github.io/threejs-3dmodel-edit/](https://three3d-0gte3eg619c78ffd-1301256746.tcloudbaseapp.com/threejs-3dmodel-edit/)
- 3.关于打包部署服务端:在 vite.config.js 里修改 base 路径来适配当前的域名路径

### 项目地址

- 1. github:[https://github.com/zhangbo126/threejs-3dmodel-edit](https://github.com/zhangbo126/threejs-3dmodel-edit)
- 2. gitee:[https://gitee.com/ZHANG_6666/Three.js3D](https://gitee.com/ZHANG_6666/Three.js3D)

### 🎵 主要技术栈

| 名称                     | 版本    | 名称         | 版本  |
| ------------------------ | ------- | ------------ | ----- |
| Vue                      | 3.2.x   | Axios        | 1.5.0 |
| Vite                     | 4.3.x   | Element-plus | 2.4.x |
| Three                    | 0.167.x | Pinia        | 2.1.x |
| Vue3-Draggable-Resizable | 1.6.x   | Mitt         | 3.0.x |
| 详见 `package.json`      | 😁      | 🥰           | 🤗    |

### 🌺 开发环境:

| 名称 | 版本    | 名称    | 版本   |
| ---- | ------- | ------- | ------ |
| node | 18.19.0 | npm     | 10.2.3 |
| yarn | 1.22.21 | windows | 10     |

### 🍻 问题/功能

1. 任何问题 bug 和功能需求欢迎提 issues
2. 更多功能持续更新中...

### 🗃️ 功能模块介绍

| 模块名称🚀     | 功能简介         | 功能简介                  | 功能简介                           | 功能简介          |
| -------------- | ---------------- | ------------------------- | ---------------------------------- | ----------------- |
| 背景           | 背景图加载       | 全景图加载                | 外部全景图（hdr,jpeg,png）         | 外部视频（video） |
| 材质           | 材质类型切换     | 材质选中效果              | 材质属性修改（颜色，网格，透明度） | 材质贴图修改      |
| 后期处理       | 模型分解         | 模型材质拖拽，缩放，平移  | 辉光效果（颜色，强度，半径 ）      |                   |
| 模型灯光       | 环境光编辑       | 平行光编辑                | 点光源编辑                         | 聚光灯编辑        |
| 模型动画       | 动画播放         | 动画配置修改              | 动画轴旋转（x,y,z）                |                   |
| 辅助线/轴配置  | 轴旋转（x,y,z）  | 模型位置修改              | 网格辅助线                         | 坐标轴辅助线      |
| 几何体模型配置 | 几何体模型选中   | 几何体模型配置修改        |                                    |                   |
| 3d标签配置     | 标签拖拽加载渲染 | 标签选中                  | 标签内容编辑                       |                   |
| 多模型配置     | 多模型选中效果   | 多模型位置,轴旋转修改     | 多模型大小缩放                     |                   |
| 左侧操作栏     | 编辑模型场景切换 | 几何体模型添加            | 外部模型加载                       | 多模型拖拽        |
| 顶部操作栏     | 模型预览         | 模型导出（.glb,obj,usdz） | 嵌入代码                           | 编辑数据保存      |
| 模型库         | 模型编辑效果展示 | 模型拖拽添加              | three.js3d模型在可视化大屏上展示   |                   |

### 💥 注意

1. 部分功能的使用对电脑的内存依赖较高，如有卡顿等场景请确保有足够的内存使用空间
2. 建议使用谷歌浏览器`（chrome）`
3. 模型数据编辑配置存储在`localStorage`如有数据相关报错清除本地数据缓存重新进入即可
4. 外部模型不支持效果预览，和数据保存
5. 3d 模型对性能依赖较高,模型库组件配置过`(>4)`,可能导致浏览器崩溃
6. 部分特殊模型文件和大模型文件加载可能会导致系统卡顿很长时间,如遇到这种情况`（欢迎提issues）`

### 💚 如果觉得该项目对你有帮助留个 star 也是不错的 ⭐

### 🥰 或者请作者喝杯咖啡吧,这将是我持续更新的动力,相信这肯定比打赏主播更有意义

![输入图片说明](public/image/code.jpg)

### 👷 界面

![输入图片说明](public/image/1.png)
![输入图片说明](public/image/2.png)
![输入图片说明](public/image/3.png)
![输入图片说明](public/image/4.png)
![输入图片说明](public/image/6.png)
![输入图片说明](public/image/7.png)
![输入图片说明](public/image/8.png)

### 🍻 相关链接

###### Three.js:[https://threejs.org/](https://threejs.org/)

###### Element-Plus:[https://element-plus.gitee.io/zh-CN/](https://element-plus.gitee.io/zh-CN/)

###### 模型下载网站 [https://sketchfab.com/feed](https://sketchfab.com/feed)

###### 贴图素材网站 [https://polyhaven.com/](https://polyhaven.com/)

###### 图片格式转换网站 [https://onlineconvertfree.com/zh/convert/hdr/](https://onlineconvertfree.com/zh/convert/hdr/)
