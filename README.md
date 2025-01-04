Image Captioning Using Encoder-Decoder Transformer

Image captioning is a multidisciplinary artificial intelligence (AI) research field
that combines computer vision, natural language processing (NLP), and machine
learning techniques. It aims to automatically generate textual descriptions for
images, bridging the semantic gap between visual content and natural language. It
has gained significant attention due to its potential applications in areas such as 
assistive technologies for visually impaired individuals, content-based image retrieval,
and enhancing the accessibility of visual content on the web. Most previous works
are based on the RNN-CNN approach, which produces inferior results compared to
image captioning using the Transformer model. 

In this project, we propose a model for image captioning using CNN and Transformer architecture. The image features
are extracted using the convolutional neural network architecture Inception V3.
Instead of using traditional recurrent neural network (RNN) as decoder, we present
a Transformer architecture. The Transformer decoder leverages self-attention
mechanisms for caption generation, enabling it to effectively recognize important
objects, their attributes, and the relationships among objects in an image. The
model is trained on the Flickr-8K dataset using the Cross-Entropy Loss Function.
Our approach aims to generate syntactically and semantically correct sentences
that accurately describe the image content
