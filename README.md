# Template for new repositories

This template is intended to be used during the development of a research project, a manuscript, or any publication that can be later "frozen" in time.
That is, the template seeks to create a structure that allows future readers to observe original data, pre-process methods, models (and versions), and results.
This template may not accommodate dynamic projects that evolve with time (i.e. models that are planned to be maintained).

## Workflow
The most convenient workflow to use this template would be:

1: Fork this repository to your account. <br>
2: Add folders or template files to make the repository more appropriate to your project needs, if any. This will be your own template from now on.<br>
3: Define the repository as a template (go to *Settings/Template repository*). <br>
4: Now, you can create your new project and select this as the template. <br>
5: Edit the README file so you present a summary of the project and information on items such as input data, models, and results.
6: Develop your project using the structure proposed in the template. For more information go to "How to work with this project "structure""
7: Upload the final products (such as publications, figures, maps, etc) to the folder with appropriate (authorized) formats.
8: To "archive your project", add the reference(s) (of the project report, research article, or article) developed within the project to the README file.
8: Rename your project adding the word "_FROZEN" at the end.

In that way, the project is assumed to be finalized and should not have new commits.

## How to work with this project "structure"

The recommendations below are general and the final way of using the template is up to the user(s).

**0_Raw_Data**: include raw data such as the downloaded information from authoritative sources. Add a README file with the references to the source data. In many cases, the data would be too large or may require permissions to be kept in the repository, hence the README file should include comments about where the data could be downloaded or requested. <br>

**1_Processed_data**: Include the post-processed data in this folder. Intermediate and final outcomes of the processing phase can be also saved. Codes associated with the post-processing are included in folder "2_Scripts_and_Models".<br>

**2_Input_files**: copy here post-processed data or intermediate results from scripts in the following folder. This could be observed initially as duplicating the data, but it avoids future mistakes that lead to re-processing data or performing re-analyses. Besides, the format files here are accommodated to the needs of the scripts. <br>

**3_Scripts_and_Models**: include in this folder any script used for downloading data, post-processing, and visualizing data; input files developed for working with specific analysis software (e.g. Opensees codes); scripts developed for analysis, sensitivity, statistics, visualization, etc. We recommend using a separate subfolder according to the task of the script(s). Scripts and models should only point to files in "2_Input_files" folders. If possible, save the analyses software used (or its version in the README file) or the environment files (e.g. *yml in python). <br>

**4_Figures**: save  the final figures, maps, and animations used for the script or slides associated with the project.<br>

**5_Tables**: tables generated for the report, article, and proceeding can be included here in formats to enable an easier way of sharing information. Use formats such as CSV. <br>

**6_Protected_data**: do not add any information that could generate data privacy issues, such as unauthorized data sharing. Instead, use a README file to explain the features of the data, the time it was collected, how it was used, and the limitations of the datasets. <br>

**7_Results**: create subfolders according to which results are saved. For example, save results from analysis software in one folder and the results from scripts in another subfolder. Make sure you protect the data obtained from simulations, that is none of the subsequent analyses may work directly over the simulation output. <br>

**8_Manuscript**: share the final version of the manuscript (pre-print version). <br>

**9_Slides**: save the slides of the project. Use informative names, organized by date. For example: "YYYY-MM-DD_ConfName" or "YYYY-MM-DD_LectureForClassCCC" <br>


