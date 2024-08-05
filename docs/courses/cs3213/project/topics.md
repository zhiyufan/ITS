Developing such an Intelligent Tutoring System (ITS) includes many conceptual and technical challenges. We summarized some of them into projects, from which the students in CS3213 need to choose one as a group project. Please find below the project summaries as proposed for the students in CS3213 (NUS AY 2021/2022). We group projects by their provided functionalities. Each project has assigned estimated difficulty levels (Low, Medium, High) in the categories: coding (i.e., programming intensity), theoretical complexity (i.e., need for background study), amount of research involved (i.e., be innovative and create something new), and the involvement of HCI (Human-Computer Interaction) aspects.

*More details can be found in our [Assignment 0](../assignments/Assignment_0.pdf).*


## Topic 1 - Parsing

**Project 1.1** *C Parser*:
Develop a parser to transform C programs into a (provided) common data structure based on the control-flow graph (CFG). Additionally, provide a concretizer, which back-transforms the program in the internal common data structure to a C source file.<br>
&#8594; [Coding: High, Theory: Low, Research: -, HCI: -]

**Project 1.2** *Python Parser*:
Same as 1.1 for Python.<br>
&#8594; [Coding: High, Theory: Low, Research: -, HCI: -]


## Topic 2 – Aligning / Matching of Programs

**Project 2.1** *CFG-Based Alignment*:
Develop an automated alignment of the reference program and the submitted program based on the basic blocks of the programs’ control-flow graph (CFG) representation. This also includes the development of an automated mapping for the variables between the reference program and the submitted program.<br>
&#8594; [Coding: Medium, Theory: Medium, Research: Low, HCI: -]


## Topic 3 – Error Localization / Program Interpretation

**Project 3.1** *C Interpreter*: 
Develop an interpreter that allows to execute a C program with regard to the basic blocks in its CFG. Further, use the provided test cases to identify the root cause of the problem with regard to the basic blocks in the CFG. Implement an error localization that compares the execution traces of a reference program and the submitted program.<br>
&#8594; [Coding: High, Theory: Medium, Research: -, HCI: -]

**Project 3.2** *Python Interpreter*:
same as 3.1 for Python<br>
&#8594; [Coding: High, Theory: Medium, Research: -, HCI: -]

**Project 3.3** *Error Localizer*:
Conduct a literature study on error localization. Develop at least two error localization algorithms from different domains (e.g., statistical fault localization and analysis-based fault localization) for the provided framework and evaluate their efficacy. <br>
&#8594; [Coding: Medium, Theory: High, Research: Low, HCI: -]


## Topic 4 – Transforming / Repairing Programs

**Project 4.1** *Refactoring-based Repair*:
Develop a repair workflow that first generates semantic-preserving refactorings of a reference program so that it increases the chances of a structural alignment with a submitted program (see Project 2.1). Afterwards, it uses a matching refactoring to repair the submitted program by mutating program expressions. Strive for a minimal repair which satisfies the failing test case(s).<br>
&#8594; [Coding: Medium, Theory: Medium, Research: Medium, HCI: -]

**Project 4.2** *Optimization-based Repair*:
Develop a repair algorithm that (1) generates local repairs at each basic block by matching the submission and the reference solution, and (2) determines the complete repair (i.e., a subset of local repairs) by using some optimization strategy, which minimizes the overall repair cost.<br>
&#8594; [Coding: Medium-High, Theory: High, Research: Low, HCI: -]

**Project 4.3** *Synthesis-based Repair*:
Develop a repair algorithm that searches for a repair by synthesizing program expressions. The synthesis will be driven by the available components at the specific source location. It requires a specification inference, which results in a repair constraint.<br>
&#8594; [Coding: Medium, Theory: High, Research: Medium, HCI: -]


## Topic 5 – Feedback Generation

**Project 5.1** *Automated Feedback*:
Develop a feedback mechanism to summarize all obtained results in an appropriate and comprehensible manner for the user. For example, show root causes of the problems and provide explanation by annotating the code.<br>
&#8594; [Coding: Low, Theory: Medium, Research: Medium, HCI: High]

**Project 5.2** *Automated Grading*:
Develop a automated grading mechanism, which is beyond simple output of passing and failing test cases, e.g., it should take into account the necessary effort for fixing the submitted program.<br>
&#8594; [Coding: Low, Theory: High, Research: High, HCI: Low]
