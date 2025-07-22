# Vibe Coding 电子书APP 📚

[![iOS](https://img.shields.io/badge/iOS-14.0%2B-blue)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.0-orange)](https://swift.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 项目概述 🎯

Vibe Coding 是一款专注于视频编码技术学习的移动端电子书应用，提供系统化的学习路径和激励机制。应用采用 Swift/SwiftUI 开发，支持 iOS 14.0+ 系统，为视频编码技术初学者、计算机视觉工程师、多媒体开发者和相关专业学生提供优质学习体验。

## 功能特点 ⭐

### 1. 章节阅读 📖
- 13章系统化学习内容，涵盖视频编码全流程
- 支持离线阅读，无网络依赖
- 代码高亮显示，图片缩放查看
- 个性化阅读体验（字体大小调节、夜间/日间模式）
- 书签和搜索功能

### 2. 激励系统 🏆
- 章节完成徽章和里程碑徽章
- 学习时长和连续学习徽章
- 个性化章节证书和课程完成证书
- 证书分享功能

### 3. 学习管理 📊
- 实时进度追踪和学习统计
- 学习日历视图
- 个人中心和徽章收藏展示

## 技术架构 🔧

- **前端框架**: Swift/SwiftUI
- **本地存储**: Core Data / SQLite
- **图片资源**: 本地Bundle资源
- **用户数据**: UserDefaults + Core Data
- **证书生成**: PDF Kit

## 项目结构 📁

```
├── App/                  # 应用入口和配置
├── Features/             # 功能模块
│   ├── Reading/          # 阅读功能
│   ├── Achievements/     # 成就系统
│   ├── Profile/          # 个人中心
│   └── Library/          # 书籍库
├── Core/                 # 核心组件
│   ├── Models/           # 数据模型
│   ├── Services/         # 服务层
│   └── Utils/            # 工具类
├── Resources/            # 资源文件
│   ├── Content/          # 章节内容
│   ├── Images/           # 图片资源
│   └── Fonts/            # 字体资源
└── UI/                   # UI组件
    ├── Components/       # 可复用组件
    ├── Styles/           # 样式定义
    └── Animations/       # 动画效果
```

## 开发路线 🚀

### Phase 1 (MVP)
- 基础阅读功能
- 13个章节内容展示
- 简单的进度追踪
- 基础徽章系统

### Phase 2
- 证书生成功能
- 高级阅读体验（夜间模式、字体调节）
- 完整的成就系统

### Phase 3
- 学习统计分析
- 社交分享功能
- 用户体验优化

## 章节内容 📖

1. **第1章**: Vibe Coding 基础概念
2. **第2章**: 数字视频基础
3. **第3章**: 视频压缩原理
4. **第4章**: H.264/AVC 标准
5. **第5章**: H.265/HEVC 标准
6. **第6章**: VP9 和 AV1 编码
7. **第7章**: 运动估计与补偿
8. **第8章**: 变换编码技术
9. **第9章**: 熵编码方法
10. **第10章**: 率失真优化
11. **第11章**: 实时编码技术
12. **第12章**: 编码器实现
13. **第13章**: 未来发展趋势

## 安装与运行 ⚙️

### 环境要求
- Xcode 13.0+
- iOS 14.0+
- Swift 5.0+

### 安装步骤

1. 克隆仓库
```bash
git clone git@github.com:yourusername/vibe-coding-app.git
cd vibe-coding-app
```

2. 安装依赖
```bash
pod install  # 如果使用CocoaPods
# 或
swift package resolve  # 如果使用Swift Package Manager
```

3. 打开项目
```bash
open VibeCoding.xcworkspace  # 如果使用CocoaPods
# 或
open VibeCoding.xcodeproj  # 如果使用Xcode项目
```

4. 运行应用
   - 选择目标设备（iPhone或iPad模拟器）
   - 点击运行按钮或按下 `Cmd+R`

## 贡献指南 👥

我们欢迎所有形式的贡献，无论是新功能、文档改进还是bug修复。请遵循以下步骤：

1. Fork 仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'feat: add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

## 版本控制 🔄

本项目使用 [语义化版本控制](https://semver.org/lang/zh-CN/)。查看 [tags](https://github.com/yourusername/vibe-coding-app/tags) 获取已发布的版本。

## 许可证 📄

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件。

## 联系方式 📧

项目维护者 - [@yourusername](https://github.com/yourusername)

项目链接: [https://github.com/yourusername/vibe-coding-app](https://github.com/yourusername/vibe-coding-app)

---

*Vibe Coding - 让视频编码学习更简单、更有趣！*