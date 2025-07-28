# 📘 Prompt Engineering Task – NCERT Content Extraction & Study Planner

## 📌 Project Overview
This project was created for **Task 1 – Prompt Engineering**. The objective is to:
1. Design **two reusable prompts**:
   - Prompt 1: Extract structured NCERT content.
   - Prompt 2: Generate a day-wise study planner.
2. Extract NCERT Class 8 Science textbook data into a **structured JSON**.
3. Convert extracted data into **Excel**.
4. Generate a **study planner** in PDF format.
5. Create a **Knowledge Graph** (text and visual) showing relationships between Chapters, Topics, Subtopics, and Content Types.

## 📂 Folder Structure
Prompt_Engineering_Task/
│── prompts/
│   ├── prompt_extraction.txt        # Prompt 1: Extraction
│   └── prompt_study_planner.txt     # Prompt 2: Study Planner
│── chapter-extract.json             # Extracted textbook data
│── Science-output.xlsx              # Excel format of extracted data
│── study_planner.pdf                # Final study planner in PDF
│── knowledge_graph.txt              # Text-based Knowledge Graph
│── knowledge_graph_detailed.png     # Visual Knowledge Graph
│── workflow_flowchart.png           # Process Flowchart
│── NCERT_Content_Extraction_StudyPlanner.ipynb # Final Jupyter Notebook
│── README.md                        # Project Documentation

## 🚀 How to Run
### ✅ Requirements
Install required libraries:
pip install pandas reportlab networkx matplotlib

### ✅ Steps
1. Clone this repository or download as ZIP.
2. Open the Jupyter Notebook:
   jupyter lab
3. Run `NCERT_Content_Extraction_StudyPlanner.ipynb` step by step.
4. Generated outputs:
   - chapter-extract.json
   - Science-output.xlsx
   - study_planner.pdf
   - knowledge_graph_detailed.png
   - workflow_flowchart.png

## ✅ Deliverables
- Prompts: prompt_extraction.txt, prompt_study_planner.txt
- Outputs: chapter-extract.json, Science-output.xlsx, study_planner.pdf, knowledge_graph.txt, knowledge_graph_detailed.png, workflow_flowchart.png
- Code: NCERT_Content_Extraction_StudyPlanner.ipynb

## 📊 Knowledge Graph
- Text Graph (knowledge_graph.txt): Shows hierarchical relationships
  Chapter: Crop Production and Management
    └─ Topic: Agricultural Practices
        └─ Subtopic: Preparation of Soil
            └─ Content Types: Paragraphs, Activities, Questions, etc.
- Visual Graph (knowledge_graph_detailed.png): Displays connections between Chapters → Topics → Subtopics → Content Types.

## 🛠 Workflow
The process includes:
1. Extract Content (Prompt 1)
2. Save Structured JSON
3. Convert JSON → Excel
4. Generate Study Planner (Prompt 2)
5. Export Planner to PDF
6. Create Knowledge Graph

See workflow_flowchart.png for visualization.

## ✨ Features
- Reusable Prompt Templates
- JSON → Excel Conversion
- Automatic Study Planner Generation
- PDF Export
- Knowledge Graph with Content Types
- Clear Documentation

## 🎯 Author
Swati Nain  
_Task completed for Prompt Engineering Evaluation – July 2025_
