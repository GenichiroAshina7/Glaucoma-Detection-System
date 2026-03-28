# Glaucoma Detection System
An ML-powered solution that helps detect and predicts cases of glaucoma based on digital fundus images.

### Prerequisites
1. VSCode with Jupyter Notebook extension installed
2. Terminal
3. Windows 11, Linux or MacOS
   
### Installation
1. Verify Python installation. Open terminal and type the following command.
    ```bash
    python --version
    ```
    If python is not installed, download it from https://www.python.org/. Ensure python version is Python 3.13.

2. Create project folder with the following structure:
```
Desktop/
├── glaucoma project/
│   ├── images/
│   └── Labels.csv
```

3. Go to https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.0.0/ and download the zip file and extract the contents. Transfer the images and csv file to the previously created folder.

4. Open terminal and create a virtual environment
```bash
python3 -m venv myenv
```
   Note: myenv can be changed to any wanted name.

5. Install the required libraries. Download requirements.txt to the folder and run the command in terminal.
   ```bash
   pip install -r requirements.txt
   ```
   
7. Download the hygd_with_cdr_final.ipynb file to the project folder and open in VSCode. Select virtual environment as the kernel.

8. Clear outputs and run all.

9. After the program has ended, run app.py. Click on localhost to open the Streamlit app.
