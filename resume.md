#import "resume.typ": *

#show: cv.with(
  author: "Bas Nijholt, PhD",
  contacts: (
    [#icon("envelope.svg") #link("mailto:bas@nijho.lt")],
    [#icon("house-chimney.svg") #link("https://nijho.lt")[nijho.lt]],
    [#icon("github.svg") #link("https://github.com/basnijholt")[GitHub]],
    [#icon("linkedin.svg") #link("https://www.linkedin.com/in/basnijholt/")[LinkedIn]],
    [#icon("map-location-dot.svg") #link("https://goo.gl/maps/W1zKYYEFjKA2HuyW8")[Kirkland, WA, USA]],
    [#icon("phone.svg") #link("tel:+14255314341")[+1 (425) 531-4341]],
  )
)

= Introduction
I specialize in developer productivity infrastructure that accelerates research and engineering workflows. As the author of #link("https://github.com/python-adaptive/adaptive")[adaptive] (parallel adaptive sampling), #link("https://github.com/pipefunc/pipefunc")[pipefunc] (DAG-based workflow framework running from laptops to HPC), #link("https://github.com/basnijholt/unidep")[unidep] (monorepo package manager: 2h → 12s installs), and #link("https://mindroom.chat")[mindroom.chat] (federated AI agent platform), I build tooling that removes friction from development cycles at scale. I maintain 30+ Python packages spanning parallel workflows, numerical algorithms, and infrastructure automation. My Ph.D. in quantum mechanics grounds me in algorithmic thinking; my engineering focus is making complex systems fast and accessible.

= Experience
#exp(
  "IonQ",
  "Staff Engineer",
  "Redmond, United States",
  "Nov 2023 – Present, 40 h/w",
  [
    - Work across developer productivity, compiler optimizations, and large-scale quantum simulations.
    - Built a framework to represent simulations as directed acyclic graphs (DAGs) that runs identically from laptops to supercomputers (open-source: pipefunc).
    - Developed simulation software combining Python with lower-level languages (C++ via pybind11) for performance-critical HPC workloads.
    - Developed software to manage simulation workloads across our HPC infrastructure.
    - Created a package manager that reduced monorepo install time from 2 hours to 12 seconds (open-source: unidep).
    - Advocate for and introduce agentic AI coding workflows to accelerate development.
  ]
)
#exp(
  "Microsoft Research — Station Q",
  "Senior Quantum Software Engineer",
  "Redmond, USA (NL until Jan 2021)",
  "Aug 2021 – Nov 2023, 40 h/w",
  [
    - Work on making the first topological quantum computer a reality, specifically on inventing, developing, and applying machine learning and data analysis tools in a variety of experimental contexts.
    - Led the development of a tool for efficient data management, enabling the upload/download of validated, N-dimensional arrays to a cloud-based data lake, and facilitated SQL querying for selective data retrieval.
    - Designed and developed advanced tools for the design and modeling of next-generation topological qubits and their control hardware.
    - Principal developer of proprietary chip design software, enabling comprehensive 3D simulations of quantum devices and automated preparation of fabrication-ready layouts, thereby accelerating the design-to-production process.
    - Developing and testing bleeding edge physics simulation capabilities for quantum information applications.
    - Inventing, developing, and applying machine learning and data analysis tools in a variety of experimental contexts.
    - Creating and maintaining HPC cloud cluster infrastructure of >100.000 CPU cores on Microsoft Azure on which quantum simulations are performed.
  ]
)
#exp(
  "Microsoft Research — Station Q",
  "Quantum Simulation Engineer",
  "Delft, the Netherlands",
  "Jan 2020 – Aug 2021, 40 h/w",
  [
    - Contributed to the development of the first topological quantum computer by designing and applying Bayesian machine learning techniques for quantum computer calibration protocols.
    - Developed automated data processing pipelines for extracting relevant physical parameters from large datasets for topological quantum computer design.
    - Formulated theories and simulation workflows to derive physical parameters from experimental data.
    - Created research software for running massively parallel adaptive parameter sweeps.
  ]
)
#exp(
  "Microsoft Research — Station Q",
  "Research Intern (2nd time)",
  "Santa Barbara, United States",
  "Apr 2019 – Jul 2019, 40 h/w",
  [
    - Developed a general-purpose Python program called Adaptive-scheduler for interactively managing adaptive parallel simulations on over 100k cores, using cloud HPC infrastructure.
    - Continued work on the previous year's project.
  ]
)
#exp(
  "Microsoft Research — Station Q",
  "Research Intern (1st time)",
  "Santa Barbara, United States",
  "May 2018 – Aug 2018, 40 h/w",
  [
    - Created a simulation code to extract spin-orbit coupling constants in semiconducting nanowires from weak-anti-localization data.
    - Contributed to Microsoft's in-house simulation software packages.
  ]
)
#exp(
  "Harvard University — Wyss Institute",
  "Research Intern",
  "Boston, United States",
  "Sep 2015 – Dec 2015, 40 h/w",
  [
    - Developed an innovative algorithm for designing large DNA origami structures during an internship at William Shih's lab.
    - Received a 9/10 grade for the project.
  ]
)
#exp(
  "TU Delft — Bètasteunpunt",
  "Student assistant",
  "Delft, the Netherlands",
  "Nov 2013 – March 2014, 4 h/w",
  [
    - Designed an engaging educational program on quantum mechanics for high school teachers, complemented by lectures on Majorana particles by Leo Kouwenhoven.
    - Created a concise educational program on image processing applications.
  ]
)
#exp(
  "Antoniuscollege Gouda",
  "(Licensed) Computer Science Teacher and Math Teacher",
  "Gouda, the Netherlands",
  "Sep 2012 – Aug 2013, 16 p/w",
  [
    - Taught mathematics to first graders of havo and vwo (pre-university) where I implemented the flipped classroom concept.
    - Taught computer science to fifth and sixth graders in their final year (pre-university) and introduced students to programming (i.e. Java), project management, game development, data.
  ]
)
#exp(
  "Lyceo",
  "Planner and software engineer",
  "Delft, the Netherlands",
  "Mar 2012 – May 2012, 40 h/w",
  [
    - Streamlined the process of automating and coordinating the scheduling of over a thousand teachers for exam training.
    - Developed a web-tool to efficiently schedule tutors for exam training sessions, managing up to 200 teachers and 1000 students per day.
  ]
)
#exp(
  "TU Delft",
  "Mathematics and mechanics help desk",
  "Delft, the Netherlands",
  "2011 – 2012, 4 h/w",
  [
    - Assisted and addressed questions from TU Delft bachelor students on calculus and mechanics at the help desk.
  ]
)
#exp(
  "Nijholt.biz",
  "Web designer",
  "Rotterdam, the Netherlands",
  "2002 – 2010 (8 years)",
  [
    - Designed and hosted websites for various clients, including dentists, hotels, restaurants, car dealerships, filmmakers, and personal webpages since the age of 12.
  ]
)

