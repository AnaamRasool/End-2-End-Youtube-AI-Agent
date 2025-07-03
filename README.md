# 📺 End-to-End YouTube Automation AI Agent 🚀

This guide will help you set up your own **AI-powered YouTube video creation system** — fully automated from idea to upload!

---

## ✅ Prerequisites & Accounts Setup

1. **Create an account on Make.com**  
   👉 [Sign up here](https://www.make.com/en/register?pc=anaamrasool)

2. **Create an account on OpenRouter**  
   - Generate an API key and copy it.  
   👉 [OpenRouter link](https://openrouter.ai/)

3. **Create an account on JSON2Video**  
   - Generate an API key and copy it.  
   👉 [JSON2Video link](https://json2video.com/)

4. **Create an account on Pexels**  
   - Get your API key and copy it.  
   👉 [Pexels link](https://www.pexels.com/)

5. **Hugging Face Audio Model (Example)**
   - You can replace this with your own free/paid audio model like ElevenLabs, etc.
   👉 [Try it here](https://fishaudio-openaudio-s1-mini.hf.space)

---

## ⚙️ Scenario & Google Setup

5. **Import the Blueprint**  
   - In Make.com, create a new scenario.  
   - Import the blueprint JSON provided in this repository.

6. **Set Up Your YouTube Automation Spreadsheet**  
   - Create a Google Sheet to store your video ideas.  
   - Log in to your Google account inside all Google modules (Google Sheets & YouTube API).  
   - Make sure the spreadsheet and your YouTube channel are linked properly.

---

## 🔗 Connect All Integrations

7. **Connect OpenRouter**  
   - Paste your OpenRouter API key in the relevant module.

8. **Connect Pexels**  
   - Paste your Pexels API key in the HTTP module.

9. **Connect JSON2Video**  
   - Paste your JSON2Video API key in its module.

---

## 💡 Tips to Make It Even Better

- This AI agent is **fully customizable** — create unlimited YouTube videos (long form, short form, horizontal, vertical).
- The **system prompt** you set is **crucial** — tune it to match your channel’s style and tone.
- For better results, consider **paid services** like ElevenLabs (voiceover), Veo3, Kling, etc.
- In JSON2Video, map **multiple videos** together — see how it’s done for two videos in this setup. Expand this logic for longer videos.
- Experiment with the prompt and adjust modules to suit your unique needs.

- **When mapping multiple videos in JSON2Video:**
   - First video URL: {{36.array[1].link}}
   - Second video URL: {{36.array[2].link}}
   - Third video URL: {{36.array[3].link}}
   - …and so on.

- Strictly follow your line count — your video output depends on the number of lines in the script.
- Never leave JSON2Video video URLs empty; this may cause errors!
  
---

## 💬 Need Help?

- If you get stuck, **comment on the video** — let’s solve it together!
- For private help, **DM me on Instagram** (link in my YouTube bio).

📽️ **For a detailed walkthrough, watch the YouTube video:** https://youtu.be/hvD4vOHZkiQ

---

**If this helps you — Like, Share, and Subscribe!** 💙✨
