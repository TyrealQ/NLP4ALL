# Overview
NLP4ALL is a project focused on advancing NLP applications in sport management research. We are presenting our vision and preliminary findings at the 2025 NASSM annual conference in San Diego. This repository contains supporting materials for our workshop presentation.

## Zeigler Folder
The `Zeigler` folder contains 33 publicly available Zeigler Award lectures published in the *Journal of Sport Management*. Each lecture is provided in PDF, Markdown, and JSON formats to facilitate verification, preprocessing, and NLP analysis.

## SystemPrompt Folder
The `SystemPrompt` folder contains the exact system prompts (Research Assistant and Supervisor roles) utilized during our experiments. These prompts can help users replicate or experiment with our analyses to verify findings or extend our methodology.

## Experiment Instructions
1. Go to [Google AI Studio](https://aistudio.google.com).
2. Select the `Gemini 2.5 Pro Preview` model.
3. Set `Temperature` to 1.
4. Choose `Structured Output` under `Tools`.
5. Use the system prompts provided in the `SystemPrompt` folder to configure `System Instructions`.
6. Upload a Zeigler lecture from the `Zeigler` folder, preferably in Markdown or JSON format.
7. Hit `Run`.
