# TikTok Strategist Studio 🎬✨  
**Create viral-ready video hooks with the help of AI**

Welcome to the **TikTok Strategist Studio** – your personal creative partner powered by AI. In this notebook, you’ll interact with an intelligent agent designed to help you:

- 🎯 Get clear on your **video topic**, **emotional tone**, and **target audience**
- ✍️ Craft **attention-grabbing opening hooks** (the first 3–5 seconds of your video)
- 📊 Score and improve your hook for maximum virality
- 🔁 Rewrite and explore new angles until it feels *just right*

---

## 🚀 What to Expect

- The assistant will **ask a few quick questions** to learn what your video is about.
- Once it knows the basics, it will **generate short hook examples**.
- If the hook doesn’t feel perfect, you can **ask it to try again** with a new style or mood.
- You'll get clear, strategic advice – in a fast and playful way.
---

## 📊 About the Dataset

To help the TikTok Strategist Agent learn from real-world examples, this project uses a [Dataset](https://www.kaggle.com/datasets/hoornik/tiktok-sample) of TikTok videos:

```python
df = pd.read_csv("/kaggle/input/tiktok-sample/tiktok_dataset.csv")
```
---

## 🛠️ How to Use This Notebook

This notebook is designed to **run automatically** from start to finish – no need to type anything unless you want to try your own ideas!

- A **USE_DEMO** flag is enabled by default: you’ll see a sample conversation play out on its own.
- If you want to interact live, you can toggle "USE_DEMO" to **False** (just follow the instructions in the cells).
- There’s nothing to install – everything runs right here.

---

## 💡 Pro Tip

TikTok success is often about trying *lots* of ideas. Use this tool like a creative partner – bounce ideas, remix tones, and see what grabs your attention. The best hook might be one you didn’t expect!

---

## 🙏 Acknowledgments

This project was inspired by **[Google 5-Day Gen AI Intensive Course on Kaggle](https://www.kaggle.com/learn-guide/5-day-genai)**.

Some of the conversational structure, design ideas, and instructional comments were adapted and built upon from their **BaristaBot** notebook in Day 3: Building an Agent with LangGraph.

Special thanks to the creators of that course for providing such a clear and accessible foundation to learn from.
