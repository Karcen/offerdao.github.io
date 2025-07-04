# 📸 offer到！AI 证件照换底色工具 / offer is here! AI Passport Photo Background Changer

这是一个纯前端的 AI 证件照处理工具，基于 **TensorFlow\.js** 和 **BodyPix / MediaPipe** 模型。
支持 **批量上传照片**，**精准抠图**，**一键换底色**（红、蓝、白等），并内置常用证件照尺寸（1寸/2寸/护照）。
无需服务器，直接在浏览器运行即可完成所有操作。
做这个网页是因为报名夏令营不同的学校要上传不同要求的照片，很麻烦。

This is a front-end AI passport photo tool powered by **TensorFlow\.js** and **BodyPix / MediaPipe** models.
It supports **batch photo upload**, **precise background removal**, **one-click background replacement** (red, blue, white, etc.), and built-in common ID photo sizes (1-inch, 2-inch, passport).
No server is required. Everything runs directly in your browser.
I developed this web application because applying to different schools for summer camps requires uploading photos that meet various specifications, which can be quite troublesome. This tool aims to simplify the process by allowing users to easily crop, resize, and adjust the background color of their photos to meet the diverse requirements of each school.

---

## 🌟 功能 Features

✅ **精准抠图**（AI 人像分割，发丝级效果）
✅ **一键更换底色**（支持常用证件照背景色和自定义颜色）
✅ **批量处理多张照片**
✅ **内置标准证件照尺寸模板**（1寸、2寸、护照等）
✅ **支持导出 JPG / PNG / WebP 格式**
✅ **纯前端运行，无需安装，无需上传服务器**

✅ **Accurate person segmentation** (AI-powered, hair-level precision)
✅ **One-click background replacement** (standard passport colors & custom colors)
✅ **Batch processing of multiple photos**
✅ **Built-in standard ID photo size templates** (1-inch, 2-inch, passport, etc.)
✅ **Export to JPG / PNG / WebP formats**
✅ **Fully client-side, no installation or server required**

---

## 🖥️ 使用方法 Usage

### 📂 上传照片 Upload Photos

* 点击或拖拽上传一张或多张图片
* 支持格式：`JPG`, `PNG`, `WebP`

### 🎨 设置参数 Adjust Settings

* **选择目标底色**：红 / 蓝 / 白 / 自定义
* **选择证件照尺寸**：1寸、2寸、护照等

### ⚡ 自动处理 Process Automatically

* AI 模型将自动识别前景与背景并替换颜色
* 实时预览处理效果

### 💾 下载 Download

* 单张下载或批量下载（ZIP）

---

## 📦 文件结构 File Structure

```
project/
├── index.html         # 网页入口 HTML
├── script.js          # 主逻辑代码（AI模型加载与处理）
├── style.css          # 页面样式
├── README.md          # 使用说明
```

---

## 🛠 技术栈 Tech Stack

| 功能 Feature               | 技术 Technology                      |
| ------------------------ | ---------------------------------- |
| 人像分割 Person Segmentation | TensorFlow\.js, BodyPix, MediaPipe |
| 前端界面 Frontend UI         | HTML5, CSS3, JavaScript            |
| 批量处理 Batch Processing    | HTML5 Canvas, JSZip                |

---

## 📏 预置证件照尺寸 Built-in Sizes

| 类型 Type     | 尺寸 Dimensions | 分辨率 DPI |
| ----------- | ------------- | ------- |
| 1寸 1-inch   | 295 x 413 px  | 300 dpi |
| 2寸 2-inch   | 413 x 579 px  | 300 dpi |
| 护照 Passport | 827 x 1063 px | 300 dpi |

---

## 📜 许可 License

MIT License.
自由修改、分发和商用。
Free to modify, distribute, and use for commercial or personal purposes.

---
