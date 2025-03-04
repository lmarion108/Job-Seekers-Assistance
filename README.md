<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Seekers Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
            width: 100%;
        }
        nav {
            background-color: #333;
            padding: 15px;
            width: 250px;
            height: 100vh;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        nav a {
            color: white;
            padding: 10px;
            text-decoration: none;
            font-size: 16px;
            margin: 5px 0;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            display: flex;
            flex: 1;
        }
        .content {
            margin-left: 250px;
            padding: 20px;
            width: 100%;
        }
        h2 {
            color: #4CAF50;
        }
        .resource-list {
            margin: 20px 0;
        }
        .resource-list ul {
            list-style-type: none;
            padding-left: 0;
        }
        .resource-list li {
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Job Seekers Dashboard</h1>
    <p>Your guide to navigating job loss and finding new opportunities</p>
</header>

<div class="container">
    <nav>
        <div>
            <a href="#job-search">Job Search</a>
            <a href="#upskilling">Upskilling & Learning</a>
            <a href="#mental-health">Mental Health Support</a>
            <a href="#resources">Resources & Links</a>
        </div>
        <div>
            <a href="#financial">Financial Resources</a>
            <a href="#job-fairs">Job Fairs & Networking</a>
        </div>
    </nav>

    <div class="content">
        <section id="job-search">
            <h2>Job Search Resources</h2>
            <div class="resource-list">
                <h3>Popular Job Search Websites</h3>
                <ul>
                    <li><a href="https://www.indeed.com" target="_blank">Indeed</a></li>
                    <li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>
                    <li><a href="https://www.glassdoor.com" target="_blank">Glassdoor</a></li>
                    <li><a href="https://www.ziprecruiter.com" target="_blank">ZipRecruiter</a></li>
                </ul>
            </div>
        </section>

        <section id="upskilling">
            <h2>Upskilling & Learning Resources</h2>
            <div class="resource-list">
                <h3>Learn New Skills</h3>
                <ul>
                    <li><a href="https://www.coursera.org" target="_blank">Coursera</a></li>
                    <li><a href="https://www.udemy.com" target="_blank">Udemy</a></li>
                    <li><a href="https://www.skillshare.com" target="_blank">Skillshare</a></li>
                    <li><a href="https://www.edx.org" target="_blank">edX</a></li>
                </ul>
            </div>
        </section>

        <section id="mental-health">
            <h2>Mental Health Support</h2>
            <div class="resource-list">
                <h3>Emotional Support & Counseling</h3>
                <ul>
                    <li><a href="https://www.7cups.com" target="_blank">7 Cups</a></li>
                    <li><a href="https://www.therapyroute.com" target="_blank">TherapyRoute</a></li>
                    <li><a href="https://www.betterhelp.com" target="_blank">BetterHelp</a></li>
                </ul>
            </div>
        </section>

        <section id="resources">
            <h2>Additional Resources</h2>
            <div class="resource-list">
                <h3>Government & Support Programs</h3>
                <ul>
                    <li><a href="https://www.careeronestop.org/" target="_blank">CareerOneStop</a></li>
                    <li><a href="https://www.usa.gov/unemployment" target="_blank">Unemployment Benefits</a></li>
                </ul>
            </div>
        </section>

        <section id="financial">
            <h2>Financial Resources</h2>
            <div class="resource-list">
                <h3>Financial Assistance & Advice</h3>
                <ul>
                    <li><a href="https://www.nfcc.org" target="_blank">National Foundation for Credit Counseling</a></li>
                    <li><a href="https://www.consumerfinance.gov" target="_blank">Consumer Financial Protection Bureau</a></li>
                </ul>
            </div>
        </section>

        <section id="job-fairs">
            <h2>Job Fairs & Networking</h2>
            <div class="resource-list">
                <h3>Find Job Fairs Near You</h3>
                <ul>
                    <li><a href="https://www.eventbrite.com" target="_blank">Eventbrite - Job Fairs</a></li>
                    <li><a href="https://www.meetup.com" target="_blank">Meetup - Networking Events</a></li>
                </ul>
            </div>
        </section>
    </div>
</div>

<footer>
    <p>Job Seekers Dashboard | All Rights Reserved | Contact Us: support@jobseekers.com</p>
</footer>

</body>
</html>
