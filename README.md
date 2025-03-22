🩸 Mask R-CNN for Blood Cell Detection
📌 Overview
This project implements Mask R-CNN using a pretrained model (trained on the MS COCO dataset) to detect red blood cells (RBCs) in microscopic images. However, since MS COCO lacks blood cell classes, the model incorrectly classifies RBCs as apples, donuts, and people.

📂 Dataset
Blood Cell Dataset (Kaggle)

Contains images of normal cells and infected cells (Pneumonia, etc.)

🛠️ Steps Involved
Loaded Mask R-CNN model pretrained on MS COCO.

Ran inference on blood cell images.

Observed misclassifications due to domain mismatch.

🧠 Key Learnings
Pretrained models are powerful, but their effectiveness depends on whether the dataset has relevant object categories.

For accurate RBC/WBC detection, we need to fine-tune Mask R-CNN on a specialized dataset.

Also explored GANs, which are useful for generating synthetic medical images!

🚀 Next Steps
Train Mask R-CNN on a custom blood cell dataset to improve predictions.

Experiment with GANs for medical image generation.
