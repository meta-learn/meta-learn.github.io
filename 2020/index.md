---
title: Workshop on Meta-Learning (MetaLearn 2020)
description: "@NeurIPS 2020 <br> 11 December 2020 <br> (Virtual-Only)"

permalink: /2020/index.html
weight: -1
redirect_from: /2020/
---

## Live participation

- Access the livestream on our virtual workshop page [here](https://neurips.cc/virtual/2020/protected/workshop_16141.html).
- Join the poster sessions on gather.town: [Session 1](https://neurips.gather.town/app/eLVTscsoraKKHuLI/posterRoom0), [Session 2](https://neurips.gather.town/app/ahqPiPXgtuJF1JU7/posterRoom1), [Session 3](https://neurips.gather.town/app/DK1OFwX1bToEpTYi/posterRoom2). You can find the sessions for each paper in the list of accepted papers below.
- Talk to us on [rocket.chat](https://neurips2020.rocket.chat/channel/meta-learning-99).

<center>
Panel discussion questions:
<div id="main_block">
        <iframe src="https://app.sli.do/event/uihcwqn4" height="100%" width="60%" style="min-height: 560px;"></iframe>
</div>
</center>

## News & Updates

- Nov 16, 2020: NeurIPS registration funding from the workshop for presenters and junior reviewers has been distributed. The NeurIPS conference also has a funding program [here](https://neurips.cc/Surveys/49).

- Nov 14, 2020: The workshop [schedule](#schedule) has been finalized! You can also find it on [NeurIPS.cc](https://nips.cc/Conferences/2020/ScheduleMultitrack?event=16141).

- Oct 30, 2020: Decisions have been sent out. Thank you to everyone who submitted or participated in [the reviewing process](#reviewing-mentorship)!

- Oct 4, 2020: The submission portal has now closed and [the reviewing process](#reviewing-mentorship) has begun.

- Sep 15, 2020: [Reviewing mentorship sign-up & recommendation form](#reviewing-mentorship) released!

- Sep 2, 2020: CMT open for [submissions](#submission-instructions)!

## Workshop Overview

### Abstract

Recent years have seen rapid progress in meta-learning methods, which transfer knowledge across tasks and domains to learn new tasks more efficiently, optimize the learning process itself, and even generate new learning methods from scratch. Meta-learning can be seen as the logical conclusion of the arc that machine learning has undergone in the last decade, from learning classifiers and policies over hand-crafted features, to learning representations over which classifiers and policies operate, and finally to learning algorithms that themselves acquire representations, classifiers, and policies.

Meta-learning methods are of substantial practical interest. For instance, they have been shown to yield new state-of-the-art automated machine learning algorithms and architectures, and have substantially improved few-shot learning systems. Moreover, the ability to improve one’s own learning capabilities through experience can also be viewed as a hallmark of intelligent beings, and there are strong connections with work on human learning in cognitive science and reward learning in neuroscience.

Some of the fundamental questions that this workshop aims to address are:

- How can we exploit our domain knowledge to effectively guide the meta-learning process?
- What are the meta-learning processes in nature (e.g., in humans), and how can we take inspiration from them?
- Which machine learning approaches are best suited for meta-learning, in which circumstances, and why?
- What principles can we learn from meta-learning to help us design the next generation of learning systems?
- How can we design more sample-efficient meta-learning methods?

In this edition of the meta-learning workshop, we want to stimulate discussion on several key underlying and unsolved questions, particularly:

- **Task distributions**: What constitutes a distribution of tasks, domains, or problems? What does it mean to have learned this distribution, and to generalize outside of this distribution?
- **Transfer/continual/lifelong learning**: What is the relationship between meta-learning and transfer/continual or lifelong learning? How do the notions of "meta-train" and "meta-test" datasets map to continual or lifelong learning?
- **Inductive biases**: What is the role of inductive biases, be they algorithmic or architectural? How do they manifest in evolution, neural architecture search, etc.? What kinds of useful inductive biases can we learn from neuroscience or cognitive science?

This workshop aims to bring together researchers from all the different communities and topics that fall under the umbrella of meta-learning. We expect that the presence of these different communities will result in a fruitful exchange of ideas and stimulate an open discussion about the current challenges in meta-learning as well as possible solutions.

In terms of prospective participants, our main targets are machine learning researchers interested in the processes related to understanding and improving current meta-learning algorithms. Specific target communities within machine learning include, but are not limited to meta-learning, AutoML, reinforcement learning, deep learning, optimization, evolutionary computation, and Bayesian optimization. We also invite submissions from researchers who study human learning and neuroscience to provide a broad perspective to the attendees.

### Virtual Format

In terms of organizing this workshop in a virtual format, we understand that accessibility across time zones is a significant challenge for a virtual meeting. We will thus offer a mix of synchronous and asynchronous formats that allow participation despite this complication. In thinking about this format, we took inspiration from best practices that emerged from past conferences.

Specifically, we will require both invited speakers and authors of accepted papers to make pre-recorded videos available in advance, allowing registered participants to engage with the recordings at any time. This will be accompanied by live offerings such as a panel session and Q&A for invited talks or spotlights, where participants will be given the opportunity to submit and vote on questions using a Q&A platform during and in advance of the livestream. One of the organizers will facilitate as a moderator for each live session.

For our virtual poster sessions, we plan to use a tool that enables audience participation such as [Gather.Town](https://gather.town/). We will allow authors to choose between one or more of three sessions held several hours apart, allowing a choice based on the most suitable time in their local time zone. 
<!--Although they will not be required to, we will also encourage them to present their poster in multiple sessions in order to maximize interaction between attendees across many timezones.-->

Finally, we will use a dedicated channel on a chat service throughout the event to provide a means of interaction between workshop participants. A schedule will be set up to include three poster sessions throughout the day to ensure that virtual attendees in all timezones will be able to participate in at least one.

More detailed instructions will be given closer to the workshop date.

### Invited Speakers

<!-- Submit challenge questions for the speakers [here](https://forms.gle/DGEev5erxAmoi6eEA).  -->

- [Timothy Hospedales](http://homepages.inf.ed.ac.uk/thospeda/index.html) (University of Edinburgh)
  <!--  **Title**  -->
- [Frank Hutter](http://http://ml.informatik.uni-freiburg.de/~hutter/) (University of Freiburg)
  <!--   **Title**  -->
- [Louis Kirsch](http://louiskirsch.com/) (IDSIA)
  <!--  **Title**  -->
- [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li) (Stanford University)
  <!--  **Title**  -->
- [Kate Rakelly](http://people.eecs.berkeley.edu/~rakelly/) (UC Berkeley)
  <!--  **Title**  -->
- [Luisa Zintgraf](https://luisazintgraf.com/) (University of Oxford)
  <!--  **Title**  -->

<!--
## Spotlights
### Morning Session
- [**Title**.](slides/metalearn2020-paper.pdf)
 *Authors*

### Afternoon Session
- [**Title**.](slides/metalearn2020-paper.pdf)
 *Authors*
-->

### Organizers

- [Roberto Calandra](https://www.robertocalandra.com/) (Facebook AI Research)
- [Jeff Clune](https://www.jeffclune.com/) (OpenAI)
- [Erin Grant](https://eringrant.github.io/) (UC Berkeley)
- [Jonathan Schwarz](https://jonathan-schwarz.github.io/) (University College London, Deepmind)
- [Joaquin Vanschoren](http://www.win.tue.nl/~jvanscho/) (Eindhoven University of Technology)
- [Francesco Visin](https://www.linkedin.com/in/francescovisin/?originalSubdomain=it) (DeepMind)
- [Jane Wang](http://www.janexwang.com) (DeepMind)

### Important Dates

- Submission deadline: [4 October 2020, 11:59 PM AoE](https://www.timeanddate.com/time/zones/aoe) - Extended!
- Notification: [30 October 2020, by 06:00 PM PDT](https://neurips.cc/Conferences/2020/Dates)
- Video recording to SlidesLive: [14 November 2020, 11:59 PM PST](https://www.timeanddate.com/time/zones/pst)
- Camera-ready submission (paper + poster) to CMT: [27 November 2020, 11:59 PM AoE](https://www.timeanddate.com/time/zones/aoe)
- Workshop: 11 December 2020

## Program

### Schedule

The workshop schedule is aligned with 11 AM to 8 PM [UTC](https://www.timeanddate.com/worldclock/timezone/utc); please see [this converter](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Workshop+on+Meta-Learning+%28MetaLearn+2020%29&iso=20201211T11) for conversion to your specific time zone.

| Beijing (CST) | Berlin (CET) | London (UTC) | New York (EST) | Vancouver (PST) |
| ----: | ----: | ----: | ----: | ----: | :------------------------------------- |
| 19:00 | 12:00 | 11:00 | 06:00 | 03:00 | Introduction and opening remarks 
| 19:10 | 12:10 | 11:10 | 06:10 | 03:10 | **Invited talk 1**: [Frank Hutter](http://http://ml.informatik.uni-freiburg.de/~hutter/), "Meta-learning neural architectures, initial weights, hyperparameters, and algorithm components". [Q&A](https://app.sli.do/event/qz6tvw2l)
| 19:40 | 12:40 | 11:40 | 06:40 | 03:40 | **Contributed talk 1**: Steinar Laenen, "On episodes, Prototypical Networks, and few-shot learning"
| 20:00 | 13:00 | 12:00 | 07:00 | 04:00 | Poster session 1
| 21:00 | 14:00 | 13:00 | 08:00 | 05:00 | **Invited talk 2**: [Luisa Zintgraf](https://luisazintgraf.com/), "Exploration in meta-reinforcement learning". [Q&A](https://app.sli.do/event/3izdak3o)
| 21:30 | 14:30 | 13:30 | 08:30 | 05:30 | **Invited talk 3**: [Timothy Hospedales](http://homepages.inf.ed.ac.uk/thospeda/index.html), "Meta-learning: Representations and objectives". [Q&A](https://app.sli.do/event/58boxk0i)
| 22:00 | 15:00 | 14:00 | 09:00 | 06:00 | _Break_
| 23:00 | 16:00 | 15:00 | 10:00 | 07:00 | Poster session 2
| 24:00 | 17:00 | 16:00 | 11:00 | 08:00 | **Invited talk 4**: [Louis Kirsch](http://louiskirsch.com/), "General meta-learning". [Q&A](https://app.sli.do/event/n8vmqbsj)
| 24:30 | 17:30 | 16:30 | 11:30 | 08:30 | **Invited talk 5**: [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li), "Creating diverse tasks to catalyze robot learning". [Q&A](https://app.sli.do/event/birytqhi)
| 01:00 | 18:00 | 17:00 | 12:00 | 09:00 | Poster session 3
| 02:00 | 19:00 | 18:00 | 13:00 |	10:00 | **Invited talk 6**: [Kate Rakelly](http://people.eecs.berkeley.edu/~rakelly/), "An inference perspective on meta-reinforcement learning". [Q&A](https://app.sli.do/event/eunlzjq0)
| 02:30 | 19:30 | 18:30 | 13:30 |	10:30 | **Contributed talk 2**: Niru Maheswaranathan, "Reverse-engineering learned optimizers reveals known and novel mechanisms"
| 02:45 | 19:45 | 18:45 | 13:45 |	10:45 | **Contributed talk 3**: Louis Tiao, "Bayesian optimization by density ratio estimation"
| 03:00 | 20:00 | 19:00 | 14:00 | 11:00 | Panel Discussion (Ask questions [here](https://app.sli.do/event/uihcwqn4))
| 04:00 | 21:00 | 20:00 | 15:00 | 12:00 | _End_


## Accepted Papers

- **Reverse engineering learned optimizers reveals known and novel mechanisms**.
*Niru Maheswaranathan, David Sussillo, Luke Metz, Ruoxi Sun, Jascha Sohl-Dickstein*. Poster Sessions: 3

- **On Episodes, Prototypical Networks, and Few-Shot Learning**.
*Steinar Laenen, Luca Bertinetto*. Poster Sessions: 1

- **Bayesian Optimization by Density Ratio Estimation**.
*Louis C Tiao, Aaron Klein, Cedric Archambeau, Edwin V. Bonilla, Matthias Seeger, Fabio Ramos*. Poster Sessions: 1, 2, 3

- **Contextual HyperNetworks for Novel Feature Adaptation**.
*Angus Lamb, Evgeny Saveliev, Yingzhen Li, Sebastian Tschiatschek, Camilla Longden, Simon Woodhead, Jose Miguel Hernandez-Lobato, Richard E. Turner, Pashmina Cameron, Cheng Zhang*. Poster Sessions: 1, 2

- **Learning to Generate Noise for Multi-Attack Robustness**.
*Divyam Madaan, Jinwoo Shin, Sung Ju Hwang*. Poster Sessions: 1, 2

- **Tailoring: encoding inductive biases by optimizing unsupervised objectives at prediction time**.
*Ferran Alet, Kenji Kawaguchi, Maria Bauza Villalonga, Nurullah Giray Kuru, Tomas Lozano-Perez, Leslie Kaelbling*. Poster Sessions: 2, 3

- **Model-Agnostic Graph Regularization for Few-Shot Learning**.
*Ethan Z Shen, Maria Brbic, Nicholas Monath, Jiaqi Zhai, Manzil Zaheer, Jure Leskovec*. Poster Sessions: 2

- **Learning Flexible Classifiers with Shot-CONditional Episodic Training**.
*Eleni Triantafillou, Vincent Dumoulin, Hugo Larochelle, Richard Zemel*. Poster Sessions: 2, 3

- **Prior-guided Bayesian Optimization**.
*Artur L.F. Souza, Luigi Nardi, Leonardo B. Oliveira, Kunle Olukotun, Marius Lindauer, Frank Hutter*. Poster Sessions: 1, 2, 3

- **Is Support Set Diversity Necessary for Meta-Learning?**.
*Oscar Li, Amrith Setlur, Virginia Smith*. Poster Sessions: 2, 3

- **How Important is the Train-Validation Split in Meta-Learning?**.
*Yu Bai, Minshuo Chen, Pan Zhou, Tuo Zhao, Jason Lee, Sham Kakade, Huan Wang, Caiming Xiong*. Poster Sessions: 3

- **Adaptive Risk Minimization: A Meta-Learning Approach for Tackling Group Shift**.
*Marvin Zhang, Henrik - Marklund, Nikita Dhawan, Abhishek Gupta, Sergey Levine, Chelsea Finn*. Poster Sessions: 3

- **Model-Based Meta-Reinforcement Learning for Flight with Suspended Payloads**.
*Suneel Belkhale*. Poster Sessions: 2, 3

- **Task Similarity Aware Meta Learning: Theory-inspired Improvement on MAML**.
*Pan Zhou, Yingtian Zou, Xiao-Tong Yuan, Jiashi Feng, Caiming Xiong, Steven Hoi* Poster Sessions: 1

- **HyperVAE: Variational Hyper-Encoding Network**.
*Phuoc Nguyen, Truyen Tran, Sunil Gupta, Santu Rana, Svetha Venkatesh, Hieu-Chi Dam* Poster Sessions: 1

- **Synthetic Petri Dish: A Novel Surrogate Model for Rapid Architecture Search**.
*Aditya Rawal, Joel Lehman, Felipe Petroski Such, Jeff Clune, Kenneth O Stanley*. Poster Sessions: 1, 2, 3

- **Meta-Learning Initializations for Image Segmentation**.
*Sean M Hendryx, Andrew Leach, Paul Hein, Clayton Morrison*. Poster Sessions: 3

- **Data Augmentation for Meta-Learning**.
*Renkun Ni, Micah Goldblum, Amr Sharaf, Kezhi Kong, Tom Goldstein*. Poster Sessions: 2

- **NAS-Bench-301 and the Case for Surrogate Benchmarks for Neural Architecture Search**.
*Julien Siems, Lucas Zimmer, Arber Zela, Jovita Lukasik, Margret Keuper, Frank Hutter*. Poster Sessions: 1

- **Prototypical Region Proposal Networks for Few-shot Localization and Classification**.
*Elliott Skomski, Aaron R Tuor, Andrew Avila, Lauren Phillips, Zachary New, Henry Kvinge, Courtney Corley, Nathan Hodas*. Poster Sessions: 3

- **Continual Model-Based Reinforcement Learning with Hypernetworks**.
*Yizhou Huang, Kevin Xie, Homanga Bharadhwaj, Florian Shkurti*. Poster Sessions: 2, 3

- **MAster of PuPpets: Model-Agnostic Meta-Learning via Pre-trained Parameters for Natural Language Generation**.
*Chien-Fu Lin, Hung-yi Lee*. Poster Sessions: 1, 2

- **Few-Shot Unsupervised Continual Learning through Meta-Examples**.
*Alessia Bertugli, Stefano Vincenzi, SIMONE CALDERARA, Andrea Passerini*. Poster Sessions: 1, 2, 3

- **Similarity of classification tasks**.
*Cuong Cao Nguyen, Thanh-Toan Do, Gustavo Carneiro*. Poster Sessions: 1

- **MobileDets: Searching for Object Detection Architecture for Mobile Accelerators**.
*Yunyang Xiong, Hanxiao Liu, Suyog Gupta, Berkin Akin, Gabriel Bender, Yongzhe Wang, Pieter-Jan Kindermans, Mingxing Tan, Prof Singh, Bo Chen*. Poster Sessions: 1

- **Towards Meta-Algorithm Selection**.
*Alexander Tornede, Marcel Wever, Eyke Hüllermeier*. Poster Sessions: 1

- **Meta-Learning via Hypernetworks**.
*Dominic Zhao, Johannes von Oswald, Seijin Kobayashi, João Sacramento, Benjamin F. Grewe*. Poster Sessions: 1, 2, 3

- **Open-Set Incremental Learning via Bayesian Prototypical Embeddings**.
*John Willes, James Harrison, Chelsea Finn, Marco Pavone, Steven L Waslander*. Poster Sessions: 2

- **Multi-Objective Multi-Fidelity Hyperparameter Optimization with Application to Fairness**.
*Robin Schmucker, Michele Donini, Valerio Perrone, Muhammad Bilal Zafar, Cedric Archambeau*. Poster Sessions: 3

- **Meta-Learning of Compositional Task Distributions in Humans and Machines**.
*Sreejan Kumar, Ishita Dasgupta, Jonathan Cohen, Nathaniel Daw, Tom Griffiths*. Poster Sessions: 3

- **Putting Theory to Work: From Learning Bounds to Meta-Learning Algorithms**.
*Quentin Bouniot, Ievgen Redko, Romaric Audigier, Angélique Loesch, Amaury Habrard*. Poster Sessions: 1, 2, 3

- **A Meta-Learning Approach for Graph Representation Learning in Multi-Task Settings**.
*Davide Buffelli, Fabio Vandin*. Poster Sessions: 1, 3

- **Few-shot Sequence Learning with Transformers**.
*Lajanugen Logeswaran, Ann Lee, Myle Ott, Honglak Lee, Marc'Aurelio Ranzato, Arthur Szlam*. Poster Sessions: 2

- **Learning not to learn: Nature versus nurture in silico**. Poster Sessions: 2, 3
*Robert T Lange, Henning Sprekeler*

- **Meta-Learning Backpropagation And Improving It**.
*Louis Kirsch, Jürgen Schmidhuber*. Poster Sessions: 1, 2, 3

- **Continual learning with direction-constrained optimization**.
*Yunfei Teng, Anna Choromanska, Murray Campbell*. Poster Sessions: 2

- **Cross-Modal Generalization: Learning in Low Resource Modalities via Meta-Alignment**.
*Paul Pu Liang, Peter Wu, Liu Ziyin, Louis-Philippe Morency, Ruslan Salakhutdinov*. Poster Sessions: 3

- **MPLP: Learning a Message Passing Learning Protocol**.
*Ettore Randazzo, Eyvind Niklasson, Alexander Mordvintsev*. Poster Sessions: 1

- **Pareto-efficient Acquisition Functions for Cost-Aware Bayesian Optimization**.
*Gauthier Guinet, Valerio Perrone, Cedric Archambeau*. Poster Sessions: 2, 3

- **Hyperparameter Transfer Across Developer Adjustments**.
*Danny Stoll, Jörg K.H. Franke, Diane Wagner, Simon Selg, Frank Hutter*. Poster Sessions: 2

- **Decoupling Exploration and Exploitation in Meta-Reinforcement Learning without Sacrifices**.
*Evan Liu, Aditi Raghunathan, Percy Liang, Chelsea Finn*. Poster Sessions: 3

- **Meta-Learning Bayesian Neural Network Priors Based on PAC-Bayesian Theory**.
*Jonas Rothfuss, Martin Josifoski, Andreas Krause*. Poster Sessions: 2, 3

- **Task Meta-Transfer from Limited Parallel Labels**.
*Yiren Jian, Karim Ahmed, Lorenzo Torresani*. Poster Sessions: 3

- **Uniform Priors for Meta-Learning**.
*Samarth Sinha, Karsten Roth, Anirudh Goyal, Marzyeh Ghassemi, Hugo Larochelle, Animesh Garg*. Poster Sessions: 1, 3

- **Defining Benchmarks for Continual Few-Shot Learning**.
*Antreas Antoniou, Massimiliano Patacchiola, Mateusz Ochal, Amos Storkey*. Poster Sessions: 2, 3

- **Flexible Dataset Distillation: Learn Labels Instead of Images**.
*Ondrej Bohdal, Yongxin Yang, Timothy Hospedales*. Poster Sessions: 1, 3

- **Measuring few-shot extrapolation with program induction**.
*Ferran Alet, Javier Lopez-Contreras, Joshua Tenenbaum, Tomas Lozano-Perez, Leslie Kaelbling*. Poster Sessions: 2, 3
 
 
## Submission Instructions

### Formatting

The submission window for this workshop is now closed. Decision notifications were sent out October 30th, 2020. Thank you to all who submitted!

We have provided a modified `.sty` file [here](neurips_2020.sty) that appropriately lists the name of the workshop when `\neuripsfinal` is enabled. Please use this style files in conjunction with corresponding LaTeX `.tex` template from the [NeurIPS website](https://neurips.cc/Conferences/2020/PaperInformation/StyleFiles) to submit a final camera-ready copy. The camera-ready can be up to <b>8 pages</b>.

Accepted papers and supplementary material will be made available on the workshop website. However, these do not constitute archival publications and no formal workshop proceedings will be made available, meaning contributors are free to publish their work in archival journals or conferences.

### FAQ

1. Can supplementary material be added beyond the 6-page limit for submissions, and are there any restrictions on it?

   Yes, you may include additional supplementary material, but you should ensure that the main paper is self-contained, since looking at supplementary material is at the discretion of the reviewers. The supplementary material should also follow the same NeurIPS format as the paper and be limited to a reasonable amount (max 10 pages in addition to the main submission).

1. Can a submission to this workshop be submitted to another NeurIPS workshop in parallel?

   We discourage this, as it leads to more work for reviewers across multiple workshops. Our suggestion is to pick one workshop to submit to.

1. Can a paper be submitted to the workshop that has already appeared at a previous conference with published proceedings?

   We won't be accepting such submissions unless they have been adapted to contain significantly new results (where novelty is one of the qualities reviewers will be asked to evaluate).

1. Can a paper be submitted to the workshop that is currently under review or will be under review at a conference during the review phase?

   MetaLearn 2020 submissions are 6 pages, i.e., much shorter than standard conference submissions. But from our side, it is perfectly fine to submit a condensed version of a parallel conference submission if it also fine for the conference in question. Our workshop does not have archival proceedings, and therefore parallel submissions of extended versions to other conferences are acceptable.
   
1. Is there a page limit constraint for the camera-ready paper?

   The page limit for the camera-ready will be 8 pages for all accepted contributions so that authors have space to address comments from the programme committee.


## Review Process

### Reviewing Mentorship

This year we are trialing a new reviewer mentorship scheme, which we hope will improve the future pool of expert reviewers in machine learning. Junior reviewers will be able to provide reviews in a guided setting and will be linked with senior reviewers who will give them feedback and advice throughout the reviewing process. It is our hope that this will be a useful learning experience for reviewers and improve the overall quality of reviewing. 

In order for this to be feasible, all submissions will be asked to provide **two** contacts who have agreed to review for the workshop. These volunteers can, of course, be authors of the submission, or people who have agreed to review on behalf of the authors. Depending on their experience reviewing, these contacts will be assigned to either a junior or senior reviewer role. All submissions will be ensured at least one senior reviewer, since we will still be directly recruiting for reviewers as in previous years.

If you would like to sign up, or recommend somebody, to be either a junior or senior reviewer, please fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSebBTVLq-IRwxsP857MmmTwtTBwyRamghnNLp71I9vr1q6-Jg/viewform?usp=sf_link) by 2 October 2020.
**The form is now closed; reviews are due on 23 October 2020.** For more detailed information on the review process, please see [this document](https://docs.google.com/document/d/1vRdY8e2ttALw_kzxviejrhkVkiJlJ7YiS3yGm9jykB0/edit?usp=sharing).

<!--
## Accepted Papers ##

- [**Title**.](papers/paper.pdf)
 *Authors*
-->

## Program Committee

We thank the program committee for shaping the excellent technical program; they are (in alphabetical order):

*Badr AlKhamissi, Alessia Bertugli, Homanga Bharadhwaj, Parminder Bhatia, Surya Bhupatiraju, Jasmin Bogatinovski, Ondrej Bohdal, Quentin Bouniot, Pavel Brazdil, Andrew Brock, Davide Buffelli, Andre Carvalho, Michael Chang, Marco Ciccone, Ignasi Clavera, Ishita Dasgupta, Nikita Dhawan, Rachit Dubey, Praneet Dutta, Thomas Elsken, Dumitru Erhan, Sergio Escalera, Ben Eysenbach, Matthias Feurer, Alexandre Galashov, Rafael Gomes Mantovani, Gauthier Guinet, Abhishek Gupta, Mehrtash Harandi, Leonard Hasenclever, Sean Hendryx, Daniel Hernandez-Lobato, Tin Ho, Kyle Hsu, Yizhou Huang, Frank Hutter, Maximilian Igl, Yiren Jian, Xiang Jiang, Martin Josifoski, Udayan Khurana, Louis Kirsch, Aaron Klein, Lars Kotthoff, Aviral Kumar, Sreejan Kumar, Nicholas Kuo, Angus Lamb, Robert Lange, Hung-yi Lee, Benjamin Letham, Ang Li, Rui Li, Chien-Fu Lin, Marius Lindauer, Evan Liu, Javier Lopez-Contreras, Ana Lorena, Divyam Madaan, Parsa Mahmoudieh, Mikhail Mekhedkin-Meskhi, Piotr Mirowski, Eric Mitchell, Igor Mordatch, Ashvin Nair, Cuong Nguyen, Renkun Ni, Eyvind Niklasson, Mateusz Ochal, Randal Olson, Razvan Pascanu, Massimiliano Patacchiola, Valerio Perrone, Valerio Perrone, Marc Pickett, Vitchyr Pong, Paul Pu Liang, Damir Pulatov, Aniruddh Raghu, Kate Rakelly, Ettore Randazzo, Dushyant Rao, Hootan Rashtian, Ievgen Redko, Mengye Ren, Stephen Roberts, Karsten Roth, Jonas Rothfuss, Andrei Rusu, Horst Samulowitz, Evgeny Saveliev, Alan Savushkin, Robin Schmucker, Brandon Schoenfeld, Ethan Shen, Julien Siems, Devendra Singh Chaplot, Samarth Sinha, Elliott Skomski, Jake Snell, Sungryull Sohn, Artur Souza, Aravind Srinivas, Nishan Srishankar, Bradly Stadie, Valdimar Steinar Ericsson Laenen, Mihai Suteu, Kevin Swersky, Jakub Sygnowski, Yunfei Teng, Louis Tiao, Alexander Tornede, Eleni Triantafillou, Johannes von Oswald, Jianan Wang, Haozhu Wang, Orion Weller, John Willes, Jiajun Wu, Kelvin Xu, Sharare Zehtabian, Marvin Zhang, Lucas Zimmer, Luisa Zintgraf, Liu Ziyin, Stefano Vincenzi*

## Past Workshops

[Workshop on Meta-Learning (MetaLearn 2017) @ NeurIPS 2017](http://metalearning.ml/2017/)

[Workshop on Meta-Learning (MetaLearn 2018) @ NeurIPS 2018](http://metalearning.ml/2018/)

[Workshop on Meta-Learning (MetaLearn 2019) @ NeurIPS 2019](http://metalearning.ml/2019/)

<!--
## Sponsors

We are grateful for the support of our sponsors, which enabled us to offer XX to several participants.
-->

## Contacts

For any further questions, you can contact us at <metalearn2020@googlegroups.com>.
