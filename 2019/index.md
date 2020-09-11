---
title: Workshop on Meta-Learning (MetaLearn 2019)
description: "@NeurIPS 2019 <br> Friday 13 December 2019 <br> Vancouver Convention Center, Vancouver, Canada"

permalink: /2019/index.html
weight: -1
redirect_from: /2019/
---

Recent years have seen rapid progress in meta-learning methods, which learn (and optimize) the performance of learning methods based on data, generate new learning methods from scratch, and learn to transfer knowledge across tasks and domains. Meta-learning can be seen as the logical conclusion of the arc that machine learning has undergone in the last decade, from learning classifiers, to learning representations, and finally to learning algorithms that themselves acquire representations and classifiers. The ability to improve one’s own learning capabilities through experience can also be viewed as a hallmark of intelligent beings, and there are strong connections with work on human learning in neuroscience.

Meta-learning methods are also of substantial practical interest, since they have, e.g., been shown to yield new state-of-the-art automated machine learning methods, novel deep learning architectures, and substantially improved one-shot learning systems. 

Some of the fundamental questions that this workshop aims to address are:
- How can we exploit our domain knowledge to effectively guide the meta-learning process?
- What are the meta-learning processes in nature (e.g, in humans), and how can we take inspiration from them?
- Which ML approaches are best suited for meta-learning, in which circumstances, and why?
- What principles can we learn from meta-learning to help us design the next generation of learning systems? 
- What are the fundamental differences in the learning “task” compared to traditional  “non-meta” learners?
- Is there a practical limit to the number of meta-learning layers (e.g., would a meta-meta-meta-learning algorithm be of practical use)?
- How can we design more sample-efficient meta-learning methods?

The goal of this workshop is to bring together researchers from all the different communities and topics that fall under the umbrella of meta-learning. We expect that the presence of these different communities will result in a fruitful exchange of ideas and stimulate an open discussion about the current challenges in meta-learning, as well as possible solutions.

In terms of prospective participants, our main targets are machine learning researchers interested in the processes related to understanding and improving current meta-learning algorithms. Specific target communities within machine learning include, but are not limited to: meta-learning, AutoML, reinforcement learning, deep learning, optimization, evolutionary computation, and Bayesian optimization. Our invited speakers also include researchers who study human learning, to provide a broad perspective to the attendees.


## Invited Speakers ##

