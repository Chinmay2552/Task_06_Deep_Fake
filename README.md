# Task_06_Deep_Fake
This project builds on Task_05: Syracuse Men’s Soccer 2024 – LLM Comparison Analysis, transforming statistical insights into short AI-generated “street interview” style videos.

The task goal: simulate 8-second interview clips where a coach answers questions about the team’s 2024 season using dataset-based insights.

For this task, I created two videos

🏟 Dataset Context

Source: 2024 Syracuse University Men’s Soccer cumulative stats

Content: Team records, player statistics, match logs, efficiency metrics, disciplinary records

Connection to Task_05: The dataset was first analyzed using ChatGPT and Perplexity AI. For Task_06, those insights were turned into short conversational interview answers.

💬 Prompts Used for Video Generation

I used Flow with Veo 3 Fast to generate the videos. Each prompt followed a template, with the specific question and answer swapped for each clip.
 prompt format:

Realistic 4K footage of a casual street interview in a lively urban setting, 
captured with a handheld camera and slight motion blur. 
A charismatic interviewer with a microphone (small logo: “Orange Insights”) stops a coach on the sidewalk. 
The interviewer asks: “Who was the most efficient goal scorer last year?” 
The coach responds: “Michal Gradus had perfect efficiency with one goal on one shot, 
but over a full season Kristjan Fortier was the most reliable, scoring two goals on six shots in fourteen games.” 
The background bustles with city life — pedestrians, traffic, shops, and murals. 
Use natural daylight and ambient city sounds.

🛠 Process & Tools

Tool Used: Flow with Veo 3 Fast for video generation
Approach: Generated single 8-second clips for each question, with scripts tied directly to Task_05 insights

What Worked:
Short, interview-style videos matched the Syracuse dataset context well
The model produced visually engaging outputs

What Didn’t Work:
Prompts weren’t always reflected 100% — e.g., logos, backgrounds, or expressions sometimes didn’t appear as scripted
Some dialogue felt less natural in delivery compared to the written script

📂 Files Included
Q1_who_was.mp4 — Efficient Goal Scorer
Who_made_the.mp4 — Offensive Impact
README.md — Documentation (this file)

Prepared by Chinmay Ranade
Task_06 – Deep Fake Interview Project
Prompts weren’t always reflected 100% — e.g., logos, backgrounds, or expressions sometimes didn’t appear as scripted

Some dialogue felt less natural in delivery compared to the written script
