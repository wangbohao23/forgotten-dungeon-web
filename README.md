# 🏰 遗忘地牢 (Forgotten Dungeon)

一个复古终端风格的文字冒险游戏，部署在 GitHub Pages 上。

![Game Screenshot](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🎮 在线游玩

**[点击开始游戏](https://wangbohao23.github.io/forgotten-dungeon-web/)**

## ✨ 游戏特性

- 🖥️ **复古终端风格** - 绿色 CRT 显示器效果，沉浸式体验
- 🗺️ **3个探索场景** - 地牢入口、滴水通道、隐秘密室
- ⚔️ **战斗系统** - 与沼泽巨鼠战斗，获得经验和战利品
- 🎒 **物品系统** - 拾取、使用物品，管理背包
- 💾 **存档功能** - 使用 localStorage 保存/加载游戏进度
- 📱 **响应式设计** - 支持桌面和移动设备

## 🎯 游戏玩法

### 基本命令

| 命令 | 说明 |
|------|------|
| `去 [方向]` / `北/南/东/西` | 移动到相邻区域 |
| `攻击` / `打` | 攻击当前敌人 |
| `检查` / `搜索` | 搜索当前区域 |
| `拾取` / `捡` | 拾取物品 |
| `使用 [物品]` | 使用消耗品 |
| `背包` | 查看背包内容 |
| `状态` | 查看角色状态 |
| `帮助` | 显示帮助信息 |

### 快捷操作

- 使用界面底部的方向按钮移动
- 点击快捷按钮执行常用命令
- 按 **Enter** 键快速执行输入的命令

## 🗺️ 游戏世界

```
        [地牢入口]
             │
             ▼
      [滴水通道] ──► [隐秘密室]
```

## 🛠️ 技术栈

- **前端**: 纯 HTML5 + CSS3 + JavaScript
- **样式**: 自定义 CRT 终端效果
- **存储**: LocalStorage 存档系统
- **部署**: GitHub Pages

## 📝 存档说明

游戏会自动保存以下数据：
- 角色属性（HP、等级、经验、金币）
- 背包物品
- 当前位置
- 游戏进度标记

点击侧边栏的 **💾 保存** 按钮手动存档，**📂 加载** 按钮读取存档。

## 🔄 更新游戏

要更新游戏内容：

```bash
# 克隆仓库
git clone https://github.com/wangbohao23/forgotten-dungeon-web.git

# 修改 index.html
# ...

# 提交更改
git add index.html
git commit -m "更新游戏内容"
git push origin main
```

GitHub Pages 会自动重新部署（约 1-2 分钟）。

## 📄 许可证

MIT License

## 🙏 致谢

字体: [VT323](https://fonts.google.com/specimen/VT323) - Google Fonts

---

**祝你在遗忘地牢中好运！⚔️**
