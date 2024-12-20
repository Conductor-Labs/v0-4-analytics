### Conductor Labs Validation Repository

Welcome to the **Conductor Labs Validation Repository**! This repository supports the validation of our **TEA Conductor**, a techno-economic analysis (TEA) application designed to help climate-tech startups commercialize their technologies. Conductor guides users through building comprehensive TEAs by distilling information, automating TEA generation, and enabling interactive refinement of process flows.

The **TEA Conductor** is a Python and Streamlit-based application that helps early-stage climate-tech innovators build robust techno-economic analyses (TEAs). The validation repository provides essential resources for reviewing and validating the outputs generated by Conductor, ensuring accuracy, reliability, and breadth in various industrial processes.


#### Repository Structure
- **analysis/**: Contains Jupyter notebooks for performing various analyses on the TEA outputs.
- **data/**: Stores data from batches of TEA runs, each in its own subdirectory containing:
  - `user_input.txt`: The inputs provided by the user.
  - `process_description.json`: Intermediate data generated during the TEA process.
  - `v1_dag.json`: The v1 process flow represented as a DAG.
  - `run.log`: See how the process flow was constructed
- **requirements.txt**: Lists the Python dependencies required to run the analysis notebooks.

For questions and feedback, please reach out at jesse@conductor-labs.com
