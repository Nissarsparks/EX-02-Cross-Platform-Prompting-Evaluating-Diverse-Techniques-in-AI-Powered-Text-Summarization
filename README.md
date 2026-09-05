# EX-02 – Cross-Platform Prompting: Evaluating Diverse Prompt Engineering Techniques in AI-Powered Applications


---

# OBJECTIVE

To design and evaluate prompts using different prompt structures and understand how a basic prompt can be improved step-by-step into a detailed and effective prompt for an AI-powered application.

---

# APPLICATION

**Application:** AI-Powered Pothole Detection System

The system uses computer vision and artificial intelligence to identify potholes from road images or video. The AI can assist in detecting potholes, describing their severity, and presenting the detection results clearly.

---

# AI PLATFORMS

The prompts can be tested using different AI platforms:

* ChatGPT
* Google Gemini
* Claude AI

---

# PROMPT ENGINEERING TECHNIQUES

The following prompt structures are used:

1. Basic Prompt
2. Role Prompt
3. Context Prompt
4. Constraint Prompt
5. Output Format Prompt

---

# 1. BASIC PROMPT

## Description

A Basic Prompt provides a simple instruction to the AI without additional context, role, constraints, or output requirements.

### Prompt

> Explain pothole detection using AI.

### Sample Output

AI explains that pothole detection uses computer vision and machine learning to identify damaged areas on roads. Images or video frames are processed and analyzed to detect potholes.

### Evaluation

* Simple and easy to understand.
* Generates a general explanation.
* Requires very little input.
* Output may be broad and less specific.
* Not suitable when a detailed project-oriented response is required.

---

# 2. ROLE PROMPT

## Description

A Role Prompt assigns a specific role to the AI. This helps the AI provide a response from the perspective of a particular expert.

### Prompt

> Act as a computer vision engineer and explain how to develop an AI-based pothole detection system.

### Sample Output

**AI:**
As a computer vision engineer, I would develop the pothole detection system using the following steps:

1. Collect road images and videos.
2. Create and label a pothole dataset.
3. Preprocess the images.
4. Train an object detection model such as YOLO.
5. Test the trained model.
6. Detect potholes in real-time video.
7. Display bounding boxes and detection confidence.

### Evaluation

* Provides a more professional response.
* Focuses on computer vision development.
* Gives technically relevant information.
* Better than a basic prompt for project development.
* The output may still require additional constraints.

---

# 3. CONTEXT PROMPT

## Description

A Context Prompt provides background information about the project. This allows the AI to understand the purpose, environment, and requirements before generating a response.

### Prompt

> I am developing a college computer vision project for detecting potholes on roads using a live camera feed. The system should identify potholes in video frames and display bounding boxes around detected potholes. Explain a suitable approach for developing this system using Python and a YOLO-based object detection model.

### Sample Output

**AI:**
A suitable approach is to use Python with OpenCV and a YOLO-based object detection model.

The development process can include:

1. Collect pothole images.
2. Annotate potholes using bounding boxes.
3. Divide the dataset into training and validation sets.
4. Train a YOLO detection model.
5. Use OpenCV to capture live video.
6. Pass each frame to the trained model.
7. Draw bounding boxes around detected potholes.
8. Display the detection confidence and results.

### Evaluation

* AI understands the project background.
* Produces more relevant technical information.
* Provides project-specific suggestions.
* Reduces irrelevant responses.
* Better suited for academic project development.

---

# 4. CONSTRAINT PROMPT

## Description

A Constraint Prompt specifies limitations or rules that the AI must follow while generating the response.

### Prompt

> I am developing a college project for real-time pothole detection using Python, OpenCV, and YOLO. Explain the implementation procedure. Use simple technical language, provide step-by-step instructions, and do not suggest hardware other than a normal webcam. Keep the explanation suitable for a student project.

### Sample Output

**AI:**

### Implementation Steps

1. **Dataset Collection**
   Collect road images containing potholes.

2. **Image Annotation**
   Label each pothole using bounding boxes.

3. **Dataset Preparation**
   Divide the dataset into training and validation images.

4. **Model Training**
   Train a YOLO model using the annotated dataset.

5. **Video Input**
   Use OpenCV to access the webcam.

6. **Pothole Detection**
   Send each video frame to the trained YOLO model.

7. **Result Display**
   Draw bounding boxes around detected potholes.

8. **Testing**
   Test the system using different road conditions.

### Evaluation

* Follows the specified restrictions.
* Uses simple technical language.
* Produces focused information.
* Suitable for student-level project implementation.
* Avoids unnecessary hardware and advanced requirements.

---

# 5. OUTPUT FORMAT PROMPT

## Description

