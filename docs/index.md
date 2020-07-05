---
layout: default
---
# The BabelPic Project
Welcome to the page of the BabelPic project!

On the left you'll find a short tl;dr of what this is all about. But, even better, you can [read our paper](https://www.aclweb.org/anthology/2020.acl-main.425/)!

## Download

We release our dataset in two formats. 
* `.txt`: a tab-separated, plaintext file containing BabelNet id, url of the image, and filename (corresponding to an image file to be found in the `.tar.gz` file);
* `.tar.gz`: an archive containing the images in BabelPic. The filenames point to the corresponding BabelNet ids.

Download the **gold** BabelPic dataset at:
* GOLD: [`.txt`](), [`.tar.gz` (Google Drive)]()

The **silver** dataset is available at:
* SILVER: [`.tar.gz` (Google Drive)]()


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

* Agostina Calabrese | `calabrese.a` at `di.uniroma1.it` | [@agostina_cal](https://twitter.com/agostina_cal)
* Michele Bevilacqua | `bevilacqua` at `di.uniroma1.it`  | [@MicheleBevila20](https://twitter.com/MicheleBevila20)
* Roberto Navigli    | `navigli` at `di.uniroma1.it`     | [@rnavigli](https://twitter.com/rnavigli)

             |
:-------------------------:|:-------------------------:
Roberto Navigli  |  ![](http://mousse-project.org/imgs/people/Navigli.png)


## License
This project is released under the CC-BY-NC 4.0 license.

## Acknowledgement
The authors gratefully acknowledge the support of the ERC Consolidator Grant MOUSSE No. 726487 under the European Union's Horizon 2020 research and innovation programme.
