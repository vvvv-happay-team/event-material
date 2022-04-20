# 基础3D图像渲染

## 参考资料

- 中文文档[3D图像渲染](https://www.nodenodenode.net/docs/libraries/3d-graphics/)


## 高阶渲染流程

参考帮助文档 ``Explanation Overview Scene Graph Basics``。

- Entities是Scene中内置的block，因而不单单是个mesh，或者是个模型，而是集成了stride引擎特征的功能块。

- Entities可以直接连接到RootScene上，或者group到RootScene上

- Entity支持父子关系的nested！

- Entity可以连接Components！

- RenderEntity是用来连接Low-Level Pipeline的节点！

## Components

因为Stride是一个游戏引擎，因而在结构上同样也采用了Entity-Component-System的架构。这一点跟unity是一样的。

