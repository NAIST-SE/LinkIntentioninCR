# Dataset Package:


This is a dataset for the paper **Understanding Shared Links and Their Intention to Meet Information Needs in Modern Code Review**.//
This artifact is a repository consisting of (i) raw dataset (ii) labeled link targets and their intentions, and (iii) script for the statistical model

## Abstract:
Code reviews serve as a quality assurance activity for software teams. Especially for Modern Code Review, sharing a link during a review discussion serves as an effective awareness mechanism where “Code reviews are good FYIs[for your information].”Although prior work has explored link sharing and the information needs of a code review, the extent to which links are used to properly conduct a review is unknown. In this study, we performed a mixed-method approach to investigate the practice of link sharing and their intentions. First, through a quantitative study of the OpenStack and Qt ecosystems, we identify19,268 patches that have 39,686 links to explore the extent to which the links are shared, and analyze a correlation between link sharing and review time. Then in a qualitative study, we analyze 400 links to understand the role and usefulness of link sharing. Results indicate that internal links are more widely referred to(93% and 80% for the two ecosystems). Importantly, although the majority of the internal links are referencing to patches, bug reports and source code are also shared in review discussions. The statistical models show that the number of internal links as an explanatory factor does have an increasing relationship with the review time. Finally, we present seven intentions of link sharing, with the context understanding being the most commonly used. To conduct a proper review, we encourage the patch author to provide clear context and explore both internal and external resources, while the review team should continue link sharing activities. Future research directions include the investigation of causality between sharing links and the review process, as well as the potential for tool support.

## Contents
* `dataset` - the dataset analyzed for each research question: [RQ1](https://github.com/NAIST-SE/AwarenessInCR/tree/master/AwarenessInCR/data_RQ1), [RQ2](https://github.com/NAIST-SE/AwarenessInCR/tree/master/AwarenessInCR/data_RQ2) and [RQ3](https://github.com/NAIST-SE/AwarenessInCR/tree/master/AwarenessInCR/data_RQ3).
* `script` - [R for the statistical models](https://github.com/NAIST-SE/AwarenessInCR/tree/master/AwarenessInCR/SVM).
* `README.md` - the description for each file.


## Authors
* Dong Wang - Nara Institute of Science and Technology, Japan
* Tao Xiao - Nara Institute of Science and Technology, Japan
* [Patanamon Thongtanunam](http://patanamon.com/) - The University of Melbourne, Australia
* [Raula Gaikovina Kula](https://raux.github.io/) - Nara Institute of Science and Technology, Japan
* Kenichi Matsumoto - Nara Institute of Science and Technology, Japan

Our dataset are published on the public domain, so that anyone may freely build upon, enhance and reuse the dataset for any purposes without restriction under copyright or database law.
