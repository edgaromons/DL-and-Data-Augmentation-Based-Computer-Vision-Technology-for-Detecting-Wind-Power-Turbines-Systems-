In this project, we:

•	Utilized Python and the PyTorch framework to develop and implement three deep learning architectures for wind turbine detection from satellite images.

•	Leveraged OpenCV and Albumentations libraries for image processing tasks, including image augmentation and preprocessing.

•	Employed Pandas and Scikit-learn for data manipulation, analysis, model selection, and evaluation.

•	Performed exploratory data analysis (EDA) on the Airbus SPOT satellites images over wind turbines dataset using Matplotlib and Seaborn for visualization.

•	Built a data pipeline and training loop within the Google Colab environment to efficiently process and train the deep learning models.

•	Applied computer vision and image segmentation techniques to address the challenge of wind turbine detection.

•	Downloaded and accessed the required datasets using OpenDatasets and Kaggle.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
