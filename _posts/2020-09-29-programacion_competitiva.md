---
title: 'Programación Competitiva'
date: 2020-09-29
permalink: /posts/2020_programacion_competitiva
tags:
  - programming
  - personal
  - spanish
---

Este es mi primer post y decidi escribirlo en español y hablar acerca de Programación, en especifico de la Programación Competitiva (_Competitive Programming_). Programación puede ser una de las actividades mas desafiantes y divertidas en la vida de un estudiante de Ciencia de la Computación (_Computer Science_). 


<!--
Every person who has studied or is studying a Computer Science career or a similar one has to program. Since our first year at university, programming is one of the most important skills which we must improve on. 

Let's define programming as the ability to solve a problem efficiently, and express this solution in some programming language. We mustn't consider that write code is programming. Programming includes other important skill that is problem-solving. The only way to improve these skills is by programming!

Competitive programming is one of the best activities you can do to practice and get better. In this article, I'm going to give a tour of competitive programming and its potential importance for your career.

\begin{figure}[!htb]
    \centering
    \includegraphics[width=\linewidth]{icpc_2019_1.png}
    \includegraphics[width=\linewidth]{icpc_2019_2.jpg}
    \caption{Porto ICPC World Finals 2019 (\myurl{icpc2019.up.pt}).}
    \label{fig:icpc}
\end{figure}

The International Collegiate Programming Contest (ICPC) is the principal motivation for computer science students in the world to compete, solve problems and write code (see Figure \ref{fig:icpc}). 

\textit{"The International Collegiate Programming Contest is an algorithmic programming contest for college students. Teams of three, representing their university, work to solve the most real-world problems, fostering collaboration, creativity, innovation, and the ability to perform under pressure. Through training and competition, teams challenge each other to raise the bar on the possible. Quite simply, it is the oldest, largest, and most prestigious programming contest in the world."\footnote{From: \myurl{icpc.baylor.edu}}}

Do you want to take part in this event? Why should you participate in the ICPC or similar ones? Are you a good programmer? How to start? Let's start talking about the problem statement structure. Every problem statement has a description, an input format, and an output format. Figure \ref{fig:icpc2018} shows a problem statement from the ICPC World Finals 2018.

\begin{figure}[!htb]
    \centering
    \includegraphics[width=\linewidth]{icpc2018.pdf}
    \caption{ICPC World Finals 2018 Problem J}
    \label{fig:icpc2018}
\end{figure}

You have to understand the problem description and design an efficient solution to solve the problem. The problem also has a time limit, usually 1 to 3 seconds, to run your code and give the correct output. So, understanding the problem includes the algorithmic complexity analysis of your solution. You have to take care of the problem size and ensure that your code runs in the time limit. 

Besides solving the problem, you need to take care of your code implementation and the correct format for reading the input and writing the output. Here I can refer you to the Competitive Programming 3 book, where you can find out excellent guidelines to start training, which includes topics like I/O, data structures, graphs, greedy, geometry, strings, dynamic programming, number theory among others. Many of these topics you have studied in courses of programming, discrete mathematics, and analysis and design of algorithms. But, here you can put on the theory in practice solving challenging problems that prepare you for your professional career.

The last step is to test your solution. The problem statement presents some test cases inputs and the respective output that your solution and code should give. You must prepare more test cases to ensure that you have solved the problem. These other test cases could be the worse input (problem limits), the minimum input values, or some tricky ones that could make your code/algorithm fail. An important task in software development is to prepare test cases for your code. So, solving contest problems train you for your future as a software developer.

\paragraph{Why does competitive programming prepare you for the future?}
Every day we meet with technology e-mail, social networks, video-games, apps in our cellphones, self-driven cars, there are programmers behind this software who have to face some problem that includes many sub-problems and write computer code. 

The development of artificial intelligence, more powerful processors, 3D scan, printers, sensors and displays, the promise of quantum computing, are open doors for excellent researchers and software developers who will face new challenge problems that could change the world. 

