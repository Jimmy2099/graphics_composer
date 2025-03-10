# graphics_composer

graphics_composer = graphic + windows manager + mouse + input + protocol

致力于打造一个可以简单重复利用的 graphics_composer 中间模块，方便在各种系统中集成和使用。

#### 组成部分
graphic
❌ 不会包含 OpenGL 和 Vulkan 的渲染代码部分

windows manager
✔ 提供窗口管理功能

mouse
✔ 支持鼠标操作

input
✔ 处理输入设备

protocol
❌ 提供简单协议，但不会过于复杂，可以很简单地集成到 Wayland 和 X11

VR
.... 后续可能会扩展支持 VR


