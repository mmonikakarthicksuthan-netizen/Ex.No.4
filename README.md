# Ex.No.4-EXP 4 Generate the Prompt and eveluate that for following prompt types - Comparative Analysis Prompt Experiential Perspective Prompt - Everyday Functioning Prompts - Universal Prompt Structures Prompt Refinements- Prompt Size Limitations.
### NAME: Monika K                                                                           
### REGISTER NUMBER : 212223090016
### Aim: To write the prompt for the following prompt types and ompare that with differenet AI tools and evaluate that using any one evaluation method (eg. Rubrics). 1.Comparative Analysis Prompt 2. Experiential Perspective Prompt 3. Everyday Functioning Prompts 4. Universal Prompt Structures Prompt Refinements 5. Prompt Size Limitations design an AI 

### Explanation - Any one use case from Unit 5 and write the prompt for that with the unit 2 Prompt types given above.

Procedure:
1.	Define the Scenario and Use Case:
Scenario:
The manufacturing industry is looking to reduce manual monitoring and increase efficiency through automation. The system will utilize IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance. The goal is to streamline the production process, minimize downtime, and enhance energy efficiency.
Target Audience:
Manufacturing companies, specifically in sectors like automotive, electronics, and food processing, where automation can significantly improve productivity.

Main Objectives:

•	Improve production efficiency by 30%.
•	Minimize machinery downtime with predictive maintenance.
•	Enable real-time monitoring and remote control of manufacturing systems.
•	Reduce energy consumption by optimizing processes.
 
2.	Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

Comparative Analysis Prompt
Definition: Asking for a comparison between two or more concepts, often highlighting similarities and differences.
•	"Compare and contrast deep learning and machine learning."
•	"How do renewable and non-renewable energy sources differ?"

Experiential Perspective Prompt:
> 	“As a software engineer, what are the benefits of using cloud computing in your projects?”
>  “From a student’s perspective, describe the challenges of online learning.”

Everyday Functioning Prompts:
*	  “Describe the role of machine learning in everyday apps like YouTube or Netflix."
*	 	“How is encryption used in daily life when sending WhatsApp messages?”

Universal Prompt Structures:
^ 	“Explain [concept] in simple terms with an example.”
^  “Explain the process of [task] step by step.”

Prompt Size Limitations:
&  	“Translate this 5000-word essay into Tamil.”
→ Manageable chunks: “Translate the first 1000 words into Tamil, then continue.”
&  “Give me 50 examples of AI applications.”
→ Adjust for size: “Give me 10 AI applications at a time.”



# Result: The various types of Prompts are executed successfully with generated the report.

Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

Objective:
Develop a scenario-based report that demonstrates how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts) can be used to optimize MediGuide’s responses in different use cases.

Algorithm:
1. Zero-Shot Prompting:
Definition:
The model responds to a user prompt without prior examples.The model is expected to generate a response based on its pre-existing knowledge and understanding

Use Case 1: Symptom Concern
User Input: “I feel dizzy after breakfast.”

Prompt:
“Give a reason for dizziness after eating in elderly diabetic patients.”

Response:
"Dizziness after meals could indicate postprandial hypotension or a blood sugar imbalance. It's advised to monitor your blood pressure and sugar levels, and consult your doctor if this happens frequently."

Use Case 2: Quick Tip
User Input: “Tell me something healthy I can do today.”

Prompt:
“Provide one health tip for elderly patients with arthritis.”

Response:
"Stretch your joints for 5–10 minutes in the morning. Gentle movement can ease stiffness."

Strengths: Simple and quick.

Limitations: Lacks personalization.

how Zero-Shot Prompting works:
image

2. Few-Shot Prompting
Definition:
The model is guided using a few input-output examples.This technique helps the model generalize from the examples to new, similar tasks. Learn Prompting

Use Case: Food Recommendations for Health Conditions
Prompt Template:

Q: What should a diabetic person have for breakfast?
A: Oatmeal with nuts and no added sugar.

Q: What’s a good lunch for a person with high blood pressure?
A: Grilled vegetables and quinoa with low-sodium dressing.

Q: What should I have for dinner if I have both diabetes and arthritis?
Response:
"Grilled salmon with steamed broccoli and sweet potato is a great option. It’s anti-inflammatory and helps regulate blood sugar."

Strengths: Personalized and pattern-aware.

Limitations: Requires curated examples.

how Few-Shot Prompting works:
Screenshot 2025-05-22 144944

3. Chain-of-Thought Prompting
Definition:
The model is encouraged to reason step by step. Chain-of-thought prompting encourages the AI to break down its reasoning into a series of intermediate steps, enhancing its ability to handle complex tasks.

Use Case: Overdose Management
User Input: “I think I took my arthritis medicine twice.”

Prompt:
“Think step-by-step to handle accidental double dosing in elderly arthritis patients.”

Response:
"First, identify the medication type. NSAIDs like ibuprofen in double doses may cause stomach irritation or kidney stress. Do not take more. Watch for nausea or dizziness. Contact your doctor or emergency care immediately."

Strengths: Logical, safe, multi-step reasoning.

Limitations: Can be long for simple queries.

How Chain-of-Thought Prompting works:
image

4. Role-Based Prompting
Definition:
The model takes on a specific persona, e.g., doctor, caregiver, friend.

Use Case 1: Emotional Comfort
User Input: “I’m feeling lonely today.”

Prompt:
“You are MediGuide, a friendly and compassionate companion. Respond empathetically.”

Response:
"I’m sorry you're feeling that way. You're not alone — I’m here with you. Want to talk, play music, or maybe call a loved one?"

Use Case 2: Daily Motivation
Prompt:
“You are a wellness coach. Encourage the user to move more today.”

Response:
"Let’s try just 5 minutes of stretching. Movement lifts your mood and strengthens your body. You can do it!"

Strengths: Empathetic and human-like.

Limitations: Needs strong persona design to avoid inconsistency.

how Role-Based Prompting works:
image

5. Multi-Modal Prompting
Definition: The model responds to inputs beyond text — images, audio, video.
Use Case 1: Prescription Label Interpretation
User Uploads: Image of a pill bottle.

Prompt:
“Read the image and explain dosage instructions for a diabetic patient.”

Response:
"This prescription says: Metformin 500mg, take one tablet after breakfast and dinner. I’ll set reminders for 9 AM and 7 PM."

Use Case 2: Symptom via Voice Input
User Voice Note: “My chest feels heavy and I’m sweating.”

Prompt:
“Transcribe and analyze this for potential heart emergency.”

Response:
"Your symptoms may be cardiac-related. Please call emergency services or visit the nearest hospital immediately."

Strengths: Real-world input support

Limitations: Requires integrated tools for image/voice recognition

how Multi-Modal Prompting works:
image

Ethical and Practical Considerations:
image

Future Enhancements:
Context-Aware Memory: Maintain conversation history to personalize care.

Sensor Integration: Real-time vitals from smartwatches (e.g., heart rate, glucose).

Multilingual Chat: Support regional Indian and global languages.

Caregiver Dashboard: Allow family/doctors to monitor conversations for alerts.

pros and cons:
Screenshot 2025-05-22 142704

Result
Diverse prompting techniques — zero-shot, few-shot, chain-of-thought, role-based, and multi-modal — greatly improve MediGuide’s interaction quality. By tailoring its responses to the specific needs, contexts, and input modalities of elderly users, MediGuide becomes a reliable, empathetic, and intelligent virtual companion.
