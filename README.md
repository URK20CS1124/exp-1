<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aneesh Singu | Resume</title>

    <style>
        .title {
            text-align: center;
        }
        .profile-img {
            height: 150px;
            position: relative;
            right: 450px;
        }
        .about {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
        }
        .nav a img {
            height: 50px;
        }
        .academics td, .academics th{
            border: 2px solid black;
        }
        .internship p{
            margin-left: 50px;
        }
        .coffee-img{
            margin-left: 60px;
        }
        .f-nav{
            border-right: 1px solid black;
            margin: 5px;
        }
    </style>
</head>

<body>
    <h1 class="title">MY RESUME</h1>
    <div class="content">
        <div class="about">
            <h3>Aneesh Singu<br>no.1/4<br> Garikapadu<br>Tadikonda, Andhra<br>Ph:
                9391823032<br>Email:singuaneesh@karunya.edu.in</h3>
            <img src="Sriram.jpg" class="profile-img">
        </div>
        <div class="nav">
            <a href="#">Visit My Website</a>
            <a href="#">My College</a>
            <a href="#">Email Me</a>
            <a href="#">Call Me</a>

            <a href="#"><img src="images/facebook.png" alt=""></a>
            <a href="#"><img src="images/linkedin.png" alt=""></a>
            <a href="#"><img src="images/instagram.png" alt=""></a>
        </div>
        <div class="career">
            <h3>Career Objective</h3>
            <p>A Career Objective or a Resume Objective is essentially a heading statement that describes your
                professional goals in two or three sentences. Employers looking to hire an employee for a position tend
                <br>to seek candidates that are driven enough to understand what they want</p>
        </div>
        <div class="academics">
            <h3>Academic Profile</h3>
            <table>
                <tr>
                    <th></th>
                    <th>School/College</th>
                    <th>Board/University</th>
                    <th>Percentage of Marks</th>
                    <th>Year of Passing</th>
                </tr>

                <tr>
                    <td>B.Tech</td>
                    <td>Karunya</td>
                    <td>Deemed</td>
                    <td>9.2</td>
                    <td>Still studying</td>
                </tr>

                <tr>
                    <td>HSC</td>
                    <td>Velammal</td>
                    <td>State Board</td>
                    <td>94</td>
                    <td>2020</td>
                </tr>

                <tr>
                    <td>SSLC</td>
                    <td>Zion</td>
                    <td>State Board</td>
                    <td>96</td>
                    <td>2018</td>
                </tr>
            </table>
        </div>

        <div class="skills">
            <h3>Technical Skills</h3>
            <ol>
                <li>Data Structures</li>
                <li>Computer Networks</li>
                <li>Web Technology</li>
                <li>Python Programming</li>
                <li>Java Programming</li>
            </ol>

            <h3>Advanced Technology Skills</h3>
            <ul>
                <li>Data Science</li>
                <li>Data Analytics</li>
                <li>Machine Learning Principles</li>
            </ul>
        </div>

        <div class="internship">
            <h3>Internship Completed</h3>
            <h3>Infosys</h3>
            <p>Completed internship in Infosys</p>
            <h3>Microsoft</h3>
            <p>Completed internship in Microsoft</p>
            <h3>CISCO</h3>
            <p>Completed internship in CISCO</p>
            <h3>Oracle</h3>
            <p>Completed internship in Oracle</p>
        </div>

        <div class="gallery">
            <h3>PHOTO GALLERY</h3>
            <div class="images">
                <img src="coffee.jpg" class="coffee-img">
                <img src="laptop.jpg">
            </div>
        </div>

        <div class="footer">
            <a href="#" class="f-nav">Career Objective </a>
            <a href="#" class="f-nav">Technical Skills </a>
            <a href="#" class="f-nav">Education </a>
            <a href="#" class="f-nav">Advanced Technology Skills </a>
            <a href="#">Internships</a>
        </div>
    </div>
</body>

</html>

