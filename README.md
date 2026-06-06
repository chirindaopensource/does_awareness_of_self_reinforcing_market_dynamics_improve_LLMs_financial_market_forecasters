# **`README.md`**

# Reflexivity as Prompt: An Empirical Replication Pipeline

<!-- PROJECT SHIELDS -->
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![arXiv](https://img.shields.io/badge/arXiv-2606.00061-b31b1b.svg)](https://arxiv.org/abs/2606.00061)
[![Journal](https://img.shields.io/badge/Journal-ArXiv%20Preprint-003366)](https://arxiv.org/abs/2606.00061)
[![Year](https://img.shields.io/badge/Year-2026-purple)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Discipline: FinEcon](https://img.shields.io/badge/Discipline-Financial%20Economics-00529B)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Discipline: MathFin](https://img.shields.io/badge/Discipline-Mathematical%20Finance-00529B)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Discipline: Econometrics](https://img.shields.io/badge/Discipline-Econometrics-00529B)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Discipline: NLP](https://img.shields.io/badge/Discipline-Natural%20Language%20Processing-00529B)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Discipline: LLMOps](https://img.shields.io/badge/Discipline-LLM%20Systems%20Engineering-00529B)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Data: Yahoo](https://img.shields.io/badge/Data-Yahoo%20Finance%20(^GSPC)-lightgrey)](https://finance.yahoo.com/)
[![Data: Shiller](https://img.shields.io/badge/Data-Robert%20Shiller%20Dataset-lightgrey)](http://www.econ.yale.edu/~shiller/data.htm)
[![Method: Rolling Window](https://img.shields.io/badge/Method-Rolling%20Window%20Estimation-orange)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Method: Factorial Ablation](https://img.shields.io/badge/Method-Factorial%20Ablation-orange)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Method: Zero-Shot](https://img.shields.io/badge/Method-Zero--Shot%20Prompting-orange)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Type Checking: mypy](https://img.shields.io/badge/type%20checking-mypy-blue)](http://mypy-lang.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=flat&logo=Jupyter&logoColor=white)](https://jupyter.org/)
[![YAML](https://img.shields.io/badge/YAML-%23CB171E.svg?style=flat&logo=yaml&logoColor=white)](https://yaml.org/)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-brightgreen)](https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters)

**Repository:** `https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters`

**Owner:** 2026 Craig Chirinda (Open Source Projects)

## Introduction

This project is an independent, professional-grade implementation of the ideas, methodologies, and experimental protocols from the paper titled **"Reflexivity as Prompt: Does Awareness of Self-Reinforcing Market Dynamics Improve LLMs as Financial Market Forecasters?"** by the author:
*   **Eugene Park**

This repository provides a complete, end-to-end computational framework for replicating the paper's findings. It delivers a highly optimized, crash-recoverable pipeline that evaluates how frontier Large Language Models (GPT-5, Claude Sonnet 4.6, Gemini 3 Pro) behave as financial forecasters during historical boom-bust cycles when injected with George Soros's theory of reflexivity. By treating the market not as an exogenous statistical process, but as a complex adaptive system governed by endogenous feedback between participant beliefs and fundamental realities, this codebase establishes a rigorous mechanism-aware forecasting architecture.

## Theoretical Background

The implemented methods bridge qualitative financial economics with quantitative prompt engineering and portfolio theory.

**1. The Theory of Reflexivity:**
The pipeline operationalizes Soros's framework, which posits two simultaneous, bidirectional functions. The *cognitive function* maps reality to participant beliefs, which are inherently biased. The *participative function* maps those biased beliefs back to reality, as capital allocation directly alters corporate fundamentals (e.g., cost of capital, balance sheet strength). 

**2. The Prevailing Bias and P/E Dynamics:**
This two-way causality generates a *prevailing bias*, mathematically operationalized in this study as the systematic deviation of the actual Price-to-Earnings (P/E) ratio from its long-run historical mean. The pipeline feeds normalized trailing twelve-month EPS and adjusted closing prices to the LLMs to allow them to detect this bias.

**3. The Seven-Stage Boom-Bust Cycle:**
The theoretical scaffold forces the LLM to classify the market into one of seven stages: Unrecognized, InitialPhase, Testing, Acceleration, Twilight, Crash, and Recovery. A critical diagnostic distinction enforced by the prompt is the transition from Twilight (prices falling, but EPS intact) to Crash (prices and EPS falling reflexively).

**4. Structural vs. Narrative Cycles:**
The pipeline evaluates models across two historically distinct episodes: the dot-com bubble (1996–2001), representing an equity P/E-driven narrative cycle, and the Global Financial Crisis (2004–2009), representing a credit-channel structural cycle.

Below is a diagram which summarizes the proposed approach:


<div align="center">
  <img src="https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters/blob/main/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters_ipo_main_4.png" alt="Pipeline Architecture" width="100%">
</div>

## Features

-   **True Idempotency and Crash-Recoverability:** Utilizes durable JSONL logging with `os.fsync` to reconstruct the exact mathematical state of the 48-cell experimental grid. The 3,456-call pipeline can be interrupted and resumed infinitely without duplicating API calls or corrupting the accumulators.
-   **Strict Data Version Calibration:** Implements an upfront buy-and-hold Sharpe ratio gate (0.65, 0.02, 0.35) that mathematically guarantees the Yahoo Finance data has not been retroactively revised, ensuring perfect reproducibility before expending API budget.
-   **Ratio-Invariant Normalization:** Executes a dynamic rolling-window normalization protocol ($P'_k = 100 \cdot P_{t_0+k-1}/P_0$) that preserves the economically essential P/E signal while stripping absolute levels and calendar dates to prevent LLM memorization.
-   **Jittered Exponential Backoff:** Provides robust handling of API rate limits across three distinct provider SDKs (OpenAI, Anthropic, Google) using a $2^{a-1} \cdot (1 + u)$ backoff schedule.
-   **Diagnostic Taxonomy:** Automatically classifies deviations from the reported results into Data Version Discrepancy, Model Version Drift, or Expected Stochasticity (specifically isolating GPT-5's temperature=1.0 behavior).

## Methodology Implemented

1.  **Data Ingestion & Alignment:** Reconciles Yahoo Finance's last-trading-day convention with Shiller's first-of-month convention using pandas `Period` indices, creating a canonical 288-month dataset.
2.  **Rolling Normalization:** Applies the base-100 normalization equations at each evaluation step $\tau$, advancing the base $P_0$ by one month iteratively.
3.  **Factorial Prompt Assembly:** Dynamically concatenates theoretical Blocks 1-5 based on a progressive-disclosure ablation design (Conditions A through D).
4.  **LLM Inference & Parsing:** Executes zero-shot calls and robustly extracts the ternary directional forecast (`up`, `neutral`, `down`) using a three-tier JSON parsing strategy with a conservative `"neutral"` fallback mechanism.
5.  **Metric Computation:** Maps forecasts to long/cash positions ($s_t \in \{1.0, 0.5, 0.0\}$), computes portfolio returns, and derives the annualized Sharpe ratio with Bessel correction ($n-1$). It strictly prohibits the mathematical error of averaging per-episode Sharpe ratios for the combined metric.

## Core Components (Notebook Structure)

*Note: All orchestrator callables and their constituent helper functions are contained within a singular, comprehensive Jupyter Notebook.*

The notebook is structured as a logical Directed Acyclic Graph (DAG), moving from raw data ingestion to terminal artifact generation:
1.  Configuration and Data Structures (Dataclasses)
2.  Data Engineering and Alignment (Tasks 1-4)
3.  Calibration and Benchmarking (Task 5)
4.  Normalization and Prompt Engineering (Tasks 6-7)
5.  API Integration and Execution Loop (Tasks 8-12)
6.  Metric Computation and Table Assembly (Tasks 13-15)
7.  Orchestration and Reproducibility Audit (Tasks 16-17)

## Key Callable: `execute_complete_research_pipeline`

The project is designed around a single, top-level user-facing interface function:

-   **`execute_complete_research_pipeline`:** This apex orchestrator function runs the entire automated research pipeline from end-to-end. A single call to this function validates the file paths, ingests the empirical data, enforces the calibration gate, configures the LLM clients, executes the 3,456-call nested evaluation loop, computes all metrics, assembles the styled pandas DataFrames (Tables 1 and 3), and generates the final reproducibility audit report. It returns a comprehensive dictionary containing all generated artifacts.

## Prerequisites

-   Python 3.10+
-   Core Python dependencies: `numpy`, `pandas`, `pyyaml`, `faker` (for synthetic testing).
-   Provider SDKs: `openai`, `anthropic`, `google-generativeai`.
-   Environment Variables: `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`, `GOOGLE_API_KEY`.

## Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters.git
    cd does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Python dependencies:**
    ```sh
    pip install numpy pandas pyyaml faker openai anthropic google-generativeai
    ```

## Input Data Structure

The pipeline requires three primary inputs:
1.  **`df_yahoo_raw` (CSV)**: The raw download from Yahoo Finance for ticker `^GSPC`. Must contain the `Date` and `Adj Close` columns. *Warning: This data is subject to retroactive revision by the provider.*
2.  **`df_shiller_raw` (Excel)**: The raw workbook from Robert Shiller. Must contain the decimal-year `Date` and the `Earnings` column.
3.  **`config.yaml`**: The master configuration file containing all experimental grid dimensions, prompt blocks, and calibration targets.

## Usage

Here is the granular, step-by-step guide to executing the end-to-end pipeline for **"Reflexivity as Prompt"**. 

*Note: It is assumed that all the callables defined in the preceding tasks of this project are present and executed within a single, unified Jupyter Notebook environment. There is no external folder with `.py` modules. It is also assumed that the master configuration file, `config.yaml`, is saved in the current working directory.*

This example demonstrates how to synthetically generate the required Yahoo Finance and Shiller datasets, save them to disk, load the study configuration from the YAML file, and execute the full research pipeline using the apex `execute_complete_research_pipeline` orchestrator.

### **Step 1: Synthetic Data Generation (`df_yahoo_raw` and `df_shiller_raw`)**

The first requirement is a high-fidelity synthetic representation of the two empirical inputs. These datasets must adhere strictly to the schemas defined in the study.

**Methodology:**
1.  **Date Generation:** We generate a sequence of 288 month-end business days spanning the study period (January 1986 to December 2009) for the Yahoo dataset, and a corresponding sequence of decimal-year floats for the Shiller dataset.
2.  **Time Series Simulation:** We simulate a price path ($P_t$) using a geometric random walk with drift, and an earnings path ($\text{EPS}_t$) that roughly tracks the price to maintain a plausible P/E ratio. *Crucial Note:* While this synthetic data perfectly matches the required schema and types, it will mathematically fail the strict buy-and-hold Sharpe ratio calibration gate (0.65, 0.02, 0.35) enforced by the pipeline. In a production environment, the exact historical data must be used. For this example, the pipeline will correctly catch this divergence and halt safely, demonstrating the fail-fast architecture.
3.  **Schema Enforcement:** We explicitly cast columns to `datetime64[ns]`, `float64`, and `int64` to match the strict validation requirements.

```python
# Import the pandas library for data manipulation and DataFrame construction.
import pandas as pd
# Import the numpy library for numerical operations and array generation.
import numpy as np
# Import the os module for filesystem operations and path validation.
import os
# Import the yaml module for parsing the configuration file.
import yaml
# Import the Faker library to generate synthetic volume data.
from faker import Faker
# Import typing modules for strict type hinting.
from typing import Dict, Any, Tuple

# Initialize the Faker instance to generate realistic large integers.
fake = Faker()
# Set the Faker seed to ensure reproducibility of the synthetic volume data.
Faker.seed(42)
# Set the NumPy random seed to ensure reproducibility of the simulated price paths.
np.random.seed(42)

# Define the function to generate and save the synthetic datasets.
def generate_and_save_synthetic_datasets(
    # The start date of the study period.
    start_date: str = "1986-01-01",
    # The end date of the study period.
    end_date: str = "2009-12-31",
    # The output filename for the Yahoo CSV.
    yahoo_filename: str = "synthetic_yahoo.csv",
    # The output filename for the Shiller Excel file.
    shiller_filename: str = "synthetic_shiller.xlsx"
) -> Tuple[str, str]:
    """
    Generates synthetic Yahoo Finance and Shiller datasets and saves them to disk.

    Purpose:
        To create high-fidelity mock datasets that mimic the exact schema, data types,
        and temporal alignment of the empirical data required by the study. This allows
        the pipeline's ingestion and validation logic to be tested.

    Inputs:
        start_date (str): The start date of the simulation in 'YYYY-MM-DD' format.
        end_date (str): The end date of the simulation in 'YYYY-MM-DD' format.
        yahoo_filename (str): The target filename for the Yahoo CSV.
        shiller_filename (str): The target filename for the Shiller Excel workbook.

    Processes:
        1. Date Generation: Creates 288 month-end business days and decimal years.
        2. Simulation: Generates a random walk for prices and a correlated EPS path.
        3. Schema Enforcement: Constructs DataFrames with exact column names and types.
        4. File I/O: Saves the DataFrames to CSV and Excel formats respectively.

    Outputs:
        Tuple[str, str]: The absolute file paths to the generated Yahoo and Shiller files.

    Raises:
        ValueError: If the generated date range does not produce exactly 288 months.
        IOError: If the files cannot be written to disk.
    """
    # 1. Generate Trading Days (Month-End Business Days)
    # Use 'BM' frequency to get the last business day of each month, mimicking Yahoo.
    dates: pd.DatetimeIndex = pd.date_range(start=start_date, end=end_date, freq='BM')
    
    # Calculate the total number of months generated.
    n_months: int = len(dates)
    # Assert that exactly 288 months were generated, as required by the study.
    if n_months != 288:
        # Raise a ValueError if the temporal span is incorrect.
        raise ValueError(f"Expected exactly 288 months, generated {n_months}.")

    # 2. Simulate Price and EPS Paths
    # Generate random normal returns with a slight positive drift.
    returns: np.ndarray = np.random.normal(loc=0.005, scale=0.04, size=n_months)
    # Calculate the cumulative sum of returns to create a price path.
    cumulative_returns: np.ndarray = np.cumsum(returns)
    # Exponentiate and scale to create a realistic starting price level (~200).
    simulated_prices: np.ndarray = 200.0 * np.exp(cumulative_returns)
    
    # Simulate EPS to roughly track prices, maintaining a P/E ratio around 15.
    # Add some random noise to the EPS path.
    simulated_eps: np.ndarray = (simulated_prices / 15.0) + np.random.normal(0, 1, size=n_months)
    # Ensure EPS remains strictly positive.
    simulated_eps = np.abs(simulated_eps) + 1.0

    # 3. Construct Yahoo Finance DataFrame
    # Initialize the dictionary with the exact required column names.
    yahoo_data: Dict[str, Any] = {
        # The Date column, formatted as strings to mimic the raw CSV.
        "Date": dates.strftime('%Y-%m-%d'),
        # Mock Open prices.
        "Open": simulated_prices * 0.99,
        # Mock High prices.
        "High": simulated_prices * 1.02,
        # Mock Low prices.
        "Low": simulated_prices * 0.98,
        # Mock Close prices.
        "Close": simulated_prices,
        # The critical Adj Close column (P_t).
        "Adj Close": simulated_prices,
        # Generate random large integers for Volume using Faker.
        "Volume": [fake.random_int(min=10000000, max=900000000) for _ in range(n_months)]
    }
    # Create the pandas DataFrame.
    df_yahoo_raw: pd.DataFrame = pd.DataFrame(yahoo_data)

    # 4. Construct Shiller DataFrame
    # Calculate decimal years: Year + (Month - 1) / 12.
    decimal_years: np.ndarray = dates.year + (dates.month - 1) / 12.0
    # Initialize the dictionary with the exact required column names.
    shiller_data: Dict[str, Any] = {
        # The decimal-year Date column.
        "Date": decimal_years,
        # Mock Price column.
        "Price": simulated_prices,
        # Mock Dividend column.
        "Dividend": simulated_prices * 0.02,
        # The critical Earnings column (EPS_t).
        "Earnings": simulated_eps,
        # Mock CPI column.
        "CPI": np.linspace(100, 215, n_months),
        # Mock Long_Rate column.
        "Long_Rate": np.linspace(8.0, 3.0, n_months),
        # Mock Real_Price column.
        "Real_Price": simulated_prices * 1.5,
        # Mock Real_Dividend column.
        "Real_Dividend": simulated_prices * 0.03,
        # Mock Real_Earnings column.
        "Real_Earnings": simulated_eps * 1.5,
        # Mock CAPE column.
        "CAPE": np.random.uniform(10, 30, size=n_months)
    }
    # Create the pandas DataFrame.
    df_shiller_raw: pd.DataFrame = pd.DataFrame(shiller_data)

    # 5. Save to Disk
    # Get the absolute path for the current working directory.
    cwd: str = os.getcwd()
    # Construct the full path for the Yahoo CSV.
    yahoo_path: str = os.path.join(cwd, yahoo_filename)
    # Construct the full path for the Shiller Excel file.
    shiller_path: str = os.path.join(cwd, shiller_filename)

    # Write the Yahoo DataFrame to CSV without an index column.
    try:
        df_yahoo_raw.to_csv(yahoo_path, index=False)
    # Catch any I/O errors during the write process.
    except IOError as e:
        # Raise a descriptive IOError.
        raise IOError(f"Failed to write Yahoo data to {yahoo_path}: {e}")

    # Write the Shiller DataFrame to Excel without an index column.
    # Note: Requires 'openpyxl' engine.
    try:
        df_shiller_raw.to_excel(shiller_path, index=False, sheet_name="Data", engine='openpyxl')
    # Catch any I/O errors during the write process.
    except IOError as e:
        # Raise a descriptive IOError.
        raise IOError(f"Failed to write Shiller data to {shiller_path}: {e}")

    # Print a success message to the console.
    print(f"Synthetic datasets generated successfully.")
    # Return the absolute file paths.
    return yahoo_path, shiller_path

# Execute the generation function and store the file paths.
yahoo_file_path, shiller_file_path = generate_and_save_synthetic_datasets()
```

### **Step 2: Loading the Configuration (`config.yaml`)**

The study relies on a deterministic configuration dictionary (`STUDY_CONFIG`) that defines all hyperparameters, prompt blocks, and evaluation metrics. We assume this file exists in the working directory as `config.yaml`.

**Methodology:**
1.  **File I/O:** Open `config.yaml` in read mode with explicit UTF-8 encoding.
2.  **Parsing:** Use `yaml.safe_load` to convert the YAML structure into a nested Python dictionary.
3.  **Validation:** Catch file existence errors and parsing errors, raising explicit exceptions to halt execution if the configuration is unavailable.

```python
# Define the function to load the YAML configuration file.
def load_study_configuration(
    # The filesystem path to the YAML configuration file.
    filepath: str = "config.yaml"
) -> Dict[str, Any]:
    """
    Loads the study configuration parameters from a YAML file into a Python dictionary.

    Purpose:
        To ingest the deterministic hyperparameters, prompt blocks, and evaluation
        metrics defined in the external configuration file, ensuring reproducibility.

    Inputs:
        filepath (str): The relative or absolute path to the YAML configuration file.

    Processes:
        1. File Access: Attempts to open the specified file in read mode.
        2. Parsing: Uses PyYAML's safe_load to parse the YAML structure securely.
        3. Validation: Catches and handles FileNotFoundError and YAMLError.

    Outputs:
        Dict[str, Any]: A nested dictionary containing the complete study configuration.

    Raises:
        TypeError: If filepath is not a string.
        FileNotFoundError: If the config.yaml file does not exist.
        yaml.YAMLError: If the file contains invalid YAML syntax.
    """
    # Validate that the filepath argument is a string.
    if not isinstance(filepath, str):
        # Raise a TypeError if the input is invalid.
        raise TypeError(f"Expected str for filepath, got {type(filepath).__name__}.")

    # Attempt to open and parse the file within a try-except block.
    try:
        # Open the file stream with explicit UTF-8 encoding.
        with open(filepath, "r", encoding="utf-8") as file:
            # Parse the YAML content safely into a Python dictionary.
            config: Dict[str, Any] = yaml.safe_load(file)
        
        # Print a success message to the console.
        print(f"Successfully loaded configuration from {filepath}")
        # Return the parsed configuration dictionary.
        return config

    # Catch the specific error if the file is missing.
    except FileNotFoundError:
        # Raise a descriptive FileNotFoundError.
        raise FileNotFoundError(f"Fatal Error: Configuration file not found at '{filepath}'.")
    # Catch any YAML parsing errors.
    except yaml.YAMLError as e:
        # Raise a descriptive YAMLError.
        raise yaml.YAMLError(f"Fatal Error: Failed to parse YAML file {filepath}: {e}")

# Load the configuration into memory.
# Note: This assumes 'config.yaml' is present in the working directory.
study_config: Dict[str, Any] = load_study_configuration("config.yaml")
```

### **Step 3: Executing the Pipeline (`execute_complete_research_pipeline`)**

With the data paths and configuration dictionary ready, we invoke the apex orchestrator. Because this is a synthetic example without real API keys, we expect the pipeline to halt at the calibration gate.

**Methodology:**
1.  **Function Call:** Pass the file paths, download date, configuration, and log path to `execute_complete_research_pipeline`.
2.  **Output Handling:** The function returns a dictionary containing the styled tables, heatmaps, and the audit report. We inspect the `status` key to determine if the pipeline succeeded or halted at the calibration gate.

```python
# ==============================================================================
# Execution of the End-to-End Study Pipeline
# ==============================================================================

# Ensure the script is being run directly.
if __name__ == "__main__":
    
    # Print an initialization message to the console.
    print("\nInitiating 'Reflexivity as Prompt' End-to-End Pipeline...")
    
    # Define the ISO-8601 download date for the Yahoo Finance data.
    download_date: str = "2026-06-06"
    # Define the path for the persistent JSONL log file.
    log_path: str = "api_execution_log.jsonl"
    
    # Execute the apex orchestrator within a try-except block to catch fatal errors.
    try:
        # Call the orchestrator, passing the generated paths and loaded config.
        # Note: In a real run, this function internally calls configure_all_llm_clients.
        # For this synthetic example, we expect it to halt at the Calibration Gate
        # because our random walk data will not match the 0.65, 0.02, 0.35 Sharpe targets.
        study_artifacts: Dict[str, Any] = execute_complete_research_pipeline(
            yahoo_csv_path=yahoo_file_path,
            shiller_excel_path=shiller_file_path,
            yahoo_download_date=download_date,
            config=study_config,
            log_file_path=log_path
        )
        
        # ==============================================================================
        # Inspecting the Outputs
        # ==============================================================================
        
        # Print a completion header.
        print("\n" + "="*80)
        print("STUDY EXECUTION COMPLETE")
        print("="*80)
        
        # Extract the execution status from the artifacts dictionary.
        pipeline_status: str = study_artifacts.get("status", "UNKNOWN")
        # Print the final status.
        print(f"Pipeline Status: {pipeline_status}")
        
        # Handle the expected calibration failure due to synthetic data.
        if pipeline_status == "CALIBRATION_FAILED":
            # Print the specific error message generated by the calibration gate.
            print("\n[Expected Halt: Data Version Discrepancy]")
            print(study_artifacts.get("error_message", "No error message provided."))
            print("\nNote: The pipeline correctly identified that the synthetic data")
            print("does not match the historical Sharpe ratio targets required by the study.")
            print("To proceed to full evaluation, real historical data must be provided.")
            
        # Handle a successful run (if real data were provided).
        elif pipeline_status == "SUCCESS":
            # 1. Accessing Main Results (Table 1 and Table 3)
            print("\n[Results Assembled Successfully]")
            print("Table 1 (Directional Accuracy) and Table 3 (Sharpe Ratios) are available")
            print("as pandas Styler objects in the artifacts dictionary.")
            
            # 2. Printing the Execution Summary
            print("\n[Execution Summary]")
            summary: Dict[str, float] = study_artifacts["execution_summary"]
            # Iterate and print the summary statistics.
            for key, value in summary.items():
                print(f"  - {key}: {value}")
                
            # 3. Printing the Final Audit Report
            print("\n" + "="*80)
            print("FINAL REPRODUCIBILITY AUDIT REPORT")
            print("="*80)
            # Extract the reproducibility report dictionary.
            report: Dict[str, Any] = study_artifacts["reproducibility_report"]
            # Print the diagnostic taxonomy results.
            print("Diagnostic Taxonomy Applied:")
            taxonomy: Dict[str, int] = report.get("diagnostic_taxonomy_applied", {})
            for category, count in taxonomy.items():
                print(f"  - {category}: {count} cells")
                
    # Catch any unexpected fatal errors that bypassed the orchestrator's internal handling.
    except Exception as e:
        # Print the fatal error message.
        print(f"\nPipeline terminated unexpectedly: {e}")
```

## Output Structure

The pipeline returns a comprehensive dictionary containing seven key artifacts:
-   **`table_1_accuracy`**: A styled pandas DataFrame (12x6 MultiIndex) showing directional accuracy.
-   **`table_3_sharpe`**: A styled pandas DataFrame showing annualized Sharpe ratios.
-   **`execution_summary`**: A dictionary detailing wall-clock time, total API calls, fallbacks, and retries.
-   **`reproducibility_report`**: The JSON-compatible audit detailing data version discrepancies vs. model drift.
-   **`heatmap_accuracy`**: A visual CSS-styled representation of the accuracy deviations.
-   **`heatmap_sharpe`**: A visual CSS-styled representation of the Sharpe deviations.
-   **`status`**: A string indicating the final execution state (`"SUCCESS"`, `"CALIBRATION_FAILED"`, or `"FATAL_ERROR"`).

## Project Structure

```
does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters/
│
├── does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters_draft.ipynb  # Main implementation notebook
├── config.yaml                           # Master configuration file (Grid, Prompts, Targets)
├── requirements.txt                      # Python package dependencies
│
├── LICENSE                               # MIT Project License File
└── README.md                             # This file
```

## Customization

The pipeline is highly customizable via the `config.yaml` file. Researchers can modify study parameters such as:
-   **Context Window Lengths:** Adjust the $W \in \{36, 60\}$ array to test the threshold at which reflexivity theory becomes actionable for different models.
-   **Position Mapping:** Alter the $\{1.0, 0.5, 0.0\}$ mapping to evaluate alternative trading strategies (e.g., allowing short selling by mapping "down" to -1.0).
-   **Historical Episodes:** Add new evaluation episodes (e.g., the 2020 COVID crash) by defining new start and end dates in the configuration, provided the underlying data spans the required periods.

## Contributing

Contributions are welcome. Please fork the repository, create a feature branch, and submit a pull request with a clear description of your changes. Adherence to PEP 8, strict type hinting (`typing` module), and the draconian requirement for line-by-line in-text comments that explain the mathematical or logical purpose of every single line of code is strictly required for all pull requests to maintain the implementation-grade standard of this repository.

## Recommended Extensions

Future extensions, building upon this foundational framework, could include:
-   **Endogenous Market Simulation:** Closing the loop by feeding the LLM's aggregate forecasts back into a synthetic price generation engine to observe true artificial reflexivity.
-   **Multi-Agent Dynamics:** Deploying heterogeneous LLMs simultaneously to simulate a market with diverse theoretical priors.
-   **Alternative Theoretical Scaffolds:** Replacing Soros's reflexivity with Minsky's Financial Instability Hypothesis or Shiller's Narrative Economics to compare the efficacy of different economic theories as reasoning prompts.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Citation

If you use this code or the methodology in your research, please cite the original paper:

```bibtex
@article{park2026reflexivity,
  title={Reflexivity as Prompt: Does Awareness of Self-Reinforcing Market Dynamics Improve LLMs as Financial Market Forecasters?},
  author={Park, Eugene},
  journal={arXiv preprint arXiv:2606.00061},
  year={2026}
}
```

For the implementation itself, you may cite this repository:
```bibtex
@misc{chirinda2026reflexivitypipeline,
  author = {Chirinda, Craig},
  title = {Reflexivity as Prompt: An Empirical Replication Pipeline},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/chirindaopensource/does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters}}
}
```

## Acknowledgments

-   Credit to **Eugene Park** for the foundational theoretical framework, the experimental design, and the operationalization of Soros's reflexivity theory into a promptable scaffold.
-   This project is built upon the exceptional tools provided by the open-source community. Sincere thanks to the developers of the scientific Python ecosystem, particularly the **NumPy** and **Pandas** contributors, as well as the maintainers of the **OpenAI**, **Anthropic**, and **Google** SDKs.


--

*This README was generated based on the structure and content of the `does_awareness_of_self_reinforcing_market_dynamics_improve_LLMs_financial_market_forecasters_draft.ipynb` notebook and follows best practices for research software documentation.*
