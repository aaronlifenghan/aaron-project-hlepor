hlepor: Language-independent Model for Machine Translation Evaluation with Reinforced Factors
====================

introduction of hLEPOR: Language independent Model for Machine Translation Evaluation with Reinforced Factors

hLEPOR is a language independent machine translation evaluation metric with reinforced factors. hLEPOR is open source, 
free for research purpose. Experiments on ACL-WMT11 corpora (English to German, French, Spanish, Czech; and the reverse
direction) show hLEPOR yields higher correlation scores with human judgments at system-level, as compared to MPF, ROSE,
METEOR, BLEU, and TER evaluation metrics. Detailed knowledge of hLEPOR is shown in the paper "Language-independent Model
for Machine Translation Evaluation with Reinforced Factors" by Aaron Li-Feng Han, Derek F. Wong, Lidia S. Chao, Liangye
He, Yi Lu, Junwen Xing and Xiaodong Zeng. in Proceedings of the Machine Translation Summit XIV, pp. 215-222. Nice, France. 
International Association for Machine Translation. (Download paper http://www.mt-archive.info/10/MTS-2013-Han.pdf#!). If you use the 
hLEPOR metric in your researches, please cite the paper.

In the ACL-WMT 2013 Metrics Task (http://www.statmt.org/wmt13/metrics-task.html), hLEPOR (i.e. LEPOR_V3.1 in the 
Workshop report paper) also yields the highest Pearson correlation score with human judgment on the English-to-Russian 
language pair, in addition to the highest average-score on five language pairs 
(**English-to-German, French, Spanish, Czech, Russian**). The detailed results of WMT13 Metrics Task is introduced in
the paper "A Description of Tunable Machine Translation Evaluation Systems in WMT13 Metrics Task" by Aaron Li-Feng Han, 
Derek F. Wong, Lidia S. Chao, Yi Lu, Liangye He, Yiming Wang and Jiaji Zhou, in Proceedings of ACL-WMT13 
(http://www.statmt.org/wmt13/pdf/WMT53.pdf).

For better performances, hLEPOR parameter setting on different langauge (or language pair) situations is available at the Table 1 (parameter values via language) of WMT13 paper https://aclanthology.org/W13-2253.pdf The parameters were mannually tuned using validation set of corresponding language. For automatic tuning of parameters, we have cushLEPOR now available at https://github.com/poethan/cushLEPOR 

# code updates
updated codes in the link: 
https://github.com/poethan/LEPOR 
https://github.com/aaronlifenghan/aaron-project-lepor (hLEPOR, nLEPOR)

--------
Citations:

@inproceedings{han2013language,
  title={Language-independent Model for Machine Translation Evaluation with Reinforced Factors},
  author={Han, Aaron L.-F. and Wong, Derek F. and Chao, Lidia S. and He, Liangye and Lu, Yi and Xing, Junwen and Zeng, Xiaodong},
  booktitle={Machine Translation Summit XIV},
  pages={215--222},
  year={2013},
  organization={International Association for Machine Translation}
}

-------------

Contact: hanlifengaaron AT gmail.com

Visit: ADAPT Centre, DCU, Dublin, Ireland
