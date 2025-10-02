#  Get Started with Prompt Builder (Salesforce Project)

This repository documents my hands-on project from Salesforce Trailhead: **Get Started with Prompt Builder**.  
In this project, I created and tested a **Prompt Template** using Einstein Generative AI to automatically generate a **Quick Summary** for Case records.

---

## 🎯 Learning Objectives
- Create and test a prompt template that includes **merge fields**.  
- Associate a prompt template with a **Case field** for field generation.  
- Streamline content generation using **Einstein Generative AI**.  

---

## 🛠 Project Steps

### 1️⃣ Enable Einstein Generative AI
- Opened **Einstein Setup** and turned on Einstein.  
- Refreshed to see new AI settings.  

### 2️⃣ Create Prompt Template
- Type: **Field Generation**  
- Name: **Quick Summary**  
- Object: **Case**  
- Field: **Quick Summary**  
- Added a prompt with merge fields:
  3️⃣ Test Prompt Template
- Selected Case **00001002** as sample.  
- Previewed and got a generated summary from **OpenAI GPT-4 Omni Mini**.  

### 4️⃣ Add Prompt Template to Case Page
- Upgraded **Case Record Page** to **Dynamic Forms**.  
- Linked **Quick Summary field** with the Prompt Template.  
- Activated page and tested field with Einstein overlay.  

---

## ✅ Final Result
- Case records now include a **Quick Summary field** powered by Einstein Generative AI.  
- With a single click, support agents can get an AI-generated case summary.  

---

## 📸 Screenshots Included
1. **Einstein Setup** (toggle enabled).  
2. **New Prompt Template Creation** (Quick Summary).  
3. **Prompt text with merge fields** inserted.  
4. **Preview step** showing generated response.  
5. **Case Page upgrade to Dynamic Forms**.  
6. **Quick Summary field with Einstein overlay suggestion**.  
7. **Final Case record showing AI-generated Quick Summary filled in**.  

---

## 🌟 Key Takeaways
- Prompt Builder lets us combine **data + instructions** for scalable AI.  
- Merge fields ensure **personalized and dynamic outputs**.  
- This feature saves support agents’ time and increases productivity.  

---

## 🔗 Source
This project was built following Salesforce Trailhead:  
👉 [Get Started with Prompt Builder](https://trailhead.salesforce.com/)  


## 📸 Screenshots
![Prompt Builder Setup]([./screenshots/Screenshot (13876).png](https://github.com/Reyhan786/salesforce-prompt-case-summarizer/blob/0338e1074667b500d6683cf1d56e99efa4a70238/screenshots/Screenshot%20(13876).png))

![Prompt Builder Setup].
(./screenshots/prompt-output.png)  
![Flow Integration](./screenshots/flow.png)  


