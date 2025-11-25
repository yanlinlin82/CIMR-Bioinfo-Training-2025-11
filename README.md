# 生物信息学基础培训

## 项目简介

本项目是一套生物信息学基础培训课程材料，使用 Quarto 制作，涵盖生物信息学的基础知识和实践技能。

### 主要内容

1. **生物信息学概述与生物学数据**
   - 生物信息学定义和研究对象
   - 常见数据格式（FASTA、FASTQ、SAM/BAM、VCF、BED、GFF/GTF等）
   - 数据格式转换和处理

2. **数据获取：公共数据库与参考数据**
   - 主要生物信息学数据库（NCBI、EBI、UCSC等）
   - 数据下载方法
   - 参考基因组和注释数据

3. **Linux基础与数据处理**
   - Linux基本概念和命令
   - 数据查看和分析
   - 批量文件处理

4. **综合实践：AI辅助完成完整项目**
   - AI辅助编程工具介绍
   - 完整分析流程实践
   - 差异表达分析案例

## 项目结构

```text
.
├── index.qmd          # 主文档（Quarto格式）
├── _quarto.yml        # Quarto配置文件
├── references.bib     # 参考文献
├── styles.css         # 样式文件
├── images/            # 图片资源
└── _book/             # 构建输出目录
```

## 构建方法

### 前置要求

- 安装 [Quarto](https://quarto.org/docs/get-started/)

### 构建步骤

```bash
# 构建为 Reveal.js 演示文稿
quarto render

# 预览（自动打开浏览器）
quarto preview
```

构建完成后，输出文件位于 `_book/` 目录。

## 作者

颜林林

## 日期

2025-11-26

## 许可证

本项目仅供教学使用。
