# Neural-Machine-Translation-English-Hindi-
Neural Machine Translation (NMT) has today become the most powerful way to perform the task of translating text from one language to another. Back in the old days,translation task was difficult to perform and led to disfluency . Traditional phrase-based translation systems use to perform their task by dividing up source sentences into multiple chunks and then translated them phrase-by-phrase.This was not like how we, humans, translate.We translate by first understanding the meaning of sentence .Neural Machine Translation (NMT) work that way . Neural Machine Translation first read the sentence in the input language and creates a thought vector from this sentence. Then, it processes the sentence vector to emit a translation. Neural machine translation usually use Recurrent Neural Network .Neural Machine Translation use recurrent neural networks by coupling them to external memory resources which they can interact with by attentional processes.
Neural Machine Translation work as follows:

  -*1)Dataset is prepared by loading dataset ,removing spaces and special character, tokenizing the dataset ,padding each sentence to a maximum length.
  -*2)Creating the encoder (encode information of source sequence into real- valued vector)and decoder(produce output sequence).
  Train the encoder-decoder model.
  -*3)In our project we used Tensorflow framework to offer low –level working example of the concept. We train a sequence to sequence model for Hindi to English translation.
