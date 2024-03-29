# QOSF-Mentorship-Program-Screening-Tasks
## Task 3 ZNE

Zero-noise extrapolation (ZNE) is a noise mitigation technique. It works by intentionally scaling the noise of a quantum circuit to then extrapolate the zero-noise limit of an observable of interest. In this task, you will build a simple ZNE function from scratch:

1. Build a simple noise model with depolarizing noise 
2. Create different circuits to test your noise models and choose the observable to measure 
3. Apply the unitary folding method. 
4. Apply the extrapolation method to get the zero-noise limit. Different extrapolation methods achieve different results, such as Linear, polynomial, and exponential.
5. Compare mitigated and unmitigated results 
6. Bonus: Run your ZNE function in real quantum hardware through the [IBM Quantum Service](https://www.ibm.com/quantum)

Check the [Mitiq documentation](https://mitiq.readthedocs.io/en/stable/guide/zne-5-theory.html) for references. You are not allowed to use the functions from Mitiq or any other frameworks where ZNE is already implemented. 

## Usage

### Getting Started

To get started with this repository, follow these steps:

### 1. Clone this Repository
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/awshaffar/QOSF-Mentorship-Program-Screening-Tasks.git
```

### 2. Install dependencies:

Before running the code, ensure that you have Python and pip installed on your system. This project supports Python 3.7 and above. You can download and install Python from the [Python](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installation/) installed on your system before proceeding with the installation. 

Next, navigate to the cloned repository directory:

```bash
cd QOSF-Mentorship-Program-Screening-Tasks
```

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

This command will install all necessary Python packages specified in the requirements.txt file, including libraries for quantum computing and data analysis.

If you prefer using a virtual environment, you can create and activate one before installing dependencies:

```bash
python -m venv venv     # Create a virtual environment
source venv/bin/activate  # Activate the virtual environment on macOS/Linux
.\venv\Scripts\activate   # Activate the virtual environment on Windows
```

Once the virtual environment is activated, you can proceed to install the dependencies using the pip install -r requirements.txt command as mentioned above.