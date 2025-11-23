# GemmaX_ChatCore_Jibitesh
A multimodal AI chat system built using **Gemma 3 models**, supporting:
- Text chat  
- Vision analysis  
- Local JAX inference  
- Function calling
  
## 1. Project Features
- **Cloud inference** using Google GenAI SDK  
- **Image + text multimodal inference**  
- **Local Gemma inference** using KerasHub + JAX  
- **Multi-turn chat** with conversation history  
- **Function calling** (datetime, currency converter)  
- **Formatted response display**  

---

## 2. Folder Structure

```
GemmaX-ChatCore/
│
├── GemmaX_ChatCore.ipynb      # Main notebook
├── assets/                    # Image files for multimodal demos
└── README.md
```


---

## 3. API Key Setup
Insert your own key inside the notebook:
```python
client = genai.Client(api_key="YOUR_API_KEY_HERE")
```
---
## 4. Usage

1. Open the notebook
2. Run setup cells
3. Use cloud or local inference
4. Test multimodal image analysis
5. Run the chat system
6. Try function calling examples

---
## 5. Notes

1. This project demonstrates a full multimodal pipeline using Gemma 3.
2. Identical versions of this project are maintained on two GitHub profiles for portfolio visibility.

---
## 6. Authors
- **Jibitesh Kumar Mishra**
- **Ankita Singh**
