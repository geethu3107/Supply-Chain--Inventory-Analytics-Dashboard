%-------------------------
% Resume in Latex
% Author : Geethu G
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{fontawesome5}
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
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}

%----------PAGE STYLE----------
\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

%----------MARGINS----------
\addtolength{\oddsidemargin}{-0.4in}
\addtolength{\evensidemargin}{-0.4in}
\addtolength{\textwidth}{0.8in}
\addtolength{\topmargin}{-0.45in}
\addtolength{\textheight}{0.95in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

%----------SECTION HEADINGS----------
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

%----------CUSTOM COMMANDS----------

\newcommand{\resumeItem}[1]{
  \item\small{{#1 \vspace{-1pt}}}
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
  \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
    \textbf{#1} & #2 \\
    \textit{\small#3} & \textit{\small #4} \\
  \end{tabular*}\vspace{-8pt}
}

\newcommand{\resumeSubSubheading}[2]{
  \item
  \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    \textit{\small#1} & \textit{\small #2} \\
  \end{tabular*}\vspace{-6pt}
}

\newcommand{\resumeProjectHeading}[2]{
  \item
  \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    \small#1 & #2 \\
  \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-3pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{
  \begin{itemize}[leftmargin=0.15in,label={}]
}

\newcommand{\resumeSubHeadingListEnd}{
  \end{itemize}
}

\newcommand{\resumeItemListStart}{
  \begin{itemize}[leftmargin=*,itemsep=0pt,topsep=0pt,parsep=0pt]
}

\newcommand{\resumeItemListEnd}{
  \end{itemize}\vspace{-6pt}
}

%-------------------------------------------
%%%%%% RESUME STARTS HERE %%%%%%%%%%%%%%%%%%%
%-------------------------------------------

\begin{document}

%----------HEADING----------

\begin{center}

{\fontsize{18}{20}\selectfont
\textbf{\scshape Geethu G}
}

\\[-1pt]

\textbf{\large Quality \& Operations Analytics}

\\[1pt]

\small
+91 9207114762 $|$
Palakkad, Kerala $|$
\href{mailto:geethuptb@gmail.com}{\underline{geethuptb@gmail.com}}
$|$
\href{https://www.linkedin.com/in/geethu-g12}{\underline{linkedin.com/in/geethu-g12}}
$|$
\href{https://github.com/geethu3107}{\underline{github.com/geethu3107}}

\end{center}

\vspace{-5mm}

%-----------PROFESSIONAL SUMMARY-----------

\section{Professional Summary}

\small
Analytical professional with hands-on experience in data validation, exception analysis, investigation, KPI reporting, and dashboard development using SQL, Python, Excel, and Power BI. Skilled in identifying data quality issues, analyzing operational patterns, and supporting process improvement through data-driven insights.
\normalsize

%-----------TECHNICAL SKILLS-----------

\section{Technical Skills}

\begin{itemize}[leftmargin=0.15in,label={}]
\small{\item{

\textbf{Quality \& Operations}: Exception Analysis, Data Validation, Investigation, Root Cause Analysis, Quality Checks, Process Improvement, KPI Reporting \\

\textbf{Data Analytics}: Data Cleaning, EDA, Trend Analysis, Statistical Analysis, Data Visualization \\

\textbf{Business Intelligence}: Power BI (DAX, Data Modeling, Power Query, KPI Cards, Drill-through), Tableau \\

\textbf{Programming \& Databases}: SQL, Python, MySQL, SQLite \\

\textbf{Microsoft Excel}: Advanced Excel, Pivot Tables, XLOOKUP, INDEX/MATCH, Pivot Charts, Power Query, Slicers \\

\textbf{Python Libraries}: Pandas, NumPy, Matplotlib \\

\textbf{Soft Skills}: Analytical Thinking, Attention to Detail, Problem Solving, Communication, Collaboration, Adaptability

}}
\end{itemize}

%-----------TECHNICAL PROJECTS-----------

\section{Technical Projects}

\resumeSubHeadingListStart

%-----------PROJECT 1-----------

\resumeProjectHeading
{
\textbf{Transportation Investigation Analysis}
\href{https://github.com/geethu3107/Transportation-Investigation-Analysis}
{\hspace{0.15em}\faGithub}
$|$ \emph{Python, Pandas, NumPy, Matplotlib}
}{}

\resumeItemListStart
\resumeItem{Analyzed 3.47M NYC Yellow Taxi transportation records to validate data quality, identify inconsistencies, and detect unusual trip, fare, passenger, and duration patterns requiring investigation.}
\resumeItem{Developed rule-based risk scoring and exception detection to classify records by severity and identify 35,181 investigation cases, including 2,181 speed and 33,100 high-fare exceptions.}
\resumeItem{Analyzed investigation cases across vendors, pickup hours, and locations to identify concentration patterns and support targeted investigation of transportation exceptions.}
\resumeItemListEnd

%-----------PROJECT 2-----------

\resumeProjectHeading
{
\textbf{Supply Chain Inventory Analytics Dashboard}
\href{https://github.com/geethu3107}{\hspace{0.15em}\faGithub}
$|$ \emph{Power BI, DAX, Excel}
}{}

\resumeItemListStart
\resumeItem{Developed a Power BI dashboard to monitor inventory levels, reorder thresholds, supplier quality, defect rates, and operational KPIs.}
\resumeItem{Created DAX measures and interactive visuals to identify stock exceptions, supplier quality patterns, and inventory risks.}
\resumeItem{Applied slicers and KPI reporting to support drill-down analysis across product categories and suppliers.}
\resumeItemListEnd

%-----------PROJECT 3-----------

\resumeProjectHeading
{
\textbf{Bank Customer Database Analysis}
\href{https://github.com/geethu3107/Bank-Customer-Data-Analysis-SQL}
{\hspace{0.15em}\faGithub}
$|$ \emph{SQL, SQLite}
}{}

\resumeItemListStart
\resumeItem{Designed and queried a relational banking database using SQLite for customer and loan data analysis.}
\resumeItem{Developed 20+ SQL queries using JOINs, GROUP BY, aggregate functions, and subqueries to extract and analyze customer data for business reporting.}
\resumeItem{Performed customer segmentation and loan portfolio analysis to identify trends and generate data-driven insights.}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------EDUCATION-----------

\section{Education}

\resumeSubHeadingListStart

\item
\textbf{M.Sc. Physics}, Central University of Kerala
\hfill 2023--2025 \textbf{ $|$ 79\%}

\vspace{-3pt}

\item
\textbf{B.Sc. Physics}, SNGS College Pattambi, Calicut University
\hfill 2020--2023 \textbf{ $|$ 82.6\%}

\resumeSubHeadingListEnd

%-----------CERTIFICATIONS-----------

\section{Certifications}

\resumeSubHeadingListStart

\item
\textbf{AI Integrated Data Analytics (In Progress)}, Entri Software Pvt Ltd
\hfill Expected: Nov 2026

\resumeItemListStart
\resumeItem{Developing skills in Excel, SQL, Power BI, Python, dashboard development, reporting, and data visualization.}
\resumeItemListEnd

\vspace{-4pt}

\item
\textbf{Data Analytics Job Simulation}, Deloitte Australia (Forage)
\hfill Aug 2026

\resumeItemListStart
\resumeItem{Completed a simulation using Tableau and Excel for data analysis, dashboard development, and visualization.}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------ACHIEVEMENTS-----------

\section{Achievements}

\resumeSubHeadingListStart
\resumeItemListStart
\resumeItem{Presented research papers at international conferences and national seminars, demonstrating strong research and technical communication.}
\resumeItem{Represented Kerala in South Zone cultural competitions and earned recognition at Kerala State Kalolsavam.}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-------------------------------------------
\end{document}
