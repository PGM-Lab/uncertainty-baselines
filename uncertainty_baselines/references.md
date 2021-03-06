# References

We don't yet have a recommended BibTeX entry if you'd like to cite our work. If
you're using specific datasets, models, or baselines, see below.

## Datasets

```
# CIFAR-10
@article{cifar10,
title = {CIFAR-10 (Canadian Institute for Advanced Research)},
author = {Alex Krizhevsky and Vinod Nair and Geoffrey Hinton},
url = {http://www.cs.toronto.edu/~kriz/cifar.html},
}

# CIFAR-100
@article{cifar100,
title = {CIFAR-100 (Canadian Institute for Advanced Research)},
author = {Alex Krizhevsky and Vinod Nair and Geoffrey Hinton},
url = {http://www.cs.toronto.edu/~kriz/cifar.html},
}

# Civil Comments Toxicity Classification
@article{civil_comments,
  title     = {Nuanced Metrics for Measuring Unintended Bias with Real Data for Text
               Classification},
  author    = {Daniel Borkan and Lucas Dixon and Jeffrey Sorensen and Nithum Thain and Lucy Vasserman},
  journal   = {CoRR},
  volume    = {abs/1903.04561},
  year      = {2019},
  url       = {http://arxiv.org/abs/1903.04561},
  archivePrefix = {arXiv},
  eprint    = {1903.04561},
  timestamp = {Sun, 31 Mar 2019 19:01:24 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1903-04561},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}

# CLINIC
@article{clinic,
  title = {An Evaluation Dataset for Intent Classification and Out-of-Scope Prediction},
  author = {Larson, Stefan and Mahendran, Anish and Peper, Joseph J and Clarke, Christopher and Lee, Andrew and Hill, Parker and Kummerfeld, Jonathan K and Leach, Kevin and Laurenzano, Michael A and Tang, Lingjia and others},
  journal = {arXiv preprint arXiv:1909.02027},
  year = {2019}
}

# Criteo
@article{criteo,
title = {Display Advertising Challenge},
url = {https://www.kaggle.com/c/criteo-display-ad-challenge.},
}

# GLUE
@inproceedings{glue,
    title = "{GLUE}: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding",
    author = "Wang, Alex  and
      Singh, Amanpreet  and
      Michael, Julian  and
      Hill, Felix  and
      Levy, Omer  and
      Bowman, Samuel",
    booktitle = "Proceedings of the 2018 {EMNLP} Workshop {B}lackbox{NLP}: Analyzing and Interpreting Neural Networks for {NLP}",
    month = nov,
    year = "2018",
    address = "Brussels, Belgium",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W18-5446",
    doi = "10.18653/v1/W18-5446",
    pages = "353--355"
}

# ImageNet
@article{imagenet,
    Author = {Olga Russakovsky and Jia Deng and Hao Su and Jonathan Krause and Sanjeev Satheesh and Sean Ma and Zhiheng Huang and Andrej Karpathy and Aditya Khosla and Michael Bernstein and Alexander C. Berg and Li Fei-Fei},
    Title = {{ImageNet Large Scale Visual Recognition Challenge}},
    Year = {2015},
    journal = {International Journal of Computer Vision (IJCV)},
    volume = {115},
    number = {3},
    pages = {211-252}
    }

# MNIST
@article{mnist,
  author = {LeCun, Yann and Cortes, Corinna},
  title = {{MNIST} handwritten digit database},
  url = {http://yann.lecun.com/exdb/mnist/},
  year = 2010
}

# MNLI
@InProceedings{N18-1101,
  author = "Williams, Adina
            and Nangia, Nikita
            and Bowman, Samuel",
  title = "A Broad-Coverage Challenge Corpus for
           Sentence Understanding through Inference",
  booktitle = "Proceedings of the 2018 Conference of
               the North American Chapter of the
               Association for Computational Linguistics:
               Human Language Technologies, Volume 1 (Long
               Papers)",
  year = "2018",
  publisher = "Association for Computational Linguistics",
  pages = "1112--1122",
  location = "New Orleans, Louisiana",
  url = "http://aclweb.org/anthology/N18-1101"
}

# Wikipedia Talk Toxicity Classification
@inproceedings{wikipedia_talk,
  author = {Wulczyn, Ellery and Thain, Nithum and Dixon, Lucas},
  title = {Ex Machina: Personal Attacks Seen at Scale},
  year = {2017},
  isbn = {9781450349130},
  publisher = {International World Wide Web Conferences Steering Committee},
  address = {Republic and Canton of Geneva, CHE},
  url = {https://doi.org/10.1145/3038912.3052591},
  doi = {10.1145/3038912.3052591},
  booktitle = {Proceedings of the 26th International Conference on World Wide Web},
  pages = {1391-1399},
  numpages = {9},
  keywords = {online discussions, wikipedia, online harassment},
  location = {Perth, Australia},
  series = {WWW '17}
}
```

## Models

```
# Residual Networks
@misc{resnet,
  title={Deep residual learning for image recognition. CoRR abs/1512.03385 (2015)},
  author={He, Kaiming and Zhang, Xiangyu and Ren, Shaoqing and Sun, Jian},
  year={2015}
}

# Criteo MLP
@inproceedings{uncertaintybenchmark,
  title={Can you trust your model's uncertainty? Evaluating predictive uncertainty under dataset shift},
  author={Snoek, Jasper and Ovadia, Yaniv and Fertig, Emily and Lakshminarayanan, Balaji and Nowozin, Sebastian and Sculley, D and Dillon, Joshua and Ren, Jie and Nado, Zachary},
  booktitle={Advances in Neural Information Processing Systems},
  pages={13969--13980},
  year={2019}
}

# Text CNN
@inproceedings{textcnn,
    title = "Convolutional Neural Networks for Sentence Classification",
    author = "Kim, Yoon",
    booktitle = "Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing ({EMNLP})",
    month = oct,
    year = "2014",
    address = "Doha, Qatar",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D14-1181",
    doi = "10.3115/v1/D14-1181",
    pages = "1746--1751",
}

# BERT
@inproceedings{bert,
    title = "{BERT}: Pre-training of Deep Bidirectional Transformers for Language Understanding",
    author = "Devlin, Jacob  and
      Chang, Ming-Wei  and
      Lee, Kenton  and
      Toutanova, Kristina",
    booktitle = "Proceedings of the 2019 Conference of the North {A}merican Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers)",
    month = jun,
    year = "2019",
    address = "Minneapolis, Minnesota",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/N19-1423",
    doi = "10.18653/v1/N19-1423",
    pages = "4171--4186",
}

# Wide ResNet-*-*
@article{zagoruyko2016wide,
  title={Wide residual networks},
  author={Zagoruyko, Sergey and Komodakis, Nikos},
  journal={arXiv preprint arXiv:1605.07146},
  year={2016}
}
```
