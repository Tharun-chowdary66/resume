<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tharun | Resume</title>
    <link rel="stylesheet" href="style.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: #f4f4f4;
            font-family: Arial, Helvetica, sans-serif;
            color: #333;
            padding: 30px;
        }
        
        .resume {
            max-width: 900px;
            margin: auto;
            background: #fff;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0, 0, 0, .15);
        }
        /* Header */
        
        header {
            background: #0d47a1;
            color: white;
            display: flex;
            align-items: center;
            padding: 30px;
        }
        
        .profile {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
            margin-right: 25px;
        }
        
        .header-text h1 {
            font-size: 36px;
        }
        
        .header-text h3 {
            margin: 8px 0;
            font-weight: 400;
        }
        
        .header-text p {
            margin: 4px 0;
        }
        
        .links {
            margin-top: 10px;
        }
        
        .links a {
            color: white;
            text-decoration: none;
            margin-right: 20px;
            font-weight: bold;
        }
        
        .links a:hover {
            text-decoration: underline;
        }
        /* Sections */
        
        section {
            padding: 25px 35px;
        }
        
        section h2 {
            color: #0d47a1;
            margin-bottom: 15px;
            border-left: 5px solid #0d47a1;
            padding-left: 10px;
        }
        /* Table */
        
        table {
            width: 100%;
            border-collapse: collapse;
        }
        
        table th {
            background: #0d47a1;
            color: white;
        }
        
        table th,
        table td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }
        /* Skills */
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skills span {
            background: #0d47a1;
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
        }
        /* Projects */
        
        .project {
            margin-bottom: 20px;
        }
        
        .project h4 {
            color: #0d47a1;
            margin-bottom: 6px;
        }
        /* Lists */
        
        ul {
            margin-left: 20px;
        }
        
        li {
            margin-bottom: 8px;
        }
        /* Footer */
        
        footer {
            background: #0d47a1;
            color: white;
            text-align: center;
            padding: 15px;
        }
        /* Responsive */
        
        @media(max-width:768px) {
            header {
                flex-direction: column;
                text-align: center;
            }
            .profile {
                margin-right: 0;
                margin-bottom: 20px;
            }
            .header-text h1 {
                font-size: 28px;
            }
            table {
                font-size: 14px;
            }
        }
    </style>
</head>

<body>

    <div class="resume">

        <!-- Header -->
        <header>
            <img src="profile.jpg" alt="Profile Photo" class="profile">
            <div class="header-text">
                <h1>Yangala Tharun</h1>
                <h3>B.Tech – AI & Data Science</h3>

                <p>📧 tharun@email.com</p>
                <p>📱 +91 9876543210</p>
                <p>📍 Chennai, India</p>

                <div class="links">
                    <a href="#">LinkedIn</a>
                    <a href="#">GitHub</a>
                </div>
            </div>
        </header>

        <!-- Career Objective -->
        <section>
            <h2>Career Objective</h2>

            <p>
                Motivated and enthusiastic AI & Data Science student seeking an opportunity to apply programming, database, and web development skills while contributing to organizational growth.
            </p>
        </section>

        <!-- Education -->
        <section>
            <h2>Education</h2>

            <table>
                <tr>
                    <th>Qualification</th>
                    <th>Institution</th>
                    <th>Year</th>
                    <th>Percentage</th>
                </tr>

                <tr>
                    <td>B.Tech AI & DS</td>
                    <td>JNN College</td>
                    <td>2023–2027</td>
                    <td>77.7%</td>
                </tr>

                <tr>
                    <td>Intermediate</td>
                    <td>Narayana College</td>
                    <td>2023</td>
                    <td>88%</td>
                </tr>

                <tr>
                    <td>SSC</td>
                    <td>Ratnam High School</td>
                    <td>2021</td>
                    <td>93%</td>
                </tr>

            </table>

        </section>

        <!-- Skills -->
        <section>

            <h2>Technical Skills</h2>

            <div class="skills">

                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
                <span>Java</span>
                <span>Python</span>
                <span>C#</span>
                <span>.NET</span>
                <span>SQL</span>
                <span>MongoDB</span>
                <span>Git</span>
                <span>GitHub</span>

            </div>

        </section>

        <!-- Projects -->
        <section>

            <h2>Projects</h2>

            <div class="project">

                <h4>AI-Powered Smart Factory Rating System</h4>

                <p>
                    Developed a dashboard to monitor factory performance using AI, real-time analytics, machine monitoring, and automated reports.
                </p>

            </div>

            <div class="project">

                <h4>Student Profile Dashboard</h4>

                <p>
                    Designed a responsive student management dashboard using HTML, CSS, and JavaScript with profile and academic details.
                </p>

            </div>

        </section>

        <!-- Certifications -->
        <section>

            <h2>Certifications</h2>

            <ul>

                <li>AWS Cloud Practitioner</li>
                <li>Java Programming</li>
                <li>Python Programming</li>
                <li>SQL Database</li>

            </ul>

        </section>

        <!-- Strengths -->
        <section>

            <h2>Strengths</h2>

            <ul>

                <li>Quick Learner</li>
                <li>Team Player</li>
                <li>Problem Solving</li>
                <li>Communication Skills</li>

            </ul>

        </section>

        <!-- Languages -->
        <section>

            <h2>Languages</h2>

            <p>English, Telugu, Tamil</p>

        </section>

        <!-- Footer -->

        <footer>

            <p>© 2026 Yangala Tharun</p>

        </footer>

    </div>

</body>

</html>