Submit challenge questions for the speakers [here](https://forms.gle/DGEev5erxAmoi6eEA).  

- [Pieter Abbeel](https://people.eecs.berkeley.edu/~pabbeel/) (UC Berkeley, Covariant.ai)  
    **Interaction of Model-based RL and Meta-RL**

- [David Abel](https://david-abel.github.io/) (Brown University)  
    **Abstraction & Meta-Reinforcement Learning**  
    Reinforcement learning is hard in a fundamental sense: even in finite and deterministic environments, it can take a large number of samples to find a near-optimal policy. In this talk, I discuss the role that abstraction can play in achieving reliable yet efficient learning and planning. I first introduce classes of state abstraction that induce a trade-off between optimality and the size of an agent's resulting abstract model, yielding a practical algorithm for learning useful and compact representations from a demonstrator. Moreover, I show how these learned, simple representations can underlie efficient learning in complex environments. Second, I analyze the problem of searching for options that make planning more efficient. I present new computational complexity results that illustrate it is NP-hard to find the optimal options that minimize planning time, but show this set can be approximated in polynomial time. Collectively, these results provide a partial path toward abstractions that minimize the difficulty of high quality learning and decision making.

- [Jeff Clune](http://jeffclune.com/) (University of Wyoming, Uber AI)  
    **How Meta-Learning Could Help Us Accomplish Our Grandest AI Ambitions, and Early, Exotic Steps in that Direction**  
    A dominant trend in machine learning is that hand-designed pipelines are replaced by higher-performing learned pipelines once sufficient compute and data are available. I argue that trend will apply to machine learning itself, and thus that the fastest path to truly powerful AI is to create AI-generating algorithms (AI-GAs) that on their own *learn* to solve the hardest AI problems. This paradigm is an all-in bet on meta-learning. To produce AI-GAs, we need work on Three Pillars: meta-learning architectures, meta-learning learning algorithms, and automatically generating environments. In this talk I will present recent work from our team in each of the three pillars: Pillar 1: Generative Teaching Networks (GTNs); Pillar 2: Differential plasticity, differentiable neuromodulated plasticity (“backpropamine”), and a Neuromodulated Meta-Learning algorithm (ANML); Pillar 3: the Paired Open-Ended Trailblazer (POET). My goal is to motivate future research into each of the three pillars and their combination.

- [Erin Grant](https://people.eecs.berkeley.edu/~eringrant/) (UC Berkeley)  
    **Meta-learning as hierarchical modelling**  

- [Raia Hadsell](http://raiahadsell.com/index.html) (DeepMind)  
    **Scalable Meta-Learning**

- [Brenden Lake](https://cims.nyu.edu/~brenden/) (NYU, Facebook AI Research)  
    **Compositional generalization in minds and machines**  
    People learn in fast and flexible ways that elude the best artificial neural networks. Once a person learns how to “dax,” they can effortlessly understand how to “dax twice” or “dax vigorously” thanks to their compositional skills. In this talk, we examine how people and machines generalize compositionally in language-like instruction learning tasks. Artificial neural networks have long been criticized for lacking systematic compositionality (Fodor & Pylshyn, 1988; Marcus, 1998), but new architectures have been tackling increasingly ambitious language tasks. In light of these developments, we reevaluate these classic criticisms and find that artificial neural nets still fail spectacularly when systematic compositionality is required. We then show how people succeed in similar few-shot learning tasks and find they utilize three inductive biases that can be incorporated into models. Finally, we show how more structured neural nets can acquire compositional skills and human-like inductive biases through meta-learning.

## Spotlights
### Morning Session
- [**MetaPoison: Learning to Craft Adversarial Poisoning Examples via Meta-Learning**.](slides/metalearn2019-huang.pdf)
 *W. Ronny Huang, Jonas Geiping, Liam  Fowl, Tom  Goldstein*
 
 - [**Meta-Learning Contextual Bandit Exploration**.](slides/metalearn2019-sharaf.pdf)
 *Amr Sharaf, Hal  Daume*
 
- [**ES-MAML: Learning to Adapt with Evolution Strategies**.](slides/metalearn2019-song.pdf)
 *Xingyou Song, Krzysztof Choromanski, Wenbo  Gao, Yuxiang  Yang, Yunhao  Tang, Aldo  Pacchiano*
 
 - [**A quantile-based approach to hyperparameter transfer learning**.](slides/metalearn2019-salinas.pdf) 
 *David Salinas, Huibin  Shen, Valerio Perrone* 
 
 - [**Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning**.](slides/metalearn2019-yu.pdf)
 *Tianhe Yu, Deirdre  Quillen, Zhanpeng  He, Ryan  Julian, Karol  Hausman, Sergey  Levine, Chelsea  Finn*
 
### Afternoon Session
- [**An empirical study of pretrained representations for few-shot classification**.](slides/metalearn2019-ramalho.pdf)
 *Tiago Ramalho, Thierry  Sousbie, Stefano  Peluchetti*
 
 - [**A Baseline for Few-Shot Image Classification**.](slides/metalearn2019-dhillon.pdf)
 *Guneet S Dhillon, Pratik  Chaudhari, Avinash Ravichandran, Stefano Soatto* 
 
 - [**Charting the Right Manifold: Manifold Mixup for Few-shot Learning**.](slides/metalearn2019-mangla.pdf)
 *Puneet Mangla, Mayank Singh, Nupur Kumari, Abhishek  Sinha, Balaji  Krishnamurthy, Vineeth  N Balasubramanian*
 
 - [**Meta-Learning of Structured Representation by Proximal Mapping**.](slides/metalearn2019-li1.pdf)
 *Mao Li, Yingyi  Ma, Hongwei  Jin, Zhan  Shi, Xinhua  Zhang*
 
 - [**Deep Subspace Networks For Few-Shot Learning**.](slides/metalearn2019-simon.pdf)
 *Christian Simon, Piotr  Koniusz, Richard  Nock, Mehrtash  Harandi*
 
 
 



## Organizers ##
- [Roberto Calandra](https://www.robertocalandra.com/) (Facebook AI Research)
- [Ignasi Clavera](https://iclavera.github.io/) (UC Berkeley)
- [Frank Hutter](http://www2.informatik.uni-freiburg.de/~hutter/) (University of Freiburg)
- [Joaquin Vanschoren](http://www.win.tue.nl/~jvanscho/) (Eindhoven University of Technology)
- [Jane Wang](http://www.janexwang.com) (DeepMind)

## Important Dates ##
- ~~Submission deadline: 10 September 2019 ([11:59 PM anywhere on Earth](https://www.timeanddate.com/time/zones/aoe))~~
- ~~Notification: 1 October 2019~~
- ~~Camera ready: 4 December 2019~~
- Workshop: 13 December 2019

## Schedule ##

| --------:| ---------------------------------------------------
| 09:00 | Introduction and opening remarks 
| 09:10 | **Erin Grant**
| 09:40 | **Jeff Clune**
| 10:10 | *Coffee & posters*
| 10:30 | Poster spotlights 1
| 10:50 | *Posters*
| 11:30 | **Pieter Abbeel**
| 12:00 | Discussion 1
| 12:30 | *Lunch break*
| 14:00 | **David Abel**
| 14:30 | **Raia Hadsell**
| 15:00 | Poster spotlights 2
| 15:20 | *Coffee & posters* 
| 16:30 | **Sebastian Flennerhag**: Meta-Learning with Warped Gradient Descent
| 16:45 | **Jessica Lee**: MetaPix: Few-shot video retargeting
| 17:00 | **Brenden Lake**
| 17:30 | Discussion 2
| 17:50 | End

[Video1](https://slideslive.com/38921882/metalearning-1)

[Video2](https://slideslive.com/38922013/metalearning-2)

[Video3](https://slideslive.com/38921884/metalearning-3)

[Video4](https://slideslive.com/38921885/metalearning-4)

<!-- 
## Submission Instructions  ##
Papers must be in the latest [NeurIPS format](https://neurips.cc/Conferences/2019/PaperInformation/StyleFiles), but with a maximum of 4 pages (excluding references). 

Papers should be anonymized upon submission. 

Accepted papers and eventual supplementary material will be made available on the workshop website. However, this does not constitute an archival publication and no formal workshop proceedings will be made available, meaning contributors are free to publish their work in archival journals or conferences.

The two best papers submitted will be presented as 15-minute contributed talks.

Submissions can be made at [https://cmt3.research.microsoft.com/METALEARN2019/Submission/Index](https://cmt3.research.microsoft.com/METALEARN2019/Submission/Index)
during the submission period. -->



### FAQ ###
1. Can supplementary material be added beyond the 4-page limit and are there any restrictions on it?

   Yes, you may include additional supplementary material, but you should ensure that the main paper is self-contained, since looking at supplementary material is at the discretion of the reviewers. The supplementary material should also follow the same NeurIPS format as the paper and be limited to a reasonable amount (max 10 pages in addition to the main submission).

2. Can a submission to this workshop be submitted to another NeurIPS workshop in parallel?

   We discourage this, as it leads to more work for reviewers across multiple workshops. Our suggestion is to pick one workshop to submit to.

3. If a submission is accepted, is it possible for all authors of the accepted paper to receive a chance to register?

   We cannot confirm this yet, but it is most likely that we will have at most one registration to offer per accepted paper.

4. Can a paper be submitted to the workshop that has already appeared at a previous conference with published proceedings?

   We won't be accepting such submissions unless they have been adapted to contain significantly new results (where novelty is one of the qualities reviewers will be asked to evaluate).

5. Can a paper be submitted to the workshop that is currently under review or will be under review at a conference during the review phase? 

	MetaLearn submissions are 4 pages, i.e., much shorter than standard conference submissions. But from our side it is perfectly fine to submit a condensed version of a parallel conference submission, if it also fine for the conference in question. Our workshop does not have archival proceedings, and therefore parallel submissions of extended versions to other conferences are acceptable.

6. Are there any instructions for poster formatting or for the camera-ready?

  - Posters should be A0, preferably on light paper. Poster can be hung up before the start of the workshop or during the breaks or poster sessions.
  - The camera-ready version of your accepted paper should be limited to 4 pages, with up to 10 pages additional materials.
	

## Accepted Papers ##

- [**Deep Subspace Networks For Few-Shot Learning**.](papers/metalearn2019-simon.pdf)
 *Christian Simon, Piotr  Koniusz, Richard  Nock, Mehrtash  Harandi*

- [**On the conditions of MAML convergence**](papers/metalearn2019-takagi.pdf)
 *Shiro Takagi, Yoshihiro Nagano, Yuki Yoshida, and Masato Okada*

- [**Constrained Bayesian Optimization with Max-Value Entropy Search**.](papers/metalearn2019-perrone.pdf) [[Appendix](papers/metalearn2019-perrone-appendix.pdf)]
 *Valerio Perrone, Iaroslav  Shcherbatyi, Rodolphe  Jenatton, Cedric  Archambeau, Matthias  Seeger* 

- [**Is Fast Adaptation All You Need?**.](paper/metalearn2019-javed.pdf)
 *Khurram Javed, Hengshuai  Yao, Martha  White*

- [**Learning to tune XGBoost with XGBoost**.](papers/metalearn2019-sommer.pdf)
 *Johanna Sommer, Dimitrios  Sarigiannis, Thomas  Parnell*

- [**Texture Bias Of CNNs Limits Few-Shot Classification Performance**.](papers/metalearn2019-ringer.pdf)
 *Sam Ringer, William JW Williams, Tom Ash, Remi Francis, David Macleod*

- [**Meta-Learning Contextual Bandit Exploration**.](papers/metalearn2019-sharaf.pdf)
 *Amr Sharaf, Hal  Daume*

- [**Gradient-Aware Model-based Policy Search**.](papers/metalearn2019-doro.pdf)
 *Pierluca D'Oro, Alberto Maria  Metelli, Andrea  Tirinzoni, Matteo  Papini, Marcello  Restelli*

- [**Transferable Neural Processes for Hyperparameter Optimization**.](papers/metalearn2019-wei.pdf)
 *Ying Wei, Peilin  Zhao, Huaxiu  Yao, Junzhou  Huang*

- [**DEGAS: Differentiable Efficient Generator Search**.](papers/metalearn2019-doveh.pdf)
 *Sivan Doveh, Raja  Giryes*

- [**Niseko: a Large-Scale Meta-Learning Dataset**.](papers/metalearn2019-shang.pdf) [[Appendix](papers/metalearn2019-shang-appendix.pdf)]
 *Zeyuan Shang, Emanuel   Zgraggen, Philipp  Eichmann, Tim  Kraska* 

- [**AutoML using Metadata Language Embeddings**.](papers/metalearn2019-drori.pdf)
 *Iddo Drori, Lu  Liu, Yi  Nian, Sharath  Koorathota, Jie  Li, Antonio K  Moretti, Juliana   Freire , Madeleine  Udell*

- [**Neural Architecture Search via Bayesian Optimization with a Neural Network Prior**.](papers/metalearn2019-white.pdf)
 *Colin White, Willie  Neiswanger, Yash  Savani*

- [**Improved Training Speed, Accuracy, and Data Utilization Through Loss Function Optimization**.](papers/metalearn2019-gonzalez.pdf) [[Appendix](papers/metalearn2019-gonzalez-appendix.pdf)]
 *Santiago Gonzalez, Risto  Miikkulainen* 

- [**Domain-Agnostic Few-Shot Classification by Learning Disparate Modulators**.](papers/metalearn2019-choi.pdf)
 *Yongseok Choi, Junyoung  Park, Subin  Yi, Dong-Yeon  Cho*

- [**Meta-analysis of Continual Learning**.](papers/metalearn2019-nguyen.pdf)
 *Cuong V. Nguyen, Alessandro Achille, Michael Lam, Tal Hassner, Vijay Mahadevan, Stefano Soatto*

- [**Meta-Learning of Structured Representation by Proximal Mapping**.](papers/metalearn2019-li1.pdf)
 *Mao Li, Yingyi  Ma, Hongwei  Jin, Zhan  Shi, Xinhua  Zhang*

- [**Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning**.](papers/metalearn2019-yu.pdf)
 *Tianhe Yu, Deirdre  Quillen, Zhanpeng  He, Ryan  Julian, Karol  Hausman, Sergey  Levine, Chelsea  Finn*

- [**An empirical study of pretrained representations for few-shot classification**.](papers/metalearn2019-ramalho.pdf)
 *Tiago Ramalho, Thierry  Sousbie, Stefano  Peluchetti*

- [**Warm Starting Method for CMA-ES**.](papers/metalearn2019-nomura.pdf)
 *Masahiro Nomura, Shuhei  Watanabe, Yoshihiko  Ozaki, Masaki  Onishi*

- [**Bayesian Optimisation over Multiple Continuous and Categorical Inputs**.](papers/metalearn2019-ru.pdf)
 *Binxin Ru, Ahsan  Alvi, Vu  Nguyen, Michael A.   Osborne, Stephen  Roberts*

- [**Noise Contrastive Meta-Learning for Conditional Density Estimation using Kernel Mean Embeddings**.](papers/metalearn2019-ton.pdf)
 *Jean-Francois Ton, Leung Chan, Yee Whye  Teh, Dino  Sejdinovic*

- [**MetaPoison: Learning to Craft Adversarial Poisoning Examples via Meta-Learning**.](papers/metalearn2019-huang.pdf)
 *W. Ronny Huang, Jonas Geiping, Liam  Fowl, Tom  Goldstein*

- [**MetaPix: Few-shot video retargeting**.](papers/metalearn2019-lee.pdf)
 *Jessica Lee, Deva Ramanan, Rohit Girdhar*

- [**Meta-Learning with Warped Gradient Descent**.](papers/metalearn2019-flennerhag.pdf)
 *Sebastian Flennerhag, Andrei A. Rusu, Razvan  Pascanu, Hujun Yin, Raia  Hadsell*

- [**Characterizing Policy Divergence for Personalized Meta-Reinforcement Learning**.](papers/metalearn2019-zhang.pdf)
 *Michael Zhang*

- [**Modular Meta-Learning with Shrinkage**.](papers/metalearn2019-chen.pdf)
 *Yutian Chen, Abram  Friesen, Feryal Behbahani, David  Budden, Matt  Hoffman, Arnaud  Doucet, Nando  de Freitas*

- [**Meta-analysis of Bayesian analyses**.](papers/metalearn2019-blomstedt.pdf) [[Appendix](papers/metalearn2019-blomstedt-appendix.pdf)]
 *Paul Blomstedt, Diego  Mesquita, Samuel  Kaski* 

- [**Ranking architectures using meta-learning**.](papers/metalearn2019-dubatovka.pdf)
 *Alina Dubatovka, Effrosyni  Kokiopoulou, Luciano  Sbaiz, Andrea  Gesmundo, Gabor  Bartok, Jesse  Berent*

- [**Meta-Learning Deep Energy-Based Memory Models**.](papers/metalearn2019-bartunov.pdf) [[Appendix](papers/metalearn2019-bartunov-appendix.pdf)]
 *Sergey Bartunov, Jack  Rae, Simon  Osindero, Timothy  Lillicrap* 

- [**ES-MAML: Learning to Adapt with Evolution Strategies**.](papers/metalearn2019-song.pdf)
 *Xingyou Song, Krzysztof Choromanski, Wenbo  Gao, Yuxiang  Yang, Yunhao  Tang, Aldo  Pacchiano*

- [**Charting the Right Manifold: Manifold Mixup for Few-shot Learning**.](papers/metalearn2019-mangla.pdf)
 *Puneet Mangla, Mayank Singh, Nupur Kumari, Abhishek  Sinha, Balaji  Krishnamurthy, Vineeth  N Balasubramanian*

- [**A quantile-based approach to hyperparameter transfer learning**.](papers/metalearn2019-salinas.pdf) [[Appendix](papers/metalearn2019-salinas-appendix.pdf)]   
 *David Salinas, Huibin  Shen, Valerio Perrone* 

- [**Learning an Adaptive Learning Rate Schedule**.](papers/metalearn2019-xu.pdf)
 *Zhen Xu, Andrew  M  Dai, Jonas  Kemp, Luke  Metz*

- [**VIABLE: Fast Adaptation via Backpropagating Learned Loss**.](papers/metalearn2019-feng.pdf)
 *Leo Feng, Luisa  Zintgraf, Bei  Peng, Shimon  Whiteson*

- [**Empirical Bayes Meta-Learning with Synthetic Gradients**.](papers/metalearn2019-hu.pdf)
 *Shell Xu Hu, Pablo  Moreno, Xi  Shen, Yang  Xiao, Neil  Lawrence, Guillaume  Obozinski, Andreas  Damianou*

- [**Zero-Shot Text Classification With Generative Language Models**.](papers/metalearn2019-puri.pdf)
 *Raul Puri, Bryan  Catanzaro*

- [**On Transfer Learning via Linearized Neural Networks**.](papers/metalearn2019-maddox.pdf)
 *Wesley J Maddox, Shuai  Tang, Pablo Moreno, Andrew Gordon Gordon  Wilson, Andreas  Damianou*

- [**Rapid Learning or Feature Reuse? Towards Understanding the Effectiveness of MAML**.](papers/metalearn2019-raghu.pdf)
 *Aniruddh Raghu, Maithra  Raghu, Oriol Vinyals, Samy  Bengio*

- [**Learning Compositional Rules via Neural Program Synthesis**.](papers/metalearn2019-nye.pdf)
 *Maxwell Nye, Armando  Solar-Lezama, Joshua  Tenenbaum, Brenden  Lake*

- [**Assay modelling with adaptive deep kernel learning**.](papers/metalearn2019-tossou.pdf)
 *Prudencio Tossou, Basile  Dura, Alexandre  Lacoste*

- [**Meta-Learning without Memorization**.](papers/metalearn2019-yin.pdf)
 *Mingzhang Michael Yin, Chelsea  Finn, George  Tucker, Sergey  Levine*

- [**Meta-reinforcement learning of causal strategies**.](papers/metalearn2019-dasgupta.pdf)
 *Ishita Dasgupta, Zeb  Kurth-Nelson, Silvia  Chiappa, Jovana  Mitrovic, Edward  Hughes, Pedro Ortega, Matthew  Botvinick, Jane  Wang*

- [**Improving Model Robustness via Automatically Incorporating Self-supervision Tasks**.](papers/metalearn2019-kim.pdf)
 *Donghwa Kim, Kangwook  Lee, Changho  Suh*

- [**Meta-learning curiosity algorithms**.](papers/metalearn2019-alet.pdf)
 *Ferran Alet, Martin  Schneider, Tomas  Lozano-Perez, Leslie  Kaelbling*

- [**Differentially Private Meta-Learning**.](papers/metalearn2019-li2.pdf)
 *Jeffrey Li, Mikhail  Khodak, Sebastian  Caldas, Ameet  Talwalkar*

- [**Neural Architecture Evolution in Deep Reinforcement Learning for Continuous Control**.](papers/metalearn2019-franke.pdf)
 *Jörg K.H. Franke, Gregor  Koehler, Noor  Awad, Frank  Hutter*

- [**Continuous Meta-Learning without Task Supervision**.](papers/metalearn2019-harrison.pdf) [[Appendix](papers/metalearn2019-harrison-appendix.pdf)] 
 *James Harrison, Apoorva  Sharma, Chelsea  Finn, Marco  Pavone* 

- [**Online Meta-Learning on Non-convex Setting**.](papers/metalearn2019-zhuang.pdf) [[Appendix](papers/metalearn2019-zhuang-appendix.pdf)] 
 *Zhenxun Zhuang, Kezi  Yu, Songtao  Lu, Lucas Glass, Yunlong  Wang* 

- [**PAC-Bayes Objectives for Meta-Learning using Deep Probabilistic Programs**.](papers/metalearn2019-warrell.pdf)
 *Jonathan Warrell*

- [**A Baseline for Few-Shot Image Classification**.](papers/metalearn2019-dhillon.pdf) [[Appendix](papers/metalearn2019-dhillon-appendix.pdf)] 
 *Guneet S Dhillon, Pratik  Chaudhari, Avinash Ravichandran, Stefano Soatto* 

- [**NASIB: Neural Architecture Search withIn Budget**.](papers/metalearn2019-singhv2.pdf)
 *Abhishek Singh, Anubhav Garg, Jinan Zhou, Shiv Ram Dubey, Debo Dutta*

- [**Understanding and Robustifying Differentiable Architecture Search**.](papers/metalearn2019-zela.pdf)
 *Arber Zela, Thomas  Elsken, Yassine  Marrakchi, Tonmoy  Saikia, Thomas  Brox, Frank  Hutter*

- [**Learning to Estimate Point-Prediction Uncertainty and Correct Output in Neural Networks**.](papers/metalearn2019-qiu.pdf) [[Appendix](papers/metalearn2019-qiu-appendix.pdf)] 
 *Xin Qiu, Elliot  Meyerson, Risto  Miikkulainen* 

- [**Towards Benchmarking and Dissecting One-shot Neural Architecture Search**.](papers/metalearn2019-siems.pdf)
 *Julien  Siems, Arber Zela, Frank  Hutter*

- [**Decoupled Meta Learning with Structured Latents**.](papers/metalearn2019-mendonca.pdf)
 *Russell Mendonca, Sergey  Levine, Chelsea  Finn*

- [**Automated Model Search Using Bayesian Optimization and Genetic Programming**.](papers/metalearn2019-schlessinger.pdf)
 *Louis B Schlessinger, Gustavo  Malkomes, Roman  Garnett*

- [**Meta-Learning for Algorithm and Hyperparameter Optimization with Surrogate Model Ensembles**.](papers/metalearn2019-manolache.pdf)
 *Georgiana Manolache, Joaquin  Vanschoren*


 
## Program Committee ##

We thank the program committee for shaping the excellent technical program (in alphabetical order):

Aaron Klein,
Abhishek Gupta,
Alexander Toshev,
Alexandre 	Galashov,
Andre Carvalho,
Andrei A. Rusu,
Ang Li,
Ashvin V. Nair,
Avi Singh,
Aviral Kumar,
Ben Eysenbach,
Benjamin Letham,
Bradly C,
Brandon Schoenfeld,
Brian Cheung,
Carlos Soares,
Daniel Hernandez,
Deirdre Quillen,
Devendra ingh,
Dumitru Erhan,
Dushyant Rao,
Eleni Triantafillou,
Erin Grant,
Esteban 	Real,
Eytan Bakshy,
Frank Hutter,
Haoran Tang,
Hugo air,
Igor Mordatch,
Jakub Sygnowski,
Jan Humplik,
Jan N. van Rijn,
Jan endrik,
Jiajun Wu,
Jonas Rothfuss,
Jonathan 	Schwarz,
Jürgen 	Schmidhuber,
Kate Rakelly,
Katharina 	Eggensperger,
Kevin Swersky,
Kyle Hsu,
Lars Kotthoff,
Leonard 	Hasenclever,
Lerrel Pinto,
Luisa Zintgraf,
Marc Pickett,
Marta 	Garnelo,
Marvin Zhang,
Matthias Seeger,
Maximilian 	Igl,
Misha 	Denil,
Parminder Bhatia,
Parsa Mahmoudieh,
Pavel Brazdil,
Pieter Gijsbers,
Piotr Mirowski,
Rachit Dubey,
Rafael Gomes,
Razvan Pascanu,
Ricardo B. Prudencio,
Roger B. Grosse,
Rowan McAllister,
Sayna Ebrahimi,
Sebastien 	Racaniere,
Sergio Escalera,
Siddharth Reddy,
Stephen Roberts,
Sungryull 	Sohn,
Surya 	Bhupatiraju,
Thomas Elsken,
Tin K. Ho,
Udayan Khurana,
Vincent Dumoulin,
Vitchyr H. Pong,
Zeyu Zheng

## Past Workshops

[Workshop on Meta-Learning (MetaLearn 2017) @ NeurIPS 2017](http://metalearning.ml/2017/)

[Workshop on Meta-Learning (MetaLearn 2018) @ NeurIPS 2018](http://metalearning.ml/2018/)

## Sponsors ##
We are grateful for the support of our sponsors, which enabled us to offer travel grants to several participants.

<img src="https://static.xx.fbcdn.net/rsrc.php/v3/yW/r/1hFIifa2Fcy.png" alt="Facebook" width="250">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Amazon" width="200">
<img src="https://upload.wikimedia.org/wikipedia/commons/1/12/DeepMind_logo.png" alt="Deepmind" width="250">

## Contacts  ##

For any further questions, you can contact us at <info@metalearning.ml>.

