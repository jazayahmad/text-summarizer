# Text Summarizer
#### Summary
- This project is about implementing an end-to-end NLP project for text summarization using the **Hugging Face API**.
- The project includes the implementation of pipelines, components, and deployment with GitHub actions.
- The project utilizes a Transformer-based model and the Hugging Face API.

#### Highlights
- Setup and creation of a GitHub repository for code management.
- Creation of a project template to define the structure and format of the project.
- Implementation of components such as data ingestion, validation, transformation, model training, and evaluation.
- Notebook experiments to test the components before writing the modular code.
- Integration of the training and prediction pipelines.
- Creation of a user app for text summarization using a post API.
- CI/CD deployment of the project on Amazon Web Services (AWS) using GitHub actions.

#### Technical Details
- Utilization of the Hugging Face API for the implementation of the NLP project.
- Installation of Transformer libraries and other required packages.
- Usage of the logging module for information logging during runtime.
- Introduction of the concept of config box for efficient access to configuration values.
- Implementation of utility functions in the utils module, such as reading YAML files and getting file size.
- Inclusion of box exception for handling custom exceptions.
- Usage of ensure annotation for type checking and handling input validation.
- Implementation of the Pegasus CNN model for text summarization.
- Training and evaluation of the model using the dataset provided.
- Saving and loading of the trained model and tokenizer.
- Generating predictions using the trained model and displaying the summary output.