---
title: "Video Source Characterization Using Encoding and Encapsulation Characteristics"
collection: publications
permalink: /publications/2022-09-05-video-source
excerpt: 'We developed a new method using video coding settings to identify the source of a video, achieving 91% accuracy across 119 video classes.'
date: 2022-09-05
venue: 'IEEE Transactions on Information Forensics and Security'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/9875355'
citation: 'E. Altinisik, H. T. Sencar and D. Tabaa, &quot;Video Source Characterization Using Encoding and Encapsulation Characteristics,&quot; in <i>IEEE Transactions on Information Forensics and Security</i>, vol. 17, pp. 3211-3224, 2022.'
---

We introduce the use of video coding settings for source identification and propose a new approach that incorporates encoding and encapsulation aspects of a video. To this end, a joint representation of the overall file metadata is developed and used in conjunction with a two-level hierarchical classification method. At the first level, our method groups videos into metaclasses considering several abstractions that represent high-level structural properties of file metadata. This is followed by a more nuanced classification of classes that comprise each metaclass. The method is evaluated on more than 20K videos obtained by combining four public video datasets. Tests show that a balanced accuracy of 91% is achieved in correctly identifying the class of a video among 119 video classes. This corresponds to an improvement of 6.5% over the conventional approach based on video file encapsulation characteristics. Analysis performed on a large, unlabeled video set also confirmed the aptness of our approach. To further demonstrate the versatility of encoding parameters, we consider attribution of partial video files where file metadata is not available. Our results show that, even in this limited setting that is intrinsic to forensic file recovery, an identification accuracy of 57% can be achieved through the use of a subset of encoding parameters estimated from coded video data.