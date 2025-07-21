## Hi there 👋
# YouTube Bot Automation (n8n)

This is an `n8n` workflow that posts a comment on a specified YouTube video using the YouTube Data API.

## 🚀 What it Does

- Takes a YouTube video ID and comment text
- Sends a POST request to the YouTube API to comment on that video
- Uses OAuth2 credentials for secure authentication

## 🛠️ How to Use

1. Import the workflow JSON into your `n8n` instance.
2. Add your own **OAuth2 YouTube API credentials** under `Credentials > OAuth2`.
3. Replace the values in the `Set` node:
   - `videoId` – the ID of the YouTube video
   - `commentText` – the comment to be posted
4. Run the workflow manually or on a trigger.

## ⚠️ Note

- This workflow references an OAuth2 credential (`oAuth2Api`) that must be configured in your own n8n instance.
- No sensitive data (keys or tokens) are included in this file.

## 📂 Files Included

- `YouTube-Bot Automation.json` – the n8n workflow file

---

Feel free to modify or expand this workflow to support dynamic input, comment scheduling, or batch operations!

<!--
**Kashhan/Kashhan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
