<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>
        Riya Shakya - Personal Portfolio
    </title>

    <meta name="description"
          content="Personal portfolio of Riya Shakya">
</head>

<body>

    <a href="#main-content">Move to main content</a>

    <header>

        <h1>Riya Shakya</h1>

        <p>Student | Web Development | Database Management</p>

        <nav aria-label="primary">

            <ul>
                <li><a href="#about-me">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

        </nav>

    </header>


    <main id="main-content">


        <!-- ABOUT ME -->

        <section id="about-me">

            <h2>ABOUT RIYA SHAKYA</h2>

            <table border="1">

                <tr>

                    <td>
                        <img src="images/profile.jpg"
                             alt="Profile photograph of Riya Shakya"
                             width="200">
                    </td>

                    <td>

                        <p>
                            My name is Riya Shakya, and I am a student
                            interested in technology, web development,
                            database management, and software engineering.
                            I enjoy learning new technologies and developing
                            simple and useful digital projects. I like
                            learning through practical activities because
                            they help me understand technical concepts
                            more clearly. My goal is to improve my
                            technical knowledge and create meaningful
                            projects using technology.
                        </p>

                    </td>

                </tr>

            </table>

        </section>


        <!-- SKILLS -->

        <section id="skills">

            <h2>TECHNICAL SKILLS</h2>

            <dl>

                <dt><strong>HTML5</strong></dt>

                <dd>
                    Creating structured and semantic web pages.
                </dd>


                <dt><strong>CSS</strong></dt>

                <dd>
                    Basic understanding of webpage styling and layout.
                </dd>


                <dt><strong>JavaScript</strong></dt>

                <dd>
                    Creating basic interactive features for websites.
                </dd>


                <dt><strong>MySQL</strong></dt>

                <dd>
                    Creating, managing, and querying databases.
                </dd>


                <dt><strong>GitHub</strong></dt>

                <dd>
                    Managing and sharing source code using repositories.
                </dd>

            </dl>

        </section>


        <!-- PROJECTS -->

        <section id="projects">

            <h2>PROJECTS</h2>


            <article>

                <h3>CloudNewaBox</h3>

                <p>
                    CloudNewaBox is a software engineering project
                    based on a Newari food Bento Box service. The
                    project allows customers to browse different
                    Newari foods, create their own Bento Box,
                    customize food preferences, select occasions,
                    and place orders.
                </p>

                <p>

                    <a href="https://github.com/RiyaShakya4/CloudNewaBox"
                       target="_blank"
                       rel="noopener noreferrer">

                        View CloudNewaBox Repository

                    </a>

                </p>

            </article>


            <article>

                <h3>Database Management System</h3>

                <p>
                    This project focused on designing and managing
                    relational databases using MySQL. The project
                    included creating tables, primary keys, foreign
                    keys, constraints, relationships, and SQL queries.
                    It helped me understand how databases store and
                    manage information efficiently.
                </p>

                <p>

                    <a href="https://github.com/RiyaShakya4/Database-Management-System.git"
                       target="_blank"
                       rel="noopener noreferrer">

                        View Database Project Repository

                    </a>

                </p>

            </article>
            <article>

                <h3>personal-protfolio</h3>

                <p>
                    My name is Riya Shakya, and I am a student
                            interested in technology, web development,
                            database management, and software engineering.
                            I enjoy learning new technologies and developing
                            simple and useful digital projects. 
                </p>

                <p>

                    <a href="https://github.com/RiyaShakya4/personal-protfolio.git"
                       target="_blank"
                       rel="noopener noreferrer">

                        View personal-protfolio Project Repository

                    </a>

                </p>

            </article>


        </section>


        <!-- EDUCATION -->

        <section id="education">

            <h2>EDUCATION</h2>

            <table border="1">

                <tr>

                    <th>Level</th>
                    <th>Institution</th>
                    <th>Status</th>

                </tr>


                <tr>

                    <td>Bachelor's Degree</td>

                    <td>
                        International American University
                    </td>

                    <td>
                        Currently Studying
                    </td>

                </tr>


                <tr>

                    <td>Higher Secondary Education</td>

                    <td>
                      Uniglobe SS college
                    </td>

                    <td>
                        Completed
                    </td>

                </tr>


                <tr>

                    <td>Secondary Education</td>

                    <td>
                        Saraswati Boarding Higher Secondary School
                    </td>

                    <td>
                        Completed
                    </td>

                </tr>

            </table>

        </section>


        <!-- CONTACT -->

        <section id="contact">

            <h2>CONTACT ME</h2>

            <form action="#" method="post">

                <table border="1">


                    <tr>

                        <td>

                            <label for="name">
                                Name:
                            </label>

                        </td>

                        <td>

                            <input type="text"
                                   id="name"
                                   name="name"
                                   required>

                        </td>

                    </tr>


                    <tr>

                        <td>

                            <label for="email">
                                Email:
                            </label>

                        </td>

                        <td>

                            <input type="email"
                                   id="email"
                                   name="email"
                                   required>

                        </td>

                    </tr>


                    <tr>

                        <td>

                            <label for="message">
                                Message:
                            </label>

                        </td>

                        <td>

                            <textarea id="message"
                                      name="message"
                                      rows="6"
                                      cols="40"
                                      required></textarea>

                        </td>

                    </tr>


                    <tr>

                        <td></td>

                        <td>

                            <button type="submit">
                                Submit
                            </button>

                        </td>

                    </tr>


                </table>

            </form>

        </section>


    </main>


    <!-- FOOTER -->

    <footer>

        <p>
            &copy; 2026 Riya Shakya. All Rights Reserved.
        </p>

        <p>
            Designed and Developed by Riya Shakya
        </p>

    </footer>


</body>

</html>
