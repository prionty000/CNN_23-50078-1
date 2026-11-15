# Running this notebook on Kaggle (GPU)

Follow these steps to run `CNN_23-50078-1.ipynb` on Kaggle and produce the
executed notebook (with all outputs) for submission.

## 1. Create the notebook
1. Go to <https://www.kaggle.com/code> → **+ New Notebook**.
2. **File → Import Notebook → Upload** and select `CNN_23-50078-1.ipynb`
   (or import it directly from the GitHub repo).

## 2. Enable GPU and Internet
Open the right-hand **Notebook options** panel (the `⋮` / settings icon):
- **Accelerator** → `GPU T4 x2` (or `GPU P100`).
- **Internet** → **On**  ← required: the first cell downloads the Beans
  dataset from Hugging Face.

## 3. Run
- Click **Run All** (or *Run → Run all*). On a GPU, all 40 epochs finish in a
  few minutes.
- The notebook prints the device as `cuda` when the GPU is active.

## 4. Collect the deliverables
After the run completes:
- **Executed notebook:** *File → Download Notebook* — this `.ipynb` now contains
  all code, outputs, training curves, confusion matrix and the printed test
  accuracy. This is the file to submit / commit.
- **Saved model:** in the right panel under **Output**, download
  `models/CNN_23-50078-1.pth` (≈9 MB).

## 5. Send it back
Send me the downloaded executed `CNN_23-50078-1.ipynb` (and the `.pth`) and I'll
commit them to the GitHub repo and fill in the results in the README.

---
**Tip:** If you prefer, you can also *Save Version → Save & Run All (Commit)* on
Kaggle to get a permanent, shareable run on your Kaggle profile.
