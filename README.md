🧬 **HIV-1 Protease Cleavage Site Prediction (Rognvaldsson et al. 2015 Reimplementation)**

📌 ***Overview***

A minimalist reimplementation of the method described in "State of the art prediction of HIV-1 protease cleavage sites" (Bioinformatics, Vol. 31, Issue 8, 2015) by Rognvaldsson et al.
Demonstrates how a linear SVM with orthogonal encoding can outperform existing predictors for HIV-1 protease cleavage.

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
