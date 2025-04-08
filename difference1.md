{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;\f2\fnil\fcharset0 STIXTwoMath-Regular;
\f3\fmodern\fcharset0 Courier;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sa321\partightenfactor0

\f0\b\fs48 \cf0 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Mathematical Introduction to Difference Equations\
\pard\pardeftab720\sa298\partightenfactor0

\fs36 \cf0 What are Difference Equations?\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Difference equations describe the evolution of variables over discrete intervals. They're fundamental for modeling discrete dynamical systems where the state of a system at a particular time depends on its state at previous discrete time points.\
A general 
\f0\b first-order difference equation
\f1\b0  takes the form:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
f\
(\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 ,\
n\
)\
,\
\
n\
=\
0\
,\
1\
,\
2\
,\
\'85\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x_\{n+1\} = f(x_n, n), \\quad n = 0, 1, 2, \\dots\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 If the function does not explicitly depend on time (
\f2 \
\pard\pardeftab720\partightenfactor0
\cf0 n\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 n\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 ), the equation simplifies to:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
f\
(\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 )\
.\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x_\{n+1\} = f(x_n).\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 First Order Equations: Stability and Equilibria\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Consider the simple linear first-order difference equation:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
a\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 +\
b\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x_\{n+1\} = a x_n + b\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Equilibrium Points\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 An equilibrium (steady-state solution) occurs when:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8727 \
\pard\pardeftab720\partightenfactor0

\f1\fs24 \cf0 x_\{n+1\} = x_n = x^*\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 Solving for the equilibrium:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8727 \
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
a\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8727 \
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 +\
b\
\
\uc0\u8658 \
\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8727 \
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
b\
1\
\uc0\u8722 \
a\
,\
\
provided\'a0\
a\
\uc0\u8800 \
1.\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x^* = a x^* + b \\quad \\Rightarrow \\quad x^* = \\frac\{b\}\{1 - a\}, \\quad \\text\{provided \} a \\neq 1.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Stability\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Stability of the equilibrium is determined by the magnitude of the derivative
\f2 \
\pard\pardeftab720\partightenfactor0
\cf0 \uc0\u8739 \
f\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8242 \
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 (\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 \uc0\u8727 \
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 )\
\uc0\u8739 \
\pard\pardeftab720\partightenfactor0

\f1 \cf0 |f'(x^*)|\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 :\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 If 
\f2 \uc0\u8739 \u8232 f\u8232 
\fs18 \uc0\u8242 \u8232 
\fs24 \uc0\u8232 (\u8232 x\u8232 
\fs18 \uc0\u8727 \u8232 
\fs24 \uc0\u8232 )\u8232 \u8739 \u8232 <\u8232 1\u8232 \u8232 
\f1 |f'(x^*)| < 1\uc0\u8232 
\f2 \uc0\u8232 
\f1 , the equilibrium is 
\f0\b stable
\f1\b0 .\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 If 
\f2 \uc0\u8739 \u8232 f\u8232 
\fs18 \uc0\u8242 \u8232 
\fs24 \uc0\u8232 (\u8232 x\u8232 
\fs18 \uc0\u8727 \u8232 
\fs24 \uc0\u8232 )\u8232 \u8739 \u8232 >\u8232 1\u8232 \u8232 
\f1 |f'(x^*)| > 1\uc0\u8232 
\f2 \uc0\u8232 
\f1 , the equilibrium is 
\f0\b unstable
\f1\b0 .\
\pard\pardeftab720\sa319\partightenfactor0

\f0\b \cf0 Example:\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0 \cf0 For
\f2 \
\pard\pardeftab720\partightenfactor0
\cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
0.5\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 +\
1\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x_\{n+1\} = 0.5 x_n + 1\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 :\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls2\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Equilibrium: 
\f2 x\uc0\u8232 
\fs18 \uc0\u8727 \u8232 
\fs24 \uc0\u8232 =\u8232 1\u8232 1\u8232 \u8722 \u8232 0.5\u8232 \u8232 \u8232 =\u8232 2\u8232 \u8232 
\f1 x^* = \\frac\{1\}\{1 - 0.5\} = 2\uc0\u8232 
\f2 \uc0\u8232 
\f1 .\
\ls2\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Stability: Since 
\f2 \uc0\u8739 \u8232 0.5\u8232 \u8739 \u8232 <\u8232 1\u8232 \u8232 
\f1 |0.5| < 1\uc0\u8232 
\f2 \uc0\u8232 
\f1 , the equilibrium is stable.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Python Example:\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 import matplotlib.pyplot as plt\
\
# parameters\
a, b = 0.5, 1\
\
# initial value\
x = [10]\
\
# iterate\
timesteps = 20\
for n in range(timesteps):\
    x.append(a * x[-1] + b)\
