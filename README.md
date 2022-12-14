# rm-dd-perses
Project: 2021FA-COSC6321-Research Methods in Computer Science \
Task: Extracting Label-specific Key Input Features for Neural Code Intelligence Models.

- - -

# What/Why/How/Who:

- What: We are trying to adopt a syntax-guided program reduction approach for reducing the size of an input program while preserving the same prediction of the code intelligence model. The approach removes irrelevant parts from an input program following grammars and keeps the minimal snippet that the code intelligence model needs to maintain its actual prediction. Therefore, by reducing some input programs of a class, we aim to extract relevant input features of the target class.

- Why: Rabin et al. [2020] attempt to find key input features of a class by manually inspecting some input programs of that class. However, the manual inspection cannot be applied to a large dataset due to the vast number of classes. Suneja et al. [2021] and Rabin et al. [2021] adopt a syntax-unaware program reduction approach, Delta Debugging [Zeller et al. 2002], to reduce the size of input programs while preserving the same prediction of the code intelligence model. However, this approach creates a large number of invalid programs as it does not follow the syntax during the reduction step. As a result, it requires an extra program validation check after the reduction step and backtracks if the reduced program is invalid, which increases the overall reduction overhead.

- How: While state-of-the-art approaches use a manual inspection or syntax-unaware program reduction approach, we focus on adopting the syntax-guided program reduction approach. In particular, we will adopt Perses [Sun et al. 2018], a syntax-guided program reduction approach, to reduce the size of an input program. The state-of-art approaches show that the syntax-unaware approach can reduce an input program. Therefore, it is more likely that the syntax-guided approach will reduce the input program significantly as it follows the syntax of the program.

- Who: In general, software engineering researchers, and in particular, those who use deep neural networks for code intelligence tasks will benefit from this work. This field has witnessed a rapid advance in recent years, and we think more researchers will pay attention to this field in the next few years.

---

# Exercise Guidelines:

- Interesting topics in CS
- Summarize out-of-domain papers
- Evaluate own research projects
- Find related research papers
- Review a related paper
- Metrics of related papers
- Evaluate a technical talk
- Higher Order Writing Concerns
- Lower Order Writing Concerns
- Technical Writing

- - -

# Anatomy of Research Paper:

- Introduction
- Related Work
- Methodology
- Result Analysis
- Threats to Validity
- Discussion and Future Plan
- Conclusion

- - -

# Research Quest:

- Complete Research Paper (https://arxiv.org/abs/2202.06474)
- Submit Paper to Conference
- Review Conference Papers
- Poster Presentation (https://www.slideshare.net/mdrafiqulrabin/rm-dd-perses)

&emsp; [ Related Work: https://github.com/mdrafiqulrabin/CI-DD-Perses ]

- - -

# References:

- Coursework: https://www2.cs.uh.edu/~gnawali/courses/cosc6321-f21/index.html
- Conference: https://sites.google.com/view/rq21
