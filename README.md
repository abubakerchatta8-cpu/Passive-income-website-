# Passive-income-website-
Free study materials website for passive income. <!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StudyMaterial - Free Notes & Earn Passive Income</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
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
            background: #f8f9fa;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Navigation */
        .navbar {
            background: #2c3e50;
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        .nav-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #3498db;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #3498db;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 150px 0 100px;
            text-align: center;
            margin-top: 60px;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        /* Study Materials */
        .materials {
            padding: 80px 0;
            background: white;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #2c3e50;
        }
        
        .materials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .material-card {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            border: 1px solid #eee;
            text-align: center;
        }
        
        .material-card:hover {
            transform: translateY(-10px);
        }
        
        .material-icon {
            font-size: 3rem;
            color: #3498db;
            margin-bottom: 1rem;
        }
        
        .material-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #2c3e50;
        }
        
        .download-btn {
            background: #27ae60;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 25px;
            display: inline-block;
            margin-top: 1rem;
            transition: background 0.3s;
        }
        
        .download-btn:hover {
            background: #219652;
        }
        
        /* Passive Income Section */
        .passive-income {
            background: #2c3e50;
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        
        .passive-income .section-title {
            color: white;
        }
        
        .income-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }
        
        .income-item {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 10px;
        }
        
        .income-amount {
            font-size: 2rem;
            font-weight: bold;
            color: #27ae60;
            display: block;
        }
        
        /* Ads Section */
        .ads-demo {
            background: #f8f9fa;
            padding: 80px 0;
            text-align: center;
        }
        
        .ad-container {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem auto;
            max-width: 600px;
            border: 2px dashed #3498db;
        }
        
        .ad-text {
            color: #666;
            font-style: italic;
        }
        
        /* How It Works */
        .how-it-works {
            padding: 80px 0;
            background: white;
        }
        
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .step {
            text-align: center;
            padding: 2rem;
            background: #f8f9fa;
            border-radius: 10px;
        }
        
        .step-number {
            background: #3498db;
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1rem;
            font-size: 1.5rem;
            font-weight: bold;
        }
        
        /* Footer */
        .footer {
            background: #34495e;
            color: white;
            padding: 3rem 0;
            text-align: center;
        }
        
        .social-links {
            margin-top: 1rem;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            margin: 0 10px;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #3498db;
        }
        
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="container nav-content">
            <div class="logo">
                <i class="fas fa-book"></i> StudyMaterial
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#materials">Study Materials</a></li>
                <li><a href="#income">Passive Income</a></li>
                <li><a href="#how-it-works">How It Works</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Free Study Materials + Passive Income 🚀</h1>
            <p>Download free notes and I earn money through ads - Win Win Situation!</p>
            <p style="margin-top: 1rem; font-size: 1.2rem;">🎯 Zero Investment • Auto Income • Work From Home</p>
        </div>
    </section>

    <!-- Study Materials -->
    <section id="materials" class="materials">
        <div class="container">
            <h2 class="section-title">Free Study Materials</h2>
            <div class="materials-grid">
                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3>Class 12 Physics Notes</h3>
                    <p>Complete physics notes with diagrams and formulas. Perfect for board exams.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>
                
                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-calculator"></i>
                    </div>
                    <h3>Mathematics Formulas</h3>
                    <p>All important math formulas, theorems, and solved examples.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>
                
                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h3>Programming Notes</h3>
                    <p>Python, Java, C++ programming concepts with code examples.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>

                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-flask"></i>
                    </div>
                    <h3>Chemistry Notes</h3>
                    <p>Organic, Inorganic chemistry with reactions and equations.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>

                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-book"></i>
                    </div>
                    <h3>English Grammar</h3>
                    <p>Complete English grammar rules and writing tips.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>

                <div class="material-card">
                    <div class="material-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Study Tips</h3>
                    <p>Effective study techniques and time management strategies.</p>
                    <a href="#" class="download-btn">
                        <i class="fas fa-download"></i> Download PDF
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Passive Income Section -->
    <section id="income" class="passive-income">
        <div class="container">
            <h2 class="section-title">How I Earn Passive Income</h2>
            <div class="income-stats">
                <div class="income-item">
                    <span class="income-amount">₹8,500</span>
                    <span>Monthly from Ads</span>
                </div>
                <div class="income-item">
                    <span class="income-amount">₹12,300</span>
                    <span>Monthly from Affiliate</span>
                </div>
                <div class="income-item">
                    <span class="income-amount">2,500+</span>
                    <span>Monthly Visitors</span>
                </div>
                <div class="income-item">
                    <span class="income-amount">24/7</span>
                    <span>Auto Income</span>
                </div>
            </div>
            
            <div style="max-width: 600px; margin: 0 auto;">
                <h3>💰 Money Comes Automatically</h3>
                <p>When students download materials, ads show automatically and I earn money without doing anything!</p>
                <p style="margin-top: 1rem; color: #ddd;">
                    <i class="fas fa-check-circle"></i> Zero maintenance required<br>
                    <i class="fas fa-check-circle"></i> Works 24/7<br>
                    <i class="fas fa-check-circle"></i> Income grows automatically
                </p>
            </div>
        </div>
    </section>

    <!-- Ads Section -->
    <section class="ads-demo">
        <div class="container">
            <h2 class="section-title">Revenue Sources</h2>
            
            <div class="ad-container">
                <h3>📱 Google Adsense</h3>
                <p class="ad-text">[This space earns money through ads when visitors come]</p>
                <p><strong>Earnings:</strong> ₹200-500 daily from ads</p>
            </div>
            
            <div class="ad-container">
                <h3>🛒 Amazon Affiliate</h3>
                <p class="ad-text">[Recommend books and earn commission]</p>
                <p><strong>Earnings:</strong> ₹5,000-15,000 monthly</p>
            </div>
            
            <div class="ad-container">
                <h3>📚 Course Promotions</h3>
                <p class="ad-text">[Promote online courses and earn]</p>
                <p><strong>Earnings:</strong> ₹10,000-20,000 monthly</p>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="how-it-works">
        <div class="container">
            <h2 class="section-title">How It Works</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>I Provide Free Education</h3>
                    <p>Upload study materials, notes, and resources for students</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Students Get Knowledge</h3>
                    <p>Students visit website and download free materials</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Ads Show Automatically</h3>
                    <p>Google ads show on website when visitors come</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>I Earn Passive Income</h3>
                    <p>Money comes automatically without any work</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <h3>🚀 Passive Income Machine</h3>
            <p>I provide free education → Students get knowledge → I earn from ads → Everyone wins! 🎉</p>
            
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
            
            <p style="margin-top: 1rem; font-size: 0.9rem; color: #bbb;">
                &copy; 2024 StudyMaterial - Education + Passive Income | Earn While You Sleep 💤
            </p>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Simulate download clicks
        document.querySelectorAll('.download-btn').forEach(btn => {
            btn.addEventListener('click', function(e) {
                e.preventDefault();
                alert('📚 Thanks for downloading! This action helps me earn through ads. 🎉\n\nIn real website, this would actually download PDF and show ads.');
            });
        });

        // Navbar background on scroll
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 100) {
                navbar.style.background = 'rgba(44, 62, 80, 0.95)';
            } else {
                navbar.style.background = '#2c3e50';
            }
        });
    </script>
</body>
</html>

