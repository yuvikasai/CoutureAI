# CoutureAI - Clothing Image Generator Using Stable Diffusion

CoutureAI is a personalized clothing image generator that leverages the Stable Diffusion Pipeline with an intuitive Streamlit interface. It allows users to generate realistic images of clothing based on detailed descriptions, empowering fashion enthusiasts to visualize their unique designs.

## Problem Statement

The fashion industry faces a challenge in offering personalized visual representations of clothing items. CoutureAI addresses this by providing a platform where users can describe clothing designs and receive customized visualizations. This tool enhances the online shopping experience by bridging the gap between imagination and reality.

## Solution Scenario

Meet Emma, a fashion-forward individual who can now use CoutureAI to visualize her custom clothing ideas. For instance, she can describe a "red satin evening gown with a sweetheart neckline and lace sleeves," and CoutureAI generates a realistic image of the dress. This helps her refine her ideas and even share them with a tailor for bespoke creations.

## Technologies Used

- **VS Code** for development
- **Hugging Face** for model integration
- **Anaconda** for environment management
- **Streamlit** for building the user interface

## Dependencies

The following packages are required to run the project:

- streamlit==1.32.0
- diffusers==0.25.0
- transformers==4.37.2
- torch==2.2.0
- huggingface-hub==0.20.3

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yuvikasai/CoutureAI.git
   cd CoutureAI
   ```

2. Create and activate a virtual environment (using Anaconda):
   ```bash
   conda create -n coutureai python=3.9
   conda activate coutureai
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Documentation

Full documentation is available in the docs file.
