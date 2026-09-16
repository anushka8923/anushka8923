\documentclass[10pt,letterpaper]{article}

% =========================================================
% PACKAGES
% =========================================================

\usepackage[
    top=0.30in,
    bottom=0.28in,
    left=0.42in,
    right=0.42in
]{geometry}

\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{titlesec}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{tikz}
\usepackage{tcolorbox}
\usepackage{ragged2e}

% =========================================================
% COLORS
% =========================================================

\definecolor{primary}{HTML}{302B63}
\definecolor{secondary}{HTML}{38BDF8}
\definecolor{accent}{HTML}{7C3AED}
\definecolor{dark}{HTML}{1F2937}
\definecolor{gray}{HTML}{6B7280}

\definecolor{cpp}{HTML}{00599C}
\definecolor{cblue}{HTML}{A8B9CC}
\definecolor{js}{HTML}{F7DF1E}
\definecolor{ts}{HTML}{3178C6}
\definecolor{react}{HTML}{61DAFB}
\definecolor{next}{HTML}{111111}
\definecolor{tailwind}{HTML}{06B6D4}
\definecolor{node}{HTML}{339933}
\definecolor{express}{HTML}{222222}
\definecolor{mongo}{HTML}{47A248}
\definecolor{postgres}{HTML}{4169E1}
\definecolor{git}{HTML}{F05032}
\definecolor{vercel}{HTML}{111111}
\definecolor{render}{HTML}{46E3B7}
\definecolor{groq}{HTML}{8B5CF6}

% =========================================================
% HYPERLINKS
% =========================================================

\hypersetup{
    colorlinks=true,
    urlcolor=secondary,
    linkcolor=primary
}

% =========================================================
% PAGE
% =========================================================

\pagestyle{empty}
\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}

% =========================================================
% SECTION STYLE
% =========================================================

\titleformat{\section}
    {\large\bfseries\color{primary}}
    {}
    {0pt}
    {}
    [\vspace{-5pt}
     \color{secondary}\rule{\textwidth}{1.2pt}]

\titlespacing*{\section}
    {0pt}{5pt}{3pt}

% =========================================================
% LIST STYLE
% =========================================================

\setlist[itemize]{
    leftmargin=0.19in,
    label=\textcolor{secondary}{\small\faAngleRight},
    itemsep=0.25pt,
    topsep=0.5pt,
    parsep=0pt,
    partopsep=0pt
}

% =========================================================
% CUSTOM SKILL BADGE
% =========================================================

