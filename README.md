# Miya Assistant - Android App

Miya Assistant 的 Android 原生应用，基于 WebView 封装。

## 特性

- 🎯 全屏沉浸式体验
- 💾 IndexedDB 无限存储（不再受限于 localStorage）
- 📥 支持 JSON 导出/导入
- 🌐 全功能网页版体验
- 📱 原生 Android 应用图标和启动器

## 构建

本项目使用 GitHub Actions 自动构建。推送代码到 main 分支后会自动触发构建，生成 APK 安装包。

### 手动构建

```bash
chmod +x gradlew
./gradlew assembleDebug
```

## 安装

1. 从 [Releases](../../releases) 页面下载最新 APK
2. 在 Android 手机上打开 APK 文件
3. 允许"安装未知来源应用"
4. 安装完成后打开即可

## 技术栈

- Android SDK 34 (minSdk 24)
- Java 17
- WebView + JavaScript
- GitHub Actions CI/CD
