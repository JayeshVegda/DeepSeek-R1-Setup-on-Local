# 🚀 Got DeepSeek R1 Running Locally – Full Setup Guide  

## 🔥 What is DeepSeek R1?  
DeepSeek R1 is a powerful **open-source AI model** that competes with **OpenAI o1** and **Claude 3.5 Sonnet** in math, coding, and reasoning tasks. The best part? You can run it **locally on your machine** for **free**, with **total privacy!**  

## 🛠️ Setup Guide (Windows, Mac, Linux)  
Follow these simple steps to get DeepSeek R1 running on your system:  

### 1️⃣ Install Ollama  
Ollama is a tool for running AI models locally. Download it here:  
🔗 [Ollama Download](https://ollama.com/download)  

### 2️⃣ Pull and Run DeepSeek R1 Locally  
Ollama supports multiple DeepSeek R1 model sizes. **Larger models require better GPU power.**  

#### Available Model Sizes:  
- **1.5B (smallest)** → `ollama run deepseek-r1:1.5b`  
- **8B** → `ollama run deepseek-r1:8b`  
- **14B** → `ollama run deepseek-r1:14b`  
- **32B** → `ollama run deepseek-r1:32b`  
- **70B (largest/smartest)** → `ollama run deepseek-r1:70b`  

**Start small!** Run the following command in your terminal to begin:  
```sh  
ollama run deepseek-r1:8b  
```  

⚠️ **Note:** The **32B and 70B versions require a powerful GPU**. Start small and upgrade based on your hardware capabilities.  

### 3️⃣ Set Up Chatbox for a Clean UI  
[Chatbox](https://chatboxai.app) is a **free, privacy-focused desktop client** for AI models.  

#### Steps to Configure Chatbox with Ollama:  
1. Download & install [Chatbox](https://chatboxai.app)  
2. Open **Settings** and change the **model provider** to **Ollama**  
3. Set the Ollama API host to `http://127.0.0.1:11434`  
4. **Save settings & start chatting with DeepSeek R1!** 🚀  

---  

## 🧪 Performance Tests  
Here are some **real-world tests** I ran on my local DeepSeek R1 setup:  

### 🔹 Explain TCP  
DeepSeek R1 provided a solid technical explanation of TCP concepts.  

### 🔹 Generate a Pac-Man Game  
It successfully generated Pac-Man game code! Though, some small bugs required manual fixes.  

---  

## 🤔 Final Thoughts  
I was initially **skeptical** due to the hype around AI models, but **DeepSeek R1 performs surprisingly well** for a **free, open-source model** that runs locally. It may not fully replace OpenAI or Claude, but it's a **great self-hosted alternative** for coding, reasoning, and general AI tasks.  

What do you think? **Try it out and let me know your thoughts!** 👇  
