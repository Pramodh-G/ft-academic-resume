@def title = "Pramodh Gopalan"

<!-- -----------------
     BIOGRAPHY SECTION
     ----------------- -->

\begin{section}{name="about"}

<!-- LEFT COLUMN -->
@@col-12,col-lg-4,profile

\img{"/assets/img/Pramodh.jpg", class="avatar avatar-circle", alt="Pramodh Gopalan"}
\portrait{
  name="Pramodh Gopalan",
  job="Sophomore Student at IITK",
  link="www.iitk.ac.in",
  linkname="Indian Institute of Technology, Kanpur",
  twitter="",
  gscholar="",
  github="https://github.com/pramodh-g",
  linkedin="https://www.linkedin.com/in/pramodh-gopalan-2617231ba/"
}
@@ <!-- end of column -->

<!-- RIGHT COLUMN -->
@@col-12,col-lg-8

\begin{biography}{resume="/assets/CV.pdf"}
  I am a sophomore at Indian Institute of Technology Kanpur majoring in Computer Science and Engineering. My main research interests lie in Analyzing the robustness properties of Machine Learning models and using them to create more robust and explainable models. More specifically, I aim to use adversarial attacks to explain why Neural Networks learn differently from humans, and then construct more explainable models. 
  
  I also want to study how neural networks optimize themselves, so that I can gain better insight into how they learn features; but I need a lot of weaponry(read as math knowledge) before I can attack it.
\end{biography}

\shortcv{
  interests= ["Adversarial Machine Learning", "Explainable Machine Learning", "Optimization"],
  education=[
    ("BTech in Computer Science and Engineering, 2023(Expected)", "Indian Institute of Technology, Kanpur")]
}

@@ <!-- end of column -->
\end{section}

<!-- --------------
     SKILLS SECTION
     -------------- -->

\begin{section}{name="skills", class="wg-featurette", rowclass="featurette"}

\sectionheading{"Skills", class="col-md-12"}

\skill{"Julia", img="/assets/img/julia-dots-color.svg"}
\skill{"Pytorch", img="/assets/img/PyTorch.png"}
\skill{"Machine Learning", fa="chart-line"}
\skill{"Stargazing", fa="camera-retro"}

\end{section}


<!-- ------------------
     EXPERIENCE SECTION
     ------------------ -->

\begin{section}{name="experience"}

\sectionheading{"Experience", class="col-12 col-lg-4"}

@@col-12,col-lg-8

\experience{
  title="CEO",
  company="GenCoin",
  descr="""
    Responsibilities include:
    * Analysing
    * Modelling
    * Deploying
    """,
  from="Jan 2017",
  to="Present",
  location="California",
  active=true
  }
\experience{
  title="Professor",
  company="University X",
  from="Jan 2016",
  to="Dec 2016",
  location="California",
  descr="Taught electronic engineering and researched semiconductor physics."
  }

@@

\end{section}

<!-- -----------------------
     ACCOMPLISHMENTS SECTION
     ----------------------- -->

\begin{section}{name="accomplishments"}

\sectionheading{"Accomplish­ments", class="col-12 col-lg-4"}

@@col-12,col-lg-8

\certificate{
  title="Neural Networks and Deep Learning",
  meta="Coursera",
  metalink="https://www.coursera.org",
  date="Oct 2018",
  certlink="https://www.coursera.org"
  }
\certificate{
  title="Blockchain Fundamentals",
  descr="Formulated informed **blockchain** models, hypotheses, and use cases.",
  meta="Coursera",
  metalink="https://www.edx.org",
  date="Mar 2018",
  certlink="https://www.edx.org"
  }
\certificate{
  title="Object-Oriented Programming in R: S3 and R6 Course",
  meta="DataCamp",
  metalink="https://www.datacamp.com",
  date="Jul 2017 – Dec 2017",
  certlink="https://www.datacamp.com"
}

@@

\end{section}

<!-- --------------------
     RECENT POSTS SECTION
     -------------------- -->

\begin{section}{name="posts", class="wg-pages"}

\sectionheading{"Recent Posts", class="col-12 col-lg-4"}

@@col-12,col-lg-8

{{recentposts 3}}

@@

\end{section}

<!-- -----------------
     PORTFOLIO SECTION XXX
     ----------------- -->

<!-- -------------
     TALKS SECTION XXX
     ------------- -->

<!-- --------------------
     FEATURED PUB SECTION XXX
     -------------------- -->

<!-- ---------------------------
     RECENT PUBLICATIONS SECTION XXX
     --------------------------- -->
