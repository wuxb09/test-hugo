---
title: "Test Lilian HTML"
summary: Learn About All Features in PaperMod
date: 2021-01-20
weight: 1
aliases: ["/papermod-features"]
tags: ["PaperMod"]
author: "Test Lilian"
---

<!DOCTYPE html>
<html lang="en" dir="auto">

<head><meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta name="robots" content="index, follow">
<title>An Overview of Deep Learning for Curious People | Lil&#39;Log</title>
<meta name="keywords" content="foundation, tutorial" />
<meta name="description" content="(The post was originated from my talk for WiMLDS x Fintech meetup hosted by Affirm.)
I believe many of you have watched or heard of the games between AlphaGo and professional Go player Lee Sedol in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he lost by 1-4 in this series versus AlphaGo.">
<meta name="author" content="Lilian Weng">
<link rel="canonical" href="https://wuxb09.github.io/test-lilian/posts/2017-06-21-overview/" />
<link crossorigin="anonymous" href="/assets/css/stylesheet.min.67a6fb6e33089cb29e856bcc95d7aa39f70049a42b123105531265a0d9f1258b.css" integrity="sha256-Z6b7bjMInLKehWvMldeqOfcASaQrEjEFUxJloNnxJYs=" rel="preload stylesheet" as="style">
<script defer crossorigin="anonymous" src="/assets/js/highlight.min.7680afc38aa6b15ddf158a4f3780b7b1f7dde7e91d26f073e6229bb7a0793c92.js" integrity="sha256-doCvw4qmsV3fFYpPN4C3sffd5&#43;kdJvBz5iKbt6B5PJI="
    onload="hljs.initHighlightingOnLoad();"></script>
<link rel="icon" href="https://wuxb09.github.io/test-lilian/favicon_peach.ico">
<link rel="icon" type="image/png" sizes="16x16" href="https://wuxb09.github.io/test-lilian/favicon-16x16.png">
<link rel="icon" type="image/png" sizes="32x32" href="https://wuxb09.github.io/test-lilian/favicon-32x32.png">
<link rel="apple-touch-icon" href="https://wuxb09.github.io/test-lilian/apple-touch-icon.png">
<link rel="mask-icon" href="https://wuxb09.github.io/test-lilian/safari-pinned-tab.svg">
<meta name="theme-color" content="#2e2e33">
<meta name="msapplication-TileColor" content="#2e2e33">
<noscript>
    <style>
        #theme-toggle,
        .top-link {
            display: none;
        }

    </style>
    <style>
        @media (prefers-color-scheme: dark) {
            :root {
                --theme: rgb(29, 30, 32);
                --entry: rgb(46, 46, 51);
                --primary: rgb(218, 218, 219);
                --secondary: rgb(155, 156, 157);
                --tertiary: rgb(65, 66, 68);
                --content: rgb(196, 196, 197);
                --hljs-bg: rgb(46, 46, 51);
                --code-bg: rgb(55, 56, 62);
                --border: rgb(51, 51, 51);
            }

            .list {
                background: var(--theme);
            }

            .list:not(.dark)::-webkit-scrollbar-track {
                background: 0 0;
            }

            .list:not(.dark)::-webkit-scrollbar-thumb {
                border-color: var(--theme);
            }
        }

    </style>
</noscript>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-HFT45VFBX6"></script>
<script>
var doNotTrack = false;
if (!doNotTrack) {
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-HFT45VFBX6', { 'anonymize_ip': false });
}
</script>
<meta property="og:title" content="An Overview of Deep Learning for Curious People" />
<meta property="og:description" content="(The post was originated from my talk for WiMLDS x Fintech meetup hosted by Affirm.)
I believe many of you have watched or heard of the games between AlphaGo and professional Go player Lee Sedol in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he lost by 1-4 in this series versus AlphaGo." />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://wuxb09.github.io/test-lilian/posts/2017-06-21-overview/" /><meta property="article:section" content="posts" />
<meta property="article:published_time" content="2017-06-21T00:00:00&#43;00:00" />
<meta property="article:modified_time" content="2017-06-21T00:00:00&#43;00:00" />

<meta name="twitter:card" content="summary"/>
<meta name="twitter:title" content="An Overview of Deep Learning for Curious People"/>
<meta name="twitter:description" content="(The post was originated from my talk for WiMLDS x Fintech meetup hosted by Affirm.)
I believe many of you have watched or heard of the games between AlphaGo and professional Go player Lee Sedol in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he lost by 1-4 in this series versus AlphaGo."/>


