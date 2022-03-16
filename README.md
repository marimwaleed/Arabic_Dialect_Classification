# Arabic_Dialect_Classification
Arabic Dialect Classification and preprocessing Data Witch scraped from API 

Arabic has a widely varying collection of dialects. Many of these dialects remain under-studied due to the rarity of resources. The goal of the shared task is to alleviate this bottleneck in the context of fine-grained Arabic dialect identification. Dialect identification is the task of classifying the dialect of the tweet writer given the tweet itself.


![image](https://user-images.githubusercontent.com/85671264/158654411-af35fd71-ec2f-4ccc-8c5f-fd0ea9e235e9.png)

Recurrent Neural Networks suffer from short-term memory. If a sequence is long enough, they’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNN’s may leave out important information from the beginning.
During back propagation, recurrent neural networks suffer from the vanishing gradient problem. Gradients are values used to update a neural networks weights. The vanishing gradient problem is when the gradient shrinks as it back propagates through time. If a gradient value becomes extremely small, it doesn’t contribute too much learning.

These gates can learn which data in a sequence is important to keep or throw away. By doing that, it can pass relevant information down the long chain of sequences to make predictions. Almost all state of the art results based on recurrent neural networks are achieved with these two networks. LSTM’s and GRU’s can be found in speech recognition, speech synthesis, and text generation. 
Ok, so by the end of this post you should have a solid understanding of why LSTM’s and GRU’s are good at processing long sequences. I am going to approach this with intuitive explanations and illustrations and avoid as much math as possible.
![LSTM-Vs-GRU-Network-Which-Has-better-Performance](https://user-images.githubusercontent.com/85671264/158656777-f39c35e5-88ad-4ae3-935c-33af84f2d775.png)


