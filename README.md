s# Chatbot using Transformer

<p align='center'>
    <img src="/images/chatbot.jpg" alt="animation" width="1000"/>
</p>

This project involves developing an end-to-end seq2seq transformer model and training it to function as a chatbot which can respond to user inputs. Two transformer models, one with word tokenizer and one with subword tokenizer were trained for 250 epochs in Kaggle (larger epochs weren't used as training unexpectedly freezes) and the BLEU scores were evaluated.

###Results

The below table summarizes the BLEU scores obtained after training the transformer model for 250 epochs.

| Tokenizer            | BLEU score |
| :-------------------:| :--------: |
| **Word tokenizer**   | 2.679      |
| **Subword tokenizer**| 0.0        |

Both the models were requested to give responses to some questions. Below images shows their responses.


#### Model with word tokenizer
<p align='center'>
    <img src="/images/chatbot_word.png" alt="animation" width="1000"/>
</p>


#### Model with subword tokenizer
<p align='center'>
    <img src="/images/chatbot_sub.png" alt="animation" width="1000"/>
</p>