<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position":  1 ,
      "name": "Posts",
      "item": "https://wuxb09.github.io/test-lilian/posts/"
    }, 
    {
      "@type": "ListItem",
      "position":  2 ,
      "name": "An Overview of Deep Learning for Curious People",
      "item": "https://wuxb09.github.io/test-lilian/posts/2017-06-21-overview/"
    }
  ]
}
</script>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "An Overview of Deep Learning for Curious People",
  "name": "An Overview of Deep Learning for Curious People",
  "description": "(The post was originated from my talk for WiMLDS x Fintech meetup hosted by Affirm.)\nI believe many of you have watched or heard of the games between AlphaGo and professional Go player Lee Sedol in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he lost by 1-4 in this series versus AlphaGo.",
  "keywords": [
    "foundation", "tutorial"
  ],
  "articleBody": "(The post was originated from my talk for WiMLDS x Fintech meetup hosted by Affirm.)\nI believe many of you have watched or heard of the games between AlphaGo and professional Go player Lee Sedol in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he lost by 1-4 in this series versus AlphaGo. Before this, Go was considered to be an intractable game for computers to master, as its simple rules lay out an exponential number of variations in the board positions, many more than what in Chess. This event surely highlighted 2016 as a big year for AI. Because of AlphaGo, much attention has been attracted to the progress of AI.\nMeanwhile, many companies are spending resources on pushing the edges of AI applications, that indeed have the potential to change or even revolutionize how we are gonna live. Familiar examples include self-driving cars, chatbots, home assistant devices and many others. One of the secret receipts behind the progress we have had in recent years is deep learning.\nWhy Does Deep Learning Work Now? Deep learning models, in simple words, are large and deep artificial neural nets. A neural network (“NN”) can be well presented in a directed acyclic graph: the input layer takes in signal vectors; one or multiple hidden layers process the outputs of the previous layer. The initial concept of a neural network can be traced back to more than half a century ago. But why does it work now? Why do people start talking about them all of a sudden?\nFig. 1. A three-layer artificial neural network. (Image source: http://cs231n.github.io/convolutional-networks/#conv) The reason is surprisingly simple:\n We have a lot more data. We have much powerful computers.  A large and deep neural network has many more layers + many more nodes in each layer, which results in exponentially many more parameters to tune. Without enough data, we cannot learn parameters efficiently. Without powerful computers, learning would be too slow and insufficient.\nHere is an interesting plot presenting the relationship between the data scale and the model performance, proposed by Andrew Ng in his “Nuts and Bolts of Applying Deep Learning” talk. On a small dataset, traditional algorithms (Regression, Random Forests, SVM, GBM, etc.) or statistical learning does a great job, but once the data scale goes up to the sky, the large NN outperforms others. Partially because compared to a traditional ML model, a neural network model has many more parameters and has the capability to learn complicated nonlinear patterns. Thus we expect the model to pick the most helpful features by itself without too much expert-involved manual feature engineering.\nFig. 2. The data scale versus the model performance. (Recreated based on: https://youtu.be/F1ka6a13S9I) Deep Learning Models Next, let’s go through a few classical deep learning models.\nConvolutional Neural Network Convolutional neural networks, short for “CNN”, is a type of feed-forward artificial neural networks, in which the connectivity pattern between its neurons is inspired by the organization of the visual cortex system. The primary visual cortex (V1) does edge detection out of the raw visual input from the retina. The secondary visual cortex (V2), also called prestriate cortex, receives the edge features from V1 and extracts simple visual properties such as orientation, spatial frequency, and color. The visual area V4 handles more complicated object attributes. All the processed visual features flow into the final logic unit, inferior temporal gyrus (IT), for object recognition. The shortcut between V1 and V4 inspires a special type of CNN with connections between non-adjacent layers: Residual Net (He, et al. 2016) containing “Residual Block” which supports some input of one layer to be passed to the component two layers later.\nFig. 3. Illustration of the human visual cortex system. (Image source: Wang \u0026 Raj 2017) Convolution is a mathematical term, here referring to an operation between two matrices. The convolutional layer has a fixed small matrix defined, also called kernel or filter. As the kernel is sliding, or convolving, across the matrix representation of the input image, it is computing the element-wise multiplication of the values in the kernel matrix and the original image values. Specially designed kernels can process images for common purposes like blurring, sharpening, edge detection and many others, fast and efficiently.\nFig. 4. The LeNet architecture consists of two sets of convolutional, activation, and pooling layers, followed by a fully-connected layer, activation, another fully-connected layer, and finally a softmax classifier (Image source: http://deeplearning.net/tutorial/lenet.html) Convolutional and pooling (or “sub-sampling” in Fig. 4) layers act like the V1, V2 and V4 visual cortex units, responding to feature extraction. The object recognition reasoning happens in the later fully-connected layers which consume the extracted features.\nRecurrent Neural Network A sequence model is usually designed to transform an input sequence into an output sequence that lives in a different domain. Recurrent neural network, short for “RNN”, is suitable for this purpose and has shown tremendous improvement in problems like handwriting recognition, speech recognition, and machine translation (Sutskever et al. 2011, Liwicki et al. 2007).\nA recurrent neural network model is born with the capability to process long sequential data and to tackle tasks with context spreading in time. The model processes one element in the sequence at one time step. After computation, the newly updated unit state is passed down to the next time step to facilitate the computation of the next element. Imagine the case when an RNN model reads all the Wikipedia articles, character by character, and then it can predict the following words given the context.\nFig. 5. A recurrent neural network with one hidden unit (left) and its unrolling version in time (right). The unrolling version illustrates what happens in time: $s\\_{t-1}$, $s\\_{t}$, and $s\\_{t+1}$ are the same unit with different states at different time steps $t-1$, $t$, and $t+1$. (Image source: LeCun, Bengio, and Hinton, 2015; Fig. 5) However, simple perceptron neurons that linearly combine the current input element and the last unit state may easily lose the long-term dependencies. For example, we start a sentence with “Alice is working at …” and later after a whole paragraph, we want to start the next sentence with “She” or “He” correctly. If the model forgets the character’s name “Alice”, we can never know. To resolve the issue, researchers created a special neuron with a much more complicated internal structure for memorizing long-term context, named “Long-short term memory (LSTM)\" cell. It is smart enough to learn for how long it should memorize the old information, when to forget, when to make use of the new data, and how to combine the old memory with new input. This introduction is so well written that I recommend everyone with interest in LSTM to read it. It has been officially promoted in the Tensorflow documentation ;-)\nFig. 6. The structure of a LSTM cell. (Image source: http://colah.github.io/posts/2015-08-Understanding-LSTMs) To demonstrate the power of RNNs, Andrej Karpathy built a character-based language model using RNN with LSTM cells. Without knowing any English vocabulary beforehand, the model could learn the relationship between characters to form words and then the relationship between words to form sentences. It could achieve a decent performance even without a huge set of training data.\nFig. 7. A character-based recurrent neural network model writes like a Shakespeare. (Image source: http://karpathy.github.io/2015/05/21/rnn-effectiveness) RNN: Sequence-to-Sequence Model The sequence-to-sequence model is an extended version of RNN, but its application field is distinguishable enough that I would like to list it in a separated section. Same as RNN, a sequence-to-sequence model operates on sequential data, but particularly it is commonly used to develop chatbots or personal assistants, both generating meaningful response for input questions. A sequence-to-sequence model consists of two RNNs, encoder and decoder. The encoder learns the contextual information from the input words and then hands over the knowledge to the decoder side through a “context vector” (or “thought vector”, as shown in Fig 8.). Finally, the decoder consumes the context vector and generates proper responses.\nFig. 8. A sequence-to-sequence model for generating Gmail auto replies. (Image source: https://research.googleblog.com/2015/11/computer-respond-to-this-email.html) Autoencoders Different from the previous models, autoencoders are for unsupervised learning. It is designed to learn a low-dimensional representation of a high-dimensional data set, similar to what Principal Components Analysis (PCA) does. The autoencoder model tries to learn an approximation function $ f(x) \\approx x $ to reproduce the input data. However, it is restricted by a bottleneck layer in the middle with a very small number of nodes. With limited capacity, the model is forced to form a very efficient encoding of the data, that is essentially the low-dimensional code we learned.\nFig. 9. An autoencoder model has a bottleneck layer with only a few neurons. (Image source: Geoffrey Hinton’s Coursera class \"Neural Networks for Machine Learning\" - Week 15) Hinton and Salakhutdinov used autoencoders to compress documents on a variety of topics. As shown in Fig 10, when both PCA and autoencoder were applied to reduce the documents onto two dimensions, autoencoder demonstrated a much better outcome. With the help of autoencoder, we can do efficient data compression to speed up the information retrieval including both documents and images.\nFig. 10. The outputs of PCA (left) and autoencoder (right) when both try to compress documents into two numbers. (Image source: Hinton \u0026 Salakhutdinov 2006) Reinforcement (Deep) Learning Since I started my post with AlphaGo, let us dig a bit more on why AlphaGo worked out. Reinforcement learning (“RL”) is one of the secrets behind its success. RL is a subfield of machine learning which allows machines and software agents to automatically determine the optimal behavior within a given context, with a goal to maximize the long-term performance measured by a given metric.\nFig. 11. AlphaGo neural network training pipeline and architecture. (Image source: Silver et al. 2016) The AlphaGo system starts with a supervised learning process to train a fast rollout policy and a policy network, relying on the manually curated training dataset of professional players' games. It learns what is the best strategy given the current position on the game board. Then it applies reinforcement learning by setting up self-play games. The RL policy network gets improved when it wins more and more games against previous versions of the policy network. In the self-play stage, AlphaGo becomes stronger and stronger by playing against itself without requiring additional external training data.\nGenerative Adversarial Network Generative adversarial network, short for “GAN”, is a type of deep generative models. GAN is able to create new examples after learning through the real data. It is consist of two models competing against each other in a zero-sum game framework. The famous deep learning researcher Yann LeCun gave it a super high praise: Generative Adversarial Network is the most interesting idea in the last ten years in machine learning. (See the Quora question: “What are some recent and potentially upcoming breakthroughs in deep learning?\")\nFig. 12. The architecture of a generative adversarial network. (Image source: http://www.kdnuggets.com/2017/01/generative-adversarial-networks-hot-topic-machine-learning.html) In the original GAN paper, GAN was proposed to generate meaningful images after learning from real photos. It comprises two independent models: the Generator and the Discriminator. The generator produces fake images and sends the output to the discriminator model. The discriminator works like a judge, as it is optimized for identifying the real photos from the fake ones. The generator model is trying hard to cheat the discriminator while the judge is trying hard not to be cheated. This interesting zero-sum game between these two models motivates both to develop their designed skills and improve their functionalities. Eventually, we take the generator model for producing new images.\nToolkits and Libraries After learning all these models, you may start wondering how you can implement the models and use them for real. Fortunately, we have many open source toolkits and libraries for building deep learning models. Tensorflow is fairly new but has attracted a lot of popularity. It turns out, TensorFlow was the most forked Github project of 2015. All that happened in a period of 2 months after its release in Nov 2015.\nHow to Learn? If you are very new to the field and willing to devote some time to studying deep learning in a more systematic way, I would recommend you to start with the book Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville. The Coursera course “Neural Networks for Machine Learning” by Geoffrey Hinton (Godfather of deep learning!). The content for the course was prepared around 2006, pretty old, but it helps you build up a solid foundation for understanding deep learning models and expedite further exploration.\nMeanwhile, maintain your curiosity and passion. The field is making progress every day. Even classical or widely adopted deep learning models may just have been proposed 1-2 years ago. Reading academic papers can help you learn stuff in depth and keep up with the cutting-edge findings.\nUseful resources  Google Scholar: http://scholar.google.com arXiv cs section: https://arxiv.org/list/cs/recent Unsupervised Feature Learning and Deep Learning Tutorial Tensorflow Tutorials Data Science Weekly KDnuggets Tons of blog posts and online tutorials Related Cousera courses awesome-deep-learning-papers  Blog posts mentioned  Explained Visually: Image Kernels Understanding LSTM Networks The Unreasonable Effectiveness of Recurrent Neural Networks Computer, respond to this email.  Interesting blogs worthy of checking  www.wildml.com colah.github.io karpathy.github.io blog.openai.com  Papers mentioned [1] He, Kaiming, et al. “Deep residual learning for image recognition.\" Proc. IEEE Conf. on computer vision and pattern recognition. 2016.\n[2] Wang, Haohan, Bhiksha Raj, and Eric P. Xing. “On the Origin of Deep Learning.\" arXiv preprint arXiv:1702.07800, 2017.\n[3] Sutskever, Ilya, James Martens, and Geoffrey E. Hinton. “Generating text with recurrent neural networks.\" Proc. of the 28th Intl. Conf. on Machine Learning (ICML). 2011.\n[4] Liwicki, Marcus, et al. “A novel approach to on-line handwriting recognition based on bidirectional long short-term memory networks.\" Proc. of 9th Intl. Conf. on Document Analysis and Recognition. 2007.\n[5] LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. “Deep learning.\" Nature 521.7553 (2015): 436-444.\n[6] Hochreiter, Sepp, and Jurgen Schmidhuber. “Long short-term memory.\" Neural computation 9.8 (1997): 1735-1780.\n[7] Cho, Kyunghyun. et al. “Learning phrase representations using RNN encoder-decoder for statistical machine translation.\" Proc. Conference on Empirical Methods in Natural Language Processing 1724–1734 (2014).\n[8] Hinton, Geoffrey E., and Ruslan R. Salakhutdinov. “Reducing the dimensionality of data with neural networks.\" science 313.5786 (2006): 504-507.\n[9] Silver, David, et al. “Mastering the game of Go with deep neural networks and tree search.\" Nature 529.7587 (2016): 484-489.\n[10] Goodfellow, Ian, et al. “Generative adversarial nets.\" NIPS, 2014.\n",
  "wordCount" : "2419",
  "inLanguage": "en",
  "datePublished": "2017-06-21T00:00:00Z",
  "dateModified": "2017-06-21T00:00:00Z",
  "author":{
    "@type": "Person",
    "name": "Lilian Weng"
  },
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://wuxb09.github.io/test-lilian/posts/2017-06-21-overview/"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Lil'Log",
    "logo": {
      "@type": "ImageObject",
      "url": "https://wuxb09.github.io/test-lilian/favicon_peach.ico"
    }
  }
}
</script>
</head>

