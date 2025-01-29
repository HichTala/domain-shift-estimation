# 📊 Domain Shift Estimation For Cross Domain Few-Shot Object Detection

Here, you will find all the tools you need to read and analyze the data I provided. Follow the steps below to get
started. 🚀

---

## 📥 Downloading the Data

1. **Get the data**
    - Download the feature vectors from this link: [🔗 Download Link](https://drive.google.com/file/d/1r4YlRP4NZicWL4kf_6XBcj2PSNSlKaEL/view?usp=sharing)

2. **Organize the data**

    - Place the downloaded files inside the `data` folder. The structure should look like this:
      ```
      📂 domain-shift-estimation
      ├── 📂 data
      │   ├── 📂 class_barycenter
      │   ├── 📂 class_features
      ├── reading_and_processing_data_script.ipynb
      ├── README.md
      └── ...
      ```

---

## ⚙️ Setting Up Your Environment

### Why Use Conda? 🐍

Conda is a powerful environment manager that simplifies dependency management and helps you avoid conflicts between
libraries.

### 🛠 Installing Conda

1. Download and install Miniconda (a lightweight version of Anaconda):
    - [Miniconda](https://docs.anaconda.com/miniconda/)

2. Follow the instructions provided by the installer.

### 🧑‍🔬 Creating a Conda Environment

1. Create a new environment for this project:
   ```bash
   conda create -n myenv python=3.10
   ```
   Replace `myenv` with a name of your choice.

2. Activate the environment:
   ```bash
   conda activate myenv
   ```

### 📦 Installing Requirements

1. Install pytorch (you should follow the instructions on the [official website](https://pytorch.org/)):

   ```bash
   pip install pytorch torchvision torchaudio
   ```

2. Install any additional dependencies listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

---

## ☁️ Use Google Colab for Simplicity

If you don't want to set up a local environment, consider using Google Colab. It's a free, browser-based environment
that requires no installation.

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload this repository to your Google Drive or link it directly from GitHub.
3. Enable GPU support for faster computations:
    - Go to the top menu bar and select **Runtime > Change runtime type**.
    - In the dialog box, set **Hardware accelerator** to **GPU** and click **Save**.

4. Verify GPU availability in your notebook by running:
   ```python
   import torch
   print(torch.cuda.is_available())
   ```

---

## 🚀 Running the Scripts

Once the environment is set up and the data is organized, you can start using the provided notebook
`reading_and_processing_data_script.ipynb`

---
Happy coding and analyzing! 🎉



