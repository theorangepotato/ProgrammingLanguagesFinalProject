# MATLAB, What Is It Good For?

*Written by: Austin Bohannon, Megan Walley, Donner Hanson, and Allison Thompson*

## Introduction
We chose MATLAB as a language to research and present because of its useability in Mathematics and Engineering related fields. It also has great features of auto-generating reliable C/C++ style code from MATLAB code which can increase the speed of the programs being used.

## History of MATLAB
MATLAB began as a mix of two mathematical packages written in Fortran and accessed with/at the terminal and has turned into a proper, larger program that uses multiple interfaces for scripting and graphical displays, dozens of different libraries, and allows for highly technical details. MATLAB’s primary creator is Cleve Moler, a man who still works on it today [3](https://en.wikipedia.org/wiki/MATLAB). However, over the last sixty years of MATLAB’s development, the program has been influenced by many people.\
\
Some of the early influencers and algorithm creators came from Moler’s early days, back when he was still a student at CalTech. He was taught by John Todd, one of the researchers and developers of the United States’ first computers: The Standards Western Automatic Computer (SWAC) [4](https://www.mathworks.com/company/newsletters/articles/the-origins-of-matlab.html). John Todd introduced Moler to mathematician George Forsythe at Stanford during Moler’s graduate years, another man who worked on the SWAC. With Forsythe, Moler worked to create a math book on matrix computations [5](https://www.mathworks.com/company/newsletters/articles/matlab-incorporates-lapack.html). In the book, algorithms were written using Fortran (and lesser known languages, like Algol and PL/l).\
\
Two decently large programs in Fortran were created in the 1970s: EISPACK and LINPACK. EISPACK was a software library that contained methods for matrices [2](http://history.siam.org/oralhistories/dongarra.htm). LINPACK was a software library that contained methods for linear algebra [1](http://www.netlib.org/linpack/)[2](http://history.siam.org/oralhistories/dongarra.htm). Both libraries were worked on by similar groups of men, Moler being one of them. Moler, now a math professor at University of New Mexico, wanted to allow his students to use and play around with the software, but encountered some difficulty: Not all students wanted to learn Fortran. To make using these libraries and algorithms simpler and more interactive, Moler began development on MATLAB. It was designed to simplify the compile, run and debug loop and provide easy inputs and outputs that were more identifiable. MATLAB included portions of both EISPACK and LINPACK and utilized Fortran: Initially, there were only eighty functions and one data type – a matrix [4](https://www.mathworks.com/company/newsletters/articles/the-origins-of-matlab.html). It was portable and almost any computer at the time could compile it, making MATLAB fairly user friendly for the time.\
\
When Moler taught a class at Stanford for a little bit, he tried to incorporate MATLAB but the math and computer science students were not impressed. On the other hand, engineering students were impressed. (This juxtaposition continues on today, with MATLAB being used heavily in the engineering industry but not as much in the computer science world.) Not content with being stagnant and having MATLAB limited in its capabilities, Jack Little, a Stanford alumni who saw one of Moler’s lectures, decided that MATLAB would be perfect for technical computing [3](https://en.wikipedia.org/wiki/MATLAB). Little and one of his work colleagues, Steve Bangert, worked with Cleve Moler to reprogram MATLAB in C, add additional tools (such as “M-files” – a way for users to store programs), graphic resources, and libraries in order to expand the program and make it applicable on the newer IBM computers that were being developed in the early 1980s [4](https://www.mathworks.com/company/newsletters/articles/the-origins-of-matlab.html)[5](https://www.mathworks.com/company/newsletters/articles/matlab-incorporates-lapack.html). The official version of MATLAB for the PC was released in December of 1984 at an IEEE conference.

## Who Uses It
![Imgur](https://imgur.com/h0rR0we.png)\
MATLAB is widely used as an applied tool for engineering, research, and academia. Companies that use MATLAB include and the typical job titles are: [8]\
\
Boeing - Networking Engineer\
MathWorks - Product Engineer - Code Gen & Verification\
MathWorks - Software Engineer in Test - MATLAB Settings and Serialization\
Amtec Inc. - Controls Engineer - MATLAB/Simulink\
Odyssey Consulting Services - Modeling and Simulation Programmer - Unmanned Air Traffic Control Simulation Programming\
TMC Technologies - Electrical Engineer with MATLAB experience\
Fiat Chrysler Automobiles - Senior Model-Based Tools Engineer\
Sparksoft - Data Scientist\
GDKN - Embedded Software Designer\
Parsons - Missile Modeling and Simulation Engineer I\
\
![Imgur](https://imgur.com/r8SeWmd.png)\
Computer software firms account for 10% of all MATLAB licenses while academia accounts for 7% of all MATLAB licenses.[7]
![Imgur](https://imgur.com/EaoFNSf.png)\
Industry data shows that what type of companies are using MATLAB and how many companies have licenses for MATLAB use:[7]\
\
Computer Software: 3394\
Higher Education: 2295\
Computer Hardware: 1622\
Staffing and Recruiting: 1419\
Information and Technology and Services: 1375\
Financial Services: 955\
Hospital and Healthcare: 931\
Aviation and Aerospace: 775\
Education Management: 754\
Medical Devices: 745\
![Imgur](https://i.imgur.com/X6Wz8Ki.png)\
Based by country the United States is the leading user of MATLAB. 16,000+ licenses are within the US, followed by 2,400+ licenses in the UK.[7]\
![Imgur](https://i.imgur.com/q7cXR8M.png)\
![Imgur](https://i.imgur.com/bBcnClo.png)\
By country and amount of companies with a MATLAB license[7]:\
\
United States : 16029\
United Kingdom : 2409\
India : 2182\
Canada : 1290\
France : 1042\
Germany : 866\
Italy : 593\
Netherlands : 543\
Spain : 491\
Australia : 45\
\
By staff size of company (employee amount) and amount of companies with a MATLAB license[7]:\
![Imgur](https://i.imgur.com/ojfmjx8.png)\
10-50 Employees 6967\
50-200 Employees 5635\
1000-5000 Employees 3573\
200-500 Employees 3057\
1-10 Employees 2253\
500-1000 Employees 2059\
\>10000 Employees 1849\
5000-10000 Employees 992\
![Imgur](https://i.imgur.com/Mx98515.png)\
A majority of the companies (~58% of the companies) that use MATLAB generate less than $50 million dollars per year.
![Imgur](https://i.imgur.com/zTHHcch.png)\
##### Case Study of MATLAB in use at Boeing:
MathWorks in tandem with Boeing created the guidance, navigation, control systems necessary for the X-40A reusable space vehicle. The vehicle needed to land on a runway and come to a full stop without a pilot controlling the vehicle.\
In order to develop the vehicle there needed to be models and simulations of the vehicle prior to actual physical testing. In order for the vehicle to be approved for physical testing the teams had to model the simulation to account for “avionics, sensors, actuators, and controllers and validating the software development metrics and processes {of the vehicle}. ”[9]\
The result of using MATLAB in the project was that the product was modelled on time and within budget, was successful on first test flight and landing, and allowed Boeing to continue contracts for unmanned flying machines.[9]\
![Imgur](https://i.imgur.com/Ex5mcXM.png)\
MATLAB can also be used in an academic setting as a teaching tool. In 2008, at the Hellenic Air Force Academy in Greece, an instructor created a MATLAB generated e-assesment GUI that would give students feedback on circuit models and on the performance of their work. If the student was satisfied with the result they could turn in the work. The students were given  a circuit diagram of a simple Common-Emitter (CE) transistor amplifier. The student would perform the following:
* Choose Base, Emitter and Collector resistors so that the amplifier gain is 100. 
* Calculate capacitor values so that the -3dB frequency of the circuit is 20 Hz.
* Calculate the currents at the Base, Emitter and Collector.

The instructor designed an application which would have a student GUI and a teacher GUI.\
“The student GUI prompts for the evaluated values and produces a Bode plot for assisting the student to verify his/her design before submitting the answer. This tool gives also the possibility of learning by using the trial-and-error approach.”  To prevent students from guessing values associated with the project, the instructor built in a “current-results” tab in the instructors side of the GUI so they could monitor the students progress.\
![Imgur](https://i.imgur.com/W89m251.png)\
##### Student GUI
The instructor’s GUI offers a “batch mode” in which an excel file can be generated in order for the instructor to track progress and results of the students in the class.\
![Imgur](https://i.imgur.com/2SbHhBl.png)\
##### Instructor “Batch Mode” MATLAB generated Excel Sheet
The benefits of designing an application like this two-part GUI for academic excellence is quite obvious.



## Where it is Used
MATLAB is used in a variety of cases. Its most frequent use is in image, data processing, and graphical representation of data in various applications including the following categories:\ 

Embedded Systems\
Control Systems\
Digital Signal Processing\
MATLAB can be used to easily implement programs that can read, and adjust audio signals. This is useful in audio engineering where you may want to create a custom sound algorithm to compress or splice audio with ease.

Wireless Communications\
MATLAB can be used to model Radio Frequency systems to 

(https://www.educba.com/uses-of-matlab/)

Linear Algebra\
Specifically Matlab shines when having to vectorize data through matrices using Linear Algebra. "Linear algebra functions in MATLAB provide fast, numerically robust matrix calculations. Capabilities include a variety of matrix factorizations, linear equation solving, computation of eigenvalues or singular values, and more."\
(https://www.mathworks.com/help/matlab/linear-algebra.html)

MATLAB contains functions, such as mldivide, for linear algebra. mldivide is simply called using the syntax:\
Input:\
A = sparse([0 2 0 1 0; 4 -1 -1 0 0; 0 0 0 3 -6; -2 0 0 0 2; 0 0 4 2 0]);\
B = sparse([8; -1; -18; 8; 20]);\
x = A\B

Output:\
x = \
   (1,1)       1.0000\
   (2,1)       2.0000\
   (3,1)       3.0000\
   (4,1)       4.0000\
   (5,1)       5.0000\

Embedded Systems\
In embedded systems MATLAB can be used in conjunction with built in code generators (from out of the box) or with third party libraries to generate C/C++ code for optimal embedded systems code. Some examples of embedded systems are washing machines, printers, automobiles, cameras, industrial machines, etc. \
(https://www.educba.com/uses-of-matlab/)

## Interesting Features

---

## Sources
