# Snowflake ML Container Runtime Quickstarts

## Overview

This repository provides a collection of quickstart guides to help you leverage Snowflake’s ML Container Runtime APIs for distributed model training using GPUs. With these examples, you'll learn how to execute machine learning workflows directly within Snowflake using popular frameworks like XGBoost, LightGBM, and PyTorch, and how to optimize training on GPU clusters.

These notebooks walk through the process of data loading, model training, and distributed execution using Snowflake’s Container Runtime environment. The goal is to introduce you to the Snowflake ML Container Runtime and demonstrate how to perform large-scale model training with minimal setup.

## Step-By-Step Guide

To dive into each of these quickstarts and set up your environment for distributed model training, please follow the step-by-step guides:

1. **Prerequisites**  
   Ensure you have the required environment set up with access to Snowflake’s Container Runtime APIs. For more details on setting up and accessing Snowflake Notebooks, refer to the [Snowflake Documentation](https://quickstarts.snowflake.com/guide/train-an-xgboost-model-with-gpus-using-snowflake-notebooks/index.html#3). 

2. **Data Loading** (Required Step)  
   Before proceeding to the model training quickstarts, you must load your dataset into Snowflake. Run the [step_1_load_dataset.ipynb](step_1_load_dataset.ipynb) notebook to load data into a Snowflake table. **This is a required step** for all the subsequent notebooks that perform model training, as they rely on data stored in Snowflake.

3. **Environment Setup**  
   Each quickstart provides instructions for setting up a Snowflake session, loading data from Snowflake tables, and configuring the necessary resources (CPUs, GPUs, etc.) for distributed training.

4. **Run the Quickstart Notebooks**  
   - **XGBoost**: Follow the instructions in the [XGBoost QuickStart Guide](https://github.com/snowflakedb/sfguide-getting-started-with-container-runtime-api/blob/main/XGBoost_on_GPU_Quickstart.ipynb) to configure distributed XGBoost training using GPUs.
   - **LightGBM**: Start with the [LightGBM QuickStart Guide](https://github.com/snowflakedb/sfguide-getting-started-with-container-runtime-api/blob/main/LightGBM_on_GPU_Quickstart.ipynb) to configure distributed LightGBM training using GPUs.
   - **PyTorch**: Learn how to train models using PyTorch with the [PyTorch QuickStart Guide](https://github.com/snowflakedb/sfguide-getting-started-with-container-runtime-api/blob/main/PyTorch_on_GPU_Quickstart.ipynb) and experience the benefits of distributed GPU training.

## Additional Resources

- [Snowflake Notebooks](https://docs.snowflake.com/en/user-guide/ui-snowsight/notebooks)
- [SPCS](https://docs.snowflake.com/en/LIMITEDACCESS/snowsight-notebooks/ui-snowsight-notebooks-runtime)
