Ethereal Script ✨
![EDIT_20260202_202842](https://github.com/user-attachments/assets/dfc1384f-9433-4051-9c42-bb4aad9242c0)


🌌 代码即画布，粒子即像素

 Ethereal-Script是一个基于Fabric的一个面向广大开发者的粒子系统编程框架

🎯 核心理念

· 无限表达：数学函数、算法、动态系统都能直接转化为视觉
· 精准控制：每一颗粒子都听从你的逻辑指令
· 实时创作：修改代码，立即看到效果，无需重新编译
· 可重复使用：构建自己的粒子库，分享给社区

🚀 愿景

我们正在构建一个完全编程驱动的粒子引擎，目标是：

· 支持10万+粒子的实时渲染
· 提供多语言脚本支持（JavaScript/Python/Lua）
· 实现物理精确的粒子行为
· 创建可组合的粒子组件系统

🛠️ 技术栈

```
Minecraft Fabric API
OpenGL Compute Shaders
实时脚本解释器
GPU加速粒子物理
```

📦 架构预览

```javascript
// 这就是Et实在的编码体验
const galaxy = ParticleSystem.create("galaxy")
  .withSource(SpiralGalaxy({
    arms: 3,
    stars: 50000,
    darkMatter: true
  }))
  .withBehavior(OrbitalDynamics())
  .withShader(NebulaShader())
  .render();
```

🔥 你能创造什么？

数学之美

```python
# 傅里叶级数可视化
fourier = FourierSeries([1, 0.5, 0.3, 0.2])
wave = fourier.visualize(1000)
```

动态艺术

```javascript
// 实时音频可视化
audio.analyze().transform(
  fft => waterfallPlot(fft)
    .colorByFrequency()
    .animateWithMusic()
);
```

生成艺术

```java
// 分形粒子系统
MandelbrotSet fractal = new MandelbrotSet(iterations=1000);
fractal.renderAsParticles(20000)
       .colorByEscapeTime()
       .zoomAnimation(60);
```

🤝 加入我们！

我们需要这样的你：

· 🔧 图形渲染开发者 - 帮我们突破性能极限
· 📐 数学/物理爱好者 - 设计优雅的数学接口
· 🎨 创意程序员 - 创造令人惊叹的粒子效果
· 📚 文档写手 - 让API变得亲切友好
· 🧪 测试狂人 - 确保每一行代码都坚如磐石

如何参与？

1. 🌟 Star 这个项目（第一步最重要！）
2. 📖 阅读 架构设计文档
3. 🔧 选择你感兴趣的模块
4. 💡 提出你的创意想法
5. 🚀 提交第一个PR！

📁 项目结构

```
ethereal-script/
├── core/          # 核心渲染引擎
├── scripting/     # 脚本解释器
├── math/          # 数学函数库
├── api/           # 公共API
├── examples/      # 示例代码库
└── docs/          # 完整文档
```

🎮 快速体验

```bash
# 克隆项目
git clone 

# 查看示例
cd examples/
code mandelbrot.es  # 打开分形示例
```

📈 路线图

Phase 1: 基础渲染 (进行中)

· 粒子批量渲染系统
· 基础脚本解释器
· 2D图形API

Phase 2: 动态系统 (规划中)

· 物理引擎集成
· 音频可视化
· 3D变换支持


💬 社区

· 📢 QQ群聊 - 2359814041

📄 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。

🙏 致谢

特别感谢所有早期贡献者，是你们让这个疯狂的想法开始变成现实。


加入我们!
本README会随着项目发展不断更新。最后一次更新：2026年1月
