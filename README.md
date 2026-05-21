# 🚀 ʟʟᴀᴍᴀᴄᴏᴅᴇʀ ᴀɪ ᴀᴘɪ

> ⚡ A clean • fast • serverless AI API built with Flask and deployed on Vercel.

Powered by Together AI ⚡  
Supports text prompts, image inputs, and multiple AI models.


## ✨ Features

- ⚡ **Fast Mode** — Quick lightweight responses
- 🧠 **Thinking Mode** — Deep reasoning & coding
- 💎 **Pro Mode** — Powerful balanced performance
- 🖼️ Vision Support (Image + Prompt)
- 📦 Clean JSON Responses
- ☁️ Vercel Serverless Deploy
- 🔑 No API Key Required


# 🔗 Endpoint

```http
GET /nomini/ai
```


# ⚙️ Parameters

| Parameter | Type | Required | Description |
|----------|------|----------|-------------|
| `prompt` | string | ✅ | Your prompt |
| `model` | string | ❌ | `fast`, `pro`, `thinking` |
| `image` | string | ❌ | Public image URL |


# 🤖 Models

| Mode | Description |
|------|-------------|
| ⚡ `fast` | Quick and lightweight |
| 💎 `pro` | Balanced performance |
| 🧠 `thinking` | Deep reasoning + coding |


# 📚 Usage Examples

## ⚡ Basic Prompt

```http
GET /nomini/ai?prompt=Explain recursion simply
```


## 💎 Pro Model

```http
GET /nomini/ai?prompt=Write binary search in python&model=pro
```


## 🧠 Thinking Model

```http
GET /nomini/ai?prompt=Create full auth system&model=thinking
```


## 🖼️ With Image

```http
GET /nomini/ai?prompt=Describe this image&image=https://example.com/photo.jpg
```


# 📥 Response

## ✅ Success

```json
{
  "status": true,
  "model": "fast",
  "response": "Recursion is when a function calls itself..."
}
```


## ❌ Error

```json
{
  "status": false,
  "error": "prompt required"
}
```


# ☁️ Deploy on Vercel

### 1️⃣ Fork or Clone Repository

```bash
git clone https://github.com/ProviderBotz/LlamaCoder
```


### 2️⃣ Import Project on Vercel

Open:

```txt
https://vercel.com/new
```


### 3️⃣ Deploy Instantly 🚀

Live URL:

```txt
https://your-project.vercel.app/nomini/ai
```


# 💻 Local Setup

## Clone Repository

```bash
git clone https://github.com/ProviderBotz/LlamaCoder
```

## Enter Directory

```bash
cd LlamaCoder
```

## Install Requirements

```bash
pip install -r requirements.txt
```

## Run Flask Server

```bash
flask --app nomini/nomini run
```


# 🌐 Local API URL

```txt
http://localhost:5000/nomini/ai
```


# 📂 Project Structure

```txt
LlamaCoder/
├── nomini/
│   └── nomini.py # MAIN API
├── requirements.txt # NOMINIS REQUIREMENTS 
├── vercel.json # FOR VERCEL DEPLOYMENT
└── README.md # THIS FILE
```


# ⚙️ Tech Stack

- 🐍 Python 3.x
- 🌶️ Flask
- ⚡ httpx
- 🤖 Together AI
- ☁️ Vercel Serverless


# 🔘 badges

<div align="center">

<a href="https://t.me/ProviderBotz">
  <img src="https://img.shields.io/badge/📢_telegram-channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
</a>

<a href="https://t.me/CrazyNobita">
  <img src="https://img.shields.io/badge/👨‍💻_developer-crazynobita-black?style=for-the-badge">
</a>

<a href="https://vercel.com/new">
  <img src="https://img.shields.io/badge/🚀_deploy-vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
</a>

</div>

# ⭐ Support

If you like this project, give it a ⭐ on GitHub and share it with others.
