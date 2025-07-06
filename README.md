🧬 **HIV-1 Protease Cleavage Site Prediction (Rognvaldsson et al. 2015 Reimplementation)**

📌 ***Overview***

A minimalist reimplementation of the method described in "State of the art prediction of HIV-1 protease cleavage sites" (Bioinformatics, Vol. 31, Issue 8, 2015) by Rognvaldsson et al.
Demonstrates how a linear SVM with orthogonal encoding can outperform existing predictors for HIV-1 protease cleavage.

HIV-1 protease is a key enzyme in the life cycle of the virus—it cleaves polyproteins into functional units, enabling the virus to mature and become infectious. Predicting where this cleavage occurs is crucial for designing effective inhibitors, which are a cornerstone of antiretroviral therapy.

Traditional methods for identifying cleavage sites often rely on complex biochemical features or deep learning models. However, the 2015 paper by Rognvaldsson et al. showed that a simple linear SVM with orthogonal encoding could outperform more elaborate approaches. This reimplementation demonstrates that insight with minimal code, making it a great example of how simplicity can rival sophistication.

⚙️ ***Setup***

pip install scikit-learn pandas numpy

🚀 ***Usage***

Run the Jupyter notebook to:

    Load the UCI HIV-1 cleavage dataset

    Encode sequences using orthogonal encoding

    Train a linear SVM classifier

    Evaluate prediction accuracy

🧠 ***Key Insight***

The original paper showed that orthogonal encoding + linear SVM beats more complex models and physicochemical feature schemes.  This notebook replicates that result with minimal fuss.

💬 ***Why This Exists***

    To demystify “state-of-the-art” bioinformatics papers

    To show that good journals ≠ intimidating implementation

    To settle a debate with a pharmacist (successfully shut down ;-) )
