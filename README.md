<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="style.css"/>
  <title>Yeşim Aygül | Portfolio</title>
  <meta name="description" content="Network Analysis, Machine Learning, Virtual Reality"/>
</head>

<body>
  <!-- Header -->
  <header>
    <a href="#home" class="logo" aria-label="Home">Yeşim <span>Aygül</span></a>

    <button class="bx bx-menu" id="menu-icon" aria-label="Toggle menu" aria-expanded="false" aria-controls="navbar"></button>

    <ul class="navbar" id="navbar" role="navigation">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Research Areas</a></li>
      <li><a href="#portfolio">Projects & Publications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>

    <div class="top-btn">
      <a href="mailto:yesim.aygul@bakircay.edu.tr" class="nav-btn">Contact Me</a>
    </div>
  </header>

  <!-- Home -->
  <section id="home" class="home">
    <div class="home-img">
      <img src="assets/ProfileImage1.jpg" alt="Profile photo of Yesim Aygul"/>
    </div>

    <div class="home-content">
      <h1>Hello, I'm <span>Yeşim</span></h1>
      <h3><span class="multiple-text"></span></h3>

      <p>
        I am a <strong>Research Assistant</strong> at Izmir Bakircay University, Department of Computer Engineering.  
        My research focuses on <em>Network Analysis</em>, 
        <em>Machine Learning</em>, and <em>Virtual Reality</em>.
      </p>


        <div class="social-icons">
        <a href="https://www.linkedin.com/in/yeşim-aygül-bb2003176"><i class='bx bxl-linkedin' aria-label="LinkedIn"></i></a>
        <a href="https://github.com/Yesim7"><i class='bx bxl-github' aria-label="GitHub"></i></a>
        <a href="https://scholar.google.com/citations?user=bpR9pcQAAAAJ&hl=tr&oi=ao"><i class='bx bxl-google' aria-label="Google Scholar"></i></a>
        
        </div>


      <a href="mailto:yesim.aygul@bakircay.edu.tr" class="btn">Contact Me</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="about">
    <div class="about-content">
      <h2 class="heading">About <span>Me</span></h2>
        
       <p style="text-align:justify; hyphens:auto;">
        I completed my <strong>BSc in Mathematics</strong> at Ege University (2020) and my 
        <strong>MSc in Computer Science</strong> at Ege University (2023).  
        Currently, I am pursuing a <strong>PhD in Computer Engineering</strong> at Izmir Bakircay University, 
        where I have been working as a research assistant since April 2024.  

        My doctoral studies are centered on <strong>distributed algorithm design</strong> and its applications in 
        network optimization. My broader research interests include <em>critical element detection in networks</em>, 
        <em>machine learning for healthcare</em>, and <em>Virtual Reality-based training systems</em>.
        </p>

      <a href="#portfolio" class="btn">View My Work</a>
    </div>

    <div class="about-img">
      <img src="assets/ProfileImage2.jpg" alt="Working environment photo"/>
    </div>
  </section>

  <!-- Research Areas -->
  <section class="services" id="services">
    <h2 class="heading">Main <span>Research Areas</span></h2>

    <div class="services-content" data-aos="zoom-in-up">
      <div class="box">
        <div class="row-icon"><i class='bx bx-git-branch'></i></div>
        <h3>Critical Element Detection</h3>
        <p>Designing centralized and distributed algorithms for detecting critical nodes/edges in multi-hop wireless networks.</p>
      </div>

      <div class="box">
        <div class="row-icon"><i class='bx bx-pulse'></i></div>
        <h3>Machine Learning in Healthcare</h3>
        <p>Prediction of disease severity, survival analysis, and decision support using classical ML and deep learning approaches.</p>
      </div>

      <div class="box">
        <div class="row-icon"><i class='bx bx-vr'></i></div>
        <h3>Virtual Reality-based Training</h3>
        <p>Scenario design and evaluation for occupational safety and campus digitalization using immersive Virtual Reality technologies.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section class="portfolio" id="portfolio">
    <h2 class="heading"><span>Projects</span></h2>

    <div class="portfolio-content" data-aos="zoom-in-up">
     

      <div class="row">
        <img src="assets/img2.png" alt="Virtual Reality safety training project - TÜBİTAK 1002 Project"/>
        <h4>Virtual Reality for Occupational Safety Training: Firefighting & Fall Simulation (Researcher, 2025–2026)</h4>
      </div>

      <div class="row">
        <img src="assets/img3.jpeg" alt="Endoscopy Artificial Intelligence project - TÜSEB Group A Emergency R&D project A3-02"/>
        <h4>EndoAI: Artificial Intelligence-based DSS for Real-Time Polyp Detection (Researcher, 2025–2026 )</h4>
      </div>

      <div class="row">
        <img src="assets/img3.jpeg" alt=".. project - TÜSEB Group A Emergency R&D project A3-02"/>
        <h4>Prediction of Survival Time in Colorectal Cancer Patients Using Ensemble Learning ... (Researcher, 2025–2026)</h4>
      </div>

       <div class="row">
        <img src="assets/img1.png" alt="Virtual Reality campus project - Scientific Research Project"/>
        <h4>Digitization of University Campuses via Virtual Reality (Researcher, 2025–2026)</h4>
      </div>
      
      <div class="row">
        <img src="assets/img8.jpg" alt=".. project - TÜBİTAK 3501 National Young Researchers Career Development Program"/>
        <h4>Design and Analysis of Centralized and Distributed Algorithms for Identifying Critical Elements in Networks (Scholarship, 2021–2023)</h4>
      </div>
      

      <h2 class="heading"> <span>Publications</span></h2>

      <div class="row">
        <img src="assets/img5.png" alt="Ad Hoc Networks paper"/>
        <h4>Distributed Detecting of Critical Nodes for Maximization of Connected ... (Ad Hoc Networks, 2025)</h4>
      </div>

      <div class="row">
        <img src="assets/img6.png" alt="BMC Emergency Medicine paper"/>
        <h4>Predicting Severity of Acute Appendicitis... (BMC Emerg Med, 2024)</h4>
      </div>

      <div class="row">
        <img src="assets/img7.png" alt="PCI 2023 conference"/>
        <h4>A Depth-First Search-Based Algorithm for the Minimization of the Largest Connected Component in Networks (PCI 2023)</h4>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2 class="heading">Contact <span>Me</span></h2>
    
    <!-- 
    <div class="contact-cards">
      <div><i class='bx bx-phone'></i> <span>Phone:</span> +90 534 328 40 59</div>
      <div><i class='bx bx-envelope'></i> <span>e-mail:</span> yesim.aygul@bakircay.edu.tr</div>
      <div><i class='bx bx-map'></i> <span>Address:</span> Seyrek Campus, Menemen / Izmir</div>
    </div>
    -->


  <form action="https://formspree.io/f/mwprkboe" method="POST">
  <div class="input-box">
    <input type="text" name="name" placeholder="Full Name" required/>
    <input type="email" name="email" placeholder="Email Address" required/>
  </div>
  <div class="input-box">
    <input type="tel" name="phone" placeholder="Phone"/>
    <input type="text" name="subject" placeholder="Subject"/>
  </div>

  <textarea name="message" cols="30" rows="10" placeholder="Your Message" required></textarea>

  <!-- İsteğe bağlı: konu başlığı ve başarılı dönüş adresi -->
  <input type="hidden" name="_subject" value="New message from Portfolio"/>

  <!-- Basit honeypot (spam azaltma) -->
  <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off"/>

  <input type="submit" value="Send Message" class="btn"/>
