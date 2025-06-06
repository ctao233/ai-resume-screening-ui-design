# AI简历筛选系统 - 设计系统

## 设计风格：简约

本设计系统采用简约风格，注重清晰的信息层级、直观的用户界面和高效的交互体验。设计元素精简，视觉干扰最小化，让用户能够专注于内容和任务。

## 色彩系统

### 主色
- 主色：#1890FF（蓝色）- 用于主要按钮、链接和重点元素
- 辅助色：#52C41A（绿色）- 用于成功状态和积极反馈
- 警告色：#FAAD14（黄色）- 用于警告信息
- 错误色：#F5222D（红色）- 用于错误状态和消极反馈

### 中性色
- 标题文字：#262626（深灰）
- 正文文字：#595959（灰色）
- 次要文字：#8C8C8C（浅灰）
- 边框颜色：#D9D9D9（淡灰）
- 分割线：#F0F0F0（极淡灰）
- 背景色：#F5F5F5（近白）
- 白色：#FFFFFF

## 排版

### 字体
- 系统默认字体：
  - Windows: 'Microsoft YaHei'
  - macOS: 'PingFang SC'
  - 通用后备: 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif

### 字号
- 大标题：24px
- 标题：20px
- 小标题：16px
- 正文：14px
- 辅助文字：12px

### 行高
- 标题：1.4
- 正文：1.6

## 间距系统

采用8px为基础单位的间距系统：
- 4px - 极小间距
- 8px - 小间距
- 16px - 中间距
- 24px - 大间距
- 32px - 特大间距
- 48px - 超大间距

## 阴影

- 轻微阴影：`0 2px 8px rgba(0, 0, 0, 0.08)` - 用于卡片、下拉菜单
- 中等阴影：`0 4px 12px rgba(0, 0, 0, 0.12)` - 用于模态框、抽屉
- 深阴影：`0 8px 24px rgba(0, 0, 0, 0.16)` - 用于重要弹出层

## 圆角

- 小圆角：2px - 用于标签、小按钮
- 中圆角：4px - 用于按钮、输入框、卡片
- 大圆角：8px - 用于模态框、抽屉
- 圆形：50% - 用于头像、徽标

## 基础组件

### 按钮

#### 主要按钮
- 背景色：#1890FF
- 文字颜色：白色
- 悬停状态：#40A9FF
- 点击状态：#096DD9

#### 次要按钮
- 背景色：白色
- 边框：1px solid #D9D9D9
- 文字颜色：#595959
- 悬停状态：边框和文字变为 #40A9FF

#### 文字按钮
- 背景色：透明
- 文字颜色：#1890FF
- 悬停状态：#40A9FF

### 输入框
- 高度：32px
- 内边距：左右12px
- 边框：1px solid #D9D9D9
- 聚焦状态：边框变为 #40A9FF，带有轻微阴影

### 卡片
- 背景色：白色
- 边框：1px solid #F0F0F0 或无边框
- 内边距：24px
- 阴影：轻微阴影

### 表格
- 表头背景色：#FAFAFA
- 边框：1px solid #F0F0F0
- 悬停行背景色：#E6F7FF

### 标签
- 内边距：左右8px，上下2px
- 圆角：小圆角
- 文字大小：12px

## 响应式设计

### 断点
- 手机：< 576px
- 平板：≥ 576px
- 小桌面：≥ 992px
- 大桌面：≥ 1200px
- 超大屏幕：≥ 1600px

### 栅格系统
- 采用24列栅格系统
- 列间距：16px（可根据需要调整）

## 图标系统

- 线性图标，统一线条粗细
- 尺寸：16px（小）、20px（中）、24px（大）
- 颜色跟随文字颜色或指定颜色

## 动效

- 过渡时间：0.2s - 0.3s
- 缓动函数：ease-in-out
- 保持简洁，避免过度动画