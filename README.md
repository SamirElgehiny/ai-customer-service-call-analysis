# AI-Powered Customer Service Call Analysis  
📞🎙️ **Speech-to-Text, Speaker Diarization, AI Insights & Agent Dialogue Optimization** 🤖🔍  

## 📌 Overview  
This system analyzes **recorded customer service calls** and applies **AI-driven enhancements** to:  
✅ **Identify speakers** (customer vs. agent).  
✅ **Extract keywords & key topics** discussed.  
✅ **Analyze customer pain points & service gaps.**  
✅ **Provide AI-generated improvements for agent dialogue.**  
✅ **Generate a structured JSON report with insights & recommendations.**  

This tool is designed to help **businesses, call centers, and customer support teams** improve communication, reduce service gaps, and enhance agent performance.  

---

## 🚀 Features  
- **Speech-to-Text Conversion** 🎙️ (Google Speech Recognition for call transcription)  
- **Speaker Diarization** 👥 (Pyannote for speaker segmentation)  
- **Keyword Extraction** 🔑 (AI-powered topic detection)  
- **AI-Powered Insights** 📊 (Summarizes customer concerns & service gaps)  
- **Agent Dialogue Optimization** 💬 (Improves agent responses with AI-generated suggestions)  
- **Structured Reports (JSON Output)** 📝 (Full transcript, insights & recommendations)  

---

## 🔄 System Workflow  

### **1️⃣ Speaker Diarization**  
- Identifies and separates speakers in the conversation (e.g., **agent vs. customer**).  
- Uses **Pyannote (Hugging Face Model)** for accurate **speaker segmentation**.  

### **2️⃣ Speech-to-Text Conversion**  
- Converts **spoken dialogue into text** using **Google Speech Recognition**.  
- Generates a **full transcript** of the call, with timestamps and labeled speakers.  

### **3️⃣ AI-Powered Keyword Extraction**  
- Uses **AI agents** to detect **key topics** discussed in the conversation.  
- Extracted **keywords help summarize the core themes of the call**.  

### **4️⃣ AI Conversation Analysis & Insights**  
- Analyzes **customer pain points**, common service issues, and agent response quality.  
- Detects **gaps in service or information clarity**.  

### **5️⃣ AI-Powered Agent Dialogue Suggestions**  
- **Enhances agent responses** by providing **AI-generated alternative suggestions**.  
- Helps agents **sound more professional, proactive, and customer-friendly**.  

### **6️⃣ AI-Generated Recommendations for Customer Service**  
- Provides **general service recommendations** to enhance customer interactions.  
- Improves **customer satisfaction and call efficiency**.  

### **7️⃣ Structured JSON Output**  
- The final output is **a structured JSON file** containing:  
  ✅ **Full transcript** with labeled speaker segments.  
  ✅ **Extracted keywords** from the conversation.  
  ✅ **AI-generated insights on service gaps & customer concerns**.  
  ✅ **Agent dialogue improvements with suggested responses**.  
  ✅ **General recommendations to optimize service quality**.  

---

## 📂 Example Data  


📁 **Sample Call Recording:** `call.wav`  
- An example **customer service conversation** used to demonstrate the system's capabilities.  
- The system **processes this audio file and generates insights**.  

📁 **Generated JSON Report:** `call.json`  
- The output file containing **structured insights from the analyzed call**.  
- **Includes:**  
  ✅ **Transcript** (with timestamps and speaker labels)  
  ✅ **Extracted keywords**  
  ✅ **AI-generated customer service insights**  
  ✅ **Agent response improvements & dialogue optimization**  
  ✅ **Actionable recommendations for service enhancement**  

To understand how the system works, check out the **included JSON file**, which provides a structured summary of the sample call.  
