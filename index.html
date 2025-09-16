<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MVCC Organizational Chart</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            padding: 30px;
            position: relative;
        }

        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 40px;
            font-size: 2.5em;
            font-weight: 300;
        }

        .org-chart {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 40px;
        }

        .level {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 30px;
            flex-wrap: wrap;
            position: relative;
        }

        .org-box {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 15px 20px;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            min-width: 180px;
            font-weight: 500;
            position: relative;
        }

        .org-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .org-box.president {
            background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
            font-size: 1.1em;
            min-width: 200px;
        }

        .org-box.vp {
            background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
            color: #333;
        }

        .org-box.avp {
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
            color: #333;
        }

        .org-box.dean {
            background: linear-gradient(135deg, #e0c3fc 0%, #9bb5ff 100%);
        }

        .org-box.staff {
            background: linear-gradient(135deg, #c2e9fb 0%, #a1c4fd 100%);
            color: #333;
            font-size: 0.9em;
        }

        .connector {
            position: absolute;
            background: #ddd;
            z-index: -1;
        }

        .vertical-connector {
            width: 2px;
            height: 30px;
            left: 50%;
            transform: translateX(-50%);
            top: -40px;
        }

        .horizontal-connector {
            height: 2px;
            top: 50%;
            transform: translateY(-50%);
        }

        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background-color: #fefefe;
            margin: 5% auto;
            padding: 30px;
            border-radius: 15px;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            animation: modalAppear 0.3s ease;
            max-height: 80vh;
            overflow-y: auto;
        }

        @keyframes modalAppear {
            from {
                opacity: 0;
                transform: scale(0.8);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close:hover {
            color: #333;
        }

        .modal h3 {
            color: #333;
            margin-bottom: 20px;
            font-size: 1.5em;
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
        }

        .modal p {
            line-height: 1.6;
            color: #666;
            margin-bottom: 15px;
        }

        .modal ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }

        .modal li {
            margin-bottom: 5px;
            color: #666;
        }

        .school-programs {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
        }

        .school-programs h4 {
            color: #333;
            margin-bottom: 10px;
        }

        /* References Section */
        .references-section {
            margin-top: 60px;
            padding-top: 40px;
            border-top: 2px solid #eee;
        }

        .references-section h2 {
            color: #333;
            font-size: 1.8em;
            margin-bottom: 25px;
            text-align: center;
            font-weight: 300;
        }

        .references-content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
        }

        .references-content p {
            margin-bottom: 15px;
            color: #555;
            text-align: left;
            padding-left: 30px;
            text-indent: -30px;
        }

        .references-content a {
            color: #4facfe;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .references-content a:hover {
            color: #667eea;
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .org-box {
                min-width: 150px;
                font-size: 0.9em;
            }
            
            .level {
                gap: 15px;
            }
            
            .modal-content {
                width: 95%;
                margin: 10% auto;
                padding: 20px;
            }
            
            .references-content p {
                padding-left: 20px;
                text-indent: -20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Mohawk Valley Community College<br>Organizational Chart: Academic Affairs Focus</h1>
        
        <div class="org-chart">
            <!-- Board of Trustees -->
            <div class="level">
                <div class="org-box" data-info="board">Board of Trustees</div>
            </div>
            
            <!-- President -->
            <div class="level">
                <div class="org-box president" data-info="president">President</div>
            </div>
            
            <!-- Vice Presidents -->
            <div class="level">
                <div class="org-box vp" data-info="vp-student">VP of Student Affairs</div>
                <div class="org-box vp" data-info="vp-academic">VP of Learning & Academic Affairs</div>
                <div class="org-box vp" data-info="vp-admin">VP of Administrative Services</div>
            </div>
            
            <!-- Assistant Vice Presidents -->
            <div class="level">
                <div class="org-box avp" data-info="avp1">AVP 1</div>
                <div class="org-box avp" data-info="avp2">AVP 2</div>
                <div class="org-box avp" data-info="avp3">AVP 3</div>
            </div>
            
            <!-- Academic Deans -->
            <div class="level">
                <div class="org-box dean" data-info="dean-general">Academic Deans</div>
                <div class="org-box dean" data-info="dean-art">Dean - School of Art</div>
                <div class="org-box dean" data-info="dean-humanities">Dean - School of Humanities</div>
                <div class="org-box dean" data-info="dean-business">Dean - School of Hospitality & Business</div>
            </div>
            
            <!-- School of Humanities Staff -->
            <div class="level">
                <div class="org-box staff" data-info="college-services">College Services Associate</div>
                <div class="org-box staff" data-info="fulltime-faculty">Full-time Faculty</div>
                <div class="org-box staff" data-info="adjunct-faculty">Adjunct Faculty</div>
            </div>
        </div>
        
        <!-- References Section -->
        <div class="references-section">
            <h2>References</h2>
            <div class="references-content">
                <p>Mohawk Valley Community College. (2001). Job description-Vice President for Administrative Services. Retrieved February 8, 2025, from <a href="https://www2.mvcc.edu/jobs/Vice%20President%20for%20Administrative%20Svcs%20.pdf" target="_blank">https://www2.mvcc.edu/jobs/Vice%20President%20for%20Administrative%20Svcs%20.pdf</a></p>
                
                <p>Mohawk Valley Community College. (2007). Position Guide-President. Retrieved February 8, 2025, from <a href="https://www2.mvcc.edu/jobs/President%205-25-07.pdf" target="_blank">https://www2.mvcc.edu/jobs/President%205-25-07.pdf</a></p>
                
                <p>Mohawk Valley Community College. (2008). Job description-Vice President for Learning & Academic Affairs. Retrieved February 8, 2025, from <a href="https://www2.mvcc.edu/jobs/Vice%20President%20for%20Learning%20&%20Acad%20Affairs.pdf" target="_blank">https://www2.mvcc.edu/jobs/Vice%20President%20for%20Learning%20&%20Acad%20Affairs.pdf</a></p>
                
                <p>Mohawk Valley Community College. (2024). Job description-Vice President for Student Affairs. Retrieved February 8, 2025, from <a href="https://www2.mvcc.edu/jobs/Vice%20President%20for%20Student%20Affairs.20240516.pdf" target="_blank">https://www2.mvcc.edu/jobs/Vice%20President%20for%20Student%20Affairs.20240516.pdf</a></p>
                
                <p>Mohawk Valley Community College. (2025). <em>Board of Trustees</em>. Retrieved February 8, 2025, from <a href="https://www.mvcc.edu/governance/board-of-trustees/" target="_blank">https://www.mvcc.edu/governance/board-of-trustees/</a></p>
            </div>
        </div>
    </div>

    <!-- Modal -->
    <div id="infoModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <div id="modalBody"></div>
        </div>
    </div>

    <script>
        const modal = document.getElementById('infoModal');
        const modalBody = document.getElementById('modalBody');
        const closeBtn = document.querySelector('.close');
        
        const orgData = {
            'board': {
                title: 'Board of Trustees',
                content: `
                    <p>The College is led at its highest level by the Board of Trustees. The Oneida County Executive appoints five Trustees, four are appointed by the Governor, and the student Trustee is elected annually as part of student government elections for a one-year term. All other appointments are for seven-year terms.</p>
                    
                    <p><strong>Responsibilities:</strong></p>
                    <ul>
                        <li>Sets all college policies</li>
                        <li>Negotiates contracts with bargaining units</li>
                        <li>Approves the finances of the college (budget and expenditures)</li>
                        <li>Approves appointments at most levels</li>
                        <li>Advocates to governmental agencies for the college</li>
                    </ul>
                `
            },
            'president': {
                title: 'President',
                content: `
                    <p>The president of MVCC reports to the Board of Trustees and serves as the Chief Executive and Administrative Officer of the college.</p>
                    
                    <p><strong>Key Functions:</strong></p>
                    <ul>
                        <li>Makes recommendations to the Board of Trustees regarding all facets of academic programs and staffing</li>
                        <li>Executive decision-making authority as established by the Board of Trustees</li>
                        <li>Overall leadership and strategic direction of the institution</li>
                    </ul>
                `
            },
            'vp-student': {
                title: 'Vice President of Student Affairs',
                content: `
                    <p>Oversees comprehensive student services and support systems throughout the college.</p>
                    
                    <p><strong>Areas of Responsibility:</strong></p>
                    <ul>
                        <li>Admission and enrollment processes</li>
                        <li>Holistic student support services</li>
                        <li>Student engagement and development programs</li>
                        <li>Residence life (MVCC Dormitory Corporation)</li>
                        <li>Serves as Title IX and Title VI officer for the college</li>
                    </ul>
                `
            },
            'vp-academic': {
                title: 'Vice President of Learning & Academic Affairs',
                content: `
                    <p>Responsible for developing goals and objectives, planning, organizing, and maintaining financial and staffing controls to ensure the realization of objectives.</p>
                    
                    <p><strong>Primary Functions:</strong></p>
                    <ul>
                        <li>Administering and evaluating both credit and non-credit instructional programs</li>
                        <li>Academic program development and oversight</li>
                        <li>Faculty hiring and evaluation processes</li>
                        <li>Curriculum development and approval</li>
                        <li>Student academic success initiatives</li>
                    </ul>
                `
            },
            'vp-admin': {
                title: 'Vice President of Administrative Services',
                content: `
                    <p>Serves as the Chief Fiscal Officer and Treasurer of MVCC, responsible for the acquisition and maintenance of the College physical plant, equipment, and all assets according to Board policy with approved budget guidelines.</p>
                    
                    <p><strong>Direct Reports Include:</strong></p>
                    <ul>
                        <li>Controller</li>
                        <li>Director of Facilities and Operations</li>
                        <li>Registrar</li>
                        <li>Director of Financial Aid</li>
                        <li>Chief of Campus Security</li>
                    </ul>
                `
            },
            'avp1': {
                title: 'Assistant Vice President 1',
                content: `
                    <p>Reports to the VP of Learning & Academic Affairs and oversees multiple schools and programs.</p>
                    
                    <p><strong>Areas of Oversight:</strong></p>
                    <ul>
                        <li>School of Public and Human Services</li>
                        <li>School of STEM-Career</li>
                        <li>Dual Credit programs</li>
                        <li>Center for Accelerated Pathways</li>
                    </ul>
                `
            },
            'avp2': {
                title: 'Assistant Vice President 2',
                content: `
                    <p>Reports to the VP of Learning & Academic Affairs and supervises various schools and support offices.</p>
                    
                    <p><strong>Areas of Oversight:</strong></p>
                    <ul>
                        <li>School of Art</li>
                        <li>School of Hospitality and Business</li>
                        <li>School of Humanities</li>
                        <li>Office of Assessment</li>
                        <li>Registrar's Office</li>
                        <li>Office of Online Learning</li>
                        <li>College in Prison Program</li>
                    </ul>
                `
            },
            'avp3': {
                title: 'Assistant Vice President 3',
                content: `
                    <p>Reports to the VP of Learning & Academic Affairs and manages STEM-focused programs and partnerships.</p>
                    
                    <p><strong>Areas of Oversight:</strong></p>
                    <ul>
                        <li>School of STEM-Transfer</li>
                        <li>School of Health Sciences</li>
                        <li>Governmental STEM grants</li>
                        <li>STEM programs in conjunction with Griffis Air Force Base</li>
                    </ul>
                `
            },
            'dean-general': {
                title: 'Academic Deans',
                content: `
                    <p>Each Academic Dean administrates the degree and certificate programs, and course offerings within their respective School.</p>
                    
                    <p><strong>Key Responsibilities:</strong></p>
                    <ul>
                        <li>Evaluate faculty performance</li>
                        <li>Maintain course schedules and staffing</li>
                        <li>Assign teaching loads according to CBA guidelines</li>
                        <li>Work with students to ensure satisfactory academic progress</li>
                        <li>Maintain academic rigor and integrity</li>
                        <li>Review transfer courses and certify graduation</li>
                    </ul>
                `
            },
            'dean-art': {
                title: 'Dean - School of Art',
                content: `
                    <p>Administers creative and digital arts programs designed to prepare students for careers in various artistic fields.</p>
                    
                    <div class="school-programs">
                        <h4>Programs Offered:</h4>
                        <ul>
                            <li>Digital Media & Marketing AS</li>
                            <li>Fashion Design AAS</li>
                            <li>Fine Arts AS</li>
                            <li>Game Art AAS</li>
                            <li>Graphic Design AAS</li>
                            <li>Illustration AAS</li>
                            <li>Photography AAS</li>
                            <li>Video Production AS</li>
                        </ul>
                    </div>
                `
            },
            'dean-humanities': {
                title: 'Dean - School of Humanities',
                content: `
                    <p>Oversees liberal arts and general education programs that provide foundational knowledge and critical thinking skills.</p>
                    
                    <div class="school-programs">
                        <h4>Programs Offered:</h4>
                        <ul>
                            <li>ESOL Certificate</li>
                            <li>General Studies AS</li>
                            <li>Individual Studies AA, AS, AAS, AOS</li>
                            <li>Humanities & Social Sciences AS</li>
                            <li>International Studies AS</li>
                            <li>Honors Program</li>
                        </ul>
                    </div>
                `
            },
            'dean-business': {
                title: 'Dean - School of Hospitality & Business',
                content: `
                    <p>Manages business, culinary, and hospitality programs that prepare students for careers in various business sectors.</p>
                    
                    <div class="school-programs">
                        <h4>Programs Offered:</h4>
                        <ul>
                            <li>Administrative Assistant Certificate and AAS</li>
                            <li>Business Accounting AAS</li>
                            <li>Business Administration AS and AAS</li>
                            <li>Business Analytics AS</li>
                            <li>Culinary Arts Management AOS</li>
                            <li>Food Service Administration AAS</li>
                            <li>Sports Management AS</li>
                            <li>Chef Training Certificate</li>
                            <li>Entrepreneurship Certificate</li>
                            <li>Finance Certificate</li>
                            <li>Data Analytics Certificate</li>
                        </ul>
                    </div>
                `
            },
            'college-services': {
                title: 'College Services Associate',
                content: `
                    <p>Assists the Dean of the School of Humanities in the administration of programs and courses.</p>
                    
                    <p><strong>Primary Functions:</strong></p>
                    <ul>
                        <li>Works with faculty to document course syllabi</li>
                        <li>Handles student concerns and issues</li>
                        <li>Provides administrative support for school operations</li>
                        <li>Facilitates communication between students, faculty, and administration</li>
                    </ul>
                `
            },
            'fulltime-faculty': {
                title: 'Full-time Faculty',
                content: `
                    <p>Core teaching staff who provide instruction and student support across all MVCC campuses and satellite locations.</p>
                    
                    <p><strong>Key Responsibilities:</strong></p>
                    <ul>
                        <li>Teach classes at any campus or satellite location</li>
                        <li>Full-time course load: 15 contact hours per semester</li>
                        <li>Maintain 1 office hour per section taught each week</li>
                        <li>Advise approximately 30 students majoring in School of Humanities programs</li>
                        <li>Participate in curriculum development and assessment</li>
                        <li>Engage in professional development activities</li>
                    </ul>
                `
            },
            'adjunct-faculty': {
                title: 'Adjunct Faculty',
                content: `
                    <p>Part-time instructional staff who supplement full-time faculty and provide specialized expertise across various programs.</p>
                    
                    <p><strong>Teaching Parameters:</strong></p>
                    <ul>
                        <li>Teach classes at any campus or satellite location</li>
                        <li>Maximum of 9 contact hours per term</li>
                        <li>Hold 1 office hour per section taught each week</li>
                        <li>Provide flexible scheduling options for students</li>
                        <li>Bring real-world experience to the classroom</li>
                    </ul>
                `
            }
        };

        // Add click event listeners to all org boxes
        document.querySelectorAll('.org-box').forEach(box => {
            box.addEventListener('click', function() {
                const infoKey = this.getAttribute('data-info');
                const data = orgData[infoKey];
                
                if (data) {
                    modalBody.innerHTML = `<h3>${data.title}</h3>${data.content}`;
                    modal.style.display = 'block';
                }
            });
        });

        // Close modal when clicking the close button
        closeBtn.addEventListener('click', function() {
            modal.style.display = 'none';
        });

        // Close modal when clicking outside of it
        window.addEventListener('click', function(event) {
            if (event.target === modal) {
                modal.style.display = 'none';
            }
        });

        // Close modal with Escape key
        document.addEventListener('keydown', function(event) {
            if (event.key === 'Escape' && modal.style.display === 'block') {
                modal.style.display = 'none';
            }
        });
    </script>
</body>
</html>
