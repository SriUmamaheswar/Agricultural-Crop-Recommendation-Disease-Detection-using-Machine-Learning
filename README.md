# Agricultural-Crop-Recommendation-Disease-Detection-using-Machine-Learning
A machine learning-based crop recommendation system that analyzes soil, climate, rainfall, and environmental factors to suggest suitable crops. It helps farmers make data-driven decisions, improve productivity, reduce resource wastage, and promote efficient and sustainable agriculture practices.

## Run locally

Open a terminal in the project root and follow these steps.

- Activate the virtual environment (PowerShell):

	```powershell
	Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
	& .\env\Scripts\Activate.ps1
	```

- Activate the virtual environment (CMD):

	```cmd
	..\env\Scripts\activate.bat
	```

- Install required packages from the app requirements file:

	```cmd
	pip install -r "ML CODE\AgricultreCropRecommendation\requirements.txt"
	```

- Run the Flask app using the environment Python (recommended):

	```cmd
	"D:\B_DRIVE\ACRBS&P\env\Scripts\python.exe" "ML CODE\AgricultreCropRecommendation\app.py"
	```

	Or, from the app folder after activating the env:

	```cmd
	cd "ML CODE\AgricultreCropRecommendation"
	python app.py
	```

The app will be available at http://127.0.0.1:5000