= Education
#exp(
  "Delft University of Technology",
  "Ph.D. candidate in computational quantum mechanics",
  "Delft, the Netherlands",
  "Jan 2016 – Dec 2019, 40 h/w",
  [
    - Thesis title: #link("https://github.com/basnijholt/thesis")["Towards Realistic Numerical Simulations of Majorana Devices"].
    - Conducted theoretical research on Majorana devices for qubits in topological quantum computing, #link("https://scholar.google.com/citations?user=nIO4EK4AAAAJ&hl")[resulting in 10 peer-reviewed papers and 621 citations, with an h-index of 10].
    - Contributed to various open-source projects within the Python ecosystem, including 17 conda-forge packages, HoloViews, Kwant, pandas, Jupyter, SLURM, dask, and ipyparallel.
    - Managed system administration tasks, including group's JupyterHub, Ansible, Docker, Git, and continuous integration (CI).
    - Authored 3 Python packages for facilitating adaptive computing in research (HPC), used by Microsoft, Rolls-Royce, University of Maryland, TU Delft, TU Eindhoven, University of Illinois, and more.
  ]
)
#exp(
  "Delft University of Technology",
  "Master of Science in Applied Physics",
  "Delft, The Netherlands",
  "Sep 2013 – Sep 2015",
  [
    - Specialization in Applied Physics, with a focus on quantum mechanics and computational physics.
    - Recipient of the prestigious Justus & Louise van Effen Research Grant, awarded to the top 5% of students for research at one of the world's top-20 universities (Harvard).
    - Founded a student organization that organized educational activities, including visits to CERN and networking events with alumni.
    - Thesis titled #emph[#link("http://arxiv.org/abs/1509.02675", "\"Orbital effect of magnetic field on the Majorana phase diagram\"")] under the supervision of #link("https://quantumtinkerer.tudelft.nl/", "Dr. Anton Akhmerov").
    - Achieved a GPA of 8/10.
  ]
)
#exp(
  "Delft University of Technology",
  "Bachelor of Science in Applied Physics",
  "Delft, The Netherlands",
  "Sep 2009 – Jul 2013",
  [
    - Bachelor thesis conducted at the Kavli Institute of Nanoscience Delft, Bionanoscience Department, under Cees Dekker's group: #emph[#link("https://doi.org/10.1093/nar/gkx147", "\"Single-Molecule Studies of the Annealing Helicase HARP using Magnetic Tweezers.\"")] Received a grade of 9/10.
    - Completed additional courses (31 ECTS) in Biochemistry, Molecular Genetics, Chemistry, Cell Biology, and related subjects. GPA of 8/10.
    - Completed a Minor in Computer Science Education, obtaining a second-degree teaching qualification. GPA of 9/10.
    - Actively involved in several committees at the Student Association of Applied Physics.
  ]
)

