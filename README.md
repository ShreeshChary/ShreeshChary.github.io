<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="assets/css/styles.css" />
    <!-- =====BOX ICONS===== -->
    <link
      href="https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css"
      rel="stylesheet"
    />
    <title>Shreesh Chary • Aspiring Economist & Researcher</title>
  </head>
  <body>
    <!--===== HEADER =====-->
    <header class="l-header">
      <nav class="nav bd-grid">
        <div>
          <span class="nav__logo">Shreesh Chary</span>
        </div>

        <div class="nav__menu" id="nav">
          <ul class="nav__list">
            <li class="nav__item">
              <a href="#about" class="nav__link active">About</a>
            </li>
            <li class="nav__item">
              <a href="#skills" class="nav__link">Skills</a>
            </li>
            <li class="nav__item">
              <a href="#work" class="nav__link">Publications</a>
            </li>
            <li class="nav__item">
              <a href="#achievements" class="nav__link">Achievements</a>
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link">Contact</a>
            </li>
          </ul>
        </div>

        <div class="nav__toggle" id="nav-toggle">
          <i class="bx bx-menu"></i>
        </div>
      </nav>
    </header>

    <main class="l-main">
      <!--===== HOME =====-->
      <div class="bg__full">
        <section class="home bd-grid" id="home">
          <div class="home__data">
            <h1 class="home__title">
              Hi,<br />I'm Shreesh Chary <i class="bx bx-pen"></i><br />
              Aspiring Economist and Researcher.
            </h1>
          </div>

          <div class="home__social">
            <a href="mailto:your-email@example.com" class="home__social-icon"
              ><i class="bx bx-mail-send"></i
            ></a>
            <a href="https://www.linkedin.com/in/shreesh-chary/" target="_blank"
              class="home__social-icon"
              ><i class="bx bxl-linkedin-square"></i
            ></a>
            <a href="https://github.com/shreesh-chary" target="_blank" class="home__social-icon"
              ><i class="bx bxl-github"></i
            ></a>
          </div>
        </section>
      </div>

      <!--===== ABOUT =====-->
      <section class="about section" id="about">
        <h2 class="section-title">About Me</h2>
        <div class="about__container bd-grid">
          <div>
            <p class="about__text">
              I am a master's graduate in economics with experience in data analysis, econometric modeling, and research. My focus is on the intersections of trade, R&D, military economics, and development studies. I am proficient in Stata, R, Python, and LaTeX, with expertise in quantitative and qualitative research methods. My research involves econometric investigations into global economic patterns, knowledge spillovers, and policy analysis.
            </p>
            <a class="resume_icon" href="./resume_shreeshchary.pdf" download
              >Resume <i class="bx bxs-download"></i
            ></a>
          </div>
        </div>
      </section>

      <!--===== EDUCATION =====-->
      <section class="edu section">
        <h2 class="section-title">Education</h2>

        <div class="edu__container bd-grid">
          <div class="edu__comp">
            <div class="edu__duration">2022 - Present</div>
            <div class="edu__college">Master's in Economics</div>
            <div class="edu__college">Nottingham University</div>
            <div class="edu__grade">Expected Distinction</div>
          </div>
          <div class="edu__comp">
            <div class="edu__duration">2018 - 2022</div>
            <div class="edu__college">Symbiosis School of Economics</div>
            <div class="edu__degree">Bachelor of Science in Economics</div>
            <div class="edu__grade">First Class Honours</div>
          </div>
        </div>
      </section>

      <!--===== SKILLS =====-->
      <div class="bg__full">
        <section class="skills section" id="skills">
          <h2 class="section-title">Skills</h2>

          <div class="skills__container bd-grid">
            <div class="skill__box">
              <div class="skills__subtitle">Programming Languages</div>
              <span class="skills__data">R</span>
              <span class="skills__data">Stata</span>
              <span class="skills__data">Python</span>
            </div>
            <div class="skill__box">
              <div class="skills__subtitle">Data Analysis</div>
              <span class="skills__data">Econometrics</span>
              <span class="skills__data">Time Series</span>
              <span class="skills__data">Panel Data Models</span>
            </div>
            <div class="skill__box">
              <div class="skills__subtitle">Research Methods</div>
              <span class="skills__data">Quantitative & Qualitative</span>
              <span class="skills__data">Policy Analysis</span>
              <span class="skills__data">Literature Review</span>
            </div>
          </div>
        </section>
      </div>

      <!--===== PUBLICATIONS =====-->
      <section class="work section" id="work">
        <h2 class="section-title">Publications</h2>

        <div class="work__container bd-grid">
          <div class="work__comp">
            <h3 class="work__title">On Military Spending: An Economic Thought Perspective</h3>
            <p class="work__text">Cogent Social Sciences (May 2024)</p>
          </div>

          <div class="work__comp">
            <h3 class="work__title">Employee Grievance Redressal and Corporate Ethics</h3>
            <p class="work__text">Science and Engineering Ethics (April 2024)</p>
          </div>

          <div class="work__comp">
            <h3 class="work__title">Political Regimes and Self-Reliance in the Indian Arms Industry</h3>
            <p class="work__text">Asian Security (March 2024)</p>
          </div>

          <div class="work__comp">
            <h3 class="work__title">The Nexus Between Arms Imports, Military Expenditures and Economic Growth</h3>
            <p class="work__text">Journal of Economic Studies (August 2023)</p>
          </div>
        </div>
      </section>

      <!--==== ACHIEVEMENTS =====-->
      <section class="achievements section" id="achievements">
        <h2 class="section-title">Achievements</h2>
        <div class="achievements__container bd-grid">
          <div class="achievement__item">
            <h3>Economist of the Year</h3>
            <p>Symbiosis School of Economics (2023)</p>
          </div>

          <div class="achievement__item">
            <h3>Best Student Researcher of the Year</h3>
            <p>Symbiosis School of Economics (2024)</p>
          </div>
        </div>
      </section>

      <!--==== CONTACT =====-->
      <section class="contact section" id="contact">
        <h2 class="section-title">Contact</h2>

        <div class="contact__container bd-grid">
          <div class="contact__info">
            <h3>Email:</h3>
            <p>shreeshchary@gmail.com</p>
          </div>
          <div class="contact__info">
            <h3>LinkedIn:</h3>
            <a href="https://www.linkedin.com/in/shreesh-chary/">linkedin.com/in/shreesh-chary</a>
          </div>
          <div class="contact__info">
            <h3>GitHub:</h3>
            <a href="https://github.com/shreesh-chary">github.com/shreesh-chary</a>
          </div>
        </div>
      </section>
    </main>
  </body>
</html>
