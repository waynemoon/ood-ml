# Must-read papers and resources related to out-of-distribution generalization in machine learning
Work in progress, inspired by [causal-ml](https://github.com/jvpoulos/causal-ml).
# Content
<table>
<tr><td colspan="2"><a href="#thesis">1. Thesis</a></td></tr> 
<tr><td colspan="2"><a href="#invariance-principles">2. Invariance principles </a></td></tr> 
<tr><td colspan="2"><a href="#information-bottleneck">3. Information bottleneck</a></td></tr> 
<tr><td colspan="2"><a href="#domain-adaptation">4. Domain adaptation</a></td></tr> 
<tr><td colspan="2"><a href="#inductive-biases">5. Inductive biases</a></td></tr> 
<tr><td colspan="2"><a href="#applications">6. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#computer-vision">6.1. Computer vision</a></td>
    <td>&emsp;<a href="#natural-language-processing">6.2. Natural language processing</a></td>
<tr><td colspan="2"><a href="#benchmarks">7. Benchmarks</a></td></tr>    
</tr> 
</tr> 
</table>

## Thesis
* **Out of Distribution Generalization in Machine Learning**, 2019. [paper](https://arxiv.org/abs/2103.02667)

   Martin Arjovsky

## Invariance principles

* **Invariant Risk Minimization**, 2019. [paper](https://arxiv.org/abs/1907.02893)
   
   Martin Arjovsky, Léon Bottou, Ishaan Gulrajani, David Lopez-Paz

* **Invariant Risk Minimization Games**, ICML, 2020. [paper](https://arxiv.org/abs/2002.04692)

   Kartik Ahuja, Karthikeyan Shanmugam, Kush Varshney, Amit Dhurandhar 

* **Out-of-Distribution Generalization via Risk Extrapolation**, 2021. [paper](https://arxiv.org/abs/2003.00688)

   David Krueger, Ethan Caballero, Joern-Henrik Jacobsen, Amy Zhang, Jonathan Binas, Dinghuai Zhang, Remi Le Priol, Aaron Courville
   
* **The Risks of Invariant Risk Minimization**, ICLR, 2021. [paper](https://arxiv.org/abs/2010.05761)
   
   Elan Rosenfeld, Pradeep Ravikumar, Andrej Risteski

* **Nonlinear Invariant Risk Minimization: A Causal Approach**, 2021. [paper](https://arxiv.org/abs/2102.12353)

   Chaochao Lu, Yuhuai Wu, Jośe Miguel Hernández-Lobato, Bernhard Schölkopf


## Information bottleneck
* **Invariance Principle Meets Information Bottleneck for Out-of-Distribution Generalization**, 2021. [paper](https://arxiv.org/abs/2106.06607)
   
   Kartik Ahuja, Ethan Caballero, Dinghuai Zhang, Yoshua Bengio, Ioannis Mitliagkas, Irina Rish

## Domain adaptation
* **Advances in Domain Adaptation Theory**, Elsevier, 2019.

  Ievgen Redko, Emilie Morvant, Amaury Habrard, Marc Sebban, Younès Bennani

## Inductive biases
* **Inductive Biases for Deep Learning of Higher-Level Cognition**, 2021. [paper](https://arxiv.org/abs/2011.15091)
   
   Anirudh Goyal, Yoshua Bengio


## Applications

### Computer vision

* **Roses Are Red, Violets Are Blue... but Should Vqa Expect Them To?**, CVPR, 2021. [paper](https://arxiv.org/abs/2006.05121)
  
   Corentin Kervadec, Grigory Antipov, Moez Baccouche, Christian Wolf

### Natural language processing
* **Pretrained transformers improve out of distribution robustness**, ACL, 2020. [paper](https://arxiv.org/abs/2004.06100)
  
   Dan Hendrycks, Xiaoyuan Liu, Eric Wallace, Adam Dziedzic, Rishabh Krishnan, Dawn Song
## Benchmarks
* **WILDS: A Benchmark of in-the-Wild Distribution Shifts**, 2021. [paper](https://arxiv.org/abs/2012.07421)[code](https:// github.com/p-lambda/wilds)
  
   Pang Wei Koh, Shiori Sagawa, Henrik Marklund, Sang Michael Xie, Marvin Zhang, Akshay Balsubramani, Weihua Hu, Michihiro Yasunaga, Richard Lanas Phillips, 
   Irena Gao, Tony Lee, Etienne David, Ian Stavness, Wei Guo, Berton A. Earnshaw, Imran S. Haque, Sara Beery, Jure Leskovec, Anshul Kundaje, Emma Pierson, 
   Sergey Levine, Chelsea Finn, Percy Liang
