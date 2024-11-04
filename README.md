# LLM Fine-tuning

This project takes one LLM that can fit in a single GPU and fine-tunes it on SQuAD. All the details and steps involved are documented in the *llm_finetuning.ipynb* notebook.

## Dependencies

1. This repository uses Python 3.11.5. The use of [pyenv](https://github.com/pyenv/pyenv) is recommended:
```bash
$ pyenv install 3.11.5
$ pyenv local 3.11.5
```
2. To create a Python Virtual Environment (virtualenv) to run the code, type: 
```python -m venv my-env```  

3. Activate the new environment:
    * Windows: ```my-env\Scripts\activate.bat```
    * macOS and Linux: ```source my-env/bin/activate``` 
4. Install all the dependencies from *requirements.txt*:  
```pip install -r requirements.txt```
