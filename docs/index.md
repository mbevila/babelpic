---
layout: default
---
# BabelPic

Welcome to the page of BabelPic, a project of the [Sapienza NLP Group](http://nlp.uniroma1.it), developed with the support of the awesome [Mousse ERC project](http://mousse-project.org/)!

BabelPic, is a dataset targeting non-concrete concepts, built by cleaning the image-synset associations found within [BabelNet](https://babelnet.org/).
Our dataset was annotated manually and then extended using an automatic concept verification technique.

You can read our ACL2020 paper on [ACL Anthology](https://www.aclweb.org/anthology/2020.acl-main.425/)!

## Download

We release our dataset as a`.tar.gz` archive containing the images in BabelPic. The filenames point to the corresponding BabelNet ids.

Download the **gold** BabelPic dataset at:
* GOLD: [`.tar.gz` (Google Drive)]()

The **silver** dataset is available at:
* SILVER: [`.tar.gz` (Google Drive)]()

## Statistics

**Dataset** | **Images** | **Synsets**
Gold        |  14,931    |   2,733
Silver      |     XXX    |  10,013

## Reference
If you use our data, please cite out paper:

```
@inproceedings{calabrese-etal-2020-fatality,
    title = "Fatality Killed the Cat or: {B}abel{P}ic, a Multimodal Dataset for Non-Concrete Concepts",
    author = "Calabrese, Agostina  and
      Bevilacqua, Michele  and
      Navigli, Roberto",
    booktitle = "Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.acl-main.425",
    pages = "4680--4686",
    abstract = "Thanks to the wealth of high-quality annotated images available in popular repositories such as ImageNet, multimodal language-vision research is in full bloom. However, events, feelings and many other kinds of concepts which can be visually grounded are not well represented in current datasets. Nevertheless, we would expect a wide-coverage language understanding system to be able to classify images depicting recess and remorse, not just cats, dogs and bridges. We fill this gap by presenting BabelPic, a hand-labeled dataset built by cleaning the image-synset association found within the BabelNet Lexical Knowledge Base (LKB). BabelPic explicitly targets non-concrete concepts, thus providing refreshing new data for the community. We also show that pre-trained language-vision systems can be used to further expand the resource by exploiting natural language knowledge available in the LKB. BabelPic is available for download at http://babelpic.org.",}
```

## Authors
             
<img src="imgs/calabrese.jpg" width="200"> |  <img src="imgs/bevilacqua.jpg" width="200"> | <img src="imgs/navigli.jpg" width="200"> 
[Agostina Calabrese](https://ago3.github.io) | [Michele Bevilacqua](https://mbevila.github.io) | [Roberto Navigli](http://wwwusers.di.uniroma1.it/~navigli/)
`calabrese.a`* | `bevilacqua`* | `navigli`*
[@agostina_cal](https://twitter.com/agostina_cal) | [@MicheleBevila20](https://twitter.com/MicheleBevila20) |[@rnavigli](https://twitter.com/rnavigli) 

*`@di.uniroma1.it`

## License
This project is released under the CC-BY-NC 4.0 license.

## Acknowledgement
The authors gratefully acknowledge the support of the ERC Consolidator Grant MOUSSE No. 726487 under the European Union's Horizon 2020 research and innovation programme.
