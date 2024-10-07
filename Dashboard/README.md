City-Specific Dashboard – BuzzOnEarth by Intel'24 Hackathon
Welcome !! This dashboard provides a powerful way to visualize and analyze city-specific data using interactive components, leveraging cutting-edge Intel technologies to ensure optimized performance and efficient computation. It was developed as part of the BuzzOnEarth by Intel'24 Hackathon.

Overview
This project focuses on creating a data visualization dashboard that allows users to explore and interact with various city-specific datasets in real-time. The application is optimized using Intel’s AI and data analytics toolkits, enabling faster processing and high performance on Intel hardware. The Streamlit framework has been used to create this interactive app, making it easy to deploy and share.

Contents
app.py: The main Streamlit application file for running the dashboard.
Data/: Directory containing raw and processed city-specific data for analysis.
MyMap.html: A pre-generated map visualization included as part of the dashboard.
README.md: Instructions and setup guidelines for the project (this file).
requirements.txt: Lists all required Python packages for the project.
Intel Technologies Integrated
The project is built with Intel technologies to ensure optimized performance for data processing, deep learning inference, and scientific computing tasks.

1. Intel® Distribution of OpenVINO™ Toolkit
The Intel® Distribution of OpenVINO™ is used to optimize the deep learning models, reducing inference time on Intel hardware (CPUs, GPUs, and VPUs). This toolkit allows faster AI computations, which is vital for interactive dashboards handling real-time data.

2. Intel® oneAPI AI Analytics Toolkit (AI Kit)
The Intel® oneAPI AI Analytics Toolkit enhances machine learning workloads using optimized libraries, including:

Intel® DAAL (Data Analytics Acceleration Library)
Intel® oneDAL (Data Analytics Library)
Intel® Distribution for Python
These libraries provide significant performance improvements when processing large datasets and executing machine learning models.

3. Intel® Math Kernel Library (Intel® MKL)
Intel® MKL is used for high-performance computations like matrix operations and linear algebra, essential for processing the city-specific datasets and ensuring efficient analytics workflows.

Setup Instructions
Follow the steps below to set up your environment and run the dashboard application.

Step 1: Clone the Repository
Start by cloning this repository:

bash
Copy code
git clone <repository-url>
cd Dashboard
Step 2: Create and Activate a Virtual Environment
Create a virtual environment to keep the project dependencies isolated:

bash
Copy code
python -m venv intel_env
Activate the virtual environment:

On Windows:

bash
Copy code
intel_env\Scripts\activate
On macOS/Linux:

bash
Copy code
source intel_env/bin/activate
Step 3: Install Dependencies
Make sure your pip is up-to-date and then install the required packages:

bash
Copy code
pip install --upgrade pip
pip install -r requirements.txt
Step 4: Install Intel Technologies
4.1. Install OpenVINO™
To install the OpenVINO™ toolkit, run the following:

bash
Copy code
pip install openvino-genai==2024.4.0
4.2. Install Intel® oneAPI AI Analytics Toolkit
You can install the toolkit via conda (recommended) or pip. Using conda:

bash
Copy code
conda install -c intel oneapi-ai-kit
4.3. Install Intel® MKL
If needed, install Intel® MKL for fast numerical computations:

bash
Copy code
pip install intel-mkl
Running the Application
Step 1: Running the Streamlit App
Once everything is installed, you can run the Streamlit application by using the following command:

bash
Copy code
streamlit run app.py
This will launch the dashboard in your default web browser, available at http://localhost:8501 (or a different port if 8501 is occupied).

Step 2: Interacting with the Dashboard
The dashboard allows you to:

Explore real-time city-specific data.
Use interactive charts, graphs, and maps to filter and visualize different metrics.
Analyze pre-generated map visualizations and other datasets.
Optimizing for Intel Hardware
To maximize the performance of the dashboard on Intel hardware, follow these steps:

OpenVINO™ Optimization: Modify your Python scripts to leverage OpenVINO™ for deep learning inference tasks. This can be done using the OpenVINO™ Inference Engine API.

Intel® MKL for Scientific Computing: Set environment variables to ensure that Python uses Intel® MKL for numerical computations:

bash
Copy code
export MKL_THREADING_LAYER=GNU
Intel® DAAL for Data Analytics: Ensure your data processing pipelines leverage Intel® DAAL to accelerate performance, especially when working with large datasets.

Data Source
data/raw/: Contains raw datasets collected from different cities.
data/processed/: Contains cleaned and processed datasets, including population data and other detailed metrics for analysis.