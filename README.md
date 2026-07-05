# Birthday Cake Visualization Based on Python Turtle
<div align="center">
<img src="https://img.shields.io/badge/Python-3.x-blue.svg" alt="Python Version">
<img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License">
<img src="https://img.shields.io/badge/Standard-Library-orange.svg" alt="Zero Dependencies">
</div>

## 1、 Project Overview
This is a vector drawing program implemented based on Python built-in `turtle` graphics library, designed for birthday custom creative rendering.
The program uses parametric ellipse equations to draw multi-layer cake body, stereoscopic candle models, random star particle decoration, and supports custom birthday text rendering.
All dependencies are Python native standard libraries, no extra pip installation required, compatible with Windows/macOS/Linux all mainstream operating systems.

## 2、 Core Technical Features
- 🎂 Parametric geometric drawing: Use trigonometric function to generate smooth ellipse cake outline
- 🕯️ Multi-layer stereoscopic structure: Cake base, cream interlayer, wax candle, flame multi-layer composite rendering
- ✨ Random particle decoration: Multi-region scattered colorful star dot background decoration
- 📝 Custom text module: Support configurable birthday greetings, recipient signature, font size and color
- 🖥️ Adaptive window layout: Fixed 900×600 drawing canvas, adjustable background color theme
- 🧩 Zero third-party dependencies: Only rely on built-in `turtle` / `math` / `random` standard modules

## 3、 Environment & Compatibility
| System | Runtime Requirement | Supplementary Operation |
|--------|---------------------|------------------------|
| Windows | Python 3.6+ | Built-in turtle, run directly |
| macOS | Python 3.8+ | Execute `brew install python-tk` before running |
| Linux | Python 3.7+ | Install dependency `sudo apt install python3-tk` |

## 4、 Quick Start Guide
### 1. Clone Repository to Local
git clone https://github.com/Aventardo7777/birthday-cake-turtle-py.git
### 2. Enter Project Directory & Execute Script
cd birthday-cake-turtle-py
python 蛋糕.py
### 3. Preview Effect
After running, a 900×600 drawing window will pop up, automatically render complete birthday cake graphics, keep window open until manual close.

## 5、Standard Project File Structure
<img width="1210" height="171" alt="image" src="https://github.com/user-attachments/assets/4e5233c8-155e-4865-8b57-6c731081b493" />

## 6、 Custom Modification Parameters
All configurable content is located in the global drawing section of the script, supporting free modification:
#### 1. Birthday recipient text: Modify the content of t.write('致：好友友  ', font=('楷体', 32, 'bold'))
#### 2.Birthday wish copy: Adjust t.write('祝 你 生 日 快 乐！前 程 似 锦！', font=('楷体', 30, 'bold'))
#### 3.Canvas size: Modify setup(width=900, height=600, startx=0, starty=0) width/height value
#### 4.Star particle quantity: Adjust the loop range of multiple for i in range(XX)
#### 5.Color palette: Replace hex color values in list color = ["#e28cb9", "#805a8c", ...]

## 7、 Open Source License
This project is open-sourced under the MIT License.
You are free to copy, modify, distribute and use the code for personal non-commercial and commercial secondary development, without additional authorization, retain the original open source statement of the project.

### README文档提交规范填写
#### 1. Commit message（短框）
docs(readme): standardize project document with professional markdown specification
#### 2. Extended description（长框）
##### Add Python version, MIT license, zero dependency professional badge;
##### Standardize project overview, core features, environment compatibility table, quick start commands;
##### Sort out standardized file directory structure, list all configurable custom parameters;
##### Unify Markdown hierarchical format, optimize readability and professional display effect on GitHub.

## 8、后续迭代维护标准操作（长期规范）
1. 更新/优化蛋糕绘图代码
2. 仓库主页 `Add file` → `Upload files`，上传新版`蛋糕.py`覆盖原文件
3. 提交文案模板（示例）


## 9、专业避坑规范要点（标准化开源仓库必备）
1. 禁止开启GitHub Pages：turtle程序依赖本地图形窗口，网页环境无法运行，无需创建跳转`index.html`；
2. 统一提交语义前缀：`feat`新增功能、`fix`修复逻辑、`docs`文档更新、`perf`性能优化、`refactor`代码重构；
3. 保留`.gitignore`自动过滤Python缓存文件，避免垃圾文件提交污染仓库；
4. 所有README使用分层Markdown、代码块、表格、徽章，提升项目专业观感；
5. 中文源码文件名`蛋糕.py`GitHub原生兼容，无需强制改为英文，本地运行无编码异常。
