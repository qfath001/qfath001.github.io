---
layout: home
---

![Profile Picture](/assets/images/professionalpicture_fathima.jpg){:class="profile-img"}

## About Me
I’m Quhura Fathima, a Computer Science graduate student at Old Dominion University with over 2 years of experience in full-stack development, database optimization, and cloud deployment. My technical expertise spans Java, Python, C++, JavaScript, SAP HANA, MySQL, and cloud platforms like AWS and Azure. I have a strong foundation in Cybersecurity, AI, and ML, with practical experience in implementing secure systems and developing data-driven solutions. In addition, I’ve worked at Accenture as an Application Development Associate, where I optimized database performance and automated processes, and at Cognizant, where I contributed to database management and business intelligence reporting. Beyond my technical skills, I am the President of ACM-W at Old Dominion University, leading initiatives to empower women in computing and foster community engagement. I am always eager to learn and apply new technologies to solve real-world problems, and I enjoy contributing to the tech community through leadership and collaboration.

## Projects

<div class="projects-container">
  <div class="project-icon" onclick="showProjectDetails(1)">
    <img src="/assets/icons/course-advising-icon.png" alt="Course Advising Portal">
    <p>Course Advising Portal</p>
  </div>
  <div class="project-icon" onclick="showProjectDetails(2)">
    <img src="/assets/icons/library-system-icon.png" alt="Library Management System">
    <p>Library Management System</p>
  </div>
  <div class="project-icon" onclick="showProjectDetails(3)">
    <img src="/assets/icons/gesture-system-icon.png" alt="Gesture-Based Input System">
    <p>Gesture-Based Input System</p>
  </div>
</div>

<!-- Project Modal/Pop-up -->
<div id="project-modal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <div id="project-details"></div>
  </div>
</div>

<script>
  function showProjectDetails(projectId) {
    var projectDetails = '';
    if (projectId === 1) {
      projectDetails = `
        <h2>Course Advising Portal</h2>
        <p><strong>Technologies:</strong> React.js, Node.js, Express.js, MySQL, Firebase, Render</p>
        <p><strong>Summary:</strong> Developed a student advising system to streamline course advising with real-time validation and form submission. Built an admin dashboard with role-based access for form approval, reducing manual workload by 40%. </p>
      `;
    } else if (projectId === 2) {
      projectDetails = `
        <h2>Library Management System</h2>
        <p><strong>Technologies:</strong> React, Node.js, MySQL (XAMPP), Bootstrap</p>
        <p><strong>Summary:</strong> Created a full-stack application with user authentication and role-based access for students, librarians, and administrators. Designed RESTful APIs for managing book inventory, improving operational efficiency.</p>
      `;
    } else if (projectId === 3) {
      projectDetails = `
        <h2>Gesture-Based Input System</h2>
        <p><strong>Technologies:</strong> Python, OpenCV, Mediapipe</p>
        <p><strong>Summary:</strong> Built a real-time hand recognition system to control media playback using gesture inputs. Led a team to implement image processing algorithms, achieving 90% recognition accuracy.</p>
      `;
    }

    document.getElementById('project-details').innerHTML = projectDetails;
    document.getElementById('project-modal').style.display = 'block';
  }

  var modal = document.getElementById('project-modal');
  var span = document.getElementsByClassName('close')[0];

  span.onclick = function() {
    modal.style.display = 'none';
  }

  window.onclick = function(event) {
    if (event.target == modal) {
      modal.style.display = 'none';
    }
  }
</script>

### Contact Information
- **Email**: [quhurafathima56@gmail.com](mailto:quhurafathima56@gmail.com)
- **LinkedIn**: [https://www.linkedin.com/in/quhurafathima/](https://www.linkedin.com/in/quhurafathima/)

## Resume
You can download my resume as a PDF by clicking the link below:
[Download Resume](assets/Resume_Latest_Fathima.pdf)

---