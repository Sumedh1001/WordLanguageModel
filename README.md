# Word Language Model
The following repo contains code for training a word-level language model to generate text based on a sequence of previous text. This type of model, while more advanced than the quickstart models offered out-of-the-box by Skafos, can easily be converted to Core ML and saved to the edge leveraging our framework. Follow along with [this blog post](), or forge ahead.

## Fire it up!
If you want to try out this example, first fork this repo to your own github account, then clone (or pull) it into a Skafos Jupyter Lab instance:

```bash
# Clone into your JLab using HTTPS auth
$ git clone https://github.com/<your-account>/WordLanguageModel.git

# OR pull into your JLab  using HTTPS auth
$ git remote add origin https://github.com/<your account>/WordLanguageModel.git
```

## What is here?
The components of this repo are:
-  `word_language_model.ipynb` - a Python notebook that contains code to train and export a word language model suing a recurrent neural network.
-  `utilities/` - a directory that contains helper functions used by `word_language_model.ipynb`.
-  `requirements.txt` - a file describing all required Python dependencies.

## Need Help?
Please contact us with questions or feedback! Here are two ways:

-  [**Signup for our Slack Channel**](https://skafosai.slack.com)
-  [**Find us on Reddit**](https://reddit.com/r/skafos) 

### Other Resources

-  [**Read more about sequence models (RNNs, etc)**](https://towardsdatascience.com/introduction-to-sequence-models-rnn-bidirectional-rnn-lstm-gru-73927ec9df15)
-  [**Another tutorial for building a similar language model**](https://machinelearningmastery.com/how-to-develop-a-word-level-neural-language-model-in-keras/)