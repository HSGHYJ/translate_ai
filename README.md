📄 PDF AI Translator
一个轻量级的 AI 工具，可以一键上传 PDF 文件，自动完成 文本提取、翻译和总结。
旨在帮助学生、研究人员和职场人士快速理解英文/外文资料。
✨ 功能亮点
•	🔍 PDF 文本提取：基于 PyMuPDF，支持扫描件和文本型 PDF
•	🌍 AI 翻译：调用 Qwen API，实现高质量中英文互译
•	📝 智能总结：自动输出文章要点，支持长文档分段总结
•	💻 简洁界面：上传 PDF → 输出翻译和总结，一步到位
🚀 使用方法
1️⃣ 克隆项目
git clone https://github.com/HSGHYJ/translate_ai
cd pdf-ai-translator
2️⃣ 安装依赖
pip install -r requirements.txt
3️⃣ 配置 API Key
在项目根目录下新建一个 .env 文件，写入：
DASHSCOPE_API_KEY=你的API密钥
4️⃣ 运行
python app.py
🛠️ 技术栈
•	后端：Python, PyMuPDF (fitz), DashScope SDK
•	AI 模型：Qwen (阿里通义千问)
•	前端：命令行 + 简单交互界面
🌟 应用场景
•	📖 学术：快速理解英文论文、教材
•	📰 职场：高效阅读外文报告、行业分析
•	💡 产品经理/研究人员：一键生成摘要，辅助决策
🔮 下一步规划
•	✅ 增加多语言支持（德语、法语、韩语等）
•	✅ Web UI 界面（Streamlit / Gradio）
•	⏳ 支持大文件分片翻译
