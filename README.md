# Agricultural-Crop-Recommendation-Disease-Detection-using-Machine-Learning
A machine learning-based crop recommendation system that analyzes soil, climate, rainfall, and environmental factors to suggest suitable crops. It helps farmers make data-driven decisions, improve productivity, reduce resource wastage, and promote efficient and sustainable agriculture practices.

## Project Workflow

1. Visit the home page to explore the application and choose a service: crop recommendation, fertilizer suggestion, or disease detection.
2. Use the crop recommendation form to enter soil values, pH, rainfall, and location information to get a tailored crop suggestion.
3. Use the fertilizer suggestion form to receive nutrient recommendations based on the selected crop and soil values.
4. Use the disease detection page to upload a plant image and identify likely diseases with treatment guidance.
5. View the model performance comparison results to understand accuracy across algorithms.

### Visual workflow

#### Home / landing page

![Home screen](ML%20CODE/AgricultreCropRecommendation/static/images/core.jpg)

#### Service selection and navigation

![Service cards](ML%20CODE/AgricultreCropRecommendation/static/images/3.jpg)

#### Performance comparison

![Model performance](ML%20CODE/AgricultreCropRecommendation/static/images/plot1.png)

#### App interface and input flow

![App workflow](ML%20CODE/AgricultreCropRecommendation/static/images/farm_background.jpg)

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

