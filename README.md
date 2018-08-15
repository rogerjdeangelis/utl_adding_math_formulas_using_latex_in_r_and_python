# utl_adding_math_formulas_using_latex_in_r_and_python
Adding Math Formulas using LaTeX in R and Python.  Keywords: sas sql join merge big data analytics macros oracle teradata mysql sas communities stackoverflow statistics artificial inteligence AI Python R Java Javascript WPS Matlab SPSS Scala Perl C C# Excel MS Access JSON graphics maps NLP natural language processing machine learning igraph DOSUBL DOW loop stackoverflow SAS community.
    Adding Math Formulas using LaTeX in SAS, R and Python;

    SAS latex tagset
    https://support.sas.com/rnd/base/ods/odsmarkup/latex.html

    github R
    https://tinyurl.com/y88ztyay
    https://github.com/rogerjdeangelis/utl_adding_math_formulas_using_latex_in_r_and_python/blob/master/utl_adding_math_formulas_using_latex_in_r_and_python

    https://tinyurl.com/y9ltl3ae
    https://github.com/rogerjdeangelis/utl_adding_math_formulas_using_latex_in_r_and_python


    see github python
    https://tinyurl.com/yb2rrtud
    https://github.com/rogerjdeangelis/utl_add_latex_equations_sas_output/blob/master/utl_adding_latex_mathematical_equations_to_sas_output_pdf_and_pptx.pdf

    https://github.com/rogerjdeangelis/utl_add_latex_equations_sas_output

    R Doc
    https://cran.r-project.org/web/packages/latex2exp/vignettes/using-latex2exp.html


    INPUT
    =====

    %let txt=A $\\LaTeX$ formula: $\\frac{2hc^2}{\\lambda^5} \\,\\frac{1}{e^{\\frac{hc}{\\lambda k_B T}} - 1}$;


    PROCESS
    =======

    %utl_submit_r64("
     library(latex2exp);
     png('d:/png/utl_adding_math_formulas_using_latex_in_r_and_python.png');
     plot(TeX('&txt'),cex=2);
     png();
    "));


    OUTPUT
    ======

    see
    https://tinyurl.com/y88ztyay