\begin{figure}[!htb]
    \centering
    \includegraphics[width=\linewidth]{style_gan.jpeg}
    \caption{From \textit{"A Style-Based Generator Architecture for Generative Adversarial Networks"} (\myurl{arxiv.org/abs/1812.04948}).}
    \label{fig:style_gan}
\end{figure}

Researching in computer science is ever discovering and creating new technology, facing problems that require an excellent background in computer science and good programming skills. You could create tools and frameworks that other programmers will use in the future. Deep learning is a good example. A machine can recognize images with less error than humans, in object and human recognition, even in medical applications like brain-tumor detection. You will not be able to differentiate a real face from a computer-generated one (see Figure \ref{fig:style_gan}). Just for mention a few potential applications.

Big companies like Google, Facebook, Amazon, Pixar, Nvidia, Intel, and start-ups, whose principal component is the software and understand the importance of software development, look for programmers with excellent programming (solving-problem) skills and a background in programming contests. Because solving a problem includes the process of abstraction, analysis, design, implementation, and testing. 

An interview for a job there, measure your ability to solve problems, it's like a competitive programming problem, where you have to explain your solution and the algorithmic complexity analysis, using all your knowledge about algorithms, data structures, the theory of computation, compilers, programming languages, discrete mathematics, software engineering, maths among other topics. You can easily prepare for a work there solving competitive programming problems.

\begin{figure}[!htb]
    \centering
        \includegraphics[width=\linewidth]{google.png}
    \caption{Google's Coding Competitions (\myurl{codingcompetitions.withgoogle.com}).}
    \label{fig:google}
\end{figure}

Google organizes yearly tree important coding competitions to motivate programmers to compete and solve challenge problems. Also, Google looks for new software developers in these events. Figure \ref{fig:google} shows a screenshot and the web page where you can find more information and register for these competitions. Facebook has a similar event called Facebook Hacker Cup. 

\paragraph{How to start?}
I have already mentioned the book
\textit{"Competitive Programming 3: The New Lower Bound of Programming Contests"} (\myurl{cpbook.net}) written by Steven Halim and Felix Halim, where you'll find an excellent guide to start and the minimum topics that you need to master to compete in any programming contests. Each chapter presents a set of exercises and problems taken from UVa (\myurl{uva.onlinejudge.org}) and integrated with uHunt (\myurl{uhunt.onlinejudge.org}) where you can track your progress and stats (see Figure \ref{fig:uhunt}). 

\begin{figure}[!htb]
    \centering
        \includegraphics[width=\linewidth]{uhunt.png}
    \caption{\myurl{uhunt.onlinejudge.org}}
    \label{fig:uhunt}
\end{figure}

Another similar and recent book is \textit{"Guide to Competitive Programming, Learning and Improving Algorithms Through Contests"}\footnote{\myurl{www.springerprofessional.de/en/guide-to-competitive-programming/15339090}} whose author is Antti Laaksonen. Also, there is a website \myurl{cp-algorithms.com} that describe a set of topics and algorithms that will help you to start solving problems.

Some online judges to start solving problems and having fun. ICPC Live Archive (\myurl{icpcarchive.ecs.baylor.edu}) and ICPC Kattis (\myurl{icpc.kattis.com}) are online judges where you can find the ICPC regionals and finals problems. Kattis include the lastest ICPC problems.  URI (\myurl{urionlinejudge.com.br}), Kattis (\myurl{open.kattis.com}), SPOJ (\myurl{spoj.com}) and UVa (\myurl{uva.onlinejudge.org}) have an archive of hundreds of problems from different sources like ICPC problems and other similar ones from other contests. Codeforces (\myurl{codeforces.com}), CodeChef (\myurl{codechef.com}) and Topcoder (\myurl{topcoder.com}) are different from the others because they organized several rounds monthly with new problems; you can compete and improve your skills in real-time contests. Finally, A2OJ (\myurl{a2oj.com}) allows you to create a contest with problems from different judges.

Now, you can start solving problems and getting better in programming. Don't forget to share what you are learning. The best way to learn and improve your skills is by teaching. Because if you understand something you can teach it, else you need to study more.

-->

