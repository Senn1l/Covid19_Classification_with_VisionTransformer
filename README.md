# Covid-19 Classification with Vision Transformer
- This project included an extensive research on topic: Transformer in Medical Analysis.
- A base Vision Transformer (ViT) model was fine-tuned on a chest X-ray image dataset.
- Additional contributor: Phạm Anh Tuyên (I omitted him in the report file).

## Project Structure
- `report/`: Contains the final report pdf.
- `result/`: Contains inference results.
- `source/`: Contains the main pipeline Jupyter Notebook (from Kaggle) and links to trained weights and the Kaggle notebook.

## Dataset
- COVID19_Pneumonia_Normal_Chest_Xray_PA_Dataset.
- Contains 3 classes: Covid, Pneumonia, Normal, each with exactly 2313 images.
- Dataset Link: https://www.kaggle.com/datasets/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset

## Inference
- Evaluation metric: confusion matrix.
- Results are available in the `report/` folder.
 
## How to run
1. Open the Kaggle notebook: [Classification with Vision Transformer](https://www.kaggle.com/code/senn1l/classification-with-vision-transformer)
2. Click Copy & Edit.
3. On the right panel, in Session options, select one of the supported GPU/TPU accelerators and turn on the Internet.
   - Note: You must have a phone-verified Kaggle account to turn on the Internet.
4. Run all cells in the notebook.
