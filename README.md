
# FinancialAnalyzer

📊 KOL 商业估值系统，支持多平台+多标签精细建模，适用于内容营销投放、定价研究、网红商业化辅助决策等。

## 🚀 如何部署到 Hugging Face Spaces

1. 将本项目上传至 GitHub；
2. 打开 [Hugging Face Spaces](https://huggingface.co/spaces)；
3. 点击 “Create new Space”：
   - SDK: 选择 `Streamlit`
   - Space name: 自定义名称
   - 链接你的 GitHub 仓库或直接上传代码文件

4. 系统会自动运行：`streamlit run app.py`

---

## 🛠️ 依赖环境（requirements.txt）

```bash
streamlit
numpy
pandas
scipy
```

---

## 📁 文件结构（主要部分）

- `app.py`：主界面入口（Streamlit）
- `influencer_pricing_system.py`：估值核心模型
- `log_price_estimator.py` 等：其他补充模型
