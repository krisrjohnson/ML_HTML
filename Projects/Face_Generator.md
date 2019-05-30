# Face Generator

Take facial landmarks of one person (me) and train a generator that can create a (my) face from that input.

-- check which GPU my windows machine has (https://www.cisco.com/c/en/us/td/docs/telepresence/endpoint/articles/cisco_telepresence_movi_find_out_graphics_card_driver_on_windows_pc_kb_540.html)
lappy: 'intel hd 520 graphics' is the name of the chip

[List][GAN_github] of useful GAN examples

## Websites:
- [GAN tips and tricks](https://medium.com/@utk.is.here/keep-calm-and-train-a-gan-pitfalls-and-tips-on-training-generative-adversarial-networks-edd529764aa9)
- [python to train ML models](https://www.jessicayung.com/using-generators-in-python-to-train-machine-learning-models/ "lol this is python generator fn")
- [keras using python generator](https://www.pyimagesearch.com/2018/12/24/how-to-use-keras-fit-and-fit_generator-a-hands-on-tutorial/ ".fit vs .fit_generator")

-- remove.bg for ex bkg removal


[GAN_github]:https://github.com/nashory/gans-awesome-applications 'GAN Applications'


## GAN Face Off
1) Celebrity data set
2) Yank out facial landmarks
3) Model to decode landmarks into a face
4) GAN to challenge and improve model


### GAN From [medium][medium_GAN] article
- "if everything goes well, the Generator (more or less) learns the true distribution of the training data and becomes really good at generating real-looking [Kris] images"
- "more filters help capture additional information which can eventually add sharpness to the generated images."
Code available in keras on [github][GAN_Basics_Github].

[medium_GAN]:https://medium.com/@utk.is.here/keep-calm-and-train-a-gan-pitfalls-and-tips-on-training-generative-adversarial-networks-edd529764aa9 'GAN tips and tricks'
[GAN_Bascis_Github]:https://github.com/utkd/gans/blob/master/cifar10dcgan.ipynb 'Basic GAN'
[DCGAN_pytorch_toot]: https://github.com/pytorch/examples/tree/master/dcgan 'DCGAN Pytorch Ex'