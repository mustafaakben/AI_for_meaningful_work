# Leveraging AI for Meaningful Work
---
## Resources
---
Elon University provides a range of resources to help faculty and staff learn about and utilize AI effectively. 
This section will be regularly updated as new resources become available.

### Elon University AI Resources
- [Elon University AI Hub](https://www.elon.edu/ai): A comprehensive platform for faculty and staff to explore and engage with AI technologies.
- [ElonGPT](https://www.elon.edu/u/academics/koenigsberger-learning-center/academic-advising/elongpt/): A specialized chatbot focused on answering university-related questions, with a primary emphasis on academic advising.
- [Elon's Enterprise Copilot](https://copilot.microsoft.com/): A powerful AI tool by Microsoft, available to Elon community members. Access requires signing in with your Elon email address.

### Additional AI Tools
- [ProductivityGPT](https://chatgpt.com/g/g-cqwSFz6LX-productivity-tools): A custom ChatGPT-based assistant designed to help develop productivity applications.
- [Event Scheduler](https://chatgpt.com/g/g-Zrqm4YZ0c-event-scheduler): An AI-powered tool to streamline event planning and scheduling.
- [SlideGPT](https://chatgpt.com/g/g-yw4P7Nu5R-slidegpt): An innovative AI assistant for creating PowerPoint presentations efficiently.

---
## Working with AI
---

## Task 1: Generating Meeting Minutes and Action Items with Zoom's AI Companion

Zoom's AI Companion can help you automatically generate meeting minutes and action items. Here's how to use it:

1. Download the Zoom app on your phone or computer.
2. During the meeting, after obtaining permission from all participants, record the session using Zoom's recording feature on **Cloud**.
3. After the meeting, access the recorded meeting on Zoom's website [here](https://elon.zoom.us/recording).
4. The AI Companion will provide a summary of the meeting and list action items.

Important Notes:
- **Obtain permission from all participants before recording the meeting.**
- Ensure you are using your Elon University Zoom account.
- Familiarize yourself with Elon's policies regarding meeting recordings and data privacy.

For a detailed guide on setting up Zoom's AI Companion, watch this tutorial video: [How to Set Up Zoom's AI Companion](https://elonuniversity-my.sharepoint.com/:v:/g/personal/makben_elon_edu/EfqdCT0smw5LgQWUyDx8t60BsMti3XEQ_K28fY-fEqmI_w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=wP3Zb6)


### Task 2: Creating Calendar Events
By using this prompt at ChatGPT, you will be creating calendar events, by using either text input or the images.

<details>
    <summary><b>Task 2: Creating Calendar Events</b></summary>

```
# Instructions for Generating a PowerPoint Presentation

1. **Document Analysis and Outline Creation**
   - Review the attached document thoroughly.
   - Extract crucial information from the file.
   - Generate a comprehensive outline based on the extracted information.
   - Present the outline to the user for approval before proceeding.

2. **Slide Design (upon user approval of the outline)**
   - Refer to the Python-pptx documentation at https://python-pptx.readthedocs.io for guidance.
   - Use Python code to design the slides with a 16:9 aspect ratio.
   - Create the presentation based on the approved outline.

3. **PPTX File Generation**
   - Generate the PPTX file using the Python-pptx library.
   - Provide the completed PPTX file to the user.
   - Use 16:9 Screen size for PPTX files.

4. **Image Enhancement (optional)**
   - Ask the user if they want to add images to their presentation.
   - If yes, propose three image ideas based on the presentation content.
   - Request the user to select one to three of these ideas.
   - Generate the selected images using the DALL-E function, with the following specifications:
     • Style: Iconic vector art
     • Background: White
     • Colors: Vibrant and colorful
     • Design: Simple yet aesthetically appealing
   - Integrate the generated images into the presentation.

5. **Final Delivery**
   - Present the completed PPTX file with any added images to the user.
   - Offer to make any final adjustments if needed.

Note: Ensure you have the necessary permissions and capabilities to perform each step, particularly regarding file handling, Python-pptx usage, and image generation with DALL-E.

**Always generate slides with 16:9 screen size. You can set the presentation aspect ratio to 16:9 with Inches(13.33), and Inches(7.5).** When you complete each section, summarize what you will do the next stage and ask permission for it.

When you are ready, state only "READY" 
```

</details>

### Task 3: Data Analysis
In this task, you will be analyzing data for your need. 

**Note for experimental purposes:** You can download the data from [here](https://github.com/mustafaakben/ai_for_students/blob/main/prompts/data/WorkshopData.csv).

<details>
    <summary><b>Task 3: Data Analysis</b></summary>

```
I am an assistant program director. I would like to analyze my department's workshop attendance data and write a report. 

Could you please read the attached document and wait for my next instructions.
```
```
We will analyze the data step-by-step. For each next stage, please wait for my approval.  

1) Calculate the attendance rate for each workshop, find the most popular and least popular workshop, show the bar chart by department of workshop.

2) Analyze the factors that might have influenced these faculty and staff members rating such as workshop topic, duration, professor, prerequisite level.

3) Find which workshops are most popular among different majors, create a box plot.

4) Finally, find which professor receives the highest grade and attendance, create bar chart.

Important before you move to the next stage, please wait for my approval and permission.
```

```
Please generate a comprehensive report with all the analysis included.
```

```
Please generate graphs for each analysis and put them in the report.
```

```
Save the report without any truncation and added images as a WORD file with the name "Report.docx". Use Python.
```
</details>  


### Task 4: Extraction Information from a Webpage
In this task, you will be extracting information from a webpage. 

Let's use this website: [click](https://www.elon.edu/u/academics/business/management/faculty/)

<details>
    <summary><b>Task 4: Extraction information from a webpage</b></summary>

```
This is a list of professors and their titles. Please extract information from this list and generate a table in the following format:

| Name | Title | Research Interest | E-Mail |

Now, for the top four professors, please write an email to inquire whether they are looking for a research assistant. Mention their research areas to show your interest.
```
</details>


### Task 5: PowerPoint Slide Generator
In this task, you will be generating a PowerPoint slide.

<details>
    <summary><b>Prompt 5: PowerPoint Slide Generator</b></summary>

```
# Instructions for Generating a PowerPoint Presentation

1. **Document Analysis and Outline Creation**
   - Review the attached document thoroughly.
   - Extract crucial information from the file.
   - Generate a comprehensive outline based on the extracted information.
   - Present the outline to the user for approval before proceeding.

2. **Slide Design (upon user approval of the outline)**
   - Refer to the Python-pptx documentation at https://python-pptx.readthedocs.io for guidance.
   - Use Python code to design the slides with a 16:9 aspect ratio.
   - Create the presentation based on the approved outline.

3. **PPTX File Generation**
   - Generate the PPTX file using the Python-pptx library.
   - Provide the completed PPTX file to the user.
   - Use 16:9 Screen size for PPTX files.

4. **Image Enhancement (optional)**
   - Ask the user if they want to add images to their presentation.
   - If yes, propose three image ideas based on the presentation content.
   - Request the user to select one to three of these ideas.
   - Generate the selected images using the DALL-E function, with the following specifications:
     • Style: Iconic vector art
     • Background: White
     • Colors: Vibrant and colorful
     • Design: Simple yet aesthetically appealing
   - Integrate the generated images into the presentation.

5. **Final Delivery**
   - Present the completed PPTX file with any added images to the user.
   - Offer to make any final adjustments if needed.

Note: Ensure you have the necessary permissions and capabilities to perform each step, particularly regarding file handling, Python-pptx usage, and image generation with DALL-E.

**Always generate slides with 16:9 screen size. You can set the presentation aspect ratio to 16:9 with Inches(13.33), and Inches(7.5).** When you complete each section, summarize what you will do the next stage and ask permission for it.

When you are ready, state ONLY "READY".
```
</details>


### Task 6: Planning – Critical Path Method
This task is designed to help faculty and staff plan and manage complex projects using the Critical Path Method (CPM). It's particularly useful when:

- You're working on a large-scale project with multiple interconnected tasks
- You need to optimize time management for a group project or personal endeavor
- You're preparing for a project management course or internship
- You want to develop skills in strategic planning and resource allocation


<details>
    <summary><b>Prompt 1: Planning – Critical Path Method</b></summary>

```
You are an AI assistant tasked with generating a Critical Path Method (CPM) analysis for a given project idea and expected finish date. Your goal is to identify possible steps in detail and ensure effective time management for the project.

Follow these steps to generate a comprehensive CPM analysis:

1. **Identify project tasks:**
   - Break down the project idea into specific, actionable tasks.
   - Ensure each task is clearly defined and measurable.

2. **Determine task dependencies:**
   - Identify which tasks must be completed before others can begin.
   - Create a logical sequence of tasks based on these dependencies.

3. **Estimate task durations:**
   - Assign a realistic time estimate to each task.
   - Consider potential challenges or delays that might affect task duration.

4. **Create a network diagram:**
   - Visually represent the tasks and their dependencies.
   - Use a format that clearly shows the flow of tasks from start to finish.

5. **Calculate the critical path:**
   - Identify the longest sequence of dependent tasks.
   - Determine the minimum time needed to complete the project.

6. **Analyze time management:**
   - Compare the critical path duration to the expected finish date.
   - Identify any potential time conflicts or areas where time management can be improved.
   - Suggest strategies for optimizing the project timeline if necessary.

Present your analysis in the following format:

- **Tasks:**
   - List all identified tasks here, numbered and with brief descriptions.

- **Dependencies:**
   - Describe task dependencies here, referencing task numbers.

- **Durations:**
   - List estimated durations for each task.

- **Network Diagram:**
   - Provide a text-based representation of the network diagram.

- **Critical Path:**
   - Identify the critical path and its duration.

- **Time Management Analysis:**
   - Provide your analysis of the project timeline, including any potential conflicts with the expected finish date and suggestions for optimization.

Ensure that your analysis is detailed, logical, and provides actionable insights for effective project management. If the expected finish date seems unrealistic based on your analysis, explain why and suggest a more feasible timeline.

Please state ready when you are ready.
```
```
Project: Create a newsletter group for Elon University as the Director of AI Integration.
Starting time: August 20, 2024
Completion time: September 20, 2024
```
</details>

---
## The End
---