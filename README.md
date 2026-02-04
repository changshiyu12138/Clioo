# Clio Collection

一个用于收藏影视和书籍的 Android 应用程序。

## 项目简介

Clio Collection 是一款简洁高效的影视书籍收藏管理应用，帮助用户记录和管理自己喜欢的电影、电视剧、书籍等内容。

## 技术栈

- **编程语言**: Kotlin
- **最低 SDK 版本**: Android 15 (API 35)
- **目标 SDK 版本**: Android 15 (API 35)
- **UI 框架**: Jetpack Compose
- **构建工具**: Gradle 8.11.1
- **Android Gradle Plugin**: 8.7.3
- **Kotlin 版本**: 2.1.0

## 项目结构

```
clioo/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/clioo/collection/
│   │       │   ├── MainActivity.kt
│   │       │   └── ui/theme/
│   │       │       ├── Color.kt
│   │       │       ├── Theme.kt
│   │       │       └── Type.kt
│   │       ├── res/
│   │       │   ├── layout/
│   │       │   ├── values/
│   │       │   │   ├── strings.xml
│   │       │   │   └── themes.xml
│   │       │   └── drawable/
│   │       └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── gradle/
│   └── wrapper/
│       └── gradle-wrapper.properties
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

## 功能特性

- [ ] 影视收藏管理
- [ ] 书籍收藏管理
- [ ] 分类与标签系统
- [ ] 搜索功能
- [ ] 数据备份与恢复

## 开发环境要求

- Android Studio Hedgehog | 2023.1.1 或更高版本
- JDK 17
- Android SDK 35

## 构建说明

### 构建项目

```bash
./gradlew build
```

### 安装到设备

```bash
./gradlew installDebug
```

## 维护者

- [Your Name] - 初始开发者

## 贡献者

欢迎贡献！请先阅读贡献指南。

## 许可证

本项目采用 MIT 许可证 - 详见 LICENSE 文件

## 联系方式

如有问题或建议，请通过以下方式联系：
- 提交 Issue
- 发送邮件

---

**注意**: 本项目仅兼容 Android 15 (API 35) 及以上版本，以减少维护成本并使用最新的 Android 特性。
