# abcd-ela

R Markdown files for creating measures of early life adversity in ABCD Data Release 7.1.

You will need to run ELAfromABCD_setup.Rmd prior to running any of the code to create scores. The setup code will create csv and rds files needed for the score calculations.

Three scores are available:
1) ELAfromABCD_ELAplus.Rmd - Creates a measure of early life adversity that includes the 10 ACEs domains plus 4 additional domains: 1) exposure to natural disasters or terrorism; 2) (lack of) safety from violence/crime; 3) (lack of) resources, and 4) long-term separation from parents/caregivers (Year 3 only). 
2) ELAfromABCD_ACEsproxy.Rmd - Creates an "ACEs proxy" variable ranging from 0-10 mapping on to previous studies using the ACEs survey (Felitti et al., 1998).
3) ELAfromABCD_youth.Rmd - Creates the youth-deferred ACEs proxy variable, which defaults to youth report of their experiences when available.

Please cite:
Breslin, F. J., Ratliff, E. L., Cohen, Z. P., Croff, J. M., & Kerr, K. L. (2025). Measuring adversity in the ABCD Study: Systematic review and recommendations for best practices. _BMC Medical Research Methodology, 25_(1), 77. https://doi.org/10.1186/s12874-025-02521-5

Original code for Data Release 5.1 is available in the data-rel-5.1 folder.
