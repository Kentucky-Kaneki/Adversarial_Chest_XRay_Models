# Adversarial_Chest_XRay_Models
A set of 3 DenseNet-121 models named BASELINE (no xray training), FINE-TUNED (trained only with clean images) and ROBUST (put through adversarial training and compared between with and witout CLAHE). Trained on NIH Chest XRay dataset. Adversarial attacks include FGSM, PGD, DeepFool Square and C&amp;W.

Need to have a kaggle legacy api token which will download a "kaggle.json" file if planning to execute the adversarial_xray_combined.ipnyb file. Place it inside the main home directory.