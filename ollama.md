# What is Ollama?
 Ollama is a platform for running LLMs locally on your machine. It eliminates the need for cloud-based interactions, offering privacy and faster responses.

 ## Key Features
 - Easy installation and command-line interaction
 - Support for multiple models
 - Offline usage of language model ensuring data security
  

##  How to install Ollama Locally
Ollama can be downloaded from  [official Ollama's website](https://ollama.com/ "Ollama") or from their  [Github repository](https://github.com/ollama/ollama "Ollama Github"). Just follow along installation prompt and type required based on the type of operating system. 

**Verify the installation** to confirm it is installed correctly
``` 
ollama --version
```

## Basic Commands of Ollama

Here are the basic commands to check when using ollama :   
 

 
 



- **To see what models are available:**
  ```bash
  ollama list
  ```
- **To download a specific model:**
  ```bash
  ollama download <model-name>
  ```
- **To run a model:**
  ```bash
  ollama run <model-name>
  ```
- **To customise a model: **
  ```bash
  ollama customize <model-name>
  ```
- **To stop a model:**
  ```bash
  ollama stop <model-name>
  ```
- **To uninstall a model:**
  ```bash
  ollama uninstall <model-name>
  ```

**Tips for Using Ollama**
- System Requirements: Ensure your computer meets the hardware requirements (e.g., sufficient RAM and GPU).
- Privacy: Since models run locally, your data stays on your computer.
- Updates: Regularly check for updates to Ollama or its models to access the latest features and improvements

**To uninstall a model:**
  ```bash
  ollama update
  ```
## Example Workflow
1. Install Ollama
2. Download the model
 **To uninstall a model:**
  ```bash
  ollama pull llama3.3
  ```
3. Run the model
**To uninstall a model:**
  ```bash
  ollama run llama3.3
  ``` 
4. Interact with the model by typing prompts in the terminal