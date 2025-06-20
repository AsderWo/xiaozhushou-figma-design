# 设置页面设计指南

## 页面结构

### 整体布局
- 背景色：#f5f7fa
- 内边距：上下左右16px
- 卡片间距：16px

### 分组卡片通用样式
- 背景色：白色
- 圆角：12px
- 阴影：0 2px 8px rgba(0,0,0,0.09)
- 内边距：16px

### 卡片标题
- 左侧主色竖条（4px宽，高度与文字匹配）
- 标题文字（16px加粗，#222）
- 底部间距：12px
- 底部有1px分割线（#f0f0f0）

### 设置项通用样式
- 高度：56px
- 左侧标签（14px常规，#222）
- 右侧控件（根据类型不同）
- 底部有1px分割线（#f0f0f0，最后一项除外）
- 垂直居中对齐

## 具体卡片设计

### 通告设置卡片
- 默认语言：
  - 左侧标签：14px常规，#222
  - 右侧picker：
    - 文字：14px常规，#666
    - 灰色箭头图标（向下，20x20px）
    - 点击展开下拉选项
- 自动复制：
  - 左侧标签：14px常规，#222
  - 右侧switch：
    - 开启状态：主色背景（#1890ff）
    - 关闭状态：灰色背景（#d9d9d9）
    - 尺寸：44x22px

### 航空公司管理卡片
- 卡片标题右侧：展开/收起箭头图标（20x20px，可点击切换）
- 列表项：
  - 左侧：
    - 航空公司代码（16px加粗，#222）
    - 航空公司名称（14px常规，#666）
  - 右侧操作按钮：
    - 编辑图标（20x20px，主色）
    - 删除图标（20x20px，主色）
    - 间距：12px
- 底部添加按钮：
  - 主色按钮（#1890ff）
  - 白色文字（14px）
  - 圆角：4px
  - 高度：32px
  - 宽度：120px
  - 居中显示
  - 上边距：12px

### 特殊目的地管理卡片
- 与航空公司管理卡片结构类似
- 列表项：
  - 左侧：
    - 中文名称（16px加粗，#222）
    - 英文名称（14px常规，#666）
  - 右侧操作按钮同上

### 其他设置卡片
- 关于：
  - 左侧标签：14px常规，#222
  - 右侧箭头图标（20x20px，灰色）
- 缓存占用：
  - 左侧标签：14px常规，#222
  - 中间数值：14px常规，#666
  - 右侧"清除缓存"按钮：
    - 警告色按钮（#f5222d）
    - 白色文字（12px）
    - 圆角：4px
    - 高度：28px
    - 内边距：左右8px

## 弹窗设计

### 关于弹窗
- 背景：半透明黑色遮罩（rgba(0,0,0,0.6)）
- 弹窗卡片：
  - 白色背景
  - 圆角：16px
  - 宽度：80%（约300px）
  - 内边距：24px
  - 居中显示
- 内容：
  - 顶部应用logo（居中，80x80px）
  - 应用名称（18px加粗，#222，居中）
  - 版本号（14px常规，#666，居中）
  - 简介（14px常规，#666，居中）
  - 底部"关闭"按钮：
    - 主色按钮（#1890ff）
    - 白色文字（14px）
    - 圆角：4px
    - 高度：40px
    - 宽度：80%
    - 居中显示
    - 上边距：16px

### 编辑/添加弹窗
- 背景同上
- 弹窗卡片同上
- 标题：16px加粗，#222，居中
- 表单项：
  - 左侧标签（14px常规，#222）
  - 右侧输入框：
    - 灰色边框（#d9d9d9）
    - 圆角：4px
    - 高度：36px
    - 内边距：左右8px
    - 字体：14px常规，#222
- 底部按钮组：
  - "取消"按钮：
    - 灰色边框（#d9d9d9）
    - 灰色文字（#666）
    - 圆角：4px
    - 高度：36px
    - 宽度：40%
  - "确认"按钮：
    - 主色按钮（#1890ff）
    - 白色文字
    - 圆角：4px
    - 高度：36px
    - 宽度：40%
  - 按钮间距：16px
  - 上边距：16px
  - 水平居中排列

## 交互说明
- 展开/收起动画：箭头旋转180度，内容展开/收起
- switch切换：滑动或点击切换状态
- 编辑/删除按钮点击触发对应操作
- 添加按钮点击弹出添加弹窗
- 关于项点击弹出关于弹窗
- 清除缓存按钮点击后显示确认提示，确认后显示清除成功提示