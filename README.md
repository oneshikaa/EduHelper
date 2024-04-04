# EduHelper: Empowering Education through Collaboration

## Description:
CloudEdu is a revolutionary cloud-based platform designed to revolutionize the way educators manage, share, and deliver educational content. With a suite of intuitive tools and features, CloudEdu aims to enhance collaboration, transparency, and engagement within the educational community. Whether you're a teacher, student, or parent, CloudEdu provides the infrastructure needed to streamline educational processes and foster meaningful interactions.

## Features:
- **Seamless Resource Management:** EduHelper allows educators to effortlessly upload, schedule, and organize a variety of educational resources including notes, flowcharts, diagrams, videos, presentations, and more. With a user-friendly interface, teachers can efficiently manage their content library to support effective teaching and learning experiences.
  
- **Curriculum Planning and Display:** Educators can easily plan and organize curriculum for upcoming weeks, ensuring transparency and preparedness in their teaching approach. CloudEdu provides intuitive tools for displaying curriculum plans, enabling educators to communicate course objectives and timelines effectively.

- **Interactive User Engagement:** EduHelper incorporates interactive apps that facilitate communication and collaboration among users. Students, parents, and teachers can engage in discussions, post questions, reply to comments, and tag relevant subjects and users. This fosters a dynamic learning environment where users can actively participate and contribute to the educational discourse.

## Class Models:
1. **Courses:**
   - Class: Defines the class level (e.g., 10th grade, 11th grade, etc.).
   - Subject: Represents the subject taught within a specific class.
   - Lesson: Organizes individual lessons within a subject.
   - Comments: Enables users to leave comments on lessons, promoting discussion and interaction.

2. **Users:**
   - Custom User Model: The platform supports multi-user model and extends the Django user model to include additional user attributes such as name, bio, profile picture, and user type.

## User Types:
- **Teachers:** Educators responsible for creating and managing educational content.
- **Students:** Individuals enrolled in courses, accessing and engaging with course materials.
- **Parents:** Guardians or caregivers of students, monitoring their educational progress and involvement.

## Installation:
1. **Clone the Repository:** `git clone https://github.com/oneshikaa/EduHelper.git`
2. **Install Dependencies:** `pip install -r requirements.txt`
3. **Run Migrations:** `python manage.py migrate`
4. **Start the Server:** `python manage.py runserver`

## Usage:
1. **Register as a User:** Create an account specifying your user type (Teacher, Student, or Parent).
2. **Access Features:** Depending on your user type, access features such as uploading resources, planning curriculum, engaging in discussions, and more.
3. **Upload and Organize Resources:** Upload educational resources and organize them into subjects and lessons for easy access and navigation.
4. **Plan Curriculum:** Plan and schedule curriculum for upcoming weeks, providing transparency and clarity to students and parents.
5. **Engage in Discussions:** Participate in discussions, post questions, and reply to comments to enhance collaborative learning experiences.