An Output Format Prompt specifies exactly how the AI should structure its response. This improves readability and makes the output easier to use in reports or presentations.

### Prompt

> Act as a computer vision engineer. I am developing a college project for real-time pothole detection using Python, OpenCV, and YOLO. Explain the implementation in simple technical language. Do not suggest hardware other than a webcam. Present the answer using the following format:
>
> **1. Objective**
> **2. Required Software**
> **3. Dataset**
> **4. Methodology**
> **5. Implementation Steps**
> **6. Expected Output**
> **7. Advantages**
> **8. Limitations**

### Sample Output

## 1. Objective

To detect potholes automatically from road images or live camera video using a YOLO-based object detection model.

## 2. Required Software

* Python
* OpenCV
* YOLO
* Google Colab or a Python environment

## 3. Dataset

A dataset containing road images with potholes is required. Each pothole should be labelled using a bounding box.

## 4. Methodology

The system captures an image or video frame, processes it using the trained YOLO model, detects potholes, and displays bounding boxes around the detected regions.

## 5. Implementation Steps

1. Collect the dataset.
2. Annotate potholes.
3. Prepare the dataset.
4. Train the YOLO model.
5. Test the trained model.
6. Connect the webcam.
7. Perform real-time detection.
8. Display the results.

## 6. Expected Output

The system displays a bounding box around detected potholes along with the class name and confidence score.

## 7. Advantages

* Automatic pothole detection.
* Real-time operation.
* Reduces manual inspection.
* Can be integrated with road-monitoring systems.

## 8. Limitations

* Detection accuracy depends on dataset quality.
* Poor lighting may affect detection.
* Occluded or very small potholes may be difficult to detect.

### Evaluation

* Highly structured response.
* Easy to read and include in a project report.
* Covers all important project components.
* Gives predictable output.
* Most useful for documentation and academic submissions.

---

# PROMPT PROGRESSION

The prompt was improved gradually from a simple instruction to a detailed project-specific instruction.

| Stage | Prompt Type          | Improvement                                  |
| ----- | -------------------- | -------------------------------------------- |
| 1     | Basic Prompt         | Gives a general question                     |
| 2     | Role Prompt          | Adds an expert role                          |
| 3     | Context Prompt       | Adds project background                      |
| 4     | Constraint Prompt    | Adds specific limitations                    |
| 5     | Output Format Prompt | Controls the structure of the final response |

---

# COMPARISON OF PROMPT TYPES

| Prompt Type          | Information Provided  | Output Quality   | Best Use                  |
| -------------------- | --------------------- | ---------------- | ------------------------- |
| Basic Prompt         | Minimal               | Basic            | General questions         |
| Role Prompt          | AI role               | Better           | Expert explanations       |
| Context Prompt       | Project background    | More relevant    | Project development       |
| Constraint Prompt    | Rules and limitations | Focused          | Specific requirements     |
| Output Format Prompt | Required structure    | Highly organized | Reports and documentation |

---

# CROSS-PLATFORM EVALUATION

| Criteria              | ChatGPT   | Gemini    | Claude AI |
| --------------------- | --------- | --------- | --------- |
| Accuracy              | Excellent | Very Good | Excellent |
| Clarity               | Excellent | Very Good | Excellent |
| Technical Relevance   | Excellent | Very Good | Excellent |
| Structure             | Excellent | Good      | Excellent |
| Instruction Following | Excellent | Very Good | Excellent |
| User Experience       | Excellent | Very Good | Excellent |

---

# OBSERVATION

* The **Basic Prompt** produced a general explanation with limited project-specific information.
* The **Role Prompt** generated a more professional response by assigning the role of a computer vision engineer.
* The **Context Prompt** improved relevance by providing details about the pothole detection project.
* The **Constraint Prompt** produced a more focused answer by specifying technical and project limitations.
* The **Output Format Prompt** generated the most organized response and was particularly useful for project documentation.
* Across different AI platforms, the final detailed prompt generally produced more useful and structured results than the basic prompt.

---

# RESULT

Thus, different prompt structures were successfully designed and evaluated for an **AI-powered Pothole Detection System**.

The experiment demonstrated that progressively adding **role, context, constraints, and output-format requirements** improves the relevance, clarity, structure, and usefulness of AI-generated responses.

---

# CONCLUSION

The experiment shows that prompt engineering plays an important role in improving AI responses.

* **Basic Prompts** are suitable for simple questions.
* **Role Prompts** provide expert-oriented responses.
* **Context Prompts** make responses more relevant to a specific project.
* **Constraint Prompts** control the scope and limitations of the response.
* **Output Format Prompts** provide organized and predictable results.

Therefore, combining all five techniques into a **final structured prompt** produces a more useful response for AI-powered project development.