\newcommand{\skill}[2]{%
    \tikz[baseline=-0.6ex]
    \node[
        rounded corners=3pt,
        fill=#1!12,
        draw=#1!55,
        line width=0.35pt,
        inner xsep=5pt,
        inner ysep=2pt,
        font=\scriptsize\bfseries
    ] {#2};
    \hspace{1.5pt}
}

% =========================================================
% DOCUMENT
% =========================================================

\begin{document}

% =========================================================
% HEADER
% =========================================================

\begin{center}

    {\fontsize{25}{28}\selectfont
    \textbf{\textcolor{primary}{Anushka}}}

    \\[-1pt]

    {\small
    \textcolor{secondary}{\textbf{Full Stack MERN Developer}}
    }

    \\[5pt]

    {\small
    \faPhone\ +91-8077838539
    \quad
    \textcolor{gray}{|}
    \quad
    \href{mailto:anushka892360@gmail.com}
    {\textcolor{dark}{\faEnvelope\ anushka892360@gmail.com}}
    \quad
    \textcolor{gray}{|}
    \quad
    \href{https://github.com/anushka8923}
    {\textcolor{dark}{\faGithub\ GitHub}}
    \quad
    \textcolor{gray}{|}
    \quad
    \href{https://www.linkedin.com/in/anushka8923/}
    {\textcolor{dark}{\faLinkedin\ LinkedIn}}
    \quad
    \textcolor{gray}{|}
    \quad
    \href{https://leetcode.com/u/anushka8923/}
    {\textcolor{dark}{\faCode\ LeetCode}}
    }

\end{center}

% =========================================================
% ABOUT ME
% =========================================================

\section*{\faUser\quad About Me}

Full Stack Developer skilled in building scalable web applications, RESTful APIs, and responsive interfaces. Experienced in JWT authentication, payment integration, database management, deployment, and AI-powered feature integration.

% =========================================================
% TECHNICAL SKILLS
% =========================================================

\section*{\faLaptopCode\quad Technical Skills}

\textbf{\textcolor{primary}{\faCode\ Languages}}\\[-1pt]
\skill{cpp}{C++}
\skill{cblue}{C}
\skill{js}{JavaScript}
\skill{ts}{TypeScript}

\vspace{2pt}

\textbf{\textcolor{primary}{\faPaintBrush\ Frontend}}\\[-1pt]
\skill{html}{HTML}
\skill{css}{CSS}
\skill{react}{React.js}
\skill{next}{Next.js}
\skill{tailwind}{Tailwind CSS}

\vspace{2pt}

\textbf{\textcolor{primary}{\faServer\ Backend \& Concepts}}\\[-1pt]
\skill{node}{Node.js}
\skill{express}{Express.js}
\skill{secondary}{REST APIs}
\skill{accent}{JWT Authentication}
\skill{accent}{DSA}
\skill{accent}{OOP}
\skill{accent}{CRUD Operations}
\skill{secondary}{API Integration}

\vspace{2pt}

\textbf{\textcolor{primary}{\faRobot\ AI Integration}}\\[-1pt]
\skill{groq}{Groq AI SDK}
\skill{accent}{AI Chatbot Integration}

\vspace{2pt}

\textbf{\textcolor{primary}{\faDatabase\ Databases \& Tools}}\\[-1pt]
\skill{mongo}{MongoDB}
\skill{postgres}{PostgreSQL}
\skill{accent}{Redis}
\skill{git}{Git}
\skill{git}{GitHub}
\skill{vercel}{VS Code}
\skill{vercel}{Vercel}
\skill{render}{Render}

\vspace{2pt}

\textbf{\textcolor{primary}{\faUsers\ Soft Skills}}\\[-1pt]
\skill{secondary}{Problem Solving}
\skill{secondary}{Effective Communication}
\skill{secondary}{Team Collaboration}
\skill{secondary}{Leadership}

% =========================================================
% FEATURED PROJECTS
% =========================================================

\section*{\faRocket\quad Featured Projects}

\textbf{\textcolor{primary}{\faCut\quad AI Barber Shop --- AI-Powered Booking Platform}}
\hfill
\href{https://github.com/anushka8923/ai-barber-shop}
{\textcolor{secondary}{\faGithub\ GitHub}}
\quad
\href{https://github.com/anushka8923/ai-barber-shop}
{\textcolor{secondary}{\faExternalLinkAlt\ Live}}

\begin{itemize}

    \item Built a full-stack barber shop booking platform using Next.js 15, React 19, Tailwind CSS, Node.js, Express.js, and MongoDB.

    \item Integrated a Groq-powered AI chatbot for customer queries on services, pricing, hairstyle recommendations, and barber consultation.

    \item Implemented real-time slot availability and booking updates using Socket.IO, allowing users to view reservation changes without refreshing the page.

    \item Developed JWT-based authentication with bcrypt password hashing and admin workflows for managing barbers, services, slots, and appointments.

    \item Implemented REST API communication using Axios and EmailJS notifications for booking confirmations.

\end{itemize}

\vspace{1pt}

\textbf{\textcolor{primary}{\faUniversity\quad College Discovery Platform}}
\hfill
\href{https://github.com/anushka8923/college-discovery-platform}
{\textcolor{secondary}{\faGithub\ GitHub}}
\quad
\href{https://college-discovery-platform-black.vercel.app/}
{\textcolor{secondary}{\faExternalLinkAlt\ Live}}

\begin{itemize}

    \item Built a full-stack platform for exploring, filtering, and comparing engineering colleges with a responsive user interface.

    \item Developed the frontend using Next.js, React.js, TypeScript, and Tailwind CSS.

    \item Created Node.js/Express.js REST APIs with PostgreSQL and implemented college comparison, predictor, and detailed college pages.

\end{itemize}

% =========================================================
% EXPERIENCE
% =========================================================

\section*{\faBriefcase\quad Experience}

\textbf{\textcolor{primary}{Full Stack Developer Intern --- Baloon}}
\hfill
\textbf{May 31, 2026 -- Aug 31, 2026}

\textit{\textcolor{gray}{Remote}}

\begin{itemize}

    \item Developed full-stack features using React.js, Node.js, Express.js, MongoDB, Redis, and REST APIs for a production event platform.

    \item Built Campus Lead Dashboard with task submission, review, resubmission, TAT, scoring, wallet, rewards, leaderboard, independent task workflows, and bulk assignment.

    \item Implemented Event Queries, Past Events, Winners Showcase, voting validation, hobby/category filtering with Redis caching, and travel features including social verification and participant management.

    \item Integrated Razorpay payments, dynamic coupons, digital receipts, Google OAuth, JWT refresh, public APIs, admin fixes, and profile/reels management.

\end{itemize}

\vspace{1pt}

\textbf{\textcolor{primary}{Frontend Developer Intern --- Code Alpha}}
\hfill
\textbf{Sep 2025 -- Oct 2025}

\textit{\textcolor{gray}{Remote}}

\begin{itemize}

    \item Developed responsive interfaces and applications using HTML, CSS, and JavaScript, including a calculator, music player, and image gallery.

\end{itemize}

% =========================================================
% LEADERSHIP
% =========================================================

\section*{\faUsers\quad Leadership}

\begin{itemize}

    \item Member, Value Education Cell, AKGEC --- coordinated with team members and supported event management.

\end{itemize}

% =========================================================
% CERTIFICATIONS
% =========================================================

\section*{\faTrophy\quad Certifications}

\begin{itemize}

    \item \textcolor{secondary}{\faFlag}\quad
    CyberGeek'26 Capture The Flag (CTF) Competition Participation Certificate --- GeekHaven, IIIT Allahabad.

    \item \textcolor{accent}{\faCertificate}\quad
    Machine Learning Certification --- Infosys.

\end{itemize}

% =========================================================
% EDUCATION
% =========================================================

\section*{\faGraduationCap\quad Education}

\textbf{\textcolor{primary}{Ajay Kumar Garg Engineering College Ghaziabad}}

\vspace{1pt}

B.Tech in Computer Science
\hfill
\textbf{\textcolor{accent}{CGPA: 7.75 \quad 2023 -- 2027}}

% =========================================================

\end{document}
