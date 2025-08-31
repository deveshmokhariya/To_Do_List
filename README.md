# To_Do_List
ABSTRACT

This project focuses on the design, development, and implementation of a dynamic To-Do List web application. The primary goal is to create a simple, intuitive, and efficient tool for users to manage their daily tasks. The application is built using core front-end web technologies: HTML for the structure, CSS for styling and user interface design, and JavaScript for functionality and user interaction.
The key features of the application include the ability for a user to add new tasks, mark tasks as completed with a visual strikethrough, and delete tasks from the list. The project successfully demonstrates the practical application of DOM (Document Object Model) manipulation, event handling, and modern CSS for creating a responsive and user-friendly experience. This report details the entire project lifecycle, from the initial objective and design methodology to the final code implementation and output.

1. OBJECTIVE

The primary objectives of this project are:
●	To design and develop a fully functional, client-side To-Do List web application. This involves creating an interface where users can interact with their list of tasks.
●	To demonstrate a strong understanding of fundamental front-end web technologies. This includes the proper use of HTML for semantic structure, CSS for presentation and layout, and JavaScript for handling logic and interactivity.
●	To implement core task management features. The application must allow users to create new tasks, visually distinguish between pending and completed tasks, and remove tasks.
●	To create a clean, intuitive, and responsive User Interface (UI). The design should be user-friendly and visually appealing, ensuring a positive User Experience (UX).
●	To gain practical experience in DOM manipulation. The project serves as a hands-on exercise in using JavaScript to dynamically create, modify, and delete HTML elements without reloading the page.

2. INTRODUCTION
2.1 Project Overview
In today's fast-paced world, task management is essential for productivity. A to-do list is a simple yet powerful tool for organizing tasks and goals. This project moves beyond the traditional pen-and-paper list to create a digital, interactive version. The "Dynamic To-Do List" is a single-page web application that runs entirely in the user's web browser, requiring no backend or database. It provides a straightforward interface for managing daily tasks efficiently.

2.2 Problem Statement
Many individuals struggle with keeping track of their daily responsibilities, leading to missed deadlines and decreased productivity. While many complex task management solutions exist, they often come with a steep learning curve or unnecessary features. The problem is the need for a simple, accessible, and easy-to-use digital tool for basic task management. This project aims to solve that problem by providing a minimalist yet effective web-based to-do list.

2.3 Scope of the Project
The scope of this project is focused on client-side functionality. The features included are:
●	Adding Tasks: Users can type a task into an input field and add it to their list.
●	Deleting Tasks: Users can remove any task from the list.
●	Marking Tasks Complete: Users can check a box next to a task, which visually marks it as complete.
The project does not include features like user accounts, data storage (tasks are lost on page refresh), cloud synchronization, or collaboration. It is designed as a foundational project to master core web development concepts.

2.4 Introduction to Web Technologies Used
The application is built on the foundational trio of front-end web development.
●	HTML (HyperText Markup Language): HTML is the standard markup language used to create the structure and content of web pages. It is the skeleton of our application. We used semantic HTML5 elements like <form>, <ul>, <li>, and <button> to ensure the structure is logical and accessible.
●	CSS (Cascading Style Sheets): CSS is the language used to describe the presentation and styling of a document written in HTML. It is the "skin" of our application, responsible for its visual appearance, layout, colors, and fonts. We used CSS for creating a modern design, including Flexbox for layout and pseudo-classes like :hover and :checked for interactive effects.
●	JavaScript: JavaScript is the high-level programming language that adds interactivity and logic to the web page. It is the "brain" of our application. We used JavaScript to listen for user actions (like button clicks), manipulate the HTML document (the DOM) to add or remove tasks, and handle all the application's logic.

3. METHODOLOGY
3.1 System Design
The application follows a simple client-side architecture. All the code (HTML, CSS, JavaScript) is sent to the user's web browser upon visiting the page. The browser's JavaScript engine then runs the code, making the page interactive. There is no server-side component; all operations happen directly within the browser.
3.2 UI/UX Design
The user interface was designed with simplicity and ease of use as the top priorities.
●	Layout: A single-column, centered layout was chosen to focus the user's attention on the list.
●	Input: A clear input field at the top with an "Add" button makes it obvious how to create a new task.
●	Task List: Each task is presented clearly. Interactive elements like the checkbox and delete button are standard UI components that users immediately understand.
●	Visual Feedback:
○	Checking a task provides immediate visual feedback by striking through the text.
○	The delete button is hidden by default and only appears when the user hovers over a task, keeping the interface clean.

5. RESULTS AND OUTPUT
  <img width="1024" height="610" alt="image" src="https://github.com/user-attachments/assets/9f1a1c33-c291-4a31-8e0b-05a6dfe538af" />
<img width="1012" height="603" alt="image" src="https://github.com/user-attachments/assets/c0be9d3c-dfee-4b5b-8542-1c12a4358e51" />
<img width="1014" height="604" alt="image" src="https://github.com/user-attachments/assets/6fbf400a-424c-4985-af50-a4fdaa9d1adc" />

 

6. CONCLUSION
6.1 Summary of Work
This project successfully achieved its objective of creating a dynamic to-do list web application using HTML, CSS, and JavaScript. The final product is a functional, single-page application that allows users to seamlessly add, delete, and mark tasks as complete. The project demonstrates a solid understanding of front-end development principles, including DOM manipulation, event handling, and modern styling techniques.

6.2 Future Scope
While the current application is fully functional for its intended purpose, there are several potential enhancements that could be made in the future:
●	Data Persistence: Implement localStorage to save the user's tasks in their browser, so the list is not lost when the page is refreshed.
●	Edit Functionality: Add the ability for users to edit a task after it has been created.
●	Task Prioritization: Introduce a feature to mark tasks with different priority levels (e.g., high, medium, low).
●	Backend Integration: Connect the application to a backend server and database to enable user accounts and cloud synchronization across devices.
