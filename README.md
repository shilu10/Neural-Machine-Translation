## Machine Translation
- Machine translation is one of the hot topic in the nlp, also known as a 
language translation. There are multiple models that are used to achieve an higher accuracy in the domain of the language translation. 
- Most Common architecture used in the machine translation is a seq2seq, which is nothing but a Encoder-Decoder architecture. Encoder takes the input language as an input, and encode it and provides a context vector(which contains information about the input sentences), decoder takes the context vector and decode to the target language.

## Model Architecture
- Vanilla Encoder Decoder Architecture: 
<img src="https://miro.medium.com/v2/resize:fit:786/format:webp/1*1JcHGUU7rFgtXC_mydUA_Q.jpeg"></img>

- Encoder Decoder with Attention:
<img  src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*XTY2_xgVt24XuFhm_-A5Sw.png"></img>

## File Structure:
- seq_seq_vanilla.ipynb       : contains the code for the vanilla Encoder Decoder with gru.
- seq_seq_attention.ipynb  : Contains the code for the Encoder Decoder with attention, Two types of attention Dot Product attention and Additive Attention(Bahdanau attention).

