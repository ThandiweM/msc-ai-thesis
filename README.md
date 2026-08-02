# AI-Enhanced Anomaly Detection in the Ethereum Blockchain

This repository contains the code accompanying my master's thesis, *"AI powered anomaly detection in Ethereum transactions:
addressing data imbalance and enhancing detection accuracy."* It implements a machine learning pipeline for detecting fraudulent Ethereum transactions using the BCCC-DeFiFraudTrans-2025 benchmark dataset. It has a focus on class imbalance handling, model explainability and a wallet grouped evaluation procedure.
This wallet grouped evaluation procedure was developed to prevent entity identity leakage between wallet level features and the transactions they describe.

The pipeline compares three tree based ensemble models namely Random Forest, XGBoost and LightGBM. It applies SHAP based feature pruning and evaluates SMOTE and cost sensitive weighting as imbalance handling techniques.
They are all evaluated under a shared and reproducible protocol.

**Dataset**: BCCC-DeFiFraudTrans-2025 (Lashkari et al., 2025) is available by request from the originating institution, the Behaviour Centric Cybersecurity Center (BCCC)
under York University, Canada.

**Note**: this repository reflects the code as executed for the thesis. Some run to run variation in the gradient-boosted models' reported figures is disclosed and discussed in the thesis.
