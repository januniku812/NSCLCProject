2023-2024 Science Fair Project

How to run: 

The NSCLCSubtypeDiagnosisProject.ipynb file uploaded just needs to be downloaded and opened in Google Colab Notebooks. Once Google Colab Notebooks opens up, locate the tab "Runtime", click on it and in the dropdown you will see the option "Run all". You can click on it to run the program.

Note: The NSCLCSubtypeDiagnosisProject.ipynb file cannot be run without downloading the exact data files referenced in the code cells from The Cancer Genome Atlas, which requires either the GDC Transfer Tool or manual downloads to save the large whole slide imaging (.svs) files and RNA Sequencing files from TCGA-LUAD and TCGA-LUSC databases as well as the CT Scan data found here: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images. This process can take several dozen hours.

**Abstract** :

Lung cancer is a leading cause of death worldwide. Early diagnosis is crucial for improving survival rates. Traditional methods of diagnosing NSCLC subtypes, such as manual analysis of CT scans and WSIs, are time-consuming and can be inaccurate. This study proposes a new hybrid deep learning model that can more accurately diagnose NSCLC subtypes. The model takes both CT scans and WSIs as input, and uses a late probability fusion technique to combine the predictions of the two models. Additionally, the model produces a subtype heat map from the WSI for pathologist review and overcomes the lack of large cell carcinoma data problem in whole slide imaging through the CT Scan in the late fusion prediction technique. The model is evaluated using subtype-based pairing of CT-scan and WSI inputs against the isolate subcomponent models.  Results show that the hybrid model can significantly reduce LUAD-LUSC misdiagnosis and improve overall accuracy compared to traditional methods. Notably, the model often corrected highly biased or inaccurate predictions from the isolate models. This research has the potential to improve patient outcomes by assisting pathologists and radiologists in enabling earlier, robust, and more accurate diagnosis of NSCLC. Further research is needed to validate the model in a larger clinical setting.

**SSRN Paper Link: *** https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5361856
