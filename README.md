# BioSentVec Example Code

BioSentVec - a biomedical language models for vector embedding biomedical entities into 700 dimensional vector. 

Each text is reperesented as a 700 dimensional array so that it can be used in downstream tasks such as building machine learning models and visualizing the embeddings, amongst few others. 

It is important to note that this model is very specific to the biomedical domain. In order to get models which are not as specific you can use models like GloVe, Word2Vec, Sent2Vec, Bag of Words (BOW), etc.

## How to run this model

1. Please download the repo using the download button or using the following command. 
```bash
git clone https://github.com/aashish-chaubey/bsv-vector-embedding.git
```
2. Create a virtual environment using `virtualenv`

 -  **Open a Terminal or Command Prompt:**
     - For Windows, you can use the Command Prompt.
     - For MacOS or Linux, you can use the Terminal.
     - Install virtualenv
    ```bash
    python -m pip install --user virtualenv
    ```

 -  **Navigate to the Directory Where You Want to Create the Environment:**
    - Use the `cd` command followed by the path to the directory.

- **Create the Virtual Environment:**
   - Use the following command to create a new virtual environment:
     ```bash
     python -m venv myenv
     ```
    - Replace `myenv` with the name you want to give to your virtual environment.

 - **Activate the Virtual Environment:**
   - On Windows, use:
     ```
     .\myenv\Scripts\activate
     ```
   - On MacOS or Linux, use:
     ```bash
     source myenv/bin/activate
     ```
3. **Once in the virtual environment. Please install all the requirements**
    ```bash
    python -m pip install -r requirements.txt
    ```

4. Run the notebook `notebooks/sent2vec-example.ipynb`
