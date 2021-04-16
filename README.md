# Identification and Remediation of Self-Admitted Technical Debt in Issue Trackers

Authors: 
Yikun Li, Mohamed Soliman, Paris Avgeriou.
Bernoulli Institute for Mathematics, Computer Science and Artificial Intelligence, University of Groningen, Groningen, The Netherlands.
Email: {yikun.li, m.a.m.soliman, p.avgeriou}@rug.nl

### Abstract:
Technical debt refers to taking shortcuts to achieve short-term goals, which might negatively influence software maintenance in the long-term. There is increasing attention on technical debt that is admitted by developers in source code comments (termed as self-admitted technical debt or SATD). But SATD in issue trackers is relatively unexplored. We performed a case study, where we manually examined 500 issues from two open source projects (i.e. Hadoop and Camel), which contained 152 SATD items. We found that: 1) eight types of technical debt are identified in issues, namely architecture, build, code, defect, design, documentation, requirement, and test debt; 2) developers identify technical debt in issues in three different points in time, and a small part is identified by its creators; 3) the majority of technical debt is paid off, 4) mostly by those who identified it or created it; 5) the median time and average time to repay technical debt are 872.3 and 25.0 hours respectively.

### Content of the replication package:

In the replication package, the following materials are included:
* Codebook.pdf - The definitions of types and indicators of technical debt that are used for manual classification.
* Technical_debt_classification.csv - The file includes a list of identified technical debt with their introduction, types, and repayment information.
* Analyzed_500_issues.zip - This zip file contains all 500 issues that we analyzed.

### Paper
Latest version available on [arXiv](https://arxiv.org/pdf/2007.01568.pdf)

Please adequately refer to the papers any time this code is being used. If you do publish a paper where this dataset helped your research, we encourage you to cite the following paper in your publications:

```
@inproceedings{li2020identification,
  title={Identification and Remediation of Self-Admitted Technical Debt in Issue Trackers},
  author={Li, Yikun and Soliman, Mohamed and Avgeriou, Paris},
  booktitle={2020 46th Euromicro Conference on Software Engineering and Advanced Applications (SEAA)},
  pages={495--503},
  year={2020},
  organization={IEEE}
}
```