</form>

 </script>

    
  <!-- Footer -->
  <footer class="footer">
    <div class="social">
      <a href="https://www.linkedin.com/in/yeşim-aygül-bb2003176"><i class='bx bxl-linkedin'></i></a>
      <a href="https://github.com/Yesim7"><i class='bx bxl-github'></i></a>
      <a href="https://scholar.google.com/citations?user=bpR9pcQAAAAJ&hl=tr&oi=ao"><i class='bx bxl-google'></i></a>
      <a href="https://akademik.yok.gov.tr/AkademikArama/AkademisyenGorevOgrenimBilgileri?islem=direct&authorId=503D379A5CECFD31"><i class='bx bx-book'></i></a>
     
      <a href="https://orcid.org/0000-0003-0605-9604">
      <i class='bx bx-id-card' aria-label="ORCID"></i>
      </a>
        <a href="https://www.researchgate.net/profile/Yesim-Ayguel?ev=hdr_xprf">
            <i class='bx bx-network-chart' aria-label="ResearchGate"></i>
        </a>
        <a href="https://bilgisayar.bakircay.edu.tr/Sayfalar/514/akademik-personel">
            <i class='bx bx-building' aria-label="Institutional Page"></i>
        </a>
    </div>
    <p class="copyright">
    <span id="year"></span> &copy; Yeşim Aygül | All Rights Reserved
    </p>

  </footer>

  <!-- Scripts -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script src="script.js"></script>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    
  const form = document.querySelector('#contact form');
  if (form) {
    const statusEl = document.createElement('p');
    statusEl.id = 'form-status';
    statusEl.setAttribute('role','status');
    statusEl.style.marginTop = '.75rem';
    form.after(statusEl);

    form.addEventListener('submit', async (e) => {
      e.preventDefault(); // Sayfanın üste zıplamasını engeller
      statusEl.textContent = 'Sending...';
      try {
        const res = await fetch(form.action, {
          method: 'POST',
          body: new FormData(form),
          headers: { 'Accept': 'application/json' }
        });
        if (res.ok) {
          form.reset();
          statusEl.textContent = 'Thanks! Your message was sent.';
        } else {
          statusEl.textContent = 'Sorry, something went wrong. Please try again.';
        }
      } catch (err) {
        statusEl.textContent = 'Network error. Please try again.';
      }
    });
  }
</script>
 

</body>
</html>