\
# plot\
plt.plot(range(timesteps + 1), x, marker='o')\
plt.xlabel('Time (n)')\
plt.ylabel('x_n')\
plt.title('Stable First Order Difference Equation')\
plt.grid()\
plt.show()\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Attractors\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 An 
\f0\b attractor
\f1\b0  is a set towards which a system evolves over time. Equilibrium points are examples of attractors. Systems may also exhibit 
\f0\b periodic attractors
\f1\b0  or 
\f0\b chaotic attractors
\f1\b0 .\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Bifurcation\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 A 
\f0\b bifurcation
\f1\b0  is a qualitative change in system behavior as parameters vary. Consider the logistic map:\
\pard\pardeftab720\partightenfactor0

\f2 \cf0 x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
+\
1\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 =\
r\
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 (\
1\
\uc0\u8722 \
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 )\
,\
\
0\
\uc0\u8804 \
x\
\pard\pardeftab720\partightenfactor0

\fs18 \cf0 n\
\pard\pardeftab720\partightenfactor0

\fs24 \cf0 \uc0\u8804 \
1\
,\
\
0\
\uc0\u8804 \
r\
\uc0\u8804 \
4\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 x_\{n+1\} = r x_n (1 - x_n), \\quad 0 \\leq x_n \\leq 1, \\quad 0 \\leq r \\leq 4\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 As
\f2 \
\pard\pardeftab720\partightenfactor0
\cf0 r\
\pard\pardeftab720\partightenfactor0

\f1 \cf0 r\
\pard\pardeftab720\sa240\partightenfactor0
\cf0 increases, the system undergoes a series of bifurcations:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls3\ilvl0\cf0 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 For 
\f2 0\uc0\u8232 <\u8232 r\u8232 <\u8232 3\u8232 \u8232 
\f1 0 < r < 3\uc0\u8232 
\f2 \uc0\u8232 
\f1 , the equilibrium is stable.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 At 
\f2 r\uc0\u8232 \u8776 \u8232 3\u8232 \u8232 
\f1 r \\approx 3\uc0\u8232 
\f2 \uc0\u8232 
\f1 , period doubling occurs, leading to periodic attractors.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 For larger 
\f2 r\uc0\u8232 \u8232 
\f1 r\uc0\u8232 
\f2 \uc0\u8232 
\f1 , further bifurcations lead to chaotic behavior.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Python Example (Logistic Bifurcation Diagram):\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 import numpy as np\
import matplotlib.pyplot as plt\
\
r_values = np.linspace(2.5, 4.0, 500)\
x = 0.5\
iterations = 1000\
last = 100\
\
plt.figure(figsize=(10,6))\
for r in r_values:\
    x_iter = x\
    for i in range(iterations - last):\
        x_iter = r * x_iter * (1 - x_iter)\
    x_vals = []\
    for i in range(last):\
        x_iter = r * x_iter * (1 - x_iter)\
        x_vals.append(x_iter)\
    plt.plot([r]*last, x_vals, ',k', alpha=0.25)\
\
plt.title('Logistic Map Bifurcation Diagram')\
plt.xlabel('Parameter r')\
plt.ylabel('Equilibrium Points')\
plt.grid()\
plt.show()\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Chaos\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Chaos occurs when a system exhibits sensitive dependence on initial conditions, meaning small differences in initial conditions yield vastly different outcomes over time.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Practical Example of Chaos:\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Weather systems are a common practical example of chaos. Tiny variations in conditions ("butterfly effect") lead to large and unpredictable variations in weather patterns.\
\pard\pardeftab720\sa280\partightenfactor0

\f0\b\fs28 \cf0 Python Demonstration (Chaos and Sensitivity):\
\pard\pardeftab720\partightenfactor0

\f3\b0\fs26 \cf0 r = 3.9\
x1, x2 = 0.5, 0.5001\
iterations = 30\
\
trajectory1, trajectory2 = [x1], [x2]\
for _ in range(iterations):\
    x1 = r * x1 * (1 - x1)\
    x2 = r * x2 * (1 - x2)\
    trajectory1.append(x1)\
    trajectory2.append(x2)\
\
plt.plot(trajectory1, label='Initial = 0.5')\
plt.plot(trajectory2, label='Initial = 0.5001')\
plt.xlabel('Time Step')\
plt.ylabel('$x_n$')\
plt.title('Sensitivity to Initial Conditions (Chaos)')\
plt.legend()\
plt.grid()\
plt.show()\
\pard\pardeftab720\sa298\partightenfactor0

\f0\b\fs36 \cf0 Conclusion\
\pard\pardeftab720\sa240\partightenfactor0

\f1\b0\fs24 \cf0 Difference equations serve as powerful tools in modeling discrete dynamic systems, from population biology and finance to climatology. Understanding stability, attractors, bifurcation, and chaos provides valuable insights into the dynamic behavior of complex systems.\
}