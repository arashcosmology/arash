<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arash Mirhosseini - Radio Astronomer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }
        
        header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: 300;
        }
        
        .subtitle {
            font-size: 1.2em;
            margin-bottom: 25px;
            opacity: 0.9;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 5px;
        }
        
        .contact-item a {
            color: white;
            text-decoration: none;
        }
        
        .contact-item a:hover {
            text-decoration: underline;
        }
        
        nav {
            background-color: #2a5298;
            padding: 15px 40px;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: opacity 0.3s;
        }
        
        nav a:hover {
            opacity: 0.7;
        }
        
        .content {
            padding: 40px;
        }
        
        section {
            margin-bottom: 50px;
        }
        
        h2 {
            color: #1e3c72;
            border-bottom: 3px solid #2a5298;
            padding-bottom: 10px;
            margin-bottom: 25px;
            font-size: 1.8em;
        }
        
        h3 {
            color: #2a5298;
            margin-top: 25px;
            margin-bottom: 15px;
            font-size: 1.3em;
        }
        
        .about-text {
            font-size: 1.05em;
            line-height: 1.8;
            color: #555;
            margin-bottom: 20px;
        }
        
        .education-item, .experience-item, .award-item {
            margin-bottom: 30px;
            padding-left: 20px;
            border-left: 3px solid #2a5298;
        }
        
        .item-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 8px;
            flex-wrap: wrap;
        }
        
        .item-title {
            font-weight: 600;
            color: #1e3c72;
            font-size: 1.1em;
        }
        
        .item-date {
            color: #666;
            font-style: italic;
            font-size: 0.95em;
        }
        
        .item-institution {
            color: #2a5298;
            margin-bottom: 5px;
        }
        
        .item-detail {
            color: #666;
            font-style: italic;
            margin-bottom: 8px;
        }
        
        .item-description {
            color: #555;
            margin-top: 10px;
        }
        
        ul.bullet-list {
            margin-left: 20px;
            margin-top: 10px;
        }
        
        ul.bullet-list li {
            margin-bottom: 8px;
            color: #555;
        }
        
        .publication-item {
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        
        .publication-authors {
            color: #555;
            font-size: 0.95em;
            margin-bottom: 5px;
        }
        
        .publication-title {
            font-weight: 600;
            color: #1e3c72;
            margin-bottom: 5px;
        }
        
        .publication-journal {
            color: #666;
            font-style: italic;
            font-size: 0.95em;
        }
        
        .publication-note {
            color: #2a5298;
            font-size: 0.9em;
            margin-top: 8px;
            padding-left: 15px;
            border-left: 2px solid #2a5298;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .skill-category {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
        }
        
        .skill-category h4 {
            color: #1e3c72;
            margin-bottom: 12px;
        }
        
        .skill-category ul {
            list-style: none;
        }
        
        .skill-category li {
            padding: 5px 0;
            color: #555;
        }
        
        .skill-category li:before {
            content: "▸ ";
            color: #2a5298;
            font-weight: bold;
        }
        
        footer {
            background-color: #1e3c72;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        .citation-count {
            display: inline-block;
            background-color: #2a5298;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-left: 10px;
        }
        
        @media (max-width: 768px) {
            header {
                padding: 40px 20px;
            }
            
            header h1 {
                font-size: 2em;
            }
            
            .content {
                padding: 20px;
            }
            
            nav {
                padding: 15px 20px;
            }
            
            nav ul {
                gap: 15px;
            }
            
            .item-header {
                flex-direction: column;
                align-items: flex-start;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Arash Mirhosseini</h1>
            <div class="subtitle">Radio Astronomer | PhD Candidate in Physics</div>
            <div class="contact-info">
                <div class="contact-item">
                    📧 <a href="mailto:arashmirhosseini@phas.ubc.ca">arashmirhosseini@phas.ubc.ca</a>
                </div>

                <div class="contact-item">
                    💻 <a href="https://github.com/arashcosmology" target="_blank">GitHub</a>
                </div>
                <div class="contact-item">
                    🎓 <a href="https://scholar.google.ca/citations?user=nef-kJMAAAAJ&hl=en" target="_blank">Google Scholar</a>
                </div>
                <div class="contact-item">
                    📍 Vancouver, BC, Canada
                </div>
            </div>
        </header>
        
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#awards">Awards</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        
        <div class="content">
            <section id="about">
                <h2>About Me</h2>
                <p class="about-text">
                    I am a PhD candidate in Physics at the University of British Columbia, working within the CHIME collaboration, specializing in radio interferometry, HI 21-cm absorption studies, and Radio Frequency Interference (RFI) mitigation.
                </p>
            </section>
            
            <section id="research">
                <h2>Research Experience</h2>
                
                <div class="experience-item">
                    <div class="item-header">
                        <div class="item-title">Search for HI 21-cm absorption systems with CHIME</div>
                        <div class="item-date">Sept. 2020 – Apr. 2026</div>
                    </div>
                    <div class="item-institution">University of British Columbia</div>
                    <div class="item-detail">Supervisor: Prof. Mark Halpern</div>
                    <ul class="bullet-list">
                        <li>Led the CHIME HI Absorber project as principal graduate researcher</li>
                        <li>Implemented compression scheme to manage the multi-petabyte data rate of CHIME Absorber data</li>
                        <li>Designed, developed, and implemented a comprehensive end-to-end pipeline for blind detection of HI 21-cm absorbers, establishing methodology directly applicable to SKA surveys</li>
                        <li>Discovered new HI 21-cm absorber at high redshift (z=2.327), demonstrating pathfinder capabilities for future SKA discoveries; paper submitted to ApJ (2025)</li>
                        <li>Collaborated with Dr. Richard Shaw (UBC) and Prof. Simon Foreman (Arizona State University)</li>
                        <li>Developed open-source tools and algorithms for the broader radio astronomy community</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="item-header">
                        <div class="item-title">High cadence kurtosis-based RFI excision for CHIME</div>
                        <div class="item-date">Jan. 2019 – Sept. 2020</div>
                    </div>
                    <div class="item-institution">University of British Columbia</div>
                    <div class="item-detail">Supervisor: Prof. Mark Halpern</div>
                    <ul class="bullet-list">
                        <li>Developed and implemented real-time RFI excision system deployed on CHIME telescope</li>
                        <li>Created adaptive algorithms that improved data quality for intensity mapping and transient detection</li>
                        <li>Published methodology and shared codebase with CHIME collaboration members</li>
                        <li>Main collaborators: Dr. Richard Shaw, Dr. Seth Siegel (McGill University)</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="item-header">
                        <div class="item-title">Search for massive black holes via microlensing</div>
                        <div class="item-date">Jan. 2017 – Jan. 2018</div>
                    </div>
                    <div class="item-institution">Linear Accelerator Laboratory, CNRS</div>
                    <div class="item-detail">Supervisor: Dr. Marc Moniez</div>
                    <ul class="bullet-list">
                        <li>Tested combining microlensing surveys to find long-duration microlensing events of massive objects</li>
                        <li>Published results in Mirhosseini & Moniez (2018), Astronomy & Astrophysics</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="item-header">
                        <div class="item-title">Broadband spectral energy distribution of unusual quasars</div>
                        <div class="item-date">Sept. 2015 – Jul. 2016</div>
                    </div>
                    <div class="item-institution">Leipzig University</div>
                    <div class="item-detail">Supervisor: Prof. Helmut Meusinger</div>
                    <ul class="bullet-list">
                        <li>Analyzed spectral characteristics of 3000 Å break quasars using multi-wavelength data</li>
                        <li>Published results in Meusinger et al. (2016), Astronomy & Astrophysics</li>
                    </ul>
                </div>
            </section>
            
            <section id="publications">
                <h2>Publications <span class="citation-count">&gt;1900 citations</span></h2>
            
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME collaboration et al.</div>
                    <div class="publication-title">Discovery of an HI 21 cm absorption system at z=2.327 with CHIME</div>
                    <div class="publication-journal">The Astrophysical Journal, Submitted (2025), arXiv:2506.11269</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME collaboration et al.</div>
                    <div class="publication-title">A Detection of Cosmological 21 cm Emission from CHIME in Cross-correlation with eBOSS Measurements of the Lyman-alpha Forest</div>
                    <div class="publication-journal">The Astrophysical Journal, 963, 23 (2024)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME collaboration et al.</div>
                    <div class="publication-title">Detection of Cosmological 21 cm Emission with the Canadian Hydrogen Intensity Mapping Experiment</div>
                    <div class="publication-journal">The Astrophysical Journal, 947, 16 (2023)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME collaboration et al.</div>
                    <div class="publication-title">An Overview of CHIME, the Canadian Hydrogen Intensity Mapping Experiment</div>
                    <div class="publication-journal">The Astrophysical Journal Supplement Series, 261, 29 (2022)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME/FRB collaboration et al.</div>
                    <div class="publication-title">The First CHIME/FRB Fast Radio Burst Catalog</div>
                    <div class="publication-journal">The Astrophysical Journal Supplement Series, 257, 59 (2021)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME/FRB collaboration et al.</div>
                    <div class="publication-title">A bright millisecond-duration radio burst from a Galactic magnetar</div>
                    <div class="publication-journal">Nature, 587, 54-58 (2020)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">CHIME/FRB collaboration et al.</div>
                    <div class="publication-title">Periodic activity from a fast radio burst source</div>
                    <div class="publication-journal">Nature, 582, 351-355 (2020)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">A. Mirhosseini & M. Moniez</div>
                    <div class="publication-title">The MEMO project: Combining all microlensing surveys to search for intermediate-mass Galactic black holes</div>
                    <div class="publication-journal">Astronomy & Astrophysics, 618, L4 (2018)</div>
                </div>
                
                <div class="publication-item">
                    <div class="publication-authors">H. Meusinger, P. Schalldach, A. Mirhosseini, & F. Pertermann</div>
                    <div class="publication-title">Broad-band spectral energy distribution of 3000Å break quasars from the Sloan Digital Sky Survey</div>
                    <div class="publication-journal">Astronomy & Astrophysics, 587, A83 (2016)</div>
                </div>
            </section>
            
            <section id="education">
                <h2>Education</h2>
                
                <div class="education-item">
                    <div class="item-header">
                        <div class="item-title">Ph.D. in Physics</div>
                        <div class="item-date">June 2026 (Expected)</div>
                    </div>
                    <div class="item-institution">University of British Columbia, Vancouver, Canada</div>
                    <div class="item-detail">Dissertation: Blind survey for HI 21-cm absorption systems with CHIME</div>
                    <div class="item-detail">Supervisor: Prof. Mark Halpern</div>
                </div>
                
                <div class="education-item">
                    <div class="item-header">
                        <div class="item-title">MSc in Astronomy</div>
                        <div class="item-date">Sept. 2020</div>
                    </div>
                    <div class="item-institution">University of British Columbia, Vancouver, Canada</div>
                    <div class="item-detail">Thesis: High-Cadence RFI excision with CHIME</div>
                    <div class="item-detail">Supervisor: Prof. Mark Halpern</div>
                </div>
                
                <div class="education-item">
                    <div class="item-header">
                        <div class="item-title">MSc in Physics</div>
                        <div class="item-date">Sept. 2018</div>
                    </div>
                    <div class="item-institution">Paris-Saclay University, Paris, France</div>
                    <div class="item-detail">Thesis: Search for intermediate-mass Galactic black holes with microlensing</div>
                    <div class="item-detail">Supervisor: Dr. Marc Moniez</div>
                </div>
                
                <div class="education-item">
                    <div class="item-header">
                        <div class="item-title">BSc in Physics</div>
                        <div class="item-date">Aug. 2016</div>
                    </div>
                    <div class="item-institution">Leipzig University, Leipzig, Germany</div>
                    <div class="item-detail">Thesis: Broadband spectral energy distribution of unusual quasars</div>
                    <div class="item-detail">Supervisor: Prof. Helmut Meusinger</div>
                </div>
            </section>
            
            <section id="awards">
                <h2>Major Awards & Scholarships</h2>
                
                <div class="award-item">
                    <div class="item-header">
                        <div class="item-title">Buchalter Cosmology First Prize (as part of CHIME collaboration)</div>
                        <div class="item-date">2024</div>
                    </div>
                    <div class="item-description">Awarded for groundbreaking cosmology work in Detection of Cosmological 21 cm Emission paper</div>
                </div>
                
                <div class="award-item">
                    <div class="item-header">
                        <div class="item-title">NSERC Brockhouse Prize (as part of CHIME collaboration)</div>
                        <div class="item-date">2022</div>
                    </div>
                    <div class="item-description">Recognizes outstanding collaborative achievements in natural sciences and engineering</div>
                </div>
                
                <div class="award-item">
                    <div class="item-header">
                        <div class="item-title">Governor General's Innovation Award (as part of CHIME collaboration)</div>
                        <div class="item-date">2020</div>
                    </div>
                    <div class="item-description">Honors contributions to Canada's success and inspiration for future generations</div>
                </div>
                
                <div class="award-item">
                    <div class="item-header">
                        <div class="item-title">Excellence Initiative (IDEX) Paris-Saclay Scholarship</div>
                        <div class="item-date">2016–2018</div>
                    </div>
                    <div class="item-description">Full merit-based scholarship for students with proven high academic level and aspiring research careers</div>
                </div>
            </section>
            
            <section id="skills">
                <h2>Technical Skills</h2>
                
                <div class="skills-grid">
                    <div class="skill-category">
                        <h4>Core Computing</h4>
                        <ul>
                            <li>Python (8+ years, NumPy, SciPy, Astropy, Matplotlib)</li>
                            <li>High Performance Computing (Compute Canada/Digital Research Alliance clusters)</li>
                            <li>Linux/Unix & Shell Scripting</li>
                            <li>Version Control (Git/GitHub)</li>
                        </ul>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Signal Processing</h4>
                        <ul>
                            <li>Large-scale interferometric data processing</li>
                            <li>Advanced statistical methods for signal detection</li>
                            <li>RFI identification and mitigation</li>
                            <li>Scalable data pipeline development</li>
                        </ul>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Languages</h4>
                        <ul>
                            <li>English (Fluent)</li>
                            <li>Persian (Native)</li>
                        </ul>
                    </div>
                </div>
            </section>
            
            <section id="contact">
                <h2>Contact</h2>
                
                <p class="about-text">
                    I'm always interested in discussing potential collaborations, postdoctoral opportunities, and research in radio astronomy. Feel free to reach out via email or connect with me on GitHub.
                </p>
                <p class="about-text">
                    <strong>Email:</strong> <a href="mailto:arashmirhosseini@phas.ubc.ca">arashmirhosseini@phas.ubc.ca</a><br>
                    <strong>GitHub:</strong> <a href="https://github.com/arashcosmology" target="_blank">github.com/arashmirhosseini</a>
                </p>
            </section>
        </div>
        
        <footer>
            <p>&copy; 2025 Arash Mirhosseini. All rights reserved.</p>
            <p style="margin-top: 10px; font-size: 0.9em; opacity: 0.8;">Last updated: November 2025</p>
        </footer>
    </div>
</body>
</html>
