# Awesome Sum-Product Networks

**awesome-spn** is a curated and structured list of resources about
*Sum-Product Networks* (SPNs), tractable deep density estimators.

This includes (even not formally published) research papers sorted by year and topics as well as
links to tutorials and code and other related Tractable Probabilistic
Models (TPMs). It is inspired by the
[SPN page](http://spn.cs.washington.edu/) at the Washington University.

## Licence and Contributing
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

**awesome-spn** is released under Public Domain. Feel free to complete
and/or correct any of these
lists. [Pull requests](https://github.com/arranger1044/awesome-spn/pulls)
are very welcome!

## Table of Contents

   * [Papers](#papers)
      * [Year](#year)
        * [2016](#2016)
        * [2015](#2015)
        * [2014](#2014)
        * [2013](#2013)
        * [2012](#2012)
        * [2011](#2011)
      * [Topic](#topics)
        * [Weight Learning](#weight-learning)
        * [Structure Learning](#structure-learning)
        * [Modeling](#modeling)
        * [Applications](#applications)
        * [Theory](#theory)
   * [Related Works](#related-works) 
      * [Arithmetic Circuits](#arithmetic-circuits)
      * [Other TPMs](#other-tpms)
   * [Resources](#resources)
      * [Dataset](#dataset)
      * [Code](#code)
      * [Talks and Tutorials](#talks-and-tutorials)
      
   * [References](#resources)
        

## Papers

Sorted by [year](#year) or [topics](#topics) 

### Year

#### 2016
   - [[Vergari2016](#vergari2016)] [**Visualizing and Understanding Sum-Product Networks**](https://arxiv.org/abs/1608.08266) *arXiv* `representation learning`
   - [[Melibari2016c](#melibari2016c)] [**Dynamic Sum-Product Networks for Tractable Inference on Sequence Data**](http://arxiv.org/abs/1511.04412)
   *PGM2016* [`modeling`](#modeling) [`structure-learning`](#structure-learning)
   - [[Jaini2016](#jaini2016)]
     [**Online Algorithms for Sum-Product Networks with Continuous Variables**](http://jmlr.org/proceedings/papers/v52/jaini16.pdf)
     *PGM2016* [`weight-learning`](#weight-learning)
   - [[Desana2016](#desana2016)]
     [**Expectation Maximization for Sum-Product Networks as Exponential Family Mixture Models**](http://arxiv.org/abs/1604.07243)
     *arXiv* [`weight-learning`](#weight-learning)
   - [[Peharz2016](#peharz2016)]
     [**On the Latent Variable Interpretation in Sum-Product Networks**](http://arxiv.org/abs/1601.06180)
     *arXiv* [`theory`](#theory)	 [`weight-learning`](#weight-learning)
   - [[Zhao2016b](#zhao2016b)]
       [**A unified approach for learning the parameters of sum-product networks**](http://arxiv.org/abs/1601.00318)    *NIPS 2016* [`weight-learning`](#weight-learning)
   - [[Yuan2016](#yuan2016)]
     [**Modeling Spatial Layout for Scene Image Understanding Via a Novel Multiscale Sum-Product Network**](http://www.sciencedirect.com/science/article/pii/S0957417416303591)
     *Expert Systems and Applications* [`applications`](#applications)
   - [[Rahman2016](#rahman2016)]
     [**Merging Strategies for Sum-Product Networks: From Trees to Graphs**](http://www.hlt.utdallas.edu/~vgogate/papers/uai16.pdf)
     *UAI2016* [`structure-learning`](#structure-learning)
   - [[Friesen2016](#friesen2016)]
     [**The Sum-Product Theorem: A Foundation for Learning Tractable Models**](http://homes.cs.washington.edu/~pedrod/papers/mlc16.pdf)
     *ICML2016* [`theory`](#theory)
   - [[Zhao2016a](#zhao2016a)]
     [**Collapsed Variational Inference for Sum-Product Networks**](http://jmlr.org/proceedings/papers/v48/zhaoa16.pdf)
     *ICML2016*	 [`weight-learning`](#weight-learning)
   - [[Rashwan2016](#rashwan2016)]
     [**Online and Distributed Bayesian Moment Matching for Parameter Learning in Sum-Product Networks**](http://www.jmlr.org/proceedings/papers/v51/rashwan16.pdf)
     *AISTATS2016* [`weight-learning`](#weight-learning)
   - [[Krakovna2016](#krakovna2016)]
     [**A Minimalistic Approach to Sum-Product Network Learning for Real Applications**](http://arxiv.org/abs/1602.04259)
     *ICLR2016* [`structure-learning`](#structure-learning)
   - [[Melibari2016b](#melibari2016b)]
     [**Sum-Product-Max Networks for Tractable Decision Making**](http://trust.sce.ntu.edu.sg/aamas16/pdfs/p1419.pdf)
     *AAMAS2016* [`modeling`](#modeling)
   - [[Melibari2016a](#melibari2016a)] [**Decision Sum-Product-Max Networks**](https://cs.uwaterloo.ca/~mmelibar/publications/melibari-aaai2016.pdf)
     *AAAI2016*	 [`modeling`](#modeling)	  [`structure-learning`](#structure-learning)
   - [[Nath2016](#nath2016)]
     [**Learning Tractable Probabilistic Models for Fault Localization**](http://homes.cs.washington.edu/~pedrod/papers/aaai16.pdf)
     *AAAI2016* [`applications`](#applications)


#### 2015
   - [[Peharz2015b](#peharz2015b)]
     [**Foundations of Sum-Product Networks for Probabilistic Modeling**](https://www.researchgate.net/profile/Robert_Peharz/publication/273000973_Foundations_of_Sum-Product_Networks_for_Probabilistic_Modeling/links/54f49ff00cf2f28c1362088b.pdf)
     *Thesis* [`theory`](#theory)
   - [[Wang2015](#wang2015)]
     [**Hierarchical Spatial Sum-Product Networks for action recognition in Still Images**](http://arxiv.org/abs/1511.05292)
     *arXiv* [`applications`](#applications)	 
   - [[Amer2015](#amer2015)]
     [**Sum Product Networks for Activity Recognition**](http://web.engr.oregonstate.edu/~sinisa/research/publications/PAMI_SPN.pdf)
     *TPAMI2015* [`applications`](#applications)
   - [[Li2015](#li2015)]
     [**Combining Sum-Product Network and Noisy-OrModel for Ontology Matching**](http://disi.unitn.it/~pavel/om2015/papers/om2015_TSpaper1.pdf)
     *OM2015* [`applications`](#applications)
   - [[Vergari2015](#vergari2015)]
     [**Simplifying, Regularizing and Strengthening Sum-Product Network Structure Learning**](http://www.di.uniba.it/~vergari/papers/Simplifying,%20Regularizing%20and%20Strengthening%20Sum-Product%20Network%20Structure%20Learning.pdf)
     *ECML-PKDD2015*  [`structure-learning`](#structure-learning)
   - [[Dennis2015](#dennis2015)]
     [**Greedy Structure Search for Sum-Product Networks**](http://www.ijcai.org/Proceedings/15/Papers/136.pdf) *IJCAI2015*	  [`structure-learning`](#structure-learning)
   - [[Friesen2015](#friesen2015)]
     [**Recursive Decomposition for Nonconvex Optimization**](https://www.cs.washington.edu/node/11282)
     *IJCAI2015*	 [`theory`](#theory)
   - [[Niepert2015](#niepert2015)]
     [**Learning and Inference in Tractable Probabilistic Knowledge Bases**](http://homes.cs.washington.edu/~pedrod/papers/uai15.pdf)
     *UAI2015* [`modeling`](#modeling)
   - [[Adel2015](#adel2015)]
     [**Learning the Structure of Sum-Product Networks via an SVD-based Algorithm**](http://auai.org/uai2015/proceedings/papers/83.pdf)
     *UAI2015*  [`structure-learning`](#structure-learning)
   - [[Zhao2015](#zhao2015)]
     [**On the Relationship between Sum-Product Networks and Bayesian Networks**](http://jmlr.org/proceedings/papers/v37/zhaoc15.pdf)
     *ICML2015* [`theory`](#theory)
   - [[Peharz2015a](#peharz2015a)]
     [**On Theoretical Properties of Sum-Product Networks**](http://www.jmlr.org/proceedings/papers/v38/peharz15.pdf)
     *AISTATS2015* [`theory`](#theory)
   - [[Nath2015](#nath2015)]
     [**Learning Relational Sum-Product Networks**](http://homes.cs.washington.edu/~pedrod/papers/aaai15.pdf)
     *AAAI2015* [`modeling`](#modeling)

#### 2014
   - [[Martens2014](#martens2014)]
     [**On the Expressive Efficiency of Sum Product Networks**](http://arxiv.org/abs/1411.7717)
     *arXiv* [`theory`](#theory)
   - [[Cheng2014](#cheng2014)]
     [**Language Modeling with Sum-Product Networks**](http://spn.cs.washington.edu/papers/is14.pdf)
     *INTERSPEECH2014* [`modeling`](#modeling) [`applications`](#applications)
   - [[Peharz2014a](#peharz2014a)]
     [**Modeling Speech with Sum-Product Networks: Application to Bandwidth Extension**](http://spn.cs.washington.edu/papers/icassp14.pdf)
     *ICASSP2014* [`applications`](#applications)
   - [[Lee2014](#lee2014)]
     [Non-Parametric Bayesian Sum-Product Networks](http://spn.cs.washington.edu/papers/ltpm2014_paper_6.pdf)
     *LTPM2014*  [`structure-learning`](#structure-learning)
   - [[Ratajczak2014](#ratajczak2014)]
     [**Sum-Product Networks for Structured Prediction: Context-Specific Deep Conditional Random Fields**](https://www.spsc.tugraz.at/biblio/ratajczak20143046)
     *LTPM2014* [`applications`](#applications)
   - [[Nath2014](#nath2014)]
     [**Learning Tractable Statistical Relational Models**](http://spn.cs.washington.edu/papers/ltpm2014_paper_4.pdf)
     *LTPM2014* [`modeling`](#modeling)
   - [[Peharz2014b](#peharz2014b)]
     [**Learning Selective Sum-Product Networks**](http://spn.cs.washington.edu/papers/ltpm2014_paper_9.pdf)
     *LTPM2014* [`weight-learning`](#weight-learning) [`modeling`](#modeling)
   - [[Rooshenas2014](#rooshenas2014)]
     [**Learning Sum-Product Networks with Direct and Indirect Interactions**](http://ix.cs.uoregon.edu/~lowd/icml14rooshenas.pdf)
     *ICML2014*  [`structure-learning`](#structure-learning)


#### 2013

   - [[Lee2013](#lee2013)]
     [**Online Incremental Structure Learning of Sum-Product Networks**](https://bi.snu.ac.kr/Publications/Conferences/International/ICONIP2013_SWLee.pdf)
     *ICONIP2013*	  [`structure-learning`](#structure-learning)
   - [[Peharz2013](#peharz2013)]
     [**Greedy Part-Wise Learning of Sum-Product Networks**](https://www.spsc.tugraz.at/sites/default/files/MergeSPN.pdf) 
     *ECML-PKDD2013*  [`structure-learning`](#structure-learning)
   - [[Gens2013](#gens2013)]
     [**Learning the Structure of Sum-Product Networks**](http://jmlr.org/proceedings/papers/v28/gens13.pdf)
     *ICML2013*  [`structure-learning`](#structure-learning)



#### 2012
   - [[Gens2012](#gens2012)]
     [**Discriminative Learning of Sum-Product Networks**](http://spn.cs.washington.edu/papers/dspn.pdf)
     *NIPS2012* [`weight-learning`](#weight-learning)
   - [[Dennis2012](#dennis2012)]
     [**Learning the Architecture of Sum-Product Networks Using Clustering on Variables**](http://papers.nips.cc/paper/4544-learning-the-architecture-of-sum-product-networks-using-clustering-on-variables.pdf)
     *NIPS2012*  [`structure-learning`](#structure-learning)
   - [[Stuhlmueller2012](#stuhlmueller2012)]
     [**Dynamic Programming Algorithm for Inference in Recursive Probabilistic Programs**](http://arxiv.org/abs/1206.3555)
     *StaRAI2012* [`modeling`](#modeling)
   - [[Amer2012](#amer2012)]
     [**Sum-product Networks for Modeling Activities with Stochastic Structure**](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr12_SPN.pdf)
     *CVPR2012* [`applications`](#applications)


#### 2011
    

   - [[Delalleau2011](#dellaleau2011)]
     [**Shallow vs. Deep Sum-Product Networks**](http://papers.nips.cc/paper/4350-shallow-vs-deep-sum-product-networks.pdf)
     *NIPS2011* [`theory`](#theory)
   - [[Poon2011](#poon2011)]
     [**Sum-Product Networks: A New Deep Architecture**](http://spn.cs.washington.edu/papers/spn.pdf)
     *UAI2011* [`modeling`](#modeling) [`weight-learning`](#weight-learning)

    



### Topics

<div id="weight-learning"></div>
#### Weight Learning
   - [[Jaini2016](#jaini2016)]
     [**Online Algorithms for Sum-Product Networks with Continuous Variables**](http://jmlr.org/proceedings/papers/v52/jaini16.pdf) `OBMM`
   - [[Desana2016](#desana2016)]
     [**Expectation Maximization for Sum-Product Networks as Exponential Family Mixture Models**](http://arxiv.org/abs/1604.07243) `EM`
   - [[Zhao2016b](#zhao2016b)]
       [**A unified approach for learning the parameters of sum-product networks**](http://arxiv.org/abs/1601.00318)
   - [[Zhao2016a](#zhao2016a)]
     [**Collapsed Variational Inference for Sum-Product Networks**](http://jmlr.org/proceedings/papers/v48/zhaoa16.pdf) `non-parametrics`
   - [[Rashwan2016](#rashwan2016)]
  [**Online and Distributed Bayesian Moment Matching for Parameter Learning in Sum-Product Networks**](http://www.jmlr.org/proceedings/papers/v51/rashwan16.pdf)
  `OBMM` `EGD`
   - [[Peharz2014b](#peharz2014b)]
     [**Learning Selective Sum-Product Networks**](http://spn.cs.washington.edu/papers/ltpm2014_paper_9.pdf)
     `ML` `SSPN`
   - [[Poon2011](#poon2011)]
   [**Sum-Product Networks: A New Deep Architecture**](http://spn.cs.washington.edu/papers/spn.pdf) `EM` `Hard EM` `SGD`
   - [[Gens2012](#gens2012)]
   [**Discriminative Learning of Sum-Product Networks**](http://spn.cs.washington.edu/papers/dspn.pdf)
   `disc Hard EM` `disc Hard SGD`

<div id="structure-learning"></div>
#### Structure Learning
   - [[Melibari2016c](#melibari2016c)][**Dynamic Sum-Product Networks for Tractable Inference on Sequence Data**](http://arxiv.org/abs/1511.04412) `hill-climbing`
   - [[Rahman2016](#rahman2016)]
     [**Merging Strategies for Sum-Product Networks: From Trees to Graphs**](http://www.hlt.utdallas.edu/~vgogate/papers/uai16.pdf)
     `pruning` `dagSPN`
   - [[Vergari2015](#vergari2015)]
     [**Simplifying, Regularizing and Strengthening Sum-Product Network Structure Learning**](http://www.di.uniba.it/~vergari/papers/Simplifying,%20Regularizing%20and%20Strengthening%20Sum-Product%20Network%20Structure%20Learning.pdf)
     `LearnSPN-b` `LearnSPN-bt` `LearnSPN-btb`
   - [[Dennis2015](#dennis2015)]
     [**Greedy Structure Search for Sum-Product Networks**](http://www.ijcai.org/Proceedings/15/Papers/136.pdf) `dagSPN`
   - [[Adel2015](#adel2015)]
     [**Learning the Structure of Sum-Product Networks via an SVD-based Algorithm**](http://auai.org/uai2015/proceedings/papers/83.pdf)
     `SPN-SVD` `DSPN-SVD`
   - [[Nath2015](#nath2015)]
     [**Learning Relational Sum-Product Networks**](http://homes.cs.washington.edu/~pedrod/papers/aaai15.pdf) `relational`
   - [[Lee2014](#lee2014)]
     [Non-Parametric Bayesian Sum-Product Networks](http://spn.cs.washington.edu/papers/ltpm2014_paper_6.pdf) `non-parametrics`
   - [[Peharz2014b](#peharz2014b)] [**Learning Selective Sum-Product Networks**](http://spn.cs.washington.edu/papers/ltpm2014_paper_9.pdf) `SSPN`
   - [[Rooshenas2014](#rooshenas2014)] [**Learning Sum-Product Networks with Direct and Indirect Interactions**](http://ix.cs.uoregon.edu/~lowd/icml14rooshenas.pdf) `ID-SPN`
   - [[Lee2013](#lee2013)]
     [**Online Incremental Structure Learning of Sum-Product Networks**](https://bi.snu.ac.kr/Publications/Conferences/International/ICONIP2013_SWLee.pdf)
   - [[Peharz2013](#peharz2013)]
     [**Greedy Part-Wise Learning of Sum-Product Networks**](https://www.spsc.tugraz.at/sites/default/files/MergeSPN.pdf) `bottom-up`
   - [[Gens2013](#gens2013)]
  [**Learning the Structure of Sum-Product Networks**](http://jmlr.org/proceedings/papers/v28/gens13.pdf) `top-down` `LearnSPN`
   - [[Dennis2012](#dennis2012)]
     [**Learning the Architecture of Sum-Product Networks Using Clustering on Variables**](http://papers.nips.cc/paper/4544-learning-the-architecture-of-sum-product-networks-using-clustering-on-variables.pdf)
     `top-down``k-means`
	 
<div id="modeling"></div>	 
#### Modeling
   - [[Melibari2016c](#melibari2016c)][**Dynamic Sum-Product Networks for Tractable Inference on Sequence Data**](http://arxiv.org/abs/1511.04412) `dynamic-SPN`
   - [[Melibari2016b](#melibari2016b)]
     [**Sum-Product-Max Networks for Tractable Decision Making**](http://trust.sce.ntu.edu.sg/aamas16/pdfs/p1419.pdf) `decision-diagram`
   - [[Melibari2016a](#melibari2016a)]
     [**Decision Sum-Product-Max Networks**](https://cs.uwaterloo.ca/~mmelibar/publications/melibari-aaai2016.pdf) `decision-diagram`
   - [[Friesen2015](#friesen2015)]
     [**Recursive Decomposition for Nonconvex Optimization**](https://www.cs.washington.edu/node/11282) `opt`
   - [[Niepert2015](#niepert2015)]
     [**Learning and Inference in Tractable Probabilistic Knowledge Bases**](http://homes.cs.washington.edu/~pedrod/papers/uai15.pdf) `relational`
   - [[Nath2015](#nath2015)]
     [**Learning Relational Sum-Product Networks**](http://homes.cs.washington.edu/~pedrod/papers/aaai15.pdf) `relational`
   - [[Nath2014](#nath2014)]
     [**Learning Tractable Statistical Relational Models**](http://spn.cs.washington.edu/papers/ltpm2014_paper_4.pdf)
   `relational`
   - [[Peharz2014b](#peharz2014b)] [**Learning Selective Sum-Product Networks**](http://spn.cs.washington.edu/papers/ltpm2014_paper_9.pdf) `SSPN`
   - [[Stuhlmueller2012](#stuhlmueller2012)]
     [**Dynamic Programming Algorithm for Inference in Recursive Probabilistic Programs**](http://arxiv.org/abs/1206.3555)
     `FSPN`
   - [[Poon2011](#poon2011)]
   [**Sum-Product Networks: A New Deep Architecture**](http://spn.cs.washington.edu/papers/spn.pdf) `SPN`
	 
<div id="applications"></div>	 
#### Applications
  
   - [[Yuan2016](#yuan2016)]
     [**Modeling Spatial Layout for Scene Image Understanding Via a Novel Multiscale Sum-Product Network**](http://www.sciencedirect.com/science/article/pii/S0957417416303591)
     `cv` `segmentation`
   - [[Nath2016](#nath2016)]
     [**Learning Tractable Probabilistic Models for Fault Localization**](http://homes.cs.washington.edu/~pedrod/papers/aaai16.pdf)
   - [[Wang2015](#wang2015)]
     [**Hierarchical Spatial Sum-Product Networks for action recognition in Still Images**](http://arxiv.org/abs/1511.05292)      `cv` `activity-recognition`
   - [[Amer2015](#amer2015)]
     [**Sum Product Networks for Activity Recognition**](http://web.engr.oregonstate.edu/~sinisa/research/publications/PAMI_SPN.pdf)
     `cv` `activity-recognition`
   - [[Li2015](#li2015)] [**Combining Sum-Product Network and Noisy-OrModel for Ontology Matching**](http://disi.unitn.it/~pavel/om2015/papers/om2015_TSpaper1.pdf) `sem-web`
   - [[Cheng2014](#cheng2014)]
     [**Language Modeling with Sum-Product Networks**](http://spn.cs.washington.edu/papers/is14.pdf)
     `sequence`
   - [[Ratajczak2014](#ratajczak2014)]
     [**Sum-Product Networks for Structured Prediction: Context-Specific Deep Conditional Random Fields**](https://www.spsc.tugraz.at/biblio/ratajczak20143046)
     `speech`
   - [[Peharz2014a](#peharz2014a)]
     [**Modeling Speech with Sum-Product Networks: Application to Bandwidth Extension**](http://spn.cs.washington.edu/papers/icassp14.pdf) `speech`
   - [[Amer2012](#amer2012)]
     [**Sum-product Networks for Modeling Activities with Stochastic Structure**](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr12_SPN.pdf)
     `cv``activity-recognition`
	 
<div id="theory"></div>   
#### Theory
   - [[Peharz2016](#peharz2016)]
     [**On the Latent Variable Interpretation in Sum-Product Networks**](http://arxiv.org/abs/1601.06180) `EM`
   - [[Friesen2016](#friesen2016)]
     [**The Sum-Product Theorem: A Foundation for Learning Tractable Models**](http://homes.cs.washington.edu/~pedrod/papers/mlc16.pdf)
     `opt` `sum-prod-theorem`
   - [[Peharz2015b](#peharz2015b)]
     [**Foundations of Sum-Product Networks for Probabilistic Modeling**](https://www.researchgate.net/profile/Robert_Peharz/publication/273000973_Foundations_of_Sum-Product_Networks_for_Probabilistic_Modeling/links/54f49ff00cf2f28c1362088b.pdf)
   - [[Friesen2015](#friesen2015)]
     [**Recursive Decomposition for Nonconvex Optimization**](https://www.cs.washington.edu/node/11282)
     `opt` `sum-prod-theorem`
   - [[Zhao2015](#zhao2015)]
     [**On the Relationship between Sum-Product Networks and Bayesian Networks**](http://jmlr.org/proceedings/papers/v37/zhaoc15.pdf)
   - [[Peharz2015a](#peharz2015a)] [**On Theoretical Properties of Sum-Product Networks**](http://www.jmlr.org/proceedings/papers/v38/peharz15.pdf)
   - [[Martens2014](#martens2014)]
     [**On the Expressive Efficiency of Sum Product Networks**](http://arxiv.org/abs/1411.7717) `depth`
   - [[Delalleau2011](#dellaleau2011)]
     [**Shallow vs. Deep Sum-Product Networks**](http://papers.nips.cc/paper/4350-shallow-vs-deep-sum-product-networks.pdf)     `depth`
	 

## Related Works

### Arithmetic Circuits

   - [[Darwiche2003](#darwiche2003)]
     [**A Differential Approach to Inference in Bayesian Networks**](Advances
     in Neural Information Processing Systems 2011) *J. ACM 2003*
   - [[Lowd2013](#lowd2013)]
     [**Learning Markov Networks With Arithmetic Circuits**](http://ix.cs.uoregon.edu/~lowd/aistats13lowd.pdf)
     *AISTATS 2013*
   - [[Rooshenas2016](#rooshenas2016)]
     [**Discriminative Structure Learning of Arithmetic Circuits**](http://www.jmlr.org/proceedings/papers/v51/rooshenas16.pdf)
     *AISTATS 2016*

### Other TPMs

   - [[Livni2013](#livni2013)]
     [**A Provably Efficient Algorithm for Training Deep Networks**](http://arxiv.org/abs/1304.7045)
     *arXiv 2013*

## Resources

### Dataset
   - 20 commonly used
     [datasets for density estimation](https://github.com/arranger1044/DEBD) as in [[Lowd2013](#lowd2013)][[Gens2013](#gens2013)][[Rooshenas2014](#rooshenas2014)][[Vergari2015](#vergari2015)][[Adel2015](#adel2015)][[Zhao2016a](#zhao2016a)][[Rooshenas2016](#rooshenas2016)]

### Code
   - [[Vergari2016](#vergari2016)]
     [**spyn-repr**](https://github.com/arranger1044/spyn-repr)
     extracting embeddings from SPNs `python3`
   - [[Vergari2015](#vergari2015)] [**spyn**](https://github.com/arranger1044/spyn) LearnSPN-B/T/B and SPN
     inference routines in Python `python3` 
   - [[Rooshenas2014](#rooshenas2014)] ID-SPN and inference routines
     on ACs implemented in the
     [**Libra Toolkit**](http://libra.cs.uoregon.edu/) `Ocaml`  
   - [[Peharz2014a](#peharz2014a)]
     [**ABE-SPN**](https://www.spsc.tugraz.at/tools/artificial-bandwidth-extension-sum-product-networks)
     Artificial Bandwidth-Extension with Sum-Product Networks `MATLAB` `C++`  
   - [**GoSPN**](https://github.com/RenatoGeh/gospn) implementing
     LearnSPN in Go `Go` 
   - [[Cheng2014](#cheng2014)]
      [**lmspn**](https://github.com/stakok/lmspn) Language modeling
      with SPNs `C++` `CUDA`
   - [**C++/Cuda porting**](https://github.com/vseledkin/SumProductNetwork)
      of Poon's architecture `C++` `CUDA`  
   - [**Python porting**](https://github.com/vseledkin/Sum-Product-Networks)
      of Poon's architecture `python2`  
   - [[Gens2013](#gens2013)]
      [**LearnSPN**](http://spn.cs.washington.edu/learnspn/) `Java`
   - [[Poon2011](#poon2011)] Code to **train** [**Poon's architecture
      weigths by EM**](http://spn.cs.washington.edu/spn/) `Java` `MPI`

### Talks and Tutorials

   - Di Mauro and Vergari [**Learning Sum-Product Networks**](http://people.idsia.ch/~alessandro/pgm/DiMauroVergari.pdf)
     tutorial at PGM'16 _2016_
   - Poupart P. **Deep Learning, Sum-Product Networks** [**Part I**](https://www.youtube.com/watch?v=eF0APeEIJNw)
     [**Part II**](https://www.youtube.com/watch?v=9-1YE_N-lnw) _2015_
   - Hernàndez-Lobato, J. M. [**An Introduction to Sum-Product Networks**](http://cbl.eng.cam.ac.uk/pub/Intranet/MLG/ResearchAndCommunicationClub/SumProductNetworks.pdf) _2013_  
   - Gens, R. [**Learning the Structure of Sum-Product Networks**](http://spn.cs.washington.edu/talks/Gens_SLSPN_ICML2013.pdf)
     [[Gens2013](#gens2013)] _2013_  
   - Poon,
     H. [**Sum-Product Networks: A New Deep Architecture**](http://spn.cs.washington.edu/talks/spn11.pdf)
     [[Poon2011](#poon2011)] _2011_
  

## References

* <p id="adel2015">
[Adel2015]<br/>
_Adel, Tameem and Balduzzi, David and Ghodsi, Ali_<br/>
**Learning the Structure of Sum-Product Networks via an SVD-based Algorithm**<br/>
Uncertainty in Artificial Intelligence 2015
</p>
* <p id="amer2012">
[Amer2012]<br/>
_Amer, Mohamed and Todorovic, Sinisa_<br/>
**Sum-Product Networks for Modeling Activities with Stochastic Structure**<br/>
2012 IEEE Conference on CVPR
</p>
* <p id="amer2015">
[Amer2015]<br/>
_Amer, Mohamed and Todorovic, Sinisa_<br/>
**Sum Product Networks for Activity Recognition**<br/>
IEEE Transactions on Pattern Analysis and Machine Intelligence<br/> 
</p>
* <p id="cheng2014">
[Cheng2014]<br/>
_Cheng, Wei-Chen and Kok, Stanley and Pham, Hoai Vu and Chieu, Hai Leong and Chai, Kian Ming Adam_<br/>
**Language modeling with Sum-Product Networks**<br/>
INTERSPEECH 2014
</p>
* <p id="darwiche2003">
[Darwiche2003]<br/>
_Darwiche, Adnan_<br/>
**A Differential Approach to Inference in Bayesian Networks**<br/>
Journal of the ACM 2003.
</p>
* <p id="dellaleau2011">
[Dellaleau2011]<br/>
_Delalleau, Olivier and Bengio, Yoshua_<br/>
**Shallow vs. Deep Sum-Product Networks**<br/>
Advances in Neural Information Processing Systems 2011.
</p>
* <p id="dennis2012">
[Dennis2012]<br/>
_Dennis, Aaron and Ventura, Dan_<br/>
**Learning the Architecture of Sum-Product Networks Using Clustering on Varibles**<br/>
Advances in Neural Information Processing Systems 25<br/>
</p>
* <p id="dennis2015">
[Dennis2015]<br/>
_Dennis, Aaron and Ventura, Dan_<br/>
**Greedy Structure Search for Sum-product Networks**<br/>
International Joint Conference on Artificial Intelligence 2015
</p>
* <p id="desana2016">
[Desana2016]<br/>
_Desana, Mattia and Schn{\"{o}}rr Christoph_<br/>
**Expectation Maximization for Sum-Product Networks as Exponential Family**<br/>
arxiv.org/abs/1604.07243
</p>
* <p id="friesen2015">
[Friesen2015]<br/>
_Friesen, Abram L and Domingos, Pedro_<br/>
**Recursive Decomposition for Nonconvex Optimization**<br/>
Proceedings of the 24th International Joint Conference on Artificial Intelligence
</p>
* <p id="friesen2016">
[Friesen2016]<br/>
_Friesen, Abram L and Domingos, Pedro_<br/>
**The Sum-Product Theorem: A Foundation for Learning Tractable Models**<br/>
ICML 2016
</p>
* <p id="gens2012">
[Gens2012]<br/>
_Gens, Robert and Domingos, Pedro_<br/>
**Discriminative Learning of Sum-Product Networks**<br/>
NIPS 2012
</p>
* <p id="gens2013">
[Gens2013]<br/>
_Gens, Robert and Domingos, Pedro_<br/>
**Learning the Structure of Sum-Product Networks**<br/>
ICML 2013
</p>
* <p id="jaini2016">
[Jaini2016]<br/>
_Jaini, Priyank and Rashwan, Abdullah and Zhao, Han and Liu, Yue and
Banijamali, Ershad and Chen, Zhitang and Poupart, Pascal_<br/>
**Online Algorithms for Sum-Product Networks with Continuous Variables**<br/>
International Conference on Probabilistic Graphical Models 2016
</p>
* <p id="krakovna2016">
[Krakovna2016]<br/>
_Krakovna, Viktoriya and Looks, Moshe_<br/>
**A Minimalistic Approach to Sum-Product Network Learning for Real Applications**<br/>
ICLR 2016
</p>
* <p id="lee2013">
[Lee2013]<br/>
_Lee, Sang-Woo and Heo, Min-Oh and Zhang, Byoung-Tak_<br/>
**Online Incremental Structure Learning of Sum-Product Networks**<br/>
ICONIP 2013
</p>
* <p id="lee2014">
[Lee2014]<br/>
_Lee, Sang-Woo and Watkins, Christopher and Zhang, Byoung-Tak_<br/>
**Non-Parametric Bayesian Sum-Product Networks**<br/>
Workshop on Learning Tractable Probabilistic Models 2014
</p>
* <p id="li2015">
[Li2015]<br/>
_Weizhuo Li_<br/>
**Combining sum-product network and noisy-or model for ontology
matching**<br/>
Proceedings of the 10th International Workshop on Ontology Matching
</p>
* <p id="livni2013">
[Livni2013]<br/>
_Livni, Roi and Shalev-Shwartz, Shai and Shamir, Ohad_<br/>
**A Provably Efficient Algorithm for Training Deep Networks**<br/>
arXiv 2013
</p>
* <p id="lowd2013">
[Lowd2013]<br/>
_Lowd, Daniel and Rooshenas, Amirmohammad_<br/>
**Learning Markov Networks With Arithmetic Circuits**<br/>
Proceedings of the 16th International Conference on Artificial Intelligence and Statistics 2013
</p>
* <p id="martens2014">
[Martens2014]<br/>
_Martens, James and Medabalimi, Venkatesh_<br/>
**On the Expressive Efficiency of Sum Product Networks**<br/>
arXiv/1411.7717
</p>
* <p id="melibari2016a">
[Melibari2016a]<br/>
_Melibari, Mazen and Poupart, Pascal and Doshi, Prashant_<br/>
**Decision Sum-Product-Max Networks**<br/>
Thirtieth AAAI Conference on Artificial Intelligence
</p>
* <p id="melibari2016b">
[Melibari2016b]<br/>
_Melibari, Mazen and Poupart, Pascal and Doshi, Prashant_<br/>
**Sum-Product-Max Networks for Tractable Decision Making**<br/>
Proceedings of the 2016 International Conference on Autonomous Agents & Multiagent Systems
</p>
* <p id="melibari2016c">
[Melibari2016c]<br/>
_Melibari, Mazen and Poupart, Pascal and Doshi, Prashant and
Trimponias, George_<br/>
**Dynamic Sum-Product Networks for Tractable Inference on Sequence Data**<br/>
International Conference on Probabilistic Graphical Models 2016
</p>
* <p id="nath2014">
[Nath2014]<br/>
_Nath, Aniruddh and Domingos, Pedro_<br/>
**Learning Tractable Statistical Relational Models**<br/>
Workshop on Learning Tractable Probabilistic Models
</p>
* <p id="nath2015">
[Nath2015]<br/>
_Nath, Aniruddh and Domingos, Pedro_<br/>
**Learning Relational Sum-Product Networks**<br/>
AAAI 2015
</p>
* <p id="nath2016">
[Nath2016]<br/>
_Nath, Aniruddh and Domingos, Pedro_<br/>
**Learning Tractable Probabilistic Models for Fault Localization**<br/>
AAAI 2016
</p>
* <p id="niepert2015">
[Niepert2015]<br/>
_Niepert, Mathias and Domingos, Pedro_<br/>
**Learning and Inference in Tractable Probabilistic Knowledge Bases**<br/>
UAI 2015
</p>
* <p id="peharz2013">
[Peharz2013]<br/>
_Peharz, Robert and Geiger, Bernhard and Pernkopf, Franz_<br/>
**Greedy Part-Wise Learning of Sum-Product Networks**<br/>
ECML-PKDD 2013
</p>
* <p id="peharz2014a">
[Peharz2014a]<br/>
_Peharz, Robert and Kapeller, Georg and Mowlaee, Pejman and Pernkopf, Franz_<br/>
**Modeling Speech with Sum-Product Networks: Application to Bandwidth Extension**<br/>
ICASSP2014
</p>
* <p id="peharz2014b">
[Peharz2014b]<br/>
_Robert Peharz and Gens, Robert and Domingos, Pedro_<br/>
**Learning Selective Sum-Product Networks**<br/>
Workshop on Learning Tractable Probabilistic Models 2014
</p>
* <p id="peharz2015a">
[Peharz2015a]<br/>
_Robert Peharz and Tschiatschek, Sebastian and Pernkopf, Franz and Domingos, Pedro_<br/>
**On Theoretical Properties of Sum-Product Networks**<br/>
Proceedings of the 18th International Conference on Artificial Intelligence and Statistics
</p>
* <p id="peharz2015b">
[Peharz2015b]<br/>
_Peharz, Robert_<br/>
**Foundations of Sum-Product Networks for Probabilistic Modeling**<br/>
PhD Thesis
</p>
* <p id="peharz2016">
[Peharz2016]<br/>
_Robert Peharz and Robert Gens and Franz Pernkopf and Pedro Domingos_<br/>
**On the Latent Variable Interpretation in Sum-Product Networks**<br/>
arxiv.org/abs/1601.06180
</p>
* <p id="poon2011">
[Poon2011]<br/>
_Poon, Hoifung and Domingos, Pedro_<br/>
**Sum-Product Network: a New Deep Architecture**<br/>
UAI 2011
</p>
* <p id="rahman2016">
[Rahman2016]<br/>
_Tahrima Rahman and Vibhav Gogate_<br/>
**Merging Strategies for Sum-Product Networks: From Trees to
Graphs**<br/>
UAI 2016
</p>
* <p id="rashwan2016">
[Rashwan2016]<br/>
_Rashwan, Abdullah and Zhao, Han and Poupart, Pascal_<br/>
**Online and Distributed Bayesian Moment Matching for Parameter Learning in Sum-Product Networks**<br/>
Proceedings of the 19th International Conference on Artificial Intelligence and Statistics
</p>
* <p id="ratajczak2014">
[Ratajczak2014]<br/>
_Ratajczak, Martin and Tschiatschek, S and Pernkopf, F_<br/>
**Sum-Product Networks for Structured Prediction: Context-Specific Deep Conditional Random Fields**<br/>
Workshop on Learning Tractable Probabilistic Models 2014
</p>
* <p id="rooshenas2014">
[Rooshenas2014]<br/>
_Rooshenas, Amirmohammad and Lowd, Daniel_<br/>
**Learning Sum-Product Networks with Direct and Indirect Variable Interactions**<br/>
ICML 2014
</p>
* <p id="rooshenas2016">
[Rooshenas2016]<br/>
_Rooshenas, Amirmohammad and Lowd, Daniel_<br/>
**Discriminative Structure Learning of Arithmetic Circuits**<br/>
Proceedings of the 19th International Conference on Artificial Intelligence and Statistics
</p>
* <p id="stuhlmueller2012">
[Stuhlmueller2012]<br/>
_Stuhlmuller, Andreas and Goodman, Noah D._<br/>
**A Dynamic Programming Algorithm for Inference in Recursive Probabilistic Programs**<br/>
StaRAI 2012
</p>
* <p id="vergari2015">
[Vergari2015]<br/>
_Vergari, Antonio and Di Mauro, Nicola and Esposito, Floriana_<br/>
**Simplifying, Regularizing and Strengthening Sum-Product Network Structure Learning**<br/>
ECML-PKDD 2015
</p>
* <p id="vergari2016">
[Vergari2016]<br/>
_Vergari, Antonio and Di Mauro, Nicola and Esposito, Floriana_<br/>
**Visualizing and Understanding Sum-Product Networks**<br/>
arXiv:1608.08266
</p>
* <p id="wang2015">
  [Wang2015]<br/>
_Wang, Jinghua and Wang, Gang_<br/>
**Hierarchical Spatial Sum-Product Networks for action recognition in Still Images**<br/>
arXiv:1511.05292
</p>
* <p id="yuan2016">
  [Yuan2016]<br/>
_Zehuan Yuan and Hao Wang and Limin Wang and Tong Lu and Shivakumara Palaiahnakote and Chew Lim Tan_<br/>
**Modeling Spatial Layout for Scene Image Understanding Via a Novel Multiscale Sum-Product Network**<br/>
Expert Systems with Applications 
</p>
* <p id="zhao2015">
[Zhao2015]<br/>
_Zhao, Han and Melibari, Mazen and Poupart, Pascal_<br/>
**On the Relationship between Sum-Product Networks and Bayesian Networks**<br/>
ICML 2015
</p>
* <p id="zhao2016a">
[Zhao2016a]<br/>
_Zhao, Han and Adel, Tameem and Gordon, Geoff and Amos, Brandon_<br/>
**Collapsed Variational Inference for Sum-Product Networks**<br/>
ICML 2016
</p>
* <p id="zhao2016b">
[Zhao2016b]<br/>
_Zhao, Han and Poupart, Pascal_<br/>
**A Unified Approach for Learning the Parameters of Sum-Product Networks**<br/>
NIPS 2016
</p>
