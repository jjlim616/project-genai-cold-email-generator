# AI Cold Email Generator

An AI-powered tool that generates personalized cold emails for business development and recruitment purposes. It is using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.

## 📝 Sample Output
![image](https://github.com/user-attachments/assets/4985c049-464a-4dbc-b683-7c6093e714e7)

## 🛠️ Architecture Diagram
![image](https://github.com/user-attachments/assets/a8dfe5d9-b1de-4e95-b67d-b430659bca9d)

## 🚀 Quick Start
1. Clone the repository
2. Install dependencies:
   ```commandline
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your Groq API key
4.  Run the streamlit app:
    ```commandline
    streamlit run app/main.py
    ```

## 🙏 Credits and Acknowledgments
This project is a modified version of the project-genai-cold-email-generator created by Codebasics. The original project provided the foundation for cold email generation using AI.

This version was created following the tutorial by Codebasics ([[Tutorial Link]](https://youtu.be/CO4E_9V6li0?si=qcsOcAedbxqNbvtp)).
📄 License
This project is licensed under the same terms as the original project - MIT License.