= Highlighted Projects
#exp(
  "Adaptive",
  "main author",
  [#icon("github.svg") #link("https://github.com/python-adaptive/adaptive")[source]],
  "",
  [
    - Developed a Python package that accelerates simulation code by intelligently sampling points in parameter space, boosting performance by 10-100 times. Widely used by researchers in computational sciences and has received >1000★ on GitHub.
  ]
)
#exp(
  "pipefunc",
  "author & maintainer",
  [#icon("github.svg") #link("https://github.com/pipefunc/pipefunc")[source]],
  "",
  [
    - Lightweight DAG framework for scientific workflows; runs identically from laptops to supercomputers.
  ]
)
#exp(
  "Topological Gap Protocol",
  "main code author",
  [#icon("github.svg") #link("https://github.com/microsoft/azure-quantum-tgp")[source]],
  "",
  [
    - Open-sourced code that performs the analysis as reported in "InAs-Al Hybrid Devices Passing the Topological Gap Protocol" by Microsoft Azure Quantum.
  ]
)
#exp(
  "mindroom.chat",
  "author & maintainer",
  [#icon("github.svg") #link("https://github.com/mindroom-ai/mindroom")[source]],
  "",
  [
    - Federated AI agent platform built on Matrix protocol; agents with persistent memory that work across Slack, Discord, Telegram, and WhatsApp via bridges.
    - Leverages Docker and Kubernetes for deployment; supports self-hosted and cloud instances with end-to-end encryption.
    - Multi-agent collaboration with 80+ tool integrations and automated scheduling workflows.
  ]
)
#exp(
  "Adaptive-scheduler",
  "main author",
  [#icon("github.svg") #link("https://github.com/basnijholt/adaptive-scheduler")[source]],
  "",
  [
    - Designed a tool for scheduling and managing adaptive interactive parallel jobs on massive scale (tested on >100,000 cores on Azure), extensively used by the Microsoft Station Q team.
  ]
)
#exp(
  "unidep",
  "author & maintainer",
  [#icon("github.svg") #link("https://github.com/basnijholt/unidep")[source]],
  "",
  [
    - Unified Conda and Pip package manager–ideal for monorepos with complex dependencies.
  ]
)
#exp(
  [#link("http://www.topocondmat.org")[topocondmat.org]],
  "online course",
  [#icon("github.svg") #link("https://github.com/basnijholt/adaptive-scheduler")[source]],
  "",
  [
    - Developed a website for an online course on topology in condensed matter, which is automatically compiled from Jupyter notebooks using CI. Also responsible for coding the interactive plots featured on the site.
  ]
)
#exp(
  "Home Assistant",
  "top 1% contributor",
  "",
  "",
  [
    - Contributed to the largest open-source home automation project (>100k users), built on Python and fully asynchronous.
    - Main developer of #link("https://github.com/basnijholt/adaptive-Lighting")[Adaptive Lighting] (with 1000s of users) and #link("https://github.com/basnijholt/home-assistant-streamdeck-yaml")[Home Assistant Streamdeck YAML], which programs a Streamdeck in YAML.
  ]
)

= Certifications
#exp(
  "TU Delft",
  "Second-degree High School Teaching Qualification in Computer Science",
  "",
  "Jan 2013",
  []
)

= Skills, Languages & Interests
- *Skills*: Python, Git, Docker, CI, Go, Bash, Linux, Ansible, High-performance computing, Machine learning, Fortran, Java, Matlab, PHP, HTML, CSS, LaTeX, LabView, and basic office programs.
- *Languages*: Dutch (native) and English (professional)
- *Interests*: world-literature (Dostoevsky), landscape photography, hiking, open-source software, home automation, AI, finance, music (Nicolas Jaar), science, biotechnology, nanoscience, art (Van Gogh, Courbet), philosophy, physics.
