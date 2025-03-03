java c
Advanced Concrete Performance ENG5224
2024/2025
Coursework 1Assigned:      Monday 3rd February 2025Due:   Thursday, 3rd March, 13:00, 2025 Submission via Moodle PageText:   Lecture notes, ATENA Tutorial, ExercisesObjectives:   Understanding of the numerical analysis of the nonlinear behaviour of reinforced concrete structuresWeight:   25% of overall grade of Advanced Concrete Performance ENG5224
Adopting a two-dimensional plane stress idealisation, use ATENA2D to analyse the short term behaviour of the reinforced concrete beam. See page 7 for the geometry and properties of the beam. This beam is similar to the one used in the ATENA2D software tutorial. However, the dimensions of the beam depend on your student number.
Investigate one failure mode.    Which failure mode you investigate depends on the last digit of your student number. If it is odd, then you must investigate failure model 1. If it is even, then you must investigate failure mode 2. For instance, if your student number is 7654321, the last digit is 1, which is odd which means that with this student number you must use failure mode 1.
For your failure mode, you should then investigate one set of parameters.
You have to adjust the reinforcement area As   to obtain your failure mode. If required, you can add shear reinforcement in the form. of vertical stirrups to the beam as well.
Failure modes:
Failure mode 1: Bending failure of an under-reinforced beam
Failure mode 2: Bending failure of an over-reinforced beam
If you are not sure how these failure modes are defined, have a look at the information provided at the beginning of the lectures.
Set of parameters:
1)
l   Compressive strength of concrete
l   Shear retention (part of fixed crack model. See the theory manual of ATENA2D)
l   Solution scheme (displacement, load and arclength control (check manual for input parameters))
2)
l   Fracture energy of concrete
l   Bond-slip of reinforcement (perfect bond, bond slip). Hint: Make sure that symmetry conditions are enforced for the reinforcement if slip is activated.
l   Mesh size
3)
l   Size of the load steps
l   Tensile strength of concrete
l   Compressive strength of concrete
For these investigations, choose first a base configuration of input parameters. It is suggested that you start with the tutorial input parameters and change, if required, the reinforcement amount and arrangement (you might need to add reinforcement), so that you obtain the failure mode that you want to investigate. Define this then as your base configuration. Next, change only one parameter at a time, so that you can be sure that the change in structural response that you obtain is due to the parameter that you would like to investigate. This sounds easier than it is done. As an example, imagine that you would like to change the compressive strength. In the tutorial, the cube compressive strength is used to calculate all concrete material parameters, including fracture energy, Young’s modulus and tensile strength. By changing this cube compressive strength value, all these parameters would change. This would not be desirable, since it would not be clear that the observed changes are due to the changes of the compressive strength or one of the other parameters. Therefore, it would be better to change only the compressive strength and leave the other parameters unchanged.
Also, it is suggested to vary the parameters strongly so that you can see a clear influence on the load displacement curves. For instance, an increase of the fracture energy by 5% compared to the base value will most likely only have a very slight influence on the load-displa代 写Advanced Concrete Performance ENG5224 2024/2025 Coursework 1Python
代做程序编程语言cement curve. In this case, it would be better to use 50% increase. Obtain the response for at least three different values of a parameter, so that you can observe a trend.
Study the influence of the parameters on the global response of your structure in the form. of load-displacement curves. Explain the trends that you observe by looking at local results, such as contour plots of stresses or strains, deformed shapes, crack patterns, etc. Not all of these local results might be meaningful for your failure mode. It very much depends on your parameters and failure mode which of the local results are most suitable to look at. Remember that for reinforced concrete structures at the ultimate limit state, the important parameters are maximum load, displacement at maximum load and ductility.
Compare your finite element results for the base configuration only   for your failure mode with the capacity calculated for your failure mode according to a Concrete Design Code of your choice (hand calculations). Results of finite element analysis and hand calculation might differ a lot. This is not a problem. However, if possible, understand why this is the case. Is it a shortcoming of the method used in the design code or a limitation of the finite element program?

Report
Each student has to produce one report (one report per student). The report must be submitted online (Moodle) as a pdf-file.   This report should summarise the analyses and include observations and conclusions regarding the influence of the above parameters.
Important: The maximum length of the entire report is calculated as 10 pages (inclusive all appendices), Times New Roman, 12pt with at least 2cm margins.The report should contain the following minimum contents:1) Cover sheet with the name and matriculation. (not part of the 10 page limit)2) A short description of models and idealisations used to solve it should be provided. Make sure that you provide enough information so that someone else could reproduce your results. The results of the base configuration should be compared to the hand calculation. Description of the analyses carried out. Presentation of the influence of the parameters on the load-displacement curves. Comparison of hand calculations with finite element results (only for the base configuration of the failure mode). Discussion of trends observed in load-displacement curves and presentation of more detailed results, such as deformation patterns and contour plots (if relevant), to explain these trends. The discussion based on local results is very important.3) Conclusions clearly stating the trends observed.
4) References (if required)
Marking
The marking will consider in equal weights the presentation of the results and the understanding.
Concerning the presentation, aim for the following:    
·   Arguments are well presented
·   Major findings are clear and easily accessible
·   The writing is accurate
·   Good English
·   All references to figures and equations are correct
·   Enough information is provided to allow others to reproduce your results
Concerning the understanding, provide sufficient discussion to show that you have understood the underlying models/theory, which give you the presented results.

Please note that standard penalties for late submission apply:
Reduction of two subgrades (e.g. B1 to B3) for each working day late, up to a maximum of 5 days.
Zero mark if more than 5 days late.
It is essential that you still submit any late coursework, even if you are going to get zero marks for it (otherwise you cannot obtain any credits for this course).
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
