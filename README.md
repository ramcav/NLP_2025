# NLP_2025

## Assignment 1

Assignment 1 is about using the `nltk` library to generate text in the style of Shakespeare using the techniques of
n-grams and basic probability.

The code for the assignment can be found in the file `shakespeare/assignment_1.ipynb`.

### About the code

The code is written in Python and uses the `nltk` library to generate text in the style of Shakespeare. The programs created read the Shakespeare texts available in the `nltk` library and first run a simple pre-processing step to remove punctuation and convert the text to lowercase. Then, ngrams for the texts passed are genereated and used to determine the frequency of a word following a combination of an n-word sequence or, in other words, an `n-gram`. These frequencies are then used to calculate the probability of a word following a given n-word sequence. 

Finally, the probabilities of the words following a given n-word sequence are used to generate text in the style of Shakespeare by randomly selecting the next word based on the probabilities of the words following the n-word sequence.

### Running the code

To run the code, you will need to have Python installed on your machine. You can download Python from the official website: https://www.python.org/downloads/

After having python downloaded, you just need to create a virtual environment and install the required libraries. You can do this by running the following commands:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

After installing the required libraries, you can run the code by going to the file `shakespeare/assignment_1.ipynb` and running the cells in the notebook.

### Assessment of the generated responses

After asking 5 participants to read the generated responses and rate them on a scale of 1 to 5, the average rating was 2.5. The responses, despite being Shakesperean, were generally not coherent and did not make much sense. This is likely due to the simplicity of the model used to generate the text, as well as because this model does not take into account the context of the words in the text. It just generates text based on the probabilities of words following a given n-word sequence.

This model can be improved by using more advanced techniques or by providing a larger dataset of Shakespeare's texts and regular text so that there are more examples to learn from.