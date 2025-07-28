# 🧾 Student Data Viewer – Streamlit App

This Streamlit app serves as a **simple dashboard for managing and viewing student and course registration information**. It allows users to navigate through multiple pages and explore datasets using an intuitive web interface.

---

## 📌 Objective

To create a multi-page Streamlit application that:
- Loads and displays student and course registration data from Excel files
- Provides clean, interactive layouts for different views
- Demonstrates basic use of Streamlit components for app development

---

## 🧰 Technologies Used

- **Python**
- **Streamlit** (UI)
- **Pandas** (data loading & manipulation)
- **Excel** (data source)

---

## 📂 Project Structure

```bash
Streamlit-checkpoint-2/
├── app.py                # Main Streamlit script
├── student_data.xlsx     # Excel file containing student info
├── registered_courses.xlsx # Excel file for course registrations
└── pages/
    └── Home.py           # Home page of the app
✨ Features
📄 Multi-page layout using streamlit.pages

📊 Student Data Display – View detailed student records

📚 Course Registration Viewer – See course enrollments

✅ Clean and minimal layout with titles, data tables, and navigation

🖼️ Screenshots
<p align="center"> <img src="images/home_page.png" alt="Home Page" width="600"/> </p> <p align="center"> <img src="images/student_data_page.png" alt="Student Data" width="600"/> </p>
▶️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/1Chizey/Streamlit-checkpoint-2.git
cd Streamlit-checkpoint-2
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Navigate through the app using the sidebar menu.

✅ Possible Improvements
Add search/filter functionality for students and courses

Upload new student data dynamically

Add charts/visuals (e.g., enrollment trends by course or gender)

Add authentication for secure access


⭐ Acknowledgements
Streamlit for providing the open-source UI framework

Pandas for data manipulation
📬 Contact
Francis Chizey
Data Scientist  | Streamlit Developer
https://github.com/1Chizey | www.linkedin.com/in/francis-chizey-8838a5256 | chizeyfrancis@gmail.com
