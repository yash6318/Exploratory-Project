# Exploratory-Project
This repository contains all the work related to Exploratory Project, which is Detection of Software Vulnerabilities and Defects and model explanation by eXplanable AI (XAI) - SHAP


# OVERALL ANALYSIS OF ALL DEFECT/VULNERABILITY DATASETS

  #### NASA [`12` - PC1/PC3/PC4/CM1/JM1/...] `Granularity - Function`  `C`
    No Defects favoured by Lower values of features:
      loc [Total / LOCodeandComment / LOBlank / LOComments] (12)
      Operands [Unique_operands / Total_Operands] (7)
      Unique_Operators (5)
      Percent Comments(4)

    No Defects favoured by Higher values of features:
      Cyclomatic_Density / Normalized_Cyclmatic_Density (10)
      Cyclomatic_Complexity (2)

  #### SOFTLAB (NASA) [`5` - AR1/AR3/AR4/AR5/AR6] `Granularity - Function`  `C`
    No Defects favoured by Lower values of features:
      loc [Total_loc / Executable_loc / Comment_Loc ] (9)
      unique_operands (3)
      Halstead_Vocabulary(3)
      Design Complexity(3)

    No Defects favoured by Higher values of features:
      Halstead_Difficulty(3)
      Normalized_Cyclomatic_Complexity (1)

  <!-- #### ReLink [`3` - Apache/Safe/Zxing] `Granularity - File ` `Java`
    No Defects favoured by Lower values of features:
      CountLine [..CodeExe / ..Code / ..CodeDecl / AvgLineCode] (5)
      SumCyclomatic [../ ..Modified / ..Strict] (4)
      CountStmtDecl / CountStmtExe (2)


    No Defects favoured by Higher values of features:
      RatioCommentTOCode (3)
      AvgLineBlank (2) -->

  #### Vulnerability Datasets (NVD/SARD) [`4` - api/au/..] `Granularity - Function` `C/C++`

    for label=0,i.e. no vulnerability -
    low values of the following attributes favoured no vulnerability:
        CountLineCodeDecl(5)
        CountSemicolon(3)


    High values of following favoured vulnerability:
        AvgLineCode(4)
        AltCountLineCode(4)
        AvgLine(4)

