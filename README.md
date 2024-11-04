# MMTPrep Tutoring Website
![<Example template>](<https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/main.png>)
![Build Status](https://img.shields.io/badge/Build%20Status-Passing-brightgreen?style=flat)

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

