%-------------------------
% Resume - Naman Bharsakale
%-------------------------

\documentclass[letterpaper,10pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{multicol}
\usepackage{xcolor}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.6in}
\addtolength{\textwidth}{1.2in}
\addtolength{\topmargin}{-.65in}
\addtolength{\textheight}{1.3in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\color{black}
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape \textbf{Naman Bharsakale}} \\ \vspace{6pt}
    {\small Maharashtra, India} \\ \vspace{4pt}
    \small
    \href{tel:7498438300}{+91 7498438300} $|$
    \href{https://www.linkedin.com/in/naman-bharsakale/}{LinkedIn} $|$
    \href{https://github.com/NamanBharsakale}{GitHub}
\end{center}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Walchand College of Engineering, Sangli}{2025 -- 2028}
      {B.Tech in Computer Science and Engineering}{}
    \vspace{5pt}
    \resumeSubheading
      {Government Polytechnic Amravati}{2022 -- 2025}
      {Diploma in Computer Engineering}{}
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Mountreach Solutions Pvt. Ltd.}{Amravati, India}
      {Software Engineering Trainee}{2024}
      \resumeItemListStart
        \resumeItem{Developed Android applications using \textbf{Java} backend, integrating \textbf{Google Maps API} to calculate real-time distances between store locations, improving logistics efficiency.}
        \resumeItem{Implemented \textbf{Firebase Cloud Messaging} to enable broadcast notifications to all users, enhancing communication workflows.}
        \resumeItem{Integrated multiple third-party APIs and utilities to extend app functionality, collaborating with team members in an agile environment.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
  \resumeSubHeadingListStart

    \resumeProjectHeading
      {\textbf{OpenNest} $|$ \emph{React, Node.js, MongoDB, Ollama AI, GitHub API, Tailwind CSS}}
      {\href{https://open-nest.vercel.app/}{[Live]} \quad \href{https://github.com/NamanBharsakale/OpenNest}{[GitHub]}}
      \resumeItemListStart
        \resumeItem{Built an \textbf{AI-powered platform} that connects developers to open-source projects by analyzing GitHub profiles and matching them with relevant repositories.}
        \resumeItem{Integrated \textbf{Ollama AI API} for intelligent repo recommendations; implemented \textbf{gamified badge system} and customizable skill selector for personalized contributions.}
        \resumeItem{Deployed full-stack MERN application on Vercel with CI/CD via GitHub integration.}
      \resumeItemListEnd

    \vspace{6pt}
    \resumeProjectHeading
      {\textbf{Sanctum Sanctorum} $|$ \emph{Node.js, Supabase, Tailwind CSS, Vercel}}
      {\href{https://sanctum-sanctorum.vercel.app/}{[Live]} \quad \href{https://github.com/NamanBharsakale/Sanctum-Sanctorum}{[GitHub]}}
      \resumeItemListStart
        \resumeItem{Designed and developed a \textbf{secure personal knowledge management platform} enabling authenticated users to store notes, links, and YouTube videos in a centralized hub.}
        \resumeItem{Integrated \textbf{Supabase} for authentication and real-time database management, ensuring data security and scalable storage.}
        \resumeItem{Architected feature roadmap including PDF upload functionality, applying \textbf{product thinking principles} to prioritize user needs and accessibility.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages:}{ Java, Python, JavaScript} \\
     \textbf{Frameworks \& Libraries:}{ React.js, Node.js, Tailwind CSS} \\
     \textbf{Databases:}{ MySQL, MongoDB, Supabase} \\
     \textbf{Tools \& Platforms:}{ Git, GitHub, Postman, Vercel, Firebase, Android Studio} \\
     \textbf{Concepts:}{ REST APIs, Data Structures \& Algorithms, Agile Development, Full-Stack Development}
    }}
 \end{itemize}

%-----------ACHIEVEMENTS-----------
\section{Honors \& Achievements}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Finalist -- TechSprint 2k26 Hackathon:} Recognized as a top finalist among 300+ participants, delivering an innovative software solution under competitive constraints. \href{https://github.com/NamanBharsakale/certificates-achievements/blob/main/Finalist-techsprint2k26.pdf}{[Certificate]} \\[2pt]
     \textbf{1st Place -- InnovateX Coding \& Debugging Challenge:} Secured first position in a combined coding and debugging competition among 200+ participants. \href{https://github.com/NamanBharsakale/certificates-achievements/blob/main/Achievement-1stWinner_InnovateX_%20Quiz%20and%20Debugging.jpg}{[Certificate]} \\[2pt]
     \textbf{MSBTE State-Level Paper Presentation:} Elected as the sole institutional representative from Government Polytechnic Amravati at the Maharashtra state-level technical paper presentation. \href{https://github.com/NamanBharsakale/certificates-achievements/blob/main/Acheivement-Represented%20GPA%20in%20MSBTE%20state%20level%20paper%20presentation.jpg}{[Certificate]} \\[2pt]
     \textbf{Academic Rank 2 -- Government Polytechnic Amravati:} Secured second rank across the entire Diploma program with 95.42\%, among top performers college-wide. \\[2pt]
     \textbf{Academic Rank 1 -- School:} Achieved first rank in school, demonstrating consistent academic excellence throughout secondary education.
    }}
 \end{itemize}

%-------------------------------------------
\end{document}
