<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Mohamed Maged | Portfolio</title>
    <style>
        :root { --primary: #003366; --bg-gray: #f2f4f8; --text-dark: #333; }
        * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: var(--bg-gray); color: var(--text-dark); margin: 0; padding: 20px; padding-bottom: 60px; }
        
        .container { max-width: 950px; margin: auto; background: white; padding: 40px; border-radius: 12px; box-shadow: 0 5px 25px rgba(0,0,0,0.08); }

        /* HEADER */
        .header { border-bottom: 3px solid var(--primary); padding-bottom: 25px; margin-bottom: 35px; }
        .header h1 { color: var(--primary); margin: 0; text-transform: uppercase; font-size: 1.8rem; letter-spacing: 1px; line-height: 1.2; }
        .header h3 { margin: 8px 0; color: #555; font-weight: 500; font-size: 1rem; }
        .contact-info { font-size: 0.9rem; color: #666; margin-top: 12px; }
        .contact-info a { color: var(--primary); text-decoration: none; font-weight: bold; }

        /* SECTIONS */
        h2.sec-title { background: #e8eaf6; padding: 10px 15px; border-left: 5px solid var(--primary); margin-top: 40px; color: var(--primary); text-transform: uppercase; font-size: 1.1rem; font-weight: bold; }
        
        /* JOB LIST STYLES */
        .job-group { margin-bottom: 30px; border-bottom: 1px solid #eee; padding-bottom: 20px; }
        .job-company { color: var(--primary); font-weight: bold; font-size: 1.1rem; margin-bottom: 10px; display: block; }
        
        .job-role { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; margin-top: 12px; }
        .role-title { font-weight: 700; color: #222; font-size: 0.95rem; }
        .role-date { font-size: 0.8rem; color: #555; background: #f0f0f0; padding: 4px 8px; border-radius: 4px; white-space: nowrap; margin-top: 5px; }
        
        .job-details { margin-top: 5px; padding-left: 20px; color: #555; font-size: 0.9rem; line-height: 1.5; }
        .job-details li { margin-bottom: 3px; }

        /* --- INTERACTIVE TABS & BROWSER --- */
        .browser-window { border: 1px solid #cacedb; border-radius: 8px; overflow: hidden; margin-top: 30px; background: white; box-shadow: 0 4px 15px rgba(0,0,0,0.05); }
        .browser-bar { background: #dfe1e5; padding: 10px; display: flex; align-items: center; gap: 10px; }
        .dots { display: flex; gap: 5px; } .dot { width: 10px; height: 10px; border-radius: 50%; background: #ccc; } .dot.red { background: #ff5f56; } .dot.yellow { background: #ffbd2e; } .dot.green { background: #27c93f; }
        .url-bar { background: white; flex-grow: 1; padding: 6px 12px; border-radius: 15px; font-size: 0.8rem; color: #555; display: flex; align-items: center; gap: 5px; }

        /* TABS Layout */
        .gs-container { display: flex; flex-direction: column; }
        .gs-sidebar { display: flex; overflow-x: auto; background: #f8f9fa; padding: 10px; border-bottom: 1px solid #ddd; gap: 10px; -webkit-overflow-scrolling: touch; }
        .gs-nav-item { padding: 8px 15px; border-radius: 20px; font-size: 0.85rem; background: white; border: 1px solid #ddd; color: #444; white-space: nowrap; cursor: pointer; }
        .gs-nav-item.active { background: var(--primary); color: white; border-color: var(--primary); }
        .gs-content { padding: 20px; min-height: 300px; }

        /* VIEWS */
        .tab-view { display: none; animation: fadeIn 0.3s; }
        .tab-view.active-view { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }

        /* ELPROF & MARKET UI Elements */
        .student-header { display: flex; align-items: center; gap: 10px; background: #f9f9f9; padding: 10px; border-radius: 8px; margin-bottom: 15px; }
        .avatar { width: 40px; height: 40px; background: #673ab7; color: white; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold; }
        .card-stat { background: white; border: 1px solid #eee; padding: 10px; border-radius: 8px; margin-bottom: 8px; display: flex; justify-content: space-between; }
        
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); gap: 10px; }
        .product-card { border: 1px solid #eee; padding: 10px; text-align: center; border-radius: 6px; }
        .price { color: #d32f2f; font-weight: bold; }

    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>Mohamed Maged Nawar</h1>
        <h3>Training Operations Supervisor | CMS & LMS Expert</h3>
        <div class="contact-info">
            📍 New Cairo, Egypt | 📞 +201021242537<br>
            🔗 <a href="https://linkedin.com/in/mohamed-maged-nawar-b5016912b">LinkedIn Profile</a>
        </div>
    </div>

    <h2 class="sec-title">Professional Experience</h2>

    <div class="job-group">
        <span class="job-company">Future University in Egypt (FUE)</span>
        
        <div class="job-role">
            <span class="role-title">University Requirements Supervisor</span>
            <span class="role-date">Feb 2025 – Present</span>
        </div>
        <ul class="job-details"><li>Leading training operations and student workflows.</li></ul>

        <div class="job-role">
            <span class="role-title">CMS Administrator</span>
            <span class="role-date">Nov 2024 – Present</span>
        </div>
        <ul class="job-details"><li>Managing website content & HTML standards.</li></ul>

        <div class="job-role">
            <span class="role-title">LMS & Zoom Administrator</span>
            <span class="role-date">Feb 2020 – Present</span>
        </div>

        <div class="job-role" style="border-top: 1px dashed #ddd; padding-top: 10px; margin-top: 10px;">
            <span class="role-title">Administrative Coordinator</span>
            <span class="role-date">Oct 2017 – Jan 2020</span>
        </div>
        <ul class="job-details">
            <li>Managed administrative processes and coordination for university requirements.</li>
            <li><strong>(Start of FUE Journey)</strong></li>
        </ul>
    </div>

    <div class="job-group">
        <span class="job-company">ElProf CS Team</span>
        <div class="job-role">
            <span class="role-title">Moderator & System Developer</span>
            <span class="role-date">Nov 2023 – Present</span>
        </div>
        <ul class="job-details">
            <li>Developed automated Student Portals using Google Apps Script.</li>
        </ul>
    </div>

    <div class="job-group">
        <span class="job-company">Pearson VUE / Certiport / OET</span>
        
        <div class="job-role">
            <span class="role-title">Team Supervisor</span>
            <span class="role-date">Jan 2024 – Present</span>
        </div>

        <div class="job-role" style="border-top: 1px dashed #ddd; padding-top: 10px; margin-top: 10px;">
            <span class="role-title">Exam Proctor & Reg. Specialist</span>
            <span class="role-date">Dec 2017 – Present</span>
        </div>
        <ul class="job-details">
            <li>Started as Exam Proctor in 2017 ensuring high-stakes exam integrity.</li>
            <li>Promoted to oversee international testing standards.</li>
        </ul>
    </div>

    <h2 class="sec-title">Technical Portfolio (Interactive)</h2>
    <p style="color:#666; font-size:0.9rem;">Click tabs to view live dashboards:</p>

    <div class="browser-window">
        <div class="browser-bar">
            <div class="dots"><div class="dot red"></div><div class="dot yellow"></div><div class="dot green"></div></div>
            <div class="url-bar">🔒 sites.google.com/view/portfolio/live-demo</div>
        </div>
        
        <div class="gs-container">
            <div class="gs-sidebar">
                <div class="gs-nav-item active" onclick="switchTab(this, 'elprof')">ElProf Portal</div>
                <div class="gs-nav-item" onclick="switchTab(this, 'market')">Market Analysis</div>
                <div class="gs-nav-item" onclick="switchTab(this, 'lms')">Moodle Admin</div>
            </div>
            
            <div class="gs-content">
                <div id="elprof" class="tab-view active-view">
                    <div class="student-header">
                        <div class="avatar">YZ</div>
                        <div>
                            <strong>Yumo Zhang</strong><br>
                            <small>ID: 20260019</small>
                        </div>
                    </div>
                    <div class="card-stat">
                        <span>Attendance Rate</span>
                        <strong style="color:green">85%</strong>
                    </div>
                    <div class="card-stat">
                        <span>Mid-Term Grade</span>
                        <strong>45 / 50</strong>
                    </div>
                </div>

                <div id="market" class="tab-view">
                    <div style="background:#e3f2fd; padding:10px; border-radius:6px; margin-bottom:15px; font-size:0.9rem;">
                        <strong>Insight:</strong> Flagship prices up by 15%.
                    </div>
                    <div class="product-grid">
                        <div class="product-card">
                            <div style="background:#eee; height:50px; margin-bottom:5px;"></div>
                            <strong>S24 Ultra</strong><br><span class="price">48,500</span>
                        </div>
                        <div class="product-card">
                            <div style="background:#eee; height:50px; margin-bottom:5px;"></div>
                            <strong>iPhone 15</strong><br><span class="price">56,200</span>
                        </div>
                        <div class="product-card">
                            <div style="background:#eee; height:50px; margin-bottom:5px;"></div>
                            <strong>Reno 11</strong><br><span class="price">18,500</span>
                        </div>
                    </div>
                </div>

                <div id="lms" class="tab-view">
                    <div style="background:#333; color:white; padding:10px; margin-bottom:10px; border-radius:4px; display:flex; justify-content:space-between;">
                        <span>Course Manager</span> <small>Admin Mode</small>
                    </div>
                    <div style="border:1px solid #ddd; padding:10px; border-left:4px solid #003366; background:white;">
                        <strong>Critical Thinking (REQ 101)</strong><br>
                        <small>Students: 450 | Inst: Dr. Ahmed</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

</div>

<script>
    function switchTab(btn, viewId) {
        // Remove active from all tabs
        let tabs = document.querySelectorAll('.gs-nav-item');
        tabs.forEach(t => t.classList.remove('active'));
        btn.classList.add('active');

        // Hide all views
        let views = document.querySelectorAll('.tab-view');
        views.forEach(v => v.classList.remove('active-view'));

        // Show selected view
        document.getElementById(viewId).classList.add('active-view');
    }
</script>

</body>
</html>
# Profile