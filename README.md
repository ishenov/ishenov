\documentclass[letterpaper,11pt]{article}

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
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
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

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

\begin{center}
    \textbf{\Huge \scshape Ishenov Baktiyar} \\ \vspace{1pt}
    \small +996 501 100-911 $|$ \href{mailto:ienof911@gmail.com}{\underline{ienof911@gmail.com}} $|$ 
    \href{https://linkedin.com/in/...}{\underline{linkedin.com/in/ishenow}} $|$
    \href{https://github.com/...}{\underline{github.com/ishenov}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Attractor School}{Bishkek, Kyrgyzstan}
      {JavaScript, ReactJS}{May. 2019 -- Aug 2020}
    \resumeSubheading
      {Polytechnic College}{Bishkek, Kyrgyzstan}
      {}{Sep. 2016 -- June 2019}
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Frontend developer}{Aug 2021 -- Present}
      {Webxloo LLC}{Ukraine, Remote work}
      \resumeItemListStart
        \resumeItem{Web Development: Developed and maintained auction websites using Vue.js and jQuery.}
        \resumeItem{Code Reviews: Conducted code reviews to maintain high code quality and shared best practices with the team.}
        \resumeItem{Team Collaboration: Worked closely with cross-functional teams including backend developers, designers, and project managers.}
        \resumeItem{Legacy Code Maintenance: Worked extensively with legacy code, conducting thorough reviews and refactoring to improve performance, readability, and maintainability.}
      \resumeItemListEnd

    \resumeSubheading
      {Frontend developer}{May 2020 -- Aug. 2021}
      {Devforge Studio}{Bishkek, Kyrgyzstan}
      \resumeItemListStart
        \resumeItem{Web Applications: Developed and maintained projects using Vue.js.}
        \resumeItem{API Integration: Created and integrated REST APIs with Node.js.}
        \resumeItem{Team Collaboration: Worked with designers, developers, and project managers.}
    \resumeItemListEnd

  \resumeSubHeadingListEnd


%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{HTML, CSS, SASS, SCSS} \\
     \textbf{JavaScript, jQuery, Ajax, Bootstrap} \\
     \textbf{Vue.js + Vuex} \\
     \textbf{React + Redux} \\
     \textbf{Node.js + NestJS, express} \\
     \textbf{MongoDB + Mongoose, MySQL} \\
     \textbf{REST API} \\
     \textbf{Git}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}
