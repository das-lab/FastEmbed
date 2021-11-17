# FastEmbed

## Research paper
We present the findings of this work in the following research paper:

**FastEmbed: Predicting vulnerability exploitation possibility based on ensemble machine learning algorithm**
<br/>Fang Y, Liu Y, Huang C, Liu L (2020) FastEmbed: Predicting vulnerability exploitation possibility based on ensemble machine learning algorithm. PLOS ONE 15(2): e0228439. https://doi.org/10.1371/journal.pone.0228439

Article Source: [FastEmbed: Predicting vulnerability exploitation possibility based on ensemble machine learning algorithm](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0228439)

## Abstract
In recent years, the number of vulnerabilities discovered and publicly disclosed has shown a sharp upward trend. However, the value of exploitation of vulnerabilities varies for attackers, considering that only a small fraction of vulnerabilities are exploited. Therefore, the realization of quick exclusion of the non-exploitable vulnerabilities and optimal patch prioritization on limited resources has become imperative for organizations. Recent works using machine learning techniques predict exploited vulnerabilities by extracting features from open-source intelligence (OSINT). However, in the face of explosive growth of vulnerability information, there is room for improvement in the application of past methods to multiple threat intelligence. A more general method is needed to deal with various threat intelligence sources. Moreover, in previous methods, traditional text processing methods were used to deal with vulnerability related descriptions, which only grasped the static statistical characteristics but ignored the context and the meaning of the words of the text. To address these challenges, we propose an exploit prediction model, which is based on a combination of fastText and LightGBM algorithm and called fastEmbed. We replicate key portions of the state-of-the-art work of exploit prediction and use them as benchmark models. Our model outperforms the baseline model whether in terms of the generalization ability or the prediction ability without temporal intermixing with an average overall improvement of 6.283% by learning the embedding of vulnerability-related text on extremely imbalanced data sets. Besides, in terms of predicting the exploits in the wild, our model also outperforms the baseline model with an F1 measure of 0.586 on the minority class (33.577% improvement over the work using features from darkweb/deepweb). The results demonstrate that the model can improve the ability to describe the exploitability of vulnerabilities and predict exploits in the wild effectively.

## Reference
If you use fastEmbed in a scientific publication, we would appreciate citations using this Bibtex entry:

```
@article{fang2020fastembed,
  title={FastEmbed: Predicting vulnerability exploitation possibility based on ensemble machine learning algorithm},
  author={Fang, Yong and Liu, Yongcheng and Huang, Cheng and Liu, Liang},
  journal={PloS one},
  volume={15},
  number={2},
  pages={e0228439},
  year={2020},
  publisher={Public Library of Science San Francisco, CA USA}
}
```

## Data sets
Data sets are available at dropbox, please see: https://www.dropbox.com/s/lx287h1sqsftsuy/FastEmbed-data.rar?dl=0
