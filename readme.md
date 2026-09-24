<img title="Awesome Machine Learning with Ruby" alt="Awesome Machine Learning with Ruby" src="header.png">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

[RubyNLP](https://github.com/arbox/nlp-with-ruby) |
[RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
[RubyInterop](https://github.com/arbox/ruby-interoperability)

# Awesome Machine Learning With Ruby

<img src="ruby.jpg" align="left" width="30px" height="30px" alt="Ruby" />

> Curated List of Ruby Machine Learning Links and Resources

[Machine Learning][ml] is a field of [Computational Science][cs] -
often nested under [AI][] research - with many practical
applications due to the ability of resulting algorithms to
systematically implement a specific solution without explicit
programmer's instructions. Obviously many algorithms need a definition
of [features][fe] to look at or a biggish [training set][ts] of data to derive the
solution from.

This curated list comprises [_awesome_][awesome] libraries,
data sources, tutorials and presentations about [Machine Learning][ml]
utilizing the [Ruby][] programming language.

A lot of useful resources on this list come from the development by
[The Ruby Science Foundation][sciruby], our [contributors][] and
our own day to day work on various ML applications.

:sparkles: Every [contribution](contributing.md) is welcome! Add links through pull
requests or create an issue to start a discussion.

Follow us on Twitter and please spread
the word using the `#RubyML` hash tag!

<!-- nodoc -->
## Contents

- [:sparkles: Tutorials](#sparkles-tutorials)
- [Machine Learning Libraries](#machine-learning-libraries)
  - [Frameworks](#frameworks)
  - [Neural networks](#neural-networks)
  - [Deep learning](#deep-learning)
  - [Kernel methods](#kernel-methods)
  - [Evolutionary algorithms](#evolutionary-algorithms)
  - [Bayesian methods](#bayesian-methods)
  - [Decision trees](#decision-trees)
  - [Clustering](#clustering)
  - [Linear classifiers](#linear-classifiers)
  - [Statistical models](#statistical-models)
  - [Gradient boosting](#gradient-boosting)
  - [Vector search](#vector-search)
- [Applications of machine learning](#applications-of-machine-learning)
- [Data structures](#data-structures)
- [Data visualization](#data-visualization)
- [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
- [Projects and Code Examples](#projects-and-code-examples)
- [Heroku buildpacks](#heroku-buildpacks)
- [Books, Blogs, Channels](#books-blogs-channels)
- [Community](#community)
- [Related Resources](#related-resources)

<!-- doc -->

## :sparkles: Tutorials

Please help us to fill out this section! :smiley:
- [Ruby neural networks](https://www.honeybadger.io/blog/ruby-neural-networks/)
- [How to implement linear regression in Ruby](https://www.practicalai.io/implementing-linear-regression-using-ruby/)
- [How to implement classification using logistic regression in Ruby](https://www.practicalai.io/implementing-classification-using-logistic-regression-in-ruby/)
- [How to implement simple binary classification using a Neural Network in Ruby](https://www.practicalai.io/implementing-simple-classification-using-neural-network-in-ruby/)
- [How to implement classification using a SVM in Ruby](https://www.practicalai.io/implementing-classification-using-a-svm-in-ruby/)
- [Unsupervised learning using k-means clustering in Ruby](https://www.practicalai.io/unsupervised-learning-using-k-means-clustering-in-ruby/)
- [Teaching an AI to play a simple game using Q-Learning in Ruby](https://www.practicalai.io/teaching-ai-play-simple-game-using-q-learning/)
- [Teaching a Neural Network to play a game using Q-Learning in Ruby](https://www.practicalai.io/teaching-a-neural-network-to-play-a-game-with-q-learning/)
- [Using the Python scikit-learn machine learning library in Ruby using PyCall](https://www.practicalai.io/using-scikit-learn-machine-learning-library-in-ruby-using-pycall/)
- [How to _evolve_ neural networks in Ruby using the Machine Learning Workbench](https://github.com/giuse/machine_learning_workbench/blob/master/examples/neuroevolution.rb) - ★ 20 stars, last push 2021-11-02.

## Machine Learning Libraries

[Machine Learning][ml] algorithms in pure Ruby or written in other
programming languages with appropriate bindings for Ruby.

### Frameworks

- [LangChain.rb](https://github.com/andreibondarev/langchainrb) - Build ML/AI-supercharged applications with Ruby's LangChain. - ★ 1,999 stars, last push 2026-09-09.
- [weka](https://github.com/paulgoetze/weka-jruby) - JRuby bindings for Weka, different ML algorithms implemented through Weka. - ★ 65 stars, last push 2026-06-24.
- [ai4r](https://github.com/SergioFierens/ai4r) - Artificial Intelligence for Ruby. - ★ 722 stars, last push 2025-07-18.
- [classifier-reborn](https://github.com/jekyll/classifier-reborn) - General classifier module to allow Bayesian and other types of classifications. <sup>\[[dep: GLS](#gls)\]</sup>. - ★ 558 stars, last push 2024-05-27.
- [scoruby](https://github.com/asafschers/scoruby) - Ruby scoring API for [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) (Predictive Model Markup Language). - ★ 70 stars, last push 2022-10-19.
- [rblearn](https://github.com/himkt/rblearn) - Feature Extraction and Crossvalidation library. - ★ 2 stars, last push 2016-08-03.
- [data_modeler](https://github.com/giuse/data_modeler) - Model your data with machine learning. Ample test coverage, examples to start fast, complete documentation. Production ready since 1.0.0. - ★ 1 star, last push 2017-06-28.
- [shogun](https://github.com/shogun-toolbox/shogun) - Polyfunctional and mature machine learning toolbox with [Ruby bindings](https://github.com/shogun-toolbox/shogun/tree/develop/src/interfaces/ruby). - ★ 3,081 stars, last push 2023-12-19.
- [aws-sdk-machinelearning](https://github.com/aws/aws-sdk-ruby) - Machine Learning API of the Amazon Web Services. - ★ 3,657 stars, last push 2026-09-24.
- [azure_mgmt_machine_learning](https://github.com/Azure/azure-sdk-for-ruby) - Machine Learning API of the Microsoft Azure. - ★ 279 stars, archived 2023-01-10.
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench) - Growing machine learning framework written in pure Ruby, high performance computing using [Numo](https://github.com/ruby-numo/), CUDA bindings through [Cumo](https://github.com/sonots/cumo). Currently implementating neural networks, evolutionary strategies, vector quantization, and plenty of examples and utilities. - ★ 20 stars, last push 2021-11-02.
- [Deep NeuroEvolution](https://github.com/giuse/DNE) - Experimental setup based on the [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench) towards searching for deep neural networks (rather than training) using evolutionary algorithms. Applications to the [OpenAI Gym](https://github.com/openai/gym) using [PyCall](https://github.com/mrkn/pycall.rb). - ★ 126 stars, last push 2019-12-31.
- [rumale](https://github.com/yoshoku/rumale) - Machine Learninig toolkit in Ruby with wide range of implemented algorithms (SVM, Logistic Regression, Linear Regression, Random Forest etc.) and interfaces similar to [Scikit-Learn][scikit] in Python. - ★ 918 stars, last push 2026-09-14.
- [eps](https://github.com/ankane/eps) - Bayesian Classification and Linear Regression with exports using [PMML](http://dmg.org/pmml/v4-3/GeneralStructure.html) and an alternative backend using [GSL][]. - ★ 693 stars, last push 2026-06-29.
- [ruby-openai](https://github.com/alexrudall/ruby-openai) - OpenAI API wrapper. - ★ 3,223 stars, last push 2026-05-01.
- [Instruct](https://github.com/instruct-rb/instruct) - Inspired by Guidance; weave code, prompts and completions together to instruct LLMs to do what you want. - ★ 49 stars, last push 2025-02-07.
### Neural networks

- [neural-net-ruby](https://github.com/gbuesing/neural-net-ruby) - Neural network written in Ruby. - ★ 127 stars, last push 2017-07-02.
- [ruby-fann](https://github.com/tangledpath/ruby-fann) - Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/). - ★ 506 stars, last push 2024-03-25.
- [cerebrum](https://github.com/irfansharif/cerebrum) - Experimental implementation for Artificial Neural Networks in Ruby. - ★ 36 stars, last push 2019-03-03.
- [tlearn-rb](https://github.com/josephwilk/tlearn-rb) - Recurrent Neural Network library for Ruby. - ★ 97 stars, last push 2018-01-04.
- [brains](https://github.com/jedld/brains-jruby) - Feed-forward neural networks for JRuby based on [brains](https://github.com/jedld/brains). - ★ 60 stars, last push 2017-03-20.
- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/neural_network) - Framework including pure-Ruby implementation of both feed-forward and recurrent neural networks (fully connected). Training available using neuroevolution (Natural Evolution Strategies algorithms). - ★ 20 stars, last push 2021-11-02.
- [rann](https://github.com/mikecmpbll/rann) - Flexible Ruby ANN implementation with backprop (through-time, for recurrent nets), gradient checking, adagrad, and parallel batch execution. - ★ 3 stars, last push 2017-12-11.

### Deep learning

- [tensor_stream](https://github.com/jedld/tensor_stream) - Ground-up and standalone reimplementation of TensorFlow for Ruby. - ★ 504 stars, last push 2020-12-26.
- [red-chainer](https://github.com/red-data-tools/red-chainer) - Deep learning framework for Ruby. - ★ 103 stars, last push 2022-01-05.
- [tensorflow](https://github.com/somaticio/tensorflow.rb) - Ruby bindings for [TensorFlow](https://www.tensorflow.org/). - ★ 832 stars, last push 2022-01-10.
- [ruby-dnn](https://github.com/unagiootoro/ruby-dnn) - Simple deep learning for Ruby. - ★ 46 stars, last push 2023-07-04.
- [torch-rb](https://github.com/ankane/torch-rb) - Ruby bindings for [LibTorch](https://github.com/pytorch/pytorch) - using [rice](https://github.com/jasonroelofs/rice). - ★ 840 stars, last push 2026-09-06.
- [mxnet](https://github.com/mrkn/mxnet.rb) - Ruby bindings for [mxnet](https://mxnet.apache.org/). - ★ 48 stars, last push 2020-12-22.

### Kernel methods

- [rb-libsvm](https://github.com/febeling/rb-libsvm) - Support Vector Machines with Ruby and the [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) library. <sup>\[[dep: bundled](#bundled)\]</sup>. - ★ 279 stars, last push 2023-12-07.

### Evolutionary algorithms

- [machine_learning_workbench](https://github.com/giuse/machine_learning_workbench/tree/master/lib/machine_learning_workbench/optimizer/natural_evolution_strategies) - Framework including pure-Ruby implementations of Natural Evolution Strategy algorithms (black-box optimization), specifically Exponential NES (XNES), Separable NES (sNES), Block-Diagonal NES (BDNES) and more. Applications include neural network search/training (neuroevolution). - ★ 20 stars, last push 2021-11-02.
- [simple_ga](https://github.com/giuse/simple_ga) - Simplest Genetic Algorithms implementation in Ruby. - ★ 11 stars, last push 2016-10-26.

### Bayesian methods

- [linnaeus](https://github.com/djcp/linnaeus) - Redis-backed Bayesian classifier. - ★ 37 stars, last push 2015-12-26.
- [naive_bayes](https://github.com/reddavis/Naive-Bayes) - Simple Naive Bayes classifier. - ★ 49 stars, last push 2012-01-29.
- [nbayes](https://github.com/oasic/nbayes) - Full-featured, Ruby implementation of Naive Bayes. - ★ 155 stars, last push 2024-02-12.

### Decision trees

- [decisiontree](https://github.com/igrigorik/decisiontree) - Decision Tree ID3 Algorithm in pure Ruby. [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>. <sup>  <sup>[[dep: GraphViz](#graphviz) |</sup>. - ★ 1,492 stars, last push 2018-10-31.

### Clustering

- [kmeans-clusterer](https://github.com/gbuesing/kmeans-clusterer) - K-means clustering in Ruby. - ★ 99 stars, last push 2020-09-21.
- [k_means](https://github.com/reddavis/K-Means) - Attempting to build a fast, memory efficient K-Means program. - ★ 113 stars, archived 2016-06-16.
- [knn](https://github.com/reddavis/knn) - Simple K Nearest Neighbour Algorithm. - ★ 37 stars, last push 2020-05-22.

### Linear classifiers

- [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) - Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification). - ★ 83 stars, last push 2023-06-27.
- [liblinear-ruby](https://github.com/kei500/liblinear-ruby) - Ruby interface to LIBLINEAR using SWIG. - ★ 82 stars, last push 2019-03-29.

### Statistical models

- [rtimbl](https://github.com/maspwr/rtimbl) - Memory based learners from the Timbl framework. - ★ 5 stars, last push 2009-10-23.
- [lda-ruby](https://github.com/ealdent/lda-ruby) - Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering. - ★ 134 stars, last push 2026-05-04.
- [maxent_string_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) - JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework. - ★ 9 stars, last push 2009-07-06.
- [omnicat](https://github.com/mustafaturan/omnicat) - Generalized rack framework for text classifications. - ★ 11 stars, last push 2021-01-13.
- [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) - Naive Bayes text classification implementation as an OmniCat classifier strategy. <sup>\[[dep: bundled](#bundled)\]</sup>. - ★ 31 stars, last push 2021-01-13.

### Gradient boosting

- [xgboost](https://github.com/PairOnAir/xgboost-ruby) - Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)\]</sup>. - ★ 20 stars, last push 2018-04-12.
- [xgb](https://github.com/ankane/xgb) - Ruby bindings for XGBoost. <sup>\[[dep: XGBoost](#xgboost)\]</sup>. - ★ 121 stars, last push 2026-09-09.
- [lightgbm](https://github.com/ankane/lightgbm) - Ruby bindings for LightGBM. <sup>\[[dep: LightGBM](#lightgbm)\]</sup>. - ★ 84 stars, last push 2026-07-18.

### Vector search

- [flann](https://github.com/mariusmuja/flann) - Ruby bindings for the [FLANN](https://github.com/flann-lib/flann) (Fast Library for Approximate Nearest Neighbors). <sup>\[[flann](#flann)\]</sup>. - ★ 2,376 stars, last push 2024-07-29.
- [annoy-rb](https://github.com/yoshoku/annoy.rb) - Ruby bindings for the [Annoy](https://github.com/spotify/annoy) (Approximate Nearest Neighbors Oh Yeah). - ★ 37 stars, last push 2026-09-18.
- [hnswlib.rb](https://github.com/yoshoku/hnswlib.rb) - Ruby bindings for the [Hnswlib](https://github.com/nmslib/hnswlib) that implements approximate nearest neighbor search with Hierarchical Navigable Small World graphs. - ★ 15 stars, last push 2026-09-14.
- [ngt-ruby](https://github.com/ankane/ngt-ruby) - Ruby bindings for the [NGT](https://github.com/yahoojapan/NGT) (Neighborhood Graph and Tree for Indexing High-dimensional data). - ★ 53 stars, last push 2026-04-02.
- [milvus](https://github.com/andreibondarev/milvus) - Ruby client for Milvus Vector DB. - ★ 33 stars, last push 2025-03-31.
- [pinecone](https://github.com/ScotterC/pinecone) - Ruby client for Pinecone Vector DB. - ★ 67 stars, last push 2026-03-18.
- [qdrant-ruby](https://github.com/andreibondarev/qdrant-ruby) - Ruby wrapper for the Qdrant vector search database API. - ★ 61 stars, last push 2026-08-12.
- [weaviate-ruby](https://github.com/andreibondarev/weaviate-ruby) - Ruby wrapper for the Weaviate vector search database API. - ★ 58 stars, last push 2026-04-17.

## Applications of machine learning

- [phashion](https://github.com/westonplatter/phashion) - Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files. <sup>\[[ImageMagick](#imagemagick) | [libjpeg](#libjpeg)\]</sup>. - ★ 711 stars, last push 2025-10-23.

## Data structures

If you're going to implement your own ML algorithms you're probably interested
in storing your feature sets efficiently. Look for appropriate
[data structures](https://github.com/arbox/data-science-with-ruby#data-structures)
in our [Data Science with Ruby][ds-with-ruby] list.

## Data visualization

Please refer to the [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
section on the [Data Science with Ruby][ds-with-ruby] list.

## Articles, Posts, Talks, and Presentations

- 2022
  - _Discover Machine Learning in Ruby_ by [Justin Bowen](https://twitter.com/TonsOfFun111) - <sup>\[[video](https://www.youtube.com/watch?v=HPbizNgcyFk)\]</sup>.
- 2019
  - _TensorStream: Bringing Machine Learning to Ruby_ by [Joseph Emmanuel Dayo](https://www.linkedin.com/in/jdayo/) - <sup>\[[post](https://medium.com/@joseph.dayo/tensorstream-bringing-machine-learning-to-ruby-114582060e3d)\]</sup>.
  - _Easy machine learning with Ruby using SVMKit_ by [@kojix](https://twitter.com/kojix2dayo) - <sup>\[[post](https://dev.to/kojix2/easy-machine-learning-with-ruby-using-svmkit-4n86)\]</sup>.
- 2018
  - _Deep Learning Programming on Ruby_ by [Kenta Murata](https://twitter.com/mrkn) - &amp; [Yusaku Hatanaka ](https://twitter.com/hatappi) <sup>\[[slides](https://speakerdeck.com/mrkn/deep-learning-programming-on-ruby) | [page](https://rubykaigi.org/2018/presentations/mrkn.html)\]</sup>.
  - _How to use trained Keras and TensorFlow machine learning models within Ruby on Rails_ by [Denis Sellu](https://twitter.com/denis_sellu) - <sup>\[[post](https://www.cookieshq.co.uk/posts/how-to-use-trained-keras-and-tensorflow-machine-learning-models-within-ruby-on-rails)\]</sup>.
- 2017
  - _Scientific Computing on JRuby_ by [Prasun Anand](https://twitter.com/prasun_anand) - <sup>\[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) | [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) | [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) | [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)\]</sup>.
  - _Is it Food? An Introduction to Machine Learning_ by [Matthew Mongeau](https://twitter.com/halogenandtoast) - <sup>\[[video](https://www.youtube.com/watch?v=8G709hKkthY) | [slides](https://www.slideshare.net/halogenandtoast/is-it-food)\]</sup>.
  - _Bayes is BAE_ by [Richard Schneeman](https://twitter.com/schneems) - <sup>\[[video](https://www.youtube.com/watch?v=bQSzZrDDV80) | [slides](https://speakerdeck.com/schneems/bayes-is-bae)\]</sup>.
  - _Ruby Roundtable: Machine Learning in Ruby_ by [RubyThursday](https://rubythursday.com/) - <sup>\[[video](https://www.youtube.com/watch?v=ScIFARN0jCo)\]</sup>.
- 2016
  - _Practical Machine Learning with Ruby_ by [Jordan Hudgens](https://twitter.com/jordanhudgens) - <sup>\[[tutorial](https://www.crondose.com/2016/12/practical-machine-learning-ruby/)\]</sup>.
  - _Deep Learning: An Introduction for Ruby Developers_ by [Geoffrey Litt](https://twitter.com/geoffreylitt) - <sup>\[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)\]</sup>.
  - _How I made a pure-Ruby word2vec program more than 3x faster_ by [Kei Sawada](https://twitter.com/remore) - <sup>\[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)\]</sup>.
  - _Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby_ by [Eric Weinstein](https://twitter.com/ericqweinstein) - <sup>\[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)\]</sup>.
  - _Building a Recommendation Engine with Machine Learning Techniques_ by [Brian Sam-Bodden](https://twitter.com/bsbodden) - <sup>\[[video](https://www.youtube.com/watch?v=SRnM_P_ygqI)\]</sup>.
  - :sparkles: [slides](https://speakerdeck.com/mrkn/sciruby-machine-learning-current-status-and-future) - _SciRuby Machine Learning: Current Status and Future_ by Kenta Murata. <sup>\[video: jp](https://www.youtube.com/watch?v=gfQ8XEy7vO4)\]</sup>.
  - [video](https://www.youtube.com/watch?v=pYC5mXHUWkc) - _Ruby Roundtable: Intro to Tensorflow_ by RubyThursday.
- 2015
  - _Machine Learning made simple with Ruby_ by [Lorenzo Masini](https://twitter.com/rugginoso) - <sup>\[[post](https://www.leanpanda.com/blog/2015-08-24-machine-learning-automatic-classification/)\]</sup>.
  - _Using Ruby Machine Learning to Find Paris Hilton Quotes_ by [Rick Carlino](https://github.com/RickCarlino) - <sup>\[[tutorial](https://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)\]</sup>.
- 2014
  - [video](https://www.youtube.com/watch?v=ppf8m-3uXvU&t=36s) - _Test Driven Neural Networks_ by Matthew Kirk.
  - _Five machine learning techniques that you can use in your Ruby apps today_ by [Benjamin Curtis](https://twitter.com/stympy) - <sup>\[[video](https://www.youtube.com/watch?v=crziu7dk6Vw) | [slides](https://speakerdeck.com/stympy/machine-learning-techniques)\]</sup>.
  - _Machine Learning for Fun and Profit_ by [John Paul Ashenfelter](https://twitter.com/johnashenfelter) - <sup>\[[video](https://www.youtube.com/watch?v=KC5MtKHm1O4)\]</sup>.
- 2013
  - [video](https://www.youtube.com/watch?v=iSug6CgxWxc) - _Sentiment Analysis using Support Vector Machines in Ruby_ by Matthew Kirk. <sup>\[code](https://github.com/hexgnu/sentiment_analyzer)\]</sup>.
  - _Recommender Systems with Ruby_ by [Marcel Caraciolo](https://twitter.com/marcelcaraciolo) - <sup>\[[slides](https://www.slideshare.net/marcelcaraciolo/recommender-systems-with-ruby-adding-machine-learning-statistics-etc)\]</sup>.
  - _Detecting Faces with Ruby: FFI in a Nutshell_ by [Marc Berszick](https://www.sitepoint.com/detecting-faces-with-ruby-ffi-in-a-nutshell/) - <sup>\[post\]</sup>.
- 2012
  - _Machine Learning with Ruby, Part One_ by [Vasily Vasinov](https://twitter.com/vasinov) - <sup>\[[tutorial](https://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)\]</sup>.
  - _Recurrent Neural Networks in Ruby_ by [Joseph Wilk](https://twitter.com/josephwilk) - <sup>\[[post](http://blog.josephwilk.net/ruby/recurrent-neural-networks-in-ruby.html)\]</sup>.
  - [video](https://www.youtube.com/watch?v=hsZcrlbBg_0) - _Recommendation Engines using Machine Learning, and JRuby_ by Matthew Kirk.
  - _Practical Machine Learning and Rails_ by [Andrew Cantino](https://twitter.com/tectonic) - And [Ryan Stout](https://twitter.com/ryanstout) <sup>\[[video](https://www.youtube.com/watch?v=vy_zQ1-F0JI)\]</sup>.

- 2011
  - _Clustering in Ruby_ by [Colin Drake](https://twitter.com/colinfdrake) - <sup>\[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)\]</sup>.
  - _Text Classification using Support Vector Machines in Ruby_ by [Rimas Silkaitis](https://twitter.com/neovintage) - <sup>\[[post](http://neovintage.org/2011/11/14/text-classification-using-support/)\]</sup>.
- 2010
  - _bayes_motel – Bayesian classification for Ruby_ by [Mike Perham](https://twitter.com/mperham) - <sup>\[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)\]</sup>.
  - _Intelligent Ruby: Getting Started with Machine Learning_ by [Ilya Grigorik](https://twitter.com/igrigorik) - <sup>\[[video](https://vimeo.com/22513786)\]</sup>.
- 2009

- 2008
  - [post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/) - _Support Vector Machines (SVM) in Ruby_ by Ilya Grigorik.
- 2007
  - [post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/) - _Decision Tree Learning in Ruby_ by Ilya Grigorik.

## Projects and Code Examples

- [Wine Clustering](https://github.com/hexgnu/wine_clustering) - Wine quality estimations clustered with different algorithms. - ★ 0 stars, last push 2014-04-02.
- [Handwritten Digits Recognition](https://github.com/jdrzj/handwritten-digits-recognition) - Using Neural Networks and Ruby. - ★ 6 stars, last push 2021-03-09.

## Heroku buildpacks

- [GSL and Ruby buildpack](https://github.com/tomwolfe/heroku-buildpack-gsl-ruby) - ★ 3 stars, last push 2020-08-15.
- [OpenCV and Ruby buildpack](https://github.com/lilibethdlc/heroku-buildpack-ruby-opencv) - ★ 3 stars, last push 2014-04-29.
- [ImageMagick buildpack](https://github.com/mcollina/heroku-buildpack-imagemagick) - ★ 46 stars, last push 2015-01-31.

## Books, Blogs, Channels

- [Kirk, Matthew](https://twitter.com/mjkirk) - _Thoughtful Machine Learning: A Test-Driven Approach_. O'Reilly, 2014. <sup>\[[Amazon](https://www.amazon.com/Thoughtful-Machine-Learning-Test-Driven-Approach/dp/1449374069) | [code](https://github.com/thoughtfulml/examples)\]</sup>.
- [Practical Artificial Intelligence](https://www.practicalai.io/) - Blog about Artificial Intelligence and Machine Learning with tutorials and code samples in Ruby.

## Community

- [SciRuby Mailing List](https://groups.google.com/forum/#!forum/sciruby-dev)
- [SciRuby Slack](https://sciruby.slack.com/)
- [Red Data Gitter](https://gitter.im/red-data-tools/)
- [Reddit](https://www.reddit.com/r/MachineLearning/search?q=Ruby&restrict_sr=on)
- [Stack Overflow](https://stackoverflow.com/search?q=machine+learning+ruby)
- [Twitter](https://twitter.com/search?q=Machine%20Learning%20Ruby&src=typd)
- [NonWebRuby](https://twitter.com/NonWebRuby)
- [Ruby AI Builders Discord](https://discord.gg/zDyFJFBTGB)
- [X Ruby AI group](https://twitter.com/i/communities/1709211359039078677)
- [Mastodon Ruby AI and Data group](https://ruby.social/@Ruby_AI_and_Data@chirp.social)

## Related Resources

- <a name="lightgbm"></a> [LightGBM](https://github.com/microsoft/LightGBM) - ★ 18,806 stars, last push 2026-09-23.
- <a name="xgboost"></a> [XGBoost](https://github.com/dmlc/xgboost) - ★ 28,789 stars, last push 2026-09-23.
- <a name="gls"></a> [GSL (GNU Scientific Library)][gsl]
- [OpenCV](https://opencv.org/) - <a name="opencv"></a>.
[Graphviz](https://www.graphviz.org/) - <a name="empty-lines-around-access-modifier"></a>.
[Gnuplot](http://www.gnuplot.info/) - <a name="gnuplot"></a>.
[X11/XQuartz](https://www.xquartz.org/) - <a name="xquartz"></a>.
[ImageMagick](https://www.imagemagick.org/script/index.php) - <a name="imagemagic"></a>.
[R](https://www.r-project.org/) - <a name="r"></a>.
[Octave](https://www.gnu.org/software/octave/) - <a name="octave"></a>.
- [scikit-learn algorithm cheatsheet](https://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) - Among other awesome items a short list of NLP related projects. - ★ 14,158 stars, last push 2026-09-22.
- [Ruby NLP](https://github.com/diasks2/ruby-nlp) - State-of-Art collection of Ruby libraries for NLP. - ★ 1,285 stars, last push 2023-03-05.
- [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) - General List of NLP related resources (mostly not for Ruby programmers). - ★ 2,225 stars, last push 2019-04-02.
- [Scientific Ruby](http://sciruby.com/) - Linear Algebra, Visualization and Scientific Computing for Ruby.
- [iRuby](https://github.com/SciRuby/iruby) - Ruby kernel for Jupyter (formerly IPython). - ★ 924 stars, last push 2026-06-30.
- [Kiba](https://github.com/thbar/kiba) - Lightweight [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) (Extract, Transform, Load) pipeline. - ★ 1,775 stars, last push 2026-01-10.
- [Awesome OCR](https://github.com/kba/awesome-ocr) - Multitude of OCR (Optical Character Recognition) resources. - ★ 3,125 stars, last push 2024-07-06.
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) - Machine Learning with TensorFlow libraries. - ★ 17,550 stars, last push 2026-02-08.
- [rb-gsl](https://github.com/SciRuby/rb-gsl) - Ruby interface to the [GNU Scientific Library](https://www.gnu.org/software/gsl/). - ★ 104 stars, last push 2024-06-03.
- [The Definitive Guide to Ruby's C API](https://silverhammermba.github.io/emberb/) - Modern Reference and Tutorial on Embedding and Extending Ruby using C programming language.

<!--- Links --->
[ruby]: https://www.ruby-lang.org/en/
[awesome]: https://github.com/sindresorhus/awesome/blob/master/awesome.md
[ml]: https://en.wikipedia.org/wiki/Machine_learning
[ds-with-ruby]: https://github.com/arbox/data-science-with-ruby
[contributors]: https://github.com/arbox/machine-learning-with-ruby/graphs/contributors
[sciruby]: https://github.com/sciruby
[ai]: https://en.wikipedia.org/wiki/Artificial_intelligence
[cs]: https://en.wikipedia.org/wiki/Computational_science
[fe]: https://en.wikipedia.org/wiki/Feature_engineering
[ts]: https://en.wikipedia.org/wiki/Test_set
[gsl]: https://www.gnu.org/software/gsl/
[scikit]: https://scikit-learn.org/stable/index.html
