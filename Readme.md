Readme

I. Prerequisites

1.Download and install Anaconda (Download link: https://www.anaconda.com/).

2.Download the code compressed package hainanucof_interactive.zip (Download link:https://github.com/wchou93/hainanucof_interactive).

3.Create a folder at any location (e.g., a "Jupyter" folder on your desktop), place the compressed package into it, and extract the contents.

II. Usage Instructions

1.Open Anaconda Navigator, select Jupyter Lab, and start it.

2.On the left side of the popped-up Jupyter Lab web window, find the path where the hainanucof_interactive folder was placed. Open it, and you will see several files such as database.py.

3.Click the blue "+" icon in the upper left corner, select "python3 (ipykernel)" under the first Notebook option, and a new window will pop up.

4.Enter %run database.py. If -Load Done- appears after running, it means the program has been successfully launched, and you can start querying and making predictions.

5.Input the compound name, CAS number, or SMILES expression to query existing synthesis schemes in the database. Additionally, you can predict the dosage ratio of ligands, the name and dosage of solvents, as well as the properties of additives, temperature, and time parameters，and the final prediction scheme will appear in the Excel table named "output_schemes" in this compressed package.
Example Input :  Can you output the synthesis schemes with TAPB as the ligand?
System Output:  
Synthesis Method 1:

Synthesis of TAPB-COF. Typically, TAPB (0.15 mmol) PMDA (0.15 mmol) were ground to powder; isoquinoline (0.05 mL) was added and grinding was continued. The mixture was trans- ferred to a glass tube, and mesitylene (0.5 mL) and NMP (0.5 mL) were added. After freezing, the tube was evacuated and sealed and then heated at 200 °C for three day。

For more details, see:https://doi.org/10.1039/d3gc04671k

Synthesis Method 2:

Synthesis of Tf-TAPB COF. A modiﬁed method was used to synthesize Tf-TAPB COF.37,38 To a mixture of 1,3,5-triformylbenzene (0.1 mmol, 16.2 mg) and 1,3,5-tris(4′-aminophenyl)benzene (0.1 mmol, 35.1 mg) was added with 1,4-dioxane (1 mL), mesitylene (1 mL) and 6 M AcOH (aq, 0.2 mL) in a 10 mL Schlenk tube (15 × 80 mm2). The suspension was sonicated for 5 min, then ﬂash frozen at 77 K, and degassed under freeze−pump−thaw for three cycles. The tube was sealed and heated at 120 °C for 7 day。


For more details, see:https://doi.org/10.1021/acs.chemmater.8b02560



Synthesis Method 3:

TAPB-Tp-COF was synthesized. Briefly, TAPB (21 mg, 0.0596 mmol) and Tp (12.27 mg, 0.0596 mmol) were solved in the mixed solvent of 1,4-dioxane (2 mL) and aqueous acetic (0.2 mL, 6.0 M), following by treating ultrasonically for 8 h.。

For more details, see:https://doi.org/10.1007/s00604-023-05987-6

Example Input: I want to Synthesize cof，using ligands 4-Hydroxyisophthaladehyde  and Tris(4-aminophenyl)amine.Predict the solvent name and dosage,and generate 10 divergent schemes 

System Output: 

Ⅲ. Frequently Asked Questions

To stop the query: In Jupyter, click Kernel → Restart to restart the kernel.
