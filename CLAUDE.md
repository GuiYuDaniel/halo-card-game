# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

从 0 开始开发的 AI 创作卡牌游戏，使用 Godot 4.5 引擎。

## 开发环境

- **引擎**: Godot 4.5
- **语言**: GDScript
- **渲染方式**: GL Compatibility (兼容模式)
- **编辑器**: 使用 Godot Editor 打开项目

## 项目结构

```
cardGameDemo/
├── project.godot      # Godot 项目配置文件
├── icon.svg           # 项目图标
├── .editorconfig      # 编辑器配置 (UTF-8)
└── .gitignore         # Git 忽略规则
```

## 常用命令

- **打开项目**: 使用 Godot Editor 打开 `project.godot`
- **运行游戏**: 在 Godot Editor 中按 F5 或点击运行按钮
- **调试场景**: 在 Godot Editor 中打开场景后按 F6

## 注意事项

- 项目处于初始化阶段，尚未创建游戏场景和脚本
- 使用 GDScript 作为脚本语言
- 配置为 GL 兼容渲染模式，确保在更多设备上运行
