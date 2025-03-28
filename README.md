# MindMesh: FROM TEXT TO MINDMAP

## **Introduction**
MindMesh is an innovative web platform that enables users to upload PDF, image, and text files, summarize their content using advanced AI algorithms, and generate mind maps for a visual representation of the information. The platform is designed for educational purposes, helping students and professionals to quickly extract key insights from documents and visualize them in an easy-to-understand format.

## **Features**
- **File Upload:** Users can upload PDF, image, and text files for processing.
- **Content Summarization:** The uploaded content is summarized using an AI summarization model, providing concise and easy-to-read summaries.
- **Mindmap Generation:** After summarizing the content, users can generate a mind map for a visual representation of the key points.
- **View Mindmap:** A separate page is available to view the generated mind map after it is created.

## **Technologies Used**
- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Python, Flask
- **AI Model:** Gemini API (for summarizing content)
- **Visualization:** Pydot for generating DOT files and rendering mind maps
- **Storage:** Firebase Storage

## **Installation Instructions**

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/MindMesh.git
    ```

2. Install the required dependencies:
   - Navigate to the project directory:
     ```bash
     cd mindmesh
     ```

3. Set up Firebase:
   - Download your `serviceAccountKey.json` from Firebase and place it in the appropriate directory for backend access.
   
4. Run the application locally:
    - Start the backend server:
      ```bash
      python app.py
      ```
    - Open the frontend in your browser:
      ```bash
      npm start
      ```

5. Visit the platform at `http://localhost:3000` to start using the summarization and mind map generation features.

