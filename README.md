# Transformers
A collection of resources to study Transformers in depth. 

## The original paper
- [Attention Is All You Need](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf)


## Paper Reviews
If you want an easily comprehensible overview of the paper, Yannic Kilcher's video is a great starting point. For a more discussion-based introduction to Transformers, take a look at AISC's or Microsoft Reading Group's recording. Lastly, Rachel from Kaggle has a 3-part series/livestream, where she reads and tries to understand the paper, while responding to viewers' questions.  

- [AISC Transformer Overview](https://www.youtube.com/watch?time_continue=2175&v=S0KakHcj_rs)
- [Yannic Kilcher](https://www.youtube.com/watch?v=iDulhoQ2pro)
- [Microsoft Reading Group](https://www.youtube.com/watch?v=y96jfSz2IHY&t=2392s)
- [Kaggle Reading Group](https://www.youtube.com/watch?v=54uLU7Nxyv8&t=2182s)


## Blog Posts
Besides paper reviews, there are also incredible blog posts available. Jay Alammar's "The Illustrated Transformer", with its simple explanations and intuitive visualizations, is the best place to start understanding the different parts of the Transformer such as self-attention, the encoder-decoder architecture and positional encoding. From there, I would read Peter Bloem's blog post, which is one of the most well-written pieces I've encountered so far, with clear wording, beautiful graphics and understandable code. It goes into further detail on the self-attention mechanism and variations of the Transformer, while also providing accompanying PyTorch code. If you want to know more about different types of attention, head to Lilian Weng's blog. 
- [Jay Alammar - The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Peter Bloem - Transformers from scratch](http://www.peterbloem.nl/blog/transformers)
- [Lilian Weng - Attention? Attention!](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)
- Attention craving RNNs(https://towardsdatascience.com/attention-craving-rnns-a-journey-into-attention-mechanisms-eec840fbc26f)
- [Positional Encoding is Transformers](https://kazemnejad.com/blog/transformer_architecture_positional_encoding/)

## Lectures and Talks
Beyond blog posts and paper reviews, you can also find some amazing lectures & talks on Transformers and self-attention online. Stanford CS224u's lecture goes into more details on the math, BERT and other contextual vectors, whereas the Stanford CS224n guest lecture (by the co-authors of the Transformer and Music Transformer) cover various use cases of self-attention. Rachel (and Jeremy) from fast.ai give another great overview of Transformer in their Intro To NLP course, but also answer some of the common confusions around Transformers such as the query, key, value system and address its application to language translation. Finally, if you want to hear more from the co-authors of the Transformer, Lukasz Kaiser and Ashish Vaswani each gave a wonderful talk on their work at Pi School 2017 and RAAIS 2019 respectively.
   
- [Stanford CS224u](https://www.youtube.com/watch?v=lzBB7xoZ3Q8&t=746s)
- [Stanford CS224n](https://www.youtube.com/watch?v=5vcj8kSwBCY&t=1211s)
- [X] [Pascal Poupart: CS480/680 Lecture 19: Attention and Transformer Networks](https://www.youtube.com/watch?v=OyFJWRnt_AY)
- [fastai Introduction to Transformers](https://www.youtube.com/watch?v=AFkGPmU16QA&list=PLtmWHNX-gukKocXQOkQjuVxglSDYWsSh9&index=18&t=848s)
- [Lukasz Kaiser's Talk](https://www.youtube.com/watch?v=rBCqOTEfxvg&t=1075s)
- [Ashish Vaswani's Talk](https://www.youtube.com/watch?v=5vcj8kSwBCY&t=1212s)
- [ChrisMcCormickAI - BERT series](https://www.youtube.com/playlist?list=PLam9sigHPGwOBuH4_4fr-XvDbe5uneaf6)
- [Giuliano Giacaglia - How Transformers Work](https://www.youtube.com/watch?v=YNSziIuuSSU&list=WL&index=84)
- [Michael Phi - Illustrated Guide to Transformers Neural Network: A step by step explanation](https://www.youtube.com/watch?v=4Bdc55j80l8&list=WL&index=448)

## Code Walkthroughs 
One of the best ways to understand a concept is implementing it in code. Harvard NLP published an annotated version of the original paper with commented-out code in PyTorch, which is discussed in one of the recorded AISC sessions linked below. If you prefer TensorFlow, there is also a TensorFlow 2.0 Tutorial with a Colab notebook that you can run for free. Once you're comfortable with the basic concepts, check out the NAACL Tutorial on Transfer Learning, which has an amazing Colab that teaches you how to pre-train a GPT2-like Transformer, fine-tune it and do multi-task learning as well as an amazing slide deck full of information about recent developments in Transfer Learning for Natural Language Processing. 
- [Harvard NLP's The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
- [AISC Video Recording of Code Review in PyTorch](https://www.youtube.com/watch?v=KMY2Knr4iAs)
- [Transformers in TensorFlow 2.0](https://www.tensorflow.org/beta/tutorials/text/transformer)
- [NAACL Tutorial Slides](http://tiny.cc/NAACLTransfer)
- [NAACL Tutorial Colab](http://tiny.cc/NAACLTransferColab)
- [Question Classification w/ Transformers](https://thevatsalsaglani.medium.com/question-classification-using-self-attention-transformer-part-1-33e990636e76)
- [Mark Saroufim - Implementing BERT and transformers from scratch](https://www.youtube.com/watch?v=EPa98fyxZ-s&list=WL&index=160&t=5270s)
- [Aurélién Geron - NLP in action using Transformers](https://www.youtube.com/watch?v=07iAf5_eix0&list=WL&index=107)


## Follow-Up Papers
Since the original paper was published, there has been a massive wave of papers building on the Transformer. Most notably, BERT, GPT-2, XLNet and Reformer. 
- [Linformer](https://arxiv.org/abs/2006.04768)
- [Reformer](https://openreview.net/forum?id=rkgNKkHtvB)
- [TransformerXL](https://arxiv.org/abs/1901.02860)
- [Evolved Transformer](https://arxiv.org/abs/1901.11117)
- [Image Transformer](https://arxiv.org/abs/1802.05751)
- [Music Transformer](https://arxiv.org/abs/1809.04281)
- [TTS Transformer](https://arxiv.org/abs/1809.08895)
- [Set Transformer](https://arxiv.org/abs/1810.00825)
- [Sparse Transformer](https://arxiv.org/abs/1904.10509)
- [Levenshtein Transformer](https://arxiv.org/abs/1905.11006)
- [BERT](https://arxiv.org/abs/1810.04805)
- [GPT-1](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- [GPT-3](https://arxiv.org/abs/2005.14165)
- [UniLM](https://arxiv.org/abs/1905.03197)
- [XLNet](https://arxiv.org/abs/1906.08237)
- [MASS](https://arxiv.org/abs/1905.02450)
- [Adapative Attention Spans](https://arxiv.org/abs/1905.07799)
- [All Attention Layers](https://arxiv.org/abs/1907.01470)
- [Large Memory Layers with Product Keys](https://arxiv.org/abs/1907.05242)

### BERT
- [Jacob Devlin's ICML Talk](https://videoken.com/embed/uN4PKDp5HOU?tocitem=4)
- [AISC](https://www.youtube.com/watch?v=BhlOGGzC0Q0)
- [Yannic Kilcher](https://www.youtube.com/watch?v=-9evrZnBorM)
- [The Illustrated BERT, ELMo, and co.](http://jalammar.github.io/illustrated-bert/)
- [Yashu Seth's BERT FAQ](https://yashuseth.blog/2019/06/12/bert-explained-faqs-understand-bert-working/)
- [Chris McCormick's BERT Embeddings Tutorial](https://mccormickml.com/2019/05/14/BERT-word-embeddings-tutorial/)
- [Chris McCormick's BERT Fine-Tuning Tutorial](https://mccormickml.com/2019/07/22/BERT-fine-tuning/)

### GPT-1, GPT-2 and GPT-3
- [OpenAI's GPT-1 Blog Post](https://openai.com/blog/language-unsupervised/)
- [OpenAI's GPT-2 Blog Post](https://openai.com/blog/better-language-models/)
- [The Illustrated GPT-2](https://jalammar.github.io/illustrated-gpt2/)
- [Alec Radford's Guest Lecture on Language Models](https://www.youtube.com/watch?v=GEtbD6pqTTE&t=2057s)
- [Yannic Kilcher on GPT-2](https://www.youtube.com/watch?v=u1_qMdb0kYU)
- [Yannic Kilcher on GPT-3](https://www.youtube.com/watch?v=SY5PvZrJhLE)
- [How GPT-3 Works - Visualizations and Animations](https://jalammar.github.io/how-gpt3-works-visualizations-animations/)
- [OpenAI GPT-3 API](https://openai.com/blog/openai-api/)

### Transformer XL and XLNet
- [AISC Review of Transformer XL](https://www.youtube.com/watch?v=cXZ9YBqH3m0&t=2226s)
- [Microsoft Reading Group on Transformer XL](https://www.youtube.com/watch?v=cXZ9YBqH3m0&t=2226s)
- [Yannic Kilcher](https://www.youtube.com/watch?v=H5vpBCLo74U)
- [NLP Breakfasts' Overview of XLNet](https://www.youtube.com/watch?v=cXZ9YBqH3m0&t=2226s)


