# 评分金字塔图生成器

这是一个基于前端技术（HTML、CSS、JavaScript）构建的评分金字塔图生成器。用户可以通过输入评分数据、选择区间大小，动态生成评分金字塔图，以可视化的方式展示评分的分布情况。

## 项目背景

评分金字塔图（Pyramid Chart）是一种双轴条形图，通过将数据分为多个区间并绘制两侧对称的条形，能够直观地展示数据在不同区间内的分布情况。该项目旨在为用户提供一个简单的工具，用于生成评分数据的金字塔图，帮助分析评分分布和趋势。

## 功能

- **输入评分数据**：用户可以输入一组评分数据，数据之间用逗号分隔。
- **选择区间大小**：用户可以通过滑动条调整评分区间的大小（Bin Width）。
- **动态生成金字塔图**：根据输入的评分数据和区间大小，自动生成左右对称的金字塔图，展示各评分区间的数量。
- **可视化展示**：通过图表呈现数据分布，右侧为正值，左侧为负值，便于分析。

## 技术栈

- **HTML**：构建静态页面结构。
- **CSS**：页面样式和布局。
- **JavaScript**：实现评分数据处理和金字塔图生成。
- **Chart.js**：用于绘制金字塔图的图表库。

## 安装和使用

### 1. 克隆仓库

首先，您需要克隆该 Git 仓库到本地：

```bash
git clone https://github.com/mudern/pyramid_draw.git