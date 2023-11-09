<div align="center">
<img width="30%" src="https://user-images.githubusercontent.com/72341453/134747028-7e2d90cc-a92f-4f66-815e-54a0d50cca54.PNG">

# StudyBuddy
</div>

**StudyBuddy** is a Python-based web application built using the Django framework, designed to simplify and enhance the study experience for students. It offers a range of features that improve organization, collaboration, and productivity.

## Key Features

### User Authentication

- Secure user registration and login system.
- Password hashing and salting for enhanced security.

### Dashboard

- A personalized dashboard for each user.
- Display upcoming assignments, tasks, and reminders.

### Task Management

- Create, edit, and delete tasks and assignments.
- Categorize tasks by subject or due date.
- Mark tasks as complete.

### Collaboration Tools

- Collaborative study groups creation and management.
- Real-time chat within study groups.
- Share files, notes, and resources within study groups.

### Resource Repository

- Upload and categorize study materials, notes, and files.
- Easily search and access resources as needed.

### Calendar and Reminders

- Add study sessions and events to the calendar.
- Set reminders for important deadlines and tasks.

### Progress Tracking

- Track and visualize your study progress over time.
- Generate reports and statistics to assess productivity.

## Technologies Used

- Django framework
- Python
- HTML, CSS, JavaScript
- Database (e.g., SQLite or PostgreSQL)

## Challenges Overcome

- Django Learning Curve: Learning Django, especially if it's your first time using the framework, can be challenging. Overcoming this challenge likely involved investing time in learning Django through documentation, tutorials, and practical exercises.

-User Authentication and Security: Implementing secure user authentication and password hashing can be complex. To overcome this challenge, you may have leveraged Django's built-in authentication system and followed best practices for securing user data.

-Real-Time Chat and Collaboration: Building real-time chat functionality within study groups might have required integrating WebSockets or a third-party library like Django Channels. You might have overcome this challenge by carefully researching and implementing real-time features.

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/hemannshu/StudyBud.git

```

--> Move into the directory where we have the project files : 
```bash
cd StudyBud

```

--> Create a virtual environment :
```bash
# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname

```

--> Activate the virtual environment :
```bash
envname\scripts\activate

```

--> Install the requirements :
```bash
pip install -r requirements.txt

```

#

### Running the App

--> To run the App, we use :
```bash
python manage.py runserver

```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/

#

### App Preview :

<table width="100%"> 
<tr>
<td width="50%">      
&nbsp; 
<br>
<p align="center">
  Feed Home
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747262-0a92233d-8010-40f8-84c5-8d94895aac44.PNG">
</td> 
<td width="50%">
<br>
<p align="center">
  Room Conversation Preview
</p>
<img src="https://user-images.githubusercontent.com/72341453/134747155-3ca5b55f-b064-4741-aeae-abe90bddf41e.PNG">  
</td>
</table>


