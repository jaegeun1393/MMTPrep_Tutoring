# MMTPrep Tutoring Website
![<Example template>](<https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/main.png>)

<div align="center">

  ![Build](https://img.shields.io/badge/Build-Complete-green)
  ![Front-end](https://img.shields.io/badge/Front--end-React%20%2B%20Vite-lightblue)
  ![Back-end](https://img.shields.io/badge/Back--end-Nodejs%20Socket-yellowgreen)
  [![Link](https://img.shields.io/badge/Link-mmtprep.com-blue)](https://mmtprep.com)
[![Design](https://img.shields.io/badge/Design-Figma-purple)](https://www.figma.com/proto/sPkQhLHX04UTgPbHhiptCw/LMS-2?node-id=1172-1364&starting-point-node-id=1172%3A1364&t=eOELep6PxhT2bGq4-1)

</div>

**Short Description:**  
This is the tutoring website named **MMTPrep**—a custom MERN project that marks my first full-stack development experience. The website initially began on Wix Studio, but as the business grew, its requirements outpaced the capabilities of Wix. This led to the creation of a more robust and feature-rich solution.

<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/1708033784779.png" alt="Example template">
</div>

**Technology Stack:**
- **Front-end:** React + Vite.js
- **Back-end:** Node.js with Socket.io

**Core Features:**
- User Management
- Blog Management
- Scheduling Management
- Invoice Management
- Online Whiteboard Management
- Student Progress Report Management

# Before Start
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/Screenshot%202024-11-03%20192220.png">
</div>

This project was designed to ensure multiple functions operate seamlessly. Initially, I considered various cloud services such as AWS and Azure, but due to the dynamically fluctuating costs tied to web traffic, I decided to use a separate hosting service and installed **cPanel** (a web deployment service) to begin development.

The process started by using **Figma** to create the design mockups and outline the display requirements for the database. From there, I established the back-end foundation and moved forward with front-end development. Throughout the project, QA sessions were conducted to identify bugs and add new features. Given the diverse user groups—students, parents, and teachers—the design was planned from the start with an optimized UI for both mobile and desktop devices.

**JavaScript** was chosen as the primary language for this web project because of its ease of adoption and the broad support it offers for various web frameworks, allowing for more efficient development.


---

## **User Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/user.png">
</div>

This feature is designed to manage all types of users, including teachers, students, and parents. It facilitates adding or modifying user information, providing a user experience similar to other well-known platforms.

## **Blog Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/Screenshot%202024-11-03%20181604.png">
</div>

The blog management tool enables admins to add or edit articles, with a focus on SEO to improve Google rankings. The blog serves as a valuable resource for parents interested in learning more about the college admissions process. Additionally, any public Notion page can be uploaded as a blog article. For users familiar with Markdown, they can simply add the Notion page address to embed the Notion article directly on the MMTPrep website.

## **Scheduling Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/Screenshot_2023-04-22_221144.png">
</div>

This tool was specifically designed for managing the Summer SAT class schedule. Previously, scheduling was handled manually, involving calls to customers and handwritten notes. To streamline this process, the scheduling tool allows the admin to set up classes, while users submit their availability. The admin then approves the schedule, greatly reducing scheduling time and administrative overhead.

## **Invoice Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/invoice.png">
</div>
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/invoice_2.png">
</div>

A unique feature of the invoice management system is the ability to track whether parents have viewed the invoice. This helps reduce missed payments by notifying parents who haven't opened their invoices.

## **Online Whiteboard Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/class_room.png">
</div>
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/Screenshot%202024-11-03%20182757.png">
</div>

One of the standout features of the MMTPrep website is the online whiteboard, built with **Socket.io** for real-time data transfer and powered by **Fabric.js**. All whiteboard data is stored in a vector format, allowing for infinite scaling. The whiteboard also tracks user connections and includes protocol tools to ensure teachers can effectively manage student interactions during the sessions.

## **Student Progress Report Management**
<div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/progress_report.png">
</div>

This feature is designed to save class notes, allowing teachers to leave detailed feedback after each session. Teachers can evaluate the class content and provide insights into a student’s attitude and progress, helping to ensure the right guidance is provided to both students and teachers.

---

## **Conclusion**  
By utilizing **Vite**, we significantly reduced web rendering times, which helped MMTPrep rank at the top of Google search results. The efficient handling of various metadata also allows users to seamlessly navigate between different tabs. This web project was developed not only for convenience for the users but also to enhance the overall user experience. The design ensures that parents can easily access information about their child’s classes, invoices, and schedules on both mobile and desktop devices.

The highlight of this web project is undoubtedly the **Online Whiteboard**. Leveraging **Socket.io**, we addressed user delay and disconnection issues, and designed the whiteboard to allow teachers and students to freely interact using uploaded PDFs or images.