<body class="" id="top">
<script>
    if (localStorage.getItem("pref-theme") === "dark") {
        document.body.classList.add('dark');
    } else if (localStorage.getItem("pref-theme") === "light") {
        document.body.classList.remove('dark')
    } else if (window.matchMedia('(prefers-color-scheme: dark)').matches) {
        document.body.classList.add('dark');
    }

</script>

<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$','$$'], ['\\[', '\\]']],
      processEscapes: true,
      processEnvironments: true
    },
    options: {
      skipHtmlTags: ['script', 'noscript', 'style', 'textarea', 'pre']
    }
  };

  window.addEventListener('load', (event) => {
      document.querySelectorAll("mjx-container").forEach(function(x){
        x.parentElement.classList += 'has-jax'})
    });

</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


<main class="main">

<article class="post-single">
  <div class="post-content"><!-- Starting earlier this year, I grew a strong curiosity of deep learning and spent some time reading about this field. To document what I’ve learned and to provide some interesting pointers to people with similar interests, I wrote this overview of deep learning models and their applications. -->
<p><span style="color: #aaaaaa;">(The post was originated from my talk for <a href="http://wimlds.org/chapters/about-bay-area/">WiMLDS x Fintech meetup</a> hosted by <a href="www.affirm.com">Affirm</a>.)</span></p>
<p>I believe many of you have watched or heard of the <a href="https://youtu.be/vFr3K2DORc8">games</a> between AlphaGo and professional Go player <a href="https://en.wikipedia.org/wiki/Lee_Sedol">Lee Sedol</a> in 2016. Lee has the highest rank of nine dan and many world championships. No doubt, he is one of the best Go players in the world, but he <a href="https://www.scientificamerican.com/article/how-the-computer-beat-the-go-master/">lost by 1-4</a> in this series versus AlphaGo. Before this, Go was considered to be an intractable game for computers to master, as its simple rules lay out an exponential number of variations in the board positions, many more than what in Chess. This event surely highlighted 2016 as a big year for AI. Because of AlphaGo, much attention has been attracted to the progress of AI.</p>
<p>Meanwhile, many companies are spending resources on pushing the edges of AI applications, that indeed have the potential to change or even revolutionize how we are gonna live. Familiar examples include self-driving cars, chatbots, home assistant devices and many others. One of the secret receipts behind the progress we have had in recent years is deep learning.</p>
<h1 id="why-does-deep-learning-work-now">Why Does Deep Learning Work Now?<a hidden class="anchor" aria-hidden="true" href="#why-does-deep-learning-work-now">#</a></h1>
<p>Deep learning models, in simple words, are large and deep artificial neural nets. A neural network (&ldquo;NN&rdquo;) can be well presented in a <a href="https://en.wikipedia.org/wiki/Directed_acyclic_graph">directed acyclic graph</a>: the input layer takes in signal vectors; one or multiple hidden layers process the outputs of the previous layer. The initial concept of a neural network can be traced back to more than <a href="https://cs.stanford.edu/people/eroberts/courses/soco/projects/neural-networks/History/history1.html">half a century ago</a>. But why does it work now? Why do people start talking about them all of a sudden?</p>
<img src="ANN.png" style="width: 400px; max-width: 100%;" class="center" />
<figcaption>Fig. 1. A three-layer artificial neural network. (Image source: <a href="http://cs231n.github.io/convolutional-networks/#conv" target="_blank">http://cs231n.github.io/convolutional-networks/#conv</a>)</figcaption>
<p>The reason is surprisingly simple:</p>
<ul>
<li>We have a lot <strong>more data</strong>.</li>
<li>We have <strong>much powerful computers</strong>.</li>
</ul>
<p>A large and deep neural network has many more layers + many more nodes in each layer, which results in exponentially many more parameters to tune. Without enough data, we cannot learn parameters efficiently. Without powerful computers, learning would be too slow and insufficient.</p>
<p>Here is an interesting plot presenting the relationship between the data scale and the model performance, proposed by Andrew Ng in his &ldquo;<a href="https://youtu.be/F1ka6a13S9I">Nuts and Bolts of Applying Deep Learning</a>&rdquo; talk. On a small dataset, traditional algorithms (Regression, Random Forests, SVM, GBM, etc.) or statistical learning does a great job, but once the data scale goes up to the sky, the large NN outperforms others. Partially because compared to a traditional ML model, a neural network model has many more parameters and has the capability to learn complicated nonlinear patterns. Thus we expect the model to pick the most helpful features by itself without too much expert-involved manual feature engineering.</p>
<img src="data_size_vs_model_performance.png" style="width: 400px; max-width: 100%;" class="center" />
<figcaption>Fig. 2. The data scale versus the model performance. (Recreated based on: <a href="https://youtu.be/F1ka6a13S9I" target="_blank">https://youtu.be/F1ka6a13S9I</a>)</figcaption>
<h1 id="deep-learning-models">Deep Learning Models<a hidden class="anchor" aria-hidden="true" href="#deep-learning-models">#</a></h1>
<p>Next, let&rsquo;s go through a few classical deep learning models.</p>
<h2 id="convolutional-neural-network">Convolutional Neural Network<a hidden class="anchor" aria-hidden="true" href="#convolutional-neural-network">#</a></h2>
<p>Convolutional neural networks, short for &ldquo;CNN&rdquo;, is a type of feed-forward artificial neural networks, in which the connectivity pattern between its neurons is inspired by the organization of the visual cortex system. The primary visual cortex (V1) does edge detection out of the raw visual input from the retina. The secondary visual cortex (V2), also called prestriate cortex, receives the edge features from V1 and extracts simple visual properties such as orientation, spatial frequency, and color. The visual area V4 handles more complicated object attributes. All the processed visual features flow into the final logic unit, inferior temporal gyrus (IT), for object recognition. The shortcut between V1 and V4 inspires a special type of CNN with connections between non-adjacent layers: Residual Net (<a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">He, et al. 2016</a>) containing &ldquo;Residual Block&rdquo; which supports some input of one layer to be passed to the component two layers later.</p>
<img src="visual_cortex_system.png" style="width: 680px; max-width: 100%;" class="center" />
<figcaption>Fig. 3. Illustration of the human visual cortex system. (Image source: <a href="https://arxiv.org/abs/1702.07800" target="_blank">Wang & Raj 2017</a>)</figcaption>
<p>Convolution is a mathematical term, here referring to an operation between two matrices. The convolutional layer has a fixed small matrix defined, also called kernel or filter. As the kernel is sliding, or convolving, across the matrix representation of the input image, it is computing the element-wise multiplication of the values in the kernel matrix and the original image values. <a href="http://setosa.io/ev/image-kernels/">Specially designed kernels</a> can process images for common purposes like blurring, sharpening, edge detection and many others, fast and efficiently.</p>
<img src="lenet.png" style="padding-bottom: 3px;" class="center" />
<figcaption>Fig. 4. The LeNet architecture consists of two sets of convolutional, activation, and pooling layers, followed by a fully-connected layer, activation, another fully-connected layer, and finally a softmax classifier (Image source: <a href="http://deeplearning.net/tutorial/lenet.html" target="_blank">http://deeplearning.net/tutorial/lenet.html</a>)</figcaption>
<p><a href="http://ufldl.stanford.edu/tutorial/supervised/FeatureExtractionUsingConvolution/">Convolutional</a> and <a href="http://ufldl.stanford.edu/tutorial/supervised/Pooling/">pooling</a> (or &ldquo;sub-sampling&rdquo; in Fig. 4) layers act like the V1, V2 and V4 visual cortex units, responding to feature extraction. The object recognition reasoning happens in the later fully-connected layers which consume the extracted features.</p>
<h2 id="recurrent-neural-network">Recurrent Neural Network<a hidden class="anchor" aria-hidden="true" href="#recurrent-neural-network">#</a></h2>
<p>A sequence model is usually designed to transform an input sequence into an output sequence that lives in a different domain. Recurrent neural network, short for &ldquo;RNN&rdquo;, is suitable for this purpose and has shown tremendous improvement in problems like handwriting recognition, speech recognition, and machine translation (<a href="http://machinelearning.wustl.edu/mlpapers/paper_files/ICML2011Sutskever_524.pdf">Sutskever et al. 2011</a>, <a href="http://www6.in.tum.de/Main/Publications/Liwicki2007a.pdf">Liwicki et al. 2007</a>).</p>
<p>A recurrent neural network model is born with the capability to process long sequential data and to tackle tasks with context spreading in time. The model processes one element in the sequence at one time step. After computation, the newly updated unit state is passed down to the next time step to facilitate the computation of the next element. Imagine the case when an RNN model reads all the Wikipedia articles, character by character, and then it can predict the following words given the context.</p>
<img src="RNN.png" style="width: 500px; max-width: 100%;" class="center" />
<figcaption>Fig. 5. A recurrent neural network with one hidden unit (left) and its unrolling version in time (right). The unrolling version illustrates what happens in time: $s\_{t-1}$, $s\_{t}$, and $s\_{t+1}$ are the same unit with different states at different time steps $t-1$, $t$, and $t+1$. (Image source: <a href="http://pages.cs.wisc.edu/~dyer/cs540/handouts/deep-learning-nature2015.pdf" target="_blank">LeCun, Bengio, and Hinton, 2015</a>; <a href="https://www.nature.com/nature/journal/v521/n7553/fig_tab/nature14539_F5.html" target="_blank">Fig. 5</a>)</figcaption>
<p>However, simple perceptron neurons that linearly combine the current input element and the last unit state may easily lose the long-term dependencies. For example, we start a sentence with &ldquo;Alice is working at &hellip;&rdquo; and later after a whole paragraph, we want to start the next sentence with &ldquo;She&rdquo; or &ldquo;He&rdquo; correctly. If the model forgets the character&rsquo;s name &ldquo;Alice&rdquo;, we can never know. To resolve the issue, researchers created a special neuron with a much more complicated internal structure for memorizing long-term context, named <a href="http://web.eecs.utk.edu/~itamar/courses/ECE-692/Bobby_paper1.pdf">&ldquo;Long-short term memory (LSTM)&quot;</a> cell. It is smart enough to learn for how long it should memorize the old information, when to forget, when to make use of the new data, and how to combine the old memory with new input. This <a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs/">introduction</a> is so well written that I recommend everyone with interest in LSTM to read it. It has been officially promoted in the <a href="https://www.tensorflow.org/tutorials/recurrent">Tensorflow documentation</a> ;-)</p>
<img src="LSTM.png" style="width: 320px; max-width: 100%;" class="center" />
<figcaption>Fig. 6. The structure of a LSTM cell. (Image source: <a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs" target="_blank">http://colah.github.io/posts/2015-08-Understanding-LSTMs</a>)</figcaption>
<p>To demonstrate the power of RNNs, <a href="http://karpathy.github.io/2015/05/21/rnn-effectiveness/">Andrej Karpathy</a> built a character-based language model using RNN with LSTM cells.  Without knowing any English vocabulary beforehand, the model could learn the relationship between characters to form words and then the relationship between words to form sentences. It could achieve a decent performance even without a huge set of training data.</p>
<img src="rnn_shakespeare.png" style="width: 500px" class="center" />
<figcaption>Fig. 7. A character-based recurrent neural network model writes like a Shakespeare. (Image source: <a href="http://karpathy.github.io/2015/05/21/rnn-effectiveness" target="_blank">http://karpathy.github.io/2015/05/21/rnn-effectiveness</a>)</figcaption>
<h2 id="rnn-sequence-to-sequence-model">RNN: Sequence-to-Sequence Model<a hidden class="anchor" aria-hidden="true" href="#rnn-sequence-to-sequence-model">#</a></h2>
<p>The <a href="https://arxiv.org/pdf/1406.1078.pdf">sequence-to-sequence model</a> is an extended version of RNN, but its application field is distinguishable enough that I would like to list it in a separated section. Same as RNN, a sequence-to-sequence model operates on sequential data, but particularly it is commonly used to develop chatbots or personal assistants, both generating meaningful response for input questions. A sequence-to-sequence model consists of two RNNs, encoder and decoder. The encoder learns the contextual information from the input words and then hands over the knowledge to the decoder side through a &ldquo;<strong>context vector</strong>&rdquo; (or &ldquo;thought vector&rdquo;, as shown in Fig 8.). Finally, the decoder consumes the context vector and generates proper responses.</p>
<img src="seq2seq_gmail.png"  class="center" />
<figcaption>Fig. 8. A sequence-to-sequence model for generating Gmail auto replies. (Image source: <a href="https://research.googleblog.com/2015/11/computer-respond-to-this-email.html" target="_blank">https://research.googleblog.com/2015/11/computer-respond-to-this-email.html</a>)</figcaption>
<h2 id="autoencoders">Autoencoders<a hidden class="anchor" aria-hidden="true" href="#autoencoders">#</a></h2>
<p>Different from the previous models, autoencoders are for unsupervised learning. It is designed to learn a <strong>low-dimensional</strong> representation of a <strong>high-dimensional</strong> data set, similar to what <a href="https://en.wikipedia.org/wiki/Principal_component_analysis">Principal Components Analysis (PCA)</a> does. The autoencoder model tries to learn an approximation function $ f(x) \approx x $ to reproduce the input data. However, it is restricted by a bottleneck layer in the middle with a very small number of nodes. With limited capacity, the model is forced to form a very efficient encoding of the data, that is essentially the low-dimensional code we learned.</p>
<img src="autoencoder.png" style="width: 300px; max-width: 100%;" class="center" />
<figcaption>Fig. 9. An autoencoder model has a bottleneck layer with only a few neurons. (Image source: Geoffrey Hinton’s Coursera class <a href="https://www.coursera.org/learn/neural-networks" target="_blank">"Neural Networks for Machine Learning"</a> - <a href="https://www.coursera.org/learn/neural-networks/home/week/15" target="_blank">Week 15</a>)</figcaption>
<p><a href="https://pdfs.semanticscholar.org/7d76/b71b700846901ac4ac119403aa737a285e36.pdf">Hinton and Salakhutdinov</a> used autoencoders to compress documents on a variety of topics. As shown in Fig 10, when both PCA and autoencoder were applied to reduce the documents onto two dimensions, autoencoder demonstrated a much better outcome. With the help of autoencoder, we can do efficient data compression to speed up the information retrieval including both documents and images.</p>
<img src="autoencoder_experiment.png" class="center" />
<figcaption>Fig. 10. The outputs of PCA (left) and autoencoder (right) when both try to compress documents into two numbers. (Image source: <a href="https://www.cs.toronto.edu/~hinton/science.pdf" target="_blank">Hinton & Salakhutdinov 2006</a>)</figcaption>
<h1 id="reinforcement-deep-learning">Reinforcement (Deep) Learning<a hidden class="anchor" aria-hidden="true" href="#reinforcement-deep-learning">#</a></h1>
<p>Since I started my post with AlphaGo, let us dig a bit more on why AlphaGo worked out. <a href="https://en.wikipedia.org/wiki/Reinforcement_learning">Reinforcement learning (&ldquo;RL&rdquo;)</a> is one of the secrets behind its success. RL is a subfield of machine learning which allows machines and software agents to automatically determine the optimal behavior within a given context, with a goal to maximize the long-term performance measured by a given metric.</p>
<img src="alphago_paper.png" class="center" />
<img src="alphago_model.png" style="width: 600px; max-width: 100%;" class="center" />
<figcaption>Fig. 11. AlphaGo neural network training pipeline and architecture. (Image source: <a href="https://www.nature.com/articles/nature16961" target="_blank">Silver et al. 2016</a>)</figcaption>
<p>The AlphaGo system starts with a supervised learning process to train a fast rollout policy and a policy network, relying on the manually curated training dataset of professional players' games. It learns what is the best strategy given the current position on the game board. Then it applies reinforcement learning by setting up self-play games. The RL policy network gets improved when it wins more and more games against previous versions of the policy network. In the self-play stage, AlphaGo becomes stronger and stronger by playing against itself without requiring additional external training data.</p>
<h2 id="generative-adversarial-network">Generative Adversarial Network<a hidden class="anchor" aria-hidden="true" href="#generative-adversarial-network">#</a></h2>
<p><a href="https://arxiv.org/pdf/1406.2661.pdf">Generative adversarial network</a>, short for &ldquo;GAN&rdquo;, is a type of deep generative models. GAN is able to create new examples after learning through the real data.  It is consist of two models competing against each other in a zero-sum game framework. The famous deep learning researcher <a href="http://yann.lecun.com/">Yann LeCun</a> gave it a super high praise: Generative Adversarial Network is the most interesting idea in the last ten years in machine learning. (See the Quora question: <a href="https://www.quora.com/What-are-some-recent-and-potentially-upcoming-breakthroughs-in-deep-learning">&ldquo;What are some recent and potentially upcoming breakthroughs in deep learning?&quot;</a>)</p>
<img src="GAN.png" style="width: 600px; max-width: 100%;" class="center" />
<figcaption>Fig. 12. The architecture of a generative adversarial network. (Image source: <a href="http://www.kdnuggets.com/2017/01/generative-adversarial-networks-hot-topic-machine-learning.html" target="_blank">http://www.kdnuggets.com/2017/01/generative-adversarial-networks-hot-topic-machine-learning.html</a>)</figcaption>
<p>In the <a href="https://arxiv.org/pdf/1406.2661.pdf">original GAN paper</a>, GAN was proposed to generate meaningful images after learning from real photos. It comprises two independent models: the <strong>Generator</strong> and the <strong>Discriminator</strong>. The generator produces fake images and sends the output to the discriminator model. The discriminator works like a judge, as it is optimized for identifying the real photos from the fake ones. The generator model is trying hard to cheat the discriminator while the judge is trying hard not to be cheated. This interesting zero-sum game between these two models motivates both to develop their designed skills and improve their functionalities. Eventually, we take the generator model for producing new images.</p>
<h1 id="toolkits-and-libraries">Toolkits and Libraries<a hidden class="anchor" aria-hidden="true" href="#toolkits-and-libraries">#</a></h1>
<p>After learning all these models, you may start wondering how you can implement the models and use them for real. Fortunately, we have many open source toolkits and libraries for building deep learning models. <a href="https://www.tensorflow.org/">Tensorflow</a> is fairly new but has attracted a lot of popularity. It turns out, TensorFlow was <a href="http://deliprao.com/archives/168">the most forked Github project of 2015</a>. All that happened in a period of 2 months after its release in Nov 2015.</p>
<img src="deep_learning_toolkits.png" style="padding-bottom: 15px; max-width: 100%;" class="center" />
<h1 id="how-to-learn">How to Learn?<a hidden class="anchor" aria-hidden="true" href="#how-to-learn">#</a></h1>
<p>If you are very new to the field and willing to devote some time to studying deep learning in a more systematic way, I would recommend you to start with the book <a href="https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1499413305&amp;sr=1-1&amp;keywords=deep+learning">Deep Learning</a> by Ian Goodfellow, Yoshua Bengio, and Aaron Courville. The Coursera course <a href="https://www.coursera.org/learn/neural-networks">&ldquo;Neural Networks for Machine Learning&rdquo;</a> by Geoffrey Hinton (<a href="https://youtu.be/uAu3jQWaN6E">Godfather of deep learning!</a>). The content for the course was prepared around 2006, pretty old, but it helps you build up a solid foundation for understanding deep learning models and expedite further exploration.</p>
<p>Meanwhile, maintain your curiosity and passion. The field is making progress every day. Even classical or widely adopted deep learning models may just have been proposed 1-2 years ago. Reading academic papers can help you learn stuff in depth and keep up with the cutting-edge findings.</p>
<h3 id="useful-resources">Useful resources<a hidden class="anchor" aria-hidden="true" href="#useful-resources">#</a></h3>
<ul>
<li>Google Scholar: <a href="http://scholar.google.com">http://scholar.google.com</a></li>
<li>arXiv cs section: <a href="https://arxiv.org/list/cs/recent">https://arxiv.org/list/cs/recent</a></li>
<li><a href="http://ufldl.stanford.edu/tutorial/">Unsupervised Feature Learning and Deep Learning Tutorial</a></li>
<li><a href="https://www.tensorflow.org/tutorials/">Tensorflow Tutorials</a></li>
<li>Data Science Weekly</li>
<li><a href="http://www.kdnuggets.com/2017/01/generative-adversarial-networks-hot-topic-machine-learning.html">KDnuggets</a></li>
<li>Tons of blog posts and online tutorials</li>
<li>Related <a href="http://coursera.com">Cousera</a> courses</li>
<li><a href="https://github.com/terryum/awesome-deep-learning-papers">awesome-deep-learning-papers</a></li>
</ul>
<h3 id="blog-posts-mentioned">Blog posts mentioned<a hidden class="anchor" aria-hidden="true" href="#blog-posts-mentioned">#</a></h3>
<ul>
<li><a href="http://setosa.io/ev/image-kernels">Explained Visually: Image Kernels</a></li>
<li><a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs/">Understanding LSTM Networks</a></li>
<li><a href="http://karpathy.github.io/2015/05/21/rnn-effectiveness/">The Unreasonable Effectiveness of Recurrent Neural Networks</a></li>
<li><a href="https://research.googleblog.com/2015/11/computer-respond-to-this-email.html">Computer, respond to this email.</a></li>
</ul>
<h3 id="interesting-blogs-worthy-of-checking">Interesting blogs worthy of checking<a hidden class="anchor" aria-hidden="true" href="#interesting-blogs-worthy-of-checking">#</a></h3>
<ul>
<li><a href="http://www.wildml.com">www.wildml.com</a></li>
<li><a href="http://colah.github.io/">colah.github.io</a></li>
<li><a href="http://karpathy.github.io/">karpathy.github.io</a></li>
<li><a href="https://blog.openai.com">blog.openai.com</a></li>
</ul>
<h3 id="papers-mentioned">Papers mentioned<a hidden class="anchor" aria-hidden="true" href="#papers-mentioned">#</a></h3>
<p>[1] He, Kaiming, et al. <a href="http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">&ldquo;Deep residual learning for image recognition.&quot;</a> Proc. IEEE Conf. on computer vision and pattern recognition. 2016.</p>
<p>[2] Wang, Haohan, Bhiksha Raj, and Eric P. Xing. <a href="https://arxiv.org/pdf/1702.07800.pdf">&ldquo;On the Origin of Deep Learning.&quot;</a> arXiv preprint arXiv:1702.07800, 2017.</p>
<p>[3] Sutskever, Ilya, James Martens, and Geoffrey E. Hinton. <a href="http://machinelearning.wustl.edu/mlpapers/paper_files/ICML2011Sutskever_524.pdf">&ldquo;Generating text with recurrent neural networks.&quot;</a> Proc. of the 28th Intl. Conf. on Machine Learning (ICML). 2011.</p>
<p>[4] Liwicki, Marcus, et al. <a href="http://www6.in.tum.de/Main/Publications/Liwicki2007a.pdf">&ldquo;A novel approach to on-line handwriting recognition based on bidirectional long short-term memory networks.&quot;</a> Proc. of 9th Intl. Conf. on Document Analysis and Recognition. 2007.</p>
<p>[5] LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. <a href="http://pages.cs.wisc.edu/~dyer/cs540/handouts/deep-learning-nature2015.pdf">&ldquo;Deep learning.&quot;</a> Nature 521.7553 (2015): 436-444.</p>
<p>[6] Hochreiter, Sepp, and Jurgen Schmidhuber. <a href="http://web.eecs.utk.edu/~itamar/courses/ECE-692/Bobby_paper1.pdf">&ldquo;Long short-term memory.&quot;</a> Neural computation 9.8 (1997): 1735-1780.</p>
<p>[7] Cho, Kyunghyun. et al. <a href="https://arxiv.org/pdf/1406.1078.pdf">&ldquo;Learning phrase representations using RNN encoder-decoder for statistical machine translation.&quot;</a> Proc. Conference on Empirical Methods in Natural Language Processing 1724–1734 (2014).</p>
<p>[8] Hinton, Geoffrey E., and Ruslan R. Salakhutdinov. <a href="https://pdfs.semanticscholar.org/7d76/b71b700846901ac4ac119403aa737a285e36.pdf">&ldquo;Reducing the dimensionality of data with neural networks.&quot;</a> science 313.5786 (2006): 504-507.</p>
<p>[9] Silver, David, et al. <a href="http://web.iitd.ac.in/~sumeet/Silver16.pdf">&ldquo;Mastering the game of Go with deep neural networks and tree search.&quot;</a> Nature 529.7587 (2016): 484-489.</p>
<p>[10] Goodfellow, Ian, et al. <a href="https://arxiv.org/pdf/1406.2661.pdf">&ldquo;Generative adversarial nets.&quot;</a> NIPS, 2014.</p>


  </div>

  <footer class="post-footer">
    <ul class="post-tags">
      <li><a href="https://wuxb09.github.io/test-lilian/tags/foundation/">foundation</a></li>
      <li><a href="https://wuxb09.github.io/test-lilian/tags/tutorial/">tutorial</a></li>
    </ul>
<nav class="paginav">
  <a class="prev" href="https://wuxb09.github.io/test-lilian/posts/2017-07-08-stock-rnn-part-1/">
    <span class="title">« </span>
    <br>
    <span>Predict Stock Prices Using RNN: Part 1</span>
  </a>
</nav>


<div class="share-buttons">
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on twitter"
        href="https://twitter.com/intent/tweet/?text=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People&amp;url=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f&amp;hashtags=foundation%2ctutorial">
        <svg version="1.1" viewBox="0 0 512 512" xml:space="preserve">
            <path
                d="M449.446,0c34.525,0 62.554,28.03 62.554,62.554l0,386.892c0,34.524 -28.03,62.554 -62.554,62.554l-386.892,0c-34.524,0 -62.554,-28.03 -62.554,-62.554l0,-386.892c0,-34.524 28.029,-62.554 62.554,-62.554l386.892,0Zm-253.927,424.544c135.939,0 210.268,-112.643 210.268,-210.268c0,-3.218 0,-6.437 -0.153,-9.502c14.406,-10.421 26.973,-23.448 36.935,-38.314c-13.18,5.824 -27.433,9.809 -42.452,11.648c15.326,-9.196 26.973,-23.602 32.49,-40.92c-14.252,8.429 -30.038,14.56 -46.896,17.931c-13.487,-14.406 -32.644,-23.295 -53.946,-23.295c-40.767,0 -73.87,33.104 -73.87,73.87c0,5.824 0.613,11.494 1.992,16.858c-61.456,-3.065 -115.862,-32.49 -152.337,-77.241c-6.284,10.881 -9.962,23.601 -9.962,37.088c0,25.594 13.027,48.276 32.95,61.456c-12.107,-0.307 -23.448,-3.678 -33.41,-9.196l0,0.92c0,35.862 25.441,65.594 59.311,72.49c-6.13,1.686 -12.72,2.606 -19.464,2.606c-4.751,0 -9.348,-0.46 -13.946,-1.38c9.349,29.426 36.628,50.728 68.965,51.341c-25.287,19.771 -57.164,31.571 -91.8,31.571c-5.977,0 -11.801,-0.306 -17.625,-1.073c32.337,21.15 71.264,33.41 112.95,33.41Z" />
        </svg>
    </a>
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on linkedin"
        href="https://www.linkedin.com/shareArticle?mini=true&amp;url=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f&amp;title=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People&amp;summary=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People&amp;source=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f">
        <svg version="1.1" viewBox="0 0 512 512" xml:space="preserve">
            <path
                d="M449.446,0c34.525,0 62.554,28.03 62.554,62.554l0,386.892c0,34.524 -28.03,62.554 -62.554,62.554l-386.892,0c-34.524,0 -62.554,-28.03 -62.554,-62.554l0,-386.892c0,-34.524 28.029,-62.554 62.554,-62.554l386.892,0Zm-288.985,423.278l0,-225.717l-75.04,0l0,225.717l75.04,0Zm270.539,0l0,-129.439c0,-69.333 -37.018,-101.586 -86.381,-101.586c-39.804,0 -57.634,21.891 -67.617,37.266l0,-31.958l-75.021,0c0.995,21.181 0,225.717 0,225.717l75.02,0l0,-126.056c0,-6.748 0.486,-13.492 2.474,-18.315c5.414,-13.475 17.767,-27.434 38.494,-27.434c27.135,0 38.007,20.707 38.007,51.037l0,120.768l75.024,0Zm-307.552,-334.556c-25.674,0 -42.448,16.879 -42.448,39.002c0,21.658 16.264,39.002 41.455,39.002l0.484,0c26.165,0 42.452,-17.344 42.452,-39.002c-0.485,-22.092 -16.241,-38.954 -41.943,-39.002Z" />
        </svg>
    </a>
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on reddit"
        href="https://reddit.com/submit?url=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f&title=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People">
        <svg version="1.1" viewBox="0 0 512 512" xml:space="preserve">
            <path
                d="M449.446,0c34.525,0 62.554,28.03 62.554,62.554l0,386.892c0,34.524 -28.03,62.554 -62.554,62.554l-386.892,0c-34.524,0 -62.554,-28.03 -62.554,-62.554l0,-386.892c0,-34.524 28.029,-62.554 62.554,-62.554l386.892,0Zm-3.446,265.638c0,-22.964 -18.616,-41.58 -41.58,-41.58c-11.211,0 -21.361,4.457 -28.841,11.666c-28.424,-20.508 -67.586,-33.757 -111.204,-35.278l18.941,-89.121l61.884,13.157c0.756,15.734 13.642,28.29 29.56,28.29c16.407,0 29.706,-13.299 29.706,-29.701c0,-16.403 -13.299,-29.702 -29.706,-29.702c-11.666,0 -21.657,6.792 -26.515,16.578l-69.105,-14.69c-1.922,-0.418 -3.939,-0.042 -5.585,1.036c-1.658,1.073 -2.811,2.761 -3.224,4.686l-21.152,99.438c-44.258,1.228 -84.046,14.494 -112.837,35.232c-7.468,-7.164 -17.589,-11.591 -28.757,-11.591c-22.965,0 -41.585,18.616 -41.585,41.58c0,16.896 10.095,31.41 24.568,37.918c-0.639,4.135 -0.99,8.328 -0.99,12.576c0,63.977 74.469,115.836 166.33,115.836c91.861,0 166.334,-51.859 166.334,-115.836c0,-4.218 -0.347,-8.387 -0.977,-12.493c14.564,-6.47 24.735,-21.034 24.735,-38.001Zm-119.474,108.193c-20.27,20.241 -59.115,21.816 -70.534,21.816c-11.428,0 -50.277,-1.575 -70.522,-21.82c-3.007,-3.008 -3.007,-7.882 0,-10.889c3.003,-2.999 7.882,-3.003 10.885,0c12.777,12.781 40.11,17.317 59.637,17.317c19.522,0 46.86,-4.536 59.657,-17.321c3.016,-2.999 7.886,-2.995 10.885,0.008c3.008,3.011 3.003,7.882 -0.008,10.889Zm-5.23,-48.781c-16.373,0 -29.701,-13.324 -29.701,-29.698c0,-16.381 13.328,-29.714 29.701,-29.714c16.378,0 29.706,13.333 29.706,29.714c0,16.374 -13.328,29.698 -29.706,29.698Zm-160.386,-29.702c0,-16.381 13.328,-29.71 29.714,-29.71c16.369,0 29.689,13.329 29.689,29.71c0,16.373 -13.32,29.693 -29.689,29.693c-16.386,0 -29.714,-13.32 -29.714,-29.693Z" />
        </svg>
    </a>
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on facebook"
        href="https://facebook.com/sharer/sharer.php?u=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f">
        <svg version="1.1" viewBox="0 0 512 512" xml:space="preserve">
            <path
                d="M449.446,0c34.525,0 62.554,28.03 62.554,62.554l0,386.892c0,34.524 -28.03,62.554 -62.554,62.554l-106.468,0l0,-192.915l66.6,0l12.672,-82.621l-79.272,0l0,-53.617c0,-22.603 11.073,-44.636 46.58,-44.636l36.042,0l0,-70.34c0,0 -32.71,-5.582 -63.982,-5.582c-65.288,0 -107.96,39.569 -107.96,111.204l0,62.971l-72.573,0l0,82.621l72.573,0l0,192.915l-191.104,0c-34.524,0 -62.554,-28.03 -62.554,-62.554l0,-386.892c0,-34.524 28.029,-62.554 62.554,-62.554l386.892,0Z" />
        </svg>
    </a>
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on whatsapp"
        href="https://api.whatsapp.com/send?text=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People%20-%20https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f">
        <svg version="1.1" viewBox="0 0 512 512" xml:space="preserve">
            <path
                d="M449.446,0c34.525,0 62.554,28.03 62.554,62.554l0,386.892c0,34.524 -28.03,62.554 -62.554,62.554l-386.892,0c-34.524,0 -62.554,-28.03 -62.554,-62.554l0,-386.892c0,-34.524 28.029,-62.554 62.554,-62.554l386.892,0Zm-58.673,127.703c-33.842,-33.881 -78.847,-52.548 -126.798,-52.568c-98.799,0 -179.21,80.405 -179.249,179.234c-0.013,31.593 8.241,62.428 23.927,89.612l-25.429,92.884l95.021,-24.925c26.181,14.28 55.659,21.807 85.658,21.816l0.074,0c98.789,0 179.206,-80.413 179.247,-179.243c0.018,-47.895 -18.61,-92.93 -52.451,-126.81Zm-126.797,275.782l-0.06,0c-26.734,-0.01 -52.954,-7.193 -75.828,-20.767l-5.441,-3.229l-56.386,14.792l15.05,-54.977l-3.542,-5.637c-14.913,-23.72 -22.791,-51.136 -22.779,-79.287c0.033,-82.142 66.867,-148.971 149.046,-148.971c39.793,0.014 77.199,15.531 105.329,43.692c28.128,28.16 43.609,65.592 43.594,105.4c-0.034,82.149 -66.866,148.983 -148.983,148.984Zm81.721,-111.581c-4.479,-2.242 -26.499,-13.075 -30.604,-14.571c-4.105,-1.495 -7.091,-2.241 -10.077,2.241c-2.986,4.483 -11.569,14.572 -14.182,17.562c-2.612,2.988 -5.225,3.364 -9.703,1.12c-4.479,-2.241 -18.91,-6.97 -36.017,-22.23c-13.314,-11.876 -22.304,-26.542 -24.916,-31.026c-2.612,-4.484 -0.279,-6.908 1.963,-9.14c2.016,-2.007 4.48,-5.232 6.719,-7.847c2.24,-2.615 2.986,-4.484 4.479,-7.472c1.493,-2.99 0.747,-5.604 -0.374,-7.846c-1.119,-2.241 -10.077,-24.288 -13.809,-33.256c-3.635,-8.733 -7.327,-7.55 -10.077,-7.688c-2.609,-0.13 -5.598,-0.158 -8.583,-0.158c-2.986,0 -7.839,1.121 -11.944,5.604c-4.105,4.484 -15.675,15.32 -15.675,37.364c0,22.046 16.048,43.342 18.287,46.332c2.24,2.99 31.582,48.227 76.511,67.627c10.685,4.615 19.028,7.371 25.533,9.434c10.728,3.41 20.492,2.929 28.209,1.775c8.605,-1.285 26.499,-10.833 30.231,-21.295c3.732,-10.464 3.732,-19.431 2.612,-21.298c-1.119,-1.869 -4.105,-2.99 -8.583,-5.232Z" />
        </svg>
    </a>
    <a target="_blank" rel="noopener noreferrer" aria-label="share An Overview of Deep Learning for Curious People on telegram"
        href="https://telegram.me/share/url?text=An%20Overview%20of%20Deep%20Learning%20for%20Curious%20People&amp;url=https%3a%2f%2fwuxb09.github.io/test-lilian%2fposts%2f2017-06-21-overview%2f">
        <svg version="1.1" xml:space="preserve" viewBox="2 2 28 28">
            <path
                d="M26.49,29.86H5.5a3.37,3.37,0,0,1-2.47-1,3.35,3.35,0,0,1-1-2.47V5.48A3.36,3.36,0,0,1,3,3,3.37,3.37,0,0,1,5.5,2h21A3.38,3.38,0,0,1,29,3a3.36,3.36,0,0,1,1,2.46V26.37a3.35,3.35,0,0,1-1,2.47A3.38,3.38,0,0,1,26.49,29.86Zm-5.38-6.71a.79.79,0,0,0,.85-.66L24.73,9.24a.55.55,0,0,0-.18-.46.62.62,0,0,0-.41-.17q-.08,0-16.53,6.11a.59.59,0,0,0-.41.59.57.57,0,0,0,.43.52l4,1.24,1.61,4.83a.62.62,0,0,0,.63.43.56.56,0,0,0,.4-.17L16.54,20l4.09,3A.9.9,0,0,0,21.11,23.15ZM13.8,20.71l-1.21-4q8.72-5.55,8.78-5.55c.15,0,.23,0,.23.16a.18.18,0,0,1,0,.06s-2.51,2.3-7.52,6.8Z" />
        </svg>
    </a>
</div>

  </footer>
</article>
    </main>
    
<footer class="footer">
    <span>&copy; 2023 <a href="https://wuxb09.github.io/test-lilian/">Lil&#39;Log</a></span>
    <span>
        Powered by
        <a href="https://gohugo.io/" rel="noopener noreferrer" target="_blank">Hugo</a> &
        <a href="https://git.io/hugopapermod" rel="noopener" target="_blank">PaperMod</a>
    </span>
</footer>
<a href="#top" aria-label="go to top" title="Go to Top (Alt + G)" class="top-link" id="top-link" accesskey="g">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 12 6" fill="currentColor">
        <path d="M12 6H0l6-6z" />
    </svg>
</a>

<script>
    let menu = document.getElementById('menu')
    if (menu) {
        menu.scrollLeft = localStorage.getItem("menu-scroll-position");
        menu.onscroll = function () {
            localStorage.setItem("menu-scroll-position", menu.scrollLeft);
        }
    }

    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener("click", function (e) {
            e.preventDefault();
            var id = this.getAttribute("href").substr(1);
            if (!window.matchMedia('(prefers-reduced-motion: reduce)').matches) {
                document.querySelector(`[id='${decodeURIComponent(id)}']`).scrollIntoView({
                    behavior: "smooth"
                });
            } else {
                document.querySelector(`[id='${decodeURIComponent(id)}']`).scrollIntoView();
            }
            if (id === "top") {
                history.replaceState(null, null, " ");
            } else {
                history.pushState(null, null, `#${id}`);
            }
        });
    });

</script>
<script>
    var mybutton = document.getElementById("top-link");
    window.onscroll = function () {
        if (document.body.scrollTop > 800 || document.documentElement.scrollTop > 800) {
            mybutton.style.visibility = "visible";
            mybutton.style.opacity = "1";
        } else {
            mybutton.style.visibility = "hidden";
            mybutton.style.opacity = "0";
        }
    };

</script>
<script>
    document.getElementById("theme-toggle").addEventListener("click", () => {
        if (document.body.className.includes("dark")) {
            document.body.classList.remove('dark');
            localStorage.setItem("pref-theme", 'light');
        } else {
            document.body.classList.add('dark');
            localStorage.setItem("pref-theme", 'dark');
        }
    })

</script>
<script>
    document.querySelectorAll('pre > code').forEach((codeblock) => {
        const container = codeblock.parentNode.parentNode;

        const copybutton = document.createElement('button');
        copybutton.classList.add('copy-code');
        copybutton.innerText = 'copy';

        function copyingDone() {
            copybutton.innerText = 'copied!';
            setTimeout(() => {
                copybutton.innerText = 'copy';
            }, 2000);
        }

        copybutton.addEventListener('click', (cb) => {
            if ('clipboard' in navigator) {
                navigator.clipboard.writeText(codeblock.textContent);
                copyingDone();
                return;
            }

            const range = document.createRange();
            range.selectNodeContents(codeblock);
            const selection = window.getSelection();
            selection.removeAllRanges();
            selection.addRange(range);
            try {
                document.execCommand('copy');
                copyingDone();
            } catch (e) { };
            selection.removeRange(range);
        });

        if (container.classList.contains("highlight")) {
            container.appendChild(copybutton);
        } else if (container.parentNode.firstChild == container) {
            
        } else if (codeblock.parentNode.parentNode.parentNode.parentNode.parentNode.nodeName == "TABLE") {
            
            codeblock.parentNode.parentNode.parentNode.parentNode.parentNode.appendChild(copybutton);
        } else {
            
            codeblock.parentNode.appendChild(copybutton);
        }
    });
</script>
</body>

</html>