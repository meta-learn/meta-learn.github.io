---
title: Workshop on Meta-Learning (MetaLearn 2018)
description: "@NeurIPS 2018 <br> Saturday 08 December 2018 <br> Palais des Congrès de Montréal, Montréal, Canada"

permalink: /2018/index.html
weight: -1
redirect_from: /2018/
---

[The list of questions from the panel discussion are here.](http://www.tricider.com/brainstorming/2WW8MHMNuTR)

Recent years have seen rapid progress in meta-learning methods, which learn (and optimize) the performance of learning methods based on data, generate new learning methods from scratch, or learn to transfer knowledge across tasks and domains. Meta-learning can be seen as the logical conclusion of the arc that machine learning has undergone in the last decade, from learning classifiers, to learning representations, and finally to learning algorithms that themselves acquire representations and classifiers. The ability to improve one’s own learning capabilities through experience can also be viewed as a hallmark of intelligent beings, and there are strong connections with work on human learning in neuroscience.

Meta-learning methods are also of substantial practical interest, since they have, e.g., been shown to yield new state-of-the-art automated machine learning methods, novel deep learning architectures, and substantially improved one-shot learning systems.

Some of the fundamental questions that this workshop aims to address are:
- What are the fundamental differences in the learning “task” compared to traditional  “non-meta” learners?
- Is there a practical limit to the number of meta-learning layers (e.g., would a meta-meta-meta-learning algorithm be of practical use)?
- How can we design more sample-efficient meta-learning methods?
- How can we exploit our domain knowledge to effectively guide the meta-learning process?
- What are the meta-learning processes in nature (e.g, in humans), and how can we take inspiration from them?
- Which ML approaches are best suited for meta-learning, in which circumstances, and why?
- What principles can we learn from meta-learning to help us design the next generation of learning systems?

The goal of this workshop is to bring together researchers from all the different communities and topics that fall under the umbrella of meta-learning. We expect that the presence of these different communities will result in a fruitful exchange of ideas and stimulate an open discussion about the current challenges in meta-learning, as well as possible solutions.

## Invited Speakers ##
- [Nando de Freitas](https://scholar.google.com/citations?user=nzEluBwAAAAJ&hl=en) (DeepMind)
- [Lise Getoor](https://getoor.soe.ucsc.edu/home) (UC Santa Cruz)
- [Hugo Larochelle](https://ai.google/research/people/105144) (Google Brain)
- [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/) (UC Berkeley)
- [Michèle Sebag](https://www.lri.fr/~sebag/) (Paris-Saclay)

## Invited Panelists  ##
- [Roberto Calandra](https://www.robertocalandra.com/) (Facebook AI Research)
- [Nando de Freitas](https://scholar.google.com/citations?user=nzEluBwAAAAJ&hl=en) (DeepMind)
- [Hugo Larochelle](https://ai.google/research/people/105144) (Google Brain)
- [Jürgen Schmidhuber](http://people.idsia.ch/~juergen/) (IDSIA)
- [Michèle Sebag](https://www.lri.fr/~sebag/) (Paris-Saclay)

## Organizers ##
- [Frank Hutter](http://www2.informatik.uni-freiburg.de/~hutter/) (University of Freiburg)
- [Joaquin Vanschoren](http://www.win.tue.nl/~jvanscho/) (Eindhoven University of Technology)
- [Erin Grant](https://people.eecs.berkeley.edu/~eringrant/) (UC Berkeley)
- [Jane Wang](http://www.janexwang.com) (DeepMind)
- [Sachin Ravi](http://www.cs.princeton.edu/~sachinr/) (Princeton)

## Important dates ##
- ~~Submission deadline: 17 October 2018 ([11:59 PM anywhere on Earth](https://www.timeanddate.com/time/zones/aoe))~~
- ~~Notification: 09 November 2018~~
- ~~Camera ready: 03 December 2018~~
- Workshop: 08 December 2018

## Schedule ##

| --------:| ---------------------------------------------------
| 09:00 | Introduction and opening remarks
| 09:10 | Invited talk 1: **Lise Getoor**, ["Exploiting structure for meta-learning"](slides/meta_learning_2018_Getoor.pdf)
| 09:40 | Poster spotlights 1
| 10:00 | Poster session 1
| 10:30 | *Coffee break*
| 11:00 | Invited talk 2: **Sergey Levine**, ["What's wrong with meta-learning (and how we can fix it)"](slides/meta_learning_2018_Levine.pdf)
| 11:30 | Poster session 2
| 12:00 | *Lunch break*
| 13:30 | Invited talk 3: **Hugo Larochelle**, ["Thoughts on progress made and challenges ahead in few-shot learning"](slides/meta_learning_2018_Larochelle.pdf)
| 14:00 | Invited talk 4: **Michèle Sebag**, ["Monte Carlo tree search for algorithm configuration: MOSAIC"](slides/meta_learning_2018_Sebag.pdf)
| 14:30 | Poster spotlights 2
| 14:50 | Poster session 3
| 15:00 | *Coffee break*
| 15:30 | Poster session 4
| 16:00 | Invited talk 5: **Nando de Freitas**, ["Tools that learn"](slides/meta_learning_2018_deFreitas.pdf)
| 16:30 | Contributed talk 1: **JD Co-Reyes**, ["Guiding policies with language via meta-learning"](slides/meta_learning_2018_CoReyes.pdf)
| 16:45 | Contributed talk 2: **Arthur Pesah & Antoine Wehenkel**, ["Recurrent machines for likelihood-free inference"](slides/meta_learning_2018_Pesah.pdf)
| 17:00 | Panel discussion
| 18:00 | End

### Invited Talks

#### Lise Getoor (UC Santa Cruz), ["Exploiting structure for meta-learning"](slides/meta_learning_2018_Getoor.pdf)

Many machine learning problems exhibit rich structural dependencies.  We need meta-learning algorithms which can represent, discover and exploit them,  and we can use structured models to express the dependencies inherent in meta-learning. In this talk, I’ll introduce some common structural dependencies, show their power and how they can be represented, and discuss how we can make use of them for meta-learning.

#### Sergey Levine (UC Berkeley), ["What's wrong with meta-learning (and how we can fix it)"](slides/meta_learning_2018_Levine.pdf)

Meta-learning, or learning to learn, offers an appealing framework for training deep neural networks to adapt quickly and efficiently to new tasks. Indeed, the framework of meta-learning holds the promise of resolving the long-standing challenge of sample complexity in deep learning: by learning to learn efficiently, deep models can be meta-trained to adapt quickly to classify new image classes from a couple of examples, or learn new skills with reinforcement learning from just a few trials.

However, although the framework of meta-learning and few-shot learning is exceedingly appealing, it carries with it a number of major challenges. First, designing neural network models for meta-learning is quite difficult, since meta-learning models must be able to ingest entire datasets to adapt effectively. I will discuss how this challenge can be addressed by describing a model-agnostic meta-learning algorithm: a meta-learning algorithm that can use any model architecture, training that architecture to adapt efficiently via simple finetuning.

The second challenge is that meta-learning trades off the challenge of algorithm design (by learning the algorithm) for the challenge of task design: the performance of meta-learning algorithms depends critically on the ability of the user to manually design large sets of diverse meta-training tasks. In practice, this often ends up being an enormous barrier to widespread adoption of meta-learning methods. I will describe our recent work on unsupervised meta-learning, where tasks are proposed automatically from unlabeled data, and discuss how unsupervised meta-learning can exceed the performance of standard unsupervised learning methods while removing the manual task design requirement inherent in standard meta-learning methods.

#### Hugo Larochelle (Google Brain), ["Thoughts on progress made and challenges ahead in few-shot learning"](slides/meta_learning_2018_Larochelle.pdf)

A lot of the recent progress on many AI tasks were enabled in part by the availability of large quantities of labeled data. Yet, humans are able to learn concepts from as little as a handful of examples. Meta-learning has been a very promising framework for addressing the problem of generalizing from small amounts of data, known as few-shot learning. In this talk, I'll present an overview of the recent research that has made exciting progress on this topic. I will also share my thoughts on the challenges and research opportunities that remain in few-shot learning, including a proposal for a new benchmark.

#### Michèle Sebag (Paris-Saclay), ["Monte Carlo tree search for algorithm configuration: MOSAIC"](slides/meta_learning_2018_Sebag.pdf)

The sensitivity of algorithms (related to machine learning, combinatorial optimization, constraint satisfaction) w.r.t. their  hyperparameters, and the difficulty of finding the algorithm and its hyperparameter setting best suited to the problem instance at hand, has led to the rapidly developing field of algorithm selection and calibration, and, focusing on machine learning, to AutoML.

Several international AutoML challenges have been organized since 2013, motivating the development of the Bayesian optimization-based approach Auto-sklearn, the randomized search approach Hyperband, and others. This talk will present a new approach, called *Monte Carlo Tree Search for Algorithm Configuration* (MOSAIC), fully exploiting the tree structure
of the algorithm portfolio-hyperparameter search space.

It is shown that MOSAIC outperforms the current AutoML winner Auto-Sklearn on both the AutoML challenge 2015, and the MNIST dataset.

Joint work: Heri Rakotoarison

#### Nando de Freitas (DeepMind), ["Tools that learn"](slides/meta_learning_2018_deFreitas.pdf)



### [Spotlights 1](slides/spotlights/spotlight1.pdf) (and Poster Sessions 1 & 2)

1. Meta-Learner with Linear Nulling
1. OBOE: Collaborative Filtering for AutoML Initialization
1. Backpropamine: Meta-Training Self-Modifying Neural Networks with Gradient Descent
1. Hyperparameter Learning via Distributional Transfer
1. Toward Multimodal Model-Agnostic Meta-Learning
1. Fast Neural Architecture Construction Using EnvelopeNets
1. Meta-Dataset: A Dataset of Datasets for Learning to Learn from Few Examples
1. Macro Neural Architecture Search Revisited
1. AutoDL Challenge Design and Beta Tests
1. Modular Meta-Learning in Abstract Graph Networks for Combinatorial Generalization
1. Cross-Modulation Networks for Few-Shot Learning
1. Large Margin Meta-Learning for Few-Shot Classification
1. Amortized Bayesian Meta-Learning
1. The Effects of Negative Adaptation in Model-Agnostic Meta-Learning
1. Mitigating Architectural Mismatch During the Evolutionary Synthesis of Deep Neural Networks
1. Evolvability ES: Scalable Evolutionary Meta-Learning
1. Consolidating the Meta-Learning Zoo: A Unifying Perspective as Posterior Predictive Inference
1. Deep Online Learning via Meta-Learning: Continual Adaptation for Model-Based RL

### [Spotlights 2](slides/spotlights/spotlight2.pdf) (and Poster Sessions 3 & 4)

1. Incremental Few-Shot Learning with Attention Attractor Networks
1. Auto-Meta: Automated Gradient-Based Meta-Learner Search
1. Transferring Knowledge Across Learning Processes
1. Few-Shot Learning for Free by Modeling Global Class Structure
1. TAEML: Task-Adaptive Ensemble of Meta-Learners
1. A Simple Transfer-Learning Extension of Hyperband
1. Learned Optimizers That Outperform SGD on Wall-Clock and Validation Loss
1. Learning to Learn with Conditional Class Dependencies
1. Unsupervised Learning via Meta-Learning
1. Control Adaptation via Meta-Learning Dynamics
1. Learning to Adapt in Dynamic, Real-World Environments via Meta-Reinforcement Learning
1. Learning to Design RNA
1. Graph Hypernetworks for Neural Architecture Search
1. Meta-Learning with Latent Embedding Optimization
1. ProMP: Proximal Meta-Policy Search
1. Attentive Task-Agnostic Meta-Learning for Few-Shot Text Classification
1. Variadic Learning by Bayesian Nonparametric Deep Embedding
1. from Nodes to Networks: Evolving Recurrent Neural Networks
1. Meta Learning for Defaults: Symbolic Defaults

## Submission Instructions  ##

<!-- Papers must be in the latest NeurIPS format, but with a maximum of 4 pages (excluding references). Papers should include the names of all authors (by uncommenting `\neuripsfinal` in the NeurIPS LaTeX template prior to submission). -->
The submission window for this workshop is now closed. Decision notifications were sent out November 9, 2018. Thank you to all who submitted!

We have provided a modified `.sty` file [here](neurips_2018.sty) that appropriately lists the name of the workshop when `\neuripsfinal` is enabled. Please use this style files in conjunction with corresponding LaTeX `.tex` template from the [NeurIPS website](https://neurips.cc/Conferences/2018/PaperInformation/StyleFiles) to submit a final camera-ready copy.

Accepted papers and supplementary material are available on the workshop website. However, these do not constitute archival publications and no formal workshop proceedings will be made available, meaning contributors are free to publish their work in archival journals or conferences.

<!-- *The two best papers submitted will be presented as 15-minute contributed talks*. -->

<!-- Submissions can be made at [https://cmt3.research.microsoft.com/metalearn2018](https://cmt3.research.microsoft.com/metalearn2018) during the submission period. -->

### FAQ ###
1. Can supplementary material be added beyond the 4-page limit and are there any restrictions on it?

   Yes, you may include additional supplementary material, but we ask that it be limited to a reasonable amount (max 10 pages in addition to the main submission) and that it follow the same NeurIPS format as the paper.

2. Can a submission to this workshop be submitted to another NeurIPS workshop in parallel?

   We discourage this, as it leads to more work for reviewers across multiple workshops. Our suggestion is to pick one workshop to submit to.

3. If a submission is accepted, is it possible for all authors of the accepted paper to receive a chance to register?

   We cannot confirm this yet, but it is most likely that we will have at most one registration to offer per accepted paper.

4. Can a paper be submitted to the workshop that has already appeared at a previous conference with published proceedings?

   We won't be accepting such submissions unless they have been adapted to contain significantly new results (where novelty is one of the qualities reviewers will be asked to evaluate).

## Accepted Abstracts  ##

-  [A Simple Transfer-Learning Extension of Hyperband](papers/metalearn2018_paper32.pdf)
[[supp]](papers/metalearn2018_paper32_supp.pdf)
*Lazar Valkov, Rodolphe Jenatton, Fela Winkelmolen, Cedric Archambeau*
-  [Amortized Bayesian Meta-Learning](papers/metalearn2018_paper63.pdf)
*Sachin Ravi, Alex Beatson*
-  [Attentive Task-Agnostic Meta-Learning for Few-Shot Text Classification](papers/metalearn2018_paper23.pdf)
*Xiang Jiang, Mohammad Havaei, Gabriel Chartrand, Hassan Chouaib, Thomas Vincent, Andrew D. Jesson, Nicolas Chapados, Stan Matwin*
-  [Auto-Meta: Automated Gradient-Based Meta-Learner Search](papers/metalearn2018_paper68.pdf)
*Sangyeul Lee, Jaehong Kim, Sungwan Kim, Moonsu Cha, Jung Kwon Lee, Yongseok Choi, Dong-Yeon Cho, Jiwon Kim, Youngduck Choi*
-  [AutoDL Challenge Design and Beta Tests](papers/metalearn2018_paper43.pdf)
*Zhengying Liu, Isabelle Guyon, Olivier Bousquet, Andre Elisseeff, Sergio Escalera, Sebastien Treger, Julio C.S. Jacques Junior, Danny Silver, Adrien Pavao, Wei Wei Tu, Lisheng Sun, Jingsong Wang, Quanming Yao*
-  [Backpropamine: Meta-Training Self-Modifying Neural Networks with Gradient Descent](papers/metalearn2018_paper10.pdf)
*Thomas Miconi, Kenneth O. Stanley, Jeff Clune*
-  [Consolidating the Meta-Learning Zoo: A Unifying Perspective as Posterior Predictive Inference](papers/metalearn2018_paper26.pdf)
*Jonathan Gordon, John Bronskill, Matthias Bauer, Richard Turner, Sebastian Nowozin*
-  [Control Adaptation via Meta-Learning Dynamics](papers/metalearn2018_paper58.pdf)
*James Harrison, Apoorva Sharma, Roberto Calandra, Marco Pavone*
-  [Cross-Modulation Networks for Few-Shot Learning](papers/metalearn2018_paper27.pdf)
*Hugo Prol Pereira, Vincent Dumoulin, Luis Herranz*
-  [Deep Online Learning via Meta-Learning: Continual Adaptation for Model-Based RL](papers/metalearn2018_paper46.pdf)
*Anusha Nagabandi, Sergey Levine, Chelsea Finn*
-  [Evolvability ES: Scalable Evolutionary Meta-Learning](papers/metalearn2018_paper62.pdf)
*Alexander Gajewski, Jeff Clune, Kenneth O. Stanley, Joel Lehman*
-  [Fast Neural Architecture Construction Using EnvelopeNets](papers/metalearn2018_paper28.pdf)
*Purushotham Kamath, Abhishek Singh, Debo Dutta*
-  [Few-Shot Learning for Free by Modeling Global Class Structure](papers/metalearn2018_paper29.pdf)
*Will S. Grathwohl, Xuechen Li, Eleni Triantafillou, Richard Zemel, David Duvenaud*
-  [From Nodes to Networks: Evolving Recurrent Neural Networks](papers/metalearn2018_paper60.pdf)
[[arXiv]](https://arxiv.org/abs/1803.04439)
*Aditya Rawal, Risto Miikkulainen*
-  [Gradient Agreement as an Optimization Objective for Meta-Learning](papers/metalearn2018_paper57.pdf)
[[arXiv]](https://arxiv.org/abs/1810.08178)
*Amir Erfan Eshratifar, David Eigen, Massoud Pedram*
-  [Graph HyperNetworks for Neural Architecture Search](papers/metalearn2018_paper41.pdf)
*Chris Zhang, Mengye Ren, Raquel Urtasun*
-  [Hyperparameter Learning via Distributional Transfer](papers/metalearn2018_paper14.pdf)
*Ho Chung Leon Law, Peilin Zhao, Junzhou Huang, Dino Sejdinovic*
-  [Incremental Few-Shot Learning with Attention Attractor Networks](papers/metalearn2018_paper56.pdf)
*Mengye Ren, Renjie Liao, Ethan Fetaya, Richard Zemel*
-  [Large Margin Meta-Learning for Few-Shot Classification](papers/metalearn2018_paper11.pdf)
*Yong Wang, Xiao-Ming Wu, Qimai Li, Jiatao Gu, Wangmeng Xiang, Lei Zhang, Victor O.K. Li*
-  [Learned Optimizers That Outperform SGD on Wall-Clock and Validation Loss](papers/metalearn2018_paper38.pdf)
*Luke Metz, Niru Maheswaranathan, Jeremy Nixon, Daniel Freeman, Jascha Sohl-Dickstein*
-  [Learning to Adapt in Dynamic, Real-World Environments via Meta-Reinforcement Learning](papers/metalearn2018_paper45.pdf)
*Anusha Nagabandi, Ignasi Clavera, Sergey Levine, Ronald Fearing, Chelsea Finn, Simin Liu, Pieter Abbeel*
-  [Learning to Design RNA](papers/metalearn2018_paper74.pdf)
*Frederic Runge, Danny Stoll, Stefan Falkner, Frank Hutter*
-  [Learning to Learn with Conditional Class Dependencies](papers/metalearn2018_paper12.pdf)
*Xiang Jiang, Mohammad Havaei, Farshid Varno, Gabriel Chartrand, Nicolas Chapados, Stan Matwin*
-  [Macro Neural Architecture Search Revisited](papers/metalearn2018_paper16.pdf)
[[supp]](papers/metalearn2018_paper16_supp.pdf)
*Hanzhang Hu, John Langford, Rich Caruana, Eric Horvitz, Martial Hebert, J. Andrew Bagnell, Debadeepta Dey*
-  [Meta Learning for Defaults: Symbolic Defaults](papers/metalearn2018_paper70.pdf)
*Jan N. Van Rijn, Florian Pfisterer, Janek Thomas, Bernd Bischl, Andreas Mueller, Joaquin Vanschoren*
-  [Meta-Dataset: A Dataset of Datasets for Learning to Learn from Few Examples](papers/metalearn2018_paper42.pdf)
[[supp]](papers/metalearn2018_paper42_supp.pdf)
*Eleni Triantafillou, Tyler Zhu, Vincent Dumoulin, Pascal Lamblin, Kelvin Xu, Ross Goroshin, Carles Gelada, Kevin Swersky, Pierre-Antoine Manzagol, Hugo Larochelle*
-  [Meta-Learner with Linear Nulling](papers/metalearn2018_paper21.pdf)
[[supp]](papers/metalearn2018_paper21_supp.pdf)
*Sung Whan Yoon, Jun Seo, Jaekyun Moon*
-  [Guiding Policies with Language via Meta-Learning](papers/metalearn2018_paper35.pdf)
*John Co-Reyes, Abhishek Gupta, Suvansh Sanjeev, Nick Altieri, John DeNero, Pieter Abbeel, Sergey Levine*
-  [Meta-Learning with Latent Embedding Optimization](papers/metalearn2018_paper34.pdf)
*Andrei A. Rusu, Dushyant Rao, Jakub Sygnowski, Oriol Vinyals, Razvan Pascanu, Simon Osindero, Raia Hadsell*
-  [Mitigating Architectural Mismatch During the Evolutionary Synthesis of Deep Neural Networks](papers/metalearn2018_paper13.pdf)
*Audrey Chung, Paul Fieguth, Alexander Wong*
-  [Modular Meta-Learning in Abstract Graph Networks for Combinatorial Generalization](papers/metalearn2018_paper54.pdf)
*Ferran Alet, Maria Bauza Villalonga, Alberto Rodriguez, Tomas Lozano-Perez, Leslie Kaelbling*
-  [OBOE: Collaborative Filtering for AutoML Initialization](papers/metalearn2018_paper39.pdf)
*Chengrun Yang, Yuji Akimoto, Dae Won Kim, Madeleine Udell*
-  [ProMP: Proximal Meta-Policy Search](papers/metalearn2018_paper59.pdf)
*Ignasi Clavera, Jonas Rothfuss, Dennis Lee, Tamim Asfour, Pieter Abbeel*
-  [Recurrent Machines for Likelihood-Free Inference](papers/metalearn2018_paper77.pdf)
*Arthur Pesah, Antoine Wehenkel, Gilles Louppe*
-  [TAEML: Task-Adaptive Ensemble of Meta-Learners](papers/metalearn2018_paper22.pdf)
*Minseop Park, Jungtaek Kim, Saehoon Kim, Yanbin Liu, Seungjin Choi*
-  [The Effects of Negative Adaptation in Model-Agnostic Meta-Learning](papers/metalearn2018_paper76.pdf)
[[arXiv]](https://arxiv.org/abs/1812.02159)
*Tristan Deleu, Yoshua Bengio*
-  [Toward Multimodal Model-Agnostic Meta-Learning](papers/metalearn2018_paper4.pdf)
[[supp]](papers/metalearn2018_paper4_supp.pdf)
Risto Vuorio, Shao-Hua Sun, Hexiang Hu, Joseph Lim*
-  [Transferring Knowledge Across Learning Processes](papers/metalearn2018_paper24.pdf)
[[supp]](papers/metalearn2018_paper24_supp.pdf)
*Sebastian Flennerhag, Andreas Damianou, Pablo Moreno, Neil Lawrence*
-  [Unsupervised Learning via Meta-Learning](papers/metalearn2018_paper15.pdf)
[[arXiv]](https://arxiv.org/abs/1810.02334)
*Kyle Hsu, Sergey Levine, Chelsea Finn*
-  [Variadic Learning by Bayesian Nonparametric Deep Embedding](papers/metalearn2018_paper37.pdf)
*Kelsey Allen, Hanul Shin, Evan Shelhamer, Joshua Tenenbaum*


## Program Committee ##

We thank the program committee for shaping the excellent technical program (in alphabetical order):   

Aaron Klein,
Abhishek Gupta,
Alexandre Lacoste,
Andre Carvalho,
Andrew Brock,
Anusha Nagabandi,
Aravind Srinivas,
Balazs Kegl,
Benjamin Letham,
Brandon Schoenfeld,
Chelsea Finn,
Daniel Hernandez-Lobato,
Dumitru Erhan,
Eleni Triantafillou,
Eytan Bakshy,
Ghassen Jerfel,
Hugo Larochelle,
Hugo Jair Escalante,
Ignasi Clavera,
Igor Mordatch,
Jake Snell,
Jan van Rijn,
Jasper Snoek,
Jürgen Schmidhuber,
Ke Li,
Lars Kotthoff,
Marius Lindauer,
Matt Hoffman,
Mengye Ren,
Michael Chang,
Misha Denil,
Parminder Bhatia,
Pavel Brazdil,
Pieter Gijsbers,
Rafael Mantovani,
Razvan Pascanu,
Ricardo Prudencio,
Roberto Calandra,
Rodolphe Jenatton,
Roger Grosse,
Roman Garnett,
Sayna Ebrahimi,
Sergio Escalera,
Stephen Roberts,
Thanard Kurutach,
Thomas Elsken,
Tin Ho,
Udayan Khurana


## Past workshops

[Workshop on Meta-Learning (MetaLearn 2017) @ NeurIPS 2017](http://metalearning.ml/2017/)

## Contacts  ##

For any further questions, you can contact us at <info@metalearning.ml>.

## Sponsors ##

We are very thankful to our corporate sponsors!

### Gold

<img src="https://www.bosch-ai.com/media/en/tech/tech_images/bosch_logo_res_340x111.png" alt="Bosch" class="inline"  width="390"/>

### Silver

<img src="https://deepmind.com/static/v0.0.0/images/deepmind_logo.png" alt="DeepMind" class="inline" width="400"/>
