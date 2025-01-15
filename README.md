# QC-Workshop-1-2024

# Python Environment Setup Instructions

## Overview
This document provides step-by-step instructions to set up a Python virtual environment with the required packages, including Jupyter, IPython, numpy, numpyarray_to_latex, and others for scientific computing and quantum computing tasks.

---

## Steps to Set Up the Environment

### 1. Create a Virtual Environment
Use the following command to create a virtual environment named `venv`:

```bash
python3 -m venv env
```

### 2. Activate the Virtual Environment

- **On Windows:**
  ```bash
  .\env\Scripts\activate
  ```

- **On macOS/Linux:**
  ```bash
  source env/bin/activate
  ```

### 3. Upgrade pip
Ensure you have the latest version of `pip`:

```bash
pip install --upgrade pip
```

### 4. Install Required Packages
Run the following command to install the required packages:

```bash
pip install -r requirements.txt
```

---

## Additional Notes

- If you encounter issues with the `dwave-ocean-sdk` package, ensure you have a compatible version of Python installed
- For detailed documentation on using `dwave-ocean-sdk`, refer to [D-Wave's official documentation](https://docs.ocean.dwavesys.com/).


---

# D-wave API signup

Reqister account here in order to get your API keys.

https://cloud.dwavesys.com/leap/signup

