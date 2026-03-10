# Ball Match 3D - CrazyGames 配色方案

> 为 CrazyGames 平台优化的两套配色方案
> 生成时间: 2026-03-10

---

## 方案 A: 霓虹 Synthwave 风格 ⭐推荐

灵感来源: Big NEON Tower Tiny Square (CrazyGames 9.3分热门游戏)

### 核心配色

| 用途 | 颜色值 | 预览 |
|------|--------|------|
| 背景主色 | `#0f0c29` | ████ 深蓝黑 |
| 背景辅色 | `#302b63` | ████ 深紫 |
| 背景高光 | `#24243e` | ████ 暗蓝紫 |
| 霓虹粉 | `#ff00ff` | ████ 亮粉 |
| 霓虹青 | `#00ffff` | ████ 亮青 |
| 霓虹紫 | `#bf00ff` | ████ 亮紫 |
| 霓虹黄 | `#ffff00` | ████ 亮黄 |
| 文字白 | `#ffffff` | ████ 纯白 |
| 文字灰 | `#a0a0a0` | ████ 浅灰 |

### 渐变定义

```css
/* 主背景 - 深蓝紫霓虹 */
--bg-gradient: linear-gradient(135deg, #0f0c29 0%, #302b63 50%, #24243e 100%);

/* 球体颜色 - 霓虹发光 */
--ball-red: radial-gradient(circle at 30% 30%, #ff0055, #cc0044);
--ball-blue: radial-gradient(circle at 30% 30%, #00ccff, #0099cc);
--ball-yellow: radial-gradient(circle at 30% 30%, #ffff00, #cccc00);
--ball-green: radial-gradient(circle at 30% 30%, #00ff99, #00cc77);
--ball-purple: radial-gradient(circle at 30% 30%, #cc00ff, #9900cc);
--ball-orange: radial-gradient(circle at 30% 30%, #ff9900, #cc7700);

/* 按钮渐变 */
--btn-primary: linear-gradient(145deg, #ff00ff, #cc00cc);
--btn-secondary: linear-gradient(145deg, #00ffff, #00cccc);
```

### 发光效果

```css
/* 霓虹发光 - 粉色 */
--glow-pink: 0 0 10px #ff00ff, 0 0 20px #ff00ff, 0 0 40px #ff00ff;

/* 霓虹发光 - 青色 */
--glow-cyan: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 40px #00ffff;

/* 球体发光 */
--ball-glow: 0 0 15px currentColor, 0 0 30px currentColor;

/* 按钮发光 */
--btn-glow: 0 0 10px rgba(255, 0, 255, 0.5), 0 0 20px rgba(255, 0, 255, 0.3);
```

### 视觉预览

```
╔══════════════════════════════════════════╗
║  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  ║  ← 深蓝紫背景
║  ▓                                      ▓  ║
║  ▓     ◉  ◉  ◉                         ▓  ║  ← 霓虹发光球体
║  ▓    粉  青  紫                        ▓  ║
║  ▓                                      ▓  ║
║  ▓    ┌─────────────┐                  ▓  ║
║  ▓    │  ░START░   │                  ▓  ║  ← 霓虹边框按钮
║  ▓    └─────────────┘                  ▓  ║
║  ▓                                      ▓  ║
║  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  ║
╚══════════════════════════════════════════╝
```

---

## 方案 B: 清新青绿风格

灵感来源: Color Match (CrazyGames 热门配色游戏)

### 核心配色

| 用途 | 颜色值 | 预览 |
|------|--------|------|
| 背景主色 | `#11998e` | ████ 青绿 |
| 背景辅色 | `#38ef7d` | ████ 亮绿 |
| 背景高光 | `#a8edea` | ████ 浅青 |
| 球体红 | `#ff6b6b` | ████ 珊瑚红 |
| 球体蓝 | `#4ecdc4` | ████ 青蓝 |
| 球体黄 | `#ffe66d` | ████ 柠檬黄 |
| 球体绿 | `#95e1d3` | ████ 薄荷绿 |
| 球体紫 | `#a8a4e6` | ████ 淡紫 |
| 球体橙 | `#ffbe76` | ████ 蜜桃橙 |
| 文字深 | `#2d3436` | ████ 深灰 |
| 文字白 | `#ffffff` | ████ 纯白 |

### 渐变定义

```css
/* 主背景 - 清新青绿 */
--bg-gradient: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);

/* 备选背景 - 更柔和 */
--bg-gradient-soft: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);

/* 球体颜色 - 柔和扁平 */
--ball-red: #ff6b6b;
--ball-blue: #4ecdc4;
--ball-yellow: #ffe66d;
--ball-green: #95e1d3;
--ball-purple: #a8a4e6;
--ball-orange: #ffbe76;

/* 按钮 */
--btn-primary: #ffffff;
--btn-secondary: rgba(255, 255, 255, 0.9);
```

### 阴影效果

```css
/* 柔和阴影 */
--shadow-soft: 0 4px 15px rgba(0, 0, 0, 0.1);
--shadow-medium: 0 8px 25px rgba(0, 0, 0, 0.15);

/* 球体阴影 */
--ball-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);

/* 按钮阴影 */
--btn-shadow: 0 4px 15px rgba(0, 0, 0, 0.15), 0 2px 5px rgba(0, 0, 0, 0.1);
```

### 视觉预览

```
╔══════════════════════════════════════════╗
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║  ← 青绿渐变背景
║  ░                                    ░  ║
║  ░     ○  ○  ○                        ░  ║  ← 简洁球体
║  ░    红  蓝  黄                       ░  ║
║  ░                                    ░  ║
║  ░    ┌─────────────┐                ░  ║
║  ░    │   START     │                ░  ║  ← 简洁白按钮
║  ░    └─────────────┘                ░  ║
║  ░                                    ░  ║
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║
╚══════════════════════════════════════════╝
```

---

## 方案对比

| 维度 | 方案 A 霓虹 | 方案 B 清新 |
|------|------------|------------|
| **风格** | 赛博朋克、现代 | 简约、解压、自然 |
| **目标用户** | 年轻玩家、喜欢刺激 | 全年龄、休闲玩家 |
| **CrazyGames 匹配度** | ⭐⭐⭐⭐⭐ Big NEON Tower 同款 | ⭐⭐⭐⭐ Color Match 同款 |
| **视觉冲击力** | 强 | 中等 |
| **长时间游玩舒适度** | 中等 | 高 |
| **与当前版本差异** | 大 | 中等 |

---

## 推荐

**主推方案 A (霓虹 Synthwave)**
- CrazyGames 上 neon 风格游戏表现更好
- Big NEON Tower 是平台高分游戏 (9.3分)
- 更符合当前游戏"Ball Match 3D"的动感特性

---

## 使用说明

1. 确认选择方案 A 或 B
2. 我将生成完整的 CSS 替换代码
3. 你可以选择性地应用（只改背景、或全改）

要生成完整的 CSS 代码吗？
