# SiMREPS Analysis Suite
## Description
Full GUI-enabled software package that performs analysis of single-molecule digital assay data using kinetic fingerprinting (SiMREPS = single-molecule recognition through equilibrium Poisson sampling).

## Availability
Software for SiMREPS data analysis is available on request for non-commercial, academic use, or for licensed commercial use, from the University of Michigan Innovation Partnerships office: innovationpartnerships@umich.edu

Academic contacts: Alexander Johnson-Buck (alebuck@umich.edu), Nils Walter (nwalter@umich.edu)

Only a Windows version is available at this time.

## SiMREPS Analysis Suite: Functionality
### SiMREPS Analysis
- Takes as input one or more TIF image stacks from fluorescence microscopy
- Finds locations with repeated SiMREPS probe binding and generates fluorescence vs. time traces from them
- Analyzes signal-to-noise and kinetics of time traces to determine the number of accepted counts (positive single-molecule analyte detection events)
- Generates plots of Nb+d, tau, and time traces
- (Optional) Applies extended dynamic range mode for situations where 
- (Optional) Plots a standard curve from concentration series and fits a 5-parameter logistic regression to the data
- (Optional) Estimates concentration from existing standard curve

### Parameter Optimization (SiMREPS Optimizer)
- Trains a machine learning classifier to identify specific single molecule analytes based on kinetics and signal-to-noise, using an input training set of positive and negative control measurements
#### App Window

#### Optimization report
<img width="1528" height="884" alt="image" src="https://github.com/user-attachments/assets/b917c78a-fd2e-4930-ada5-4033943f2541" />

## Please Cite:
### Software:
- Johnson-Buck, Alexander; Li, Jieming; Tewari, Muneesh; Walter, Nils G. (2019) A guide to nucleic acid detection by single-molecule kinetic fingerprinting. Methods 153, 3-12, DOI: 10.1016/j.ymeth.2018.08.002.
### SiMREPS Method:
- Johnson-Buck, Alexander; Su, Xin; Giraldez, Maria; Zhao, Meiping; Tewari, Muneesh; Walter, Nils G. (2015) Kinetic fingerprinting to identify and count single nucleic acids. Nature Biotechnology 33, 730-732.

## Other Publications using/related to this software:
- Li Jieming; Zhang Leyou; Johnson-Buck Alexander; and Walter Nils G. Foundation model for efficient biological discovery in single-molecule time traces. Nature Methods (Accepted).
- Dai, Liuhan; Johnson-Buck, Alexander; Laird, Peter W.; Tewari, Muneesh; and Walter, Nils G. (2024) Ultrasensitive Amplification-Free Quantification of a Methyl CpG-Rich Cancer Biomarker by Single-Molecule Kinetic Fingerprinting. Anal Chem, 96 (43), 17209-17216, DOI: 10.1021/acs.analchem.4c03002.
- Chatterjee, Tanmay; Johnson-Buck, Alexander; Walter, Nils G. (2022) Highly sensitive protein detection by aptamer-based single-molecule kinetic fingerprinting. Biosensors and Bioelectronics 216, 114639.
- Li, Zi; McNeely, Molly; Sandford, Erin; Tewari, Muneesh; Johnson-Buck, Alexander; and Walter, Nils G. (2022) Attomolar sensitivity in single biomarker counting upon aqueous two-phase surface enrichment. ACS Sensors 7, 1419-1430.
- Mandal, Shankar; Khanna, Kunal; Johnson-Buck, Alexander; Walter, Nils G. (2022) A guide to accelerated direct digital counting of single nucleic acid molecules by FRET-based intramolecular kinetic fingerprinting. Methods 197, 63-73.
- Khanna, Kunal; Mandal, Shankar; Blanchard, Aaron T.; Tewari, Muneesh; Johnson-Buck, Alexander; Walter, Nils G. (2021) Rapid kinetic fingerprinting of single nucleic acid molecules by a FRET-based dynamic nanosensor. Biosensors and Bioelectronics, 113433.
- Chatterjee, Tanmay; Knappik, Achim; Sandford, Erin; Tewari, Muneesh; Choi, Sung Won; Strong, William B.; Thrush, Evan P.; Oh, Kenneth J.; Liu, Ning; Walter, Nils G.; Johnson-Buck, Alexander (2020). Direct kinetic fingerprinting and digital counting of single protein molecules. Proceedings of the National Academy of Sciences 117 (37), 22815–22822, DOI: 10.1073/pnas.2008312117.
- Li, Jieming; Zhang, Leyou; Johnson-Buck, Alexander; Walter, Nils G. (2020) Automatic classification and segmentation of single-molecule fluorescence time traces with deep learning. Nature Communications 11 (1), 1-11.
- Mandal, Shankar; Li, Zi; Chatterjee, Tanmay; Khanna, Kunal; Montoya, Karen; Dai, Liuhan; Petersen, Chandler; Li, Lidan; Tewari, Muneesh; **Johnson-Buck, Alexander; Walter, Nils G. (2020) Direct kinetic fingerprinting for high-accuracy single-molecule counting of diverse disease biomarkers. Accounts of Chemical Research 54 (2), 388-402.
- Chatterjee, Tanmay; Li, Zi; Khanna, Kunal; Montoya, Karen; Tewari, Muneesh; Walter, Nils G.; Johnson-Buck, Alexander. (2020) Ultraspecific analyte detection by direct kinetic fingerprinting of single molecules. Trends in Analytical Chemistry 123, 115764.
