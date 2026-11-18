# 旅行住宿偏好测试

参考 MBTI 的类型组合方式，通过 4 组相互独立的住宿偏好维度（安静独处 Q / 社交互动 S、计划确定 P / 灵活探索 F、经济实用 B / 舒适享受 C、城市便利 U / 自然沉浸 N），将用户划分为 16 种旅行住宿偏好类型的中文网页小测试。

- 10 道单选题，提交后生成四字母类型代码、类型名称、维度倾向、偏好描述、推荐住宿、选房建议和避雷提醒
- 纯 Streamlit 实现，无数据库、无外部图片、无网络请求、不收集个人信息
- 本测试仅用于旅行灵感与娱乐，不构成专业心理评估或预订建议

## 本地运行

```bash
# 1. 安装依赖
pip install -r requirements.txt

# 2. 启动应用
streamlit run app.py
```

启动后浏览器会自动打开 `http://localhost:8501`。

## 部署到 Streamlit Community Cloud

1. 将本项目文件（`app.py`、`requirements.txt`、`README.md`）推送到 GitHub 仓库；
2. 打开 [share.streamlit.io](https://share.streamlit.io) 并登录；
3. 点击 **Create app** → **From existing repo**，选择该仓库，主文件路径填写 `app.py`；
4. 点击 **Deploy**，等待构建完成即可获得公开访问链接。

> 无需任何密钥或环境变量。
