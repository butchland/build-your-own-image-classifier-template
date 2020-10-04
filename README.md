# build-your-own-image-classifier-binder-app-template
This is a template github project for building your binder app based on the article [Build (and Run!) Your Image Classifier using Colab, Binder, Github and Google Drive](https://butchland.github.io/butchland-machine-learning-notes/machine%20learning/2020/10/05/byoic-on-colab-part2.html). This template is based on the [instructions posted on the fastai forums here](https://forums.fast.ai/t/deploying-your-notebook-as-an-app-under-10-minutes/70621?u=butchland).

## Instructions for Deploying to Binder

_Do the next steps only after making sure you already created and exported the learner (`export.pkl`) and your stripped down voila app notebook is ready (preferably tested in a jupyter notebook environment with voila)._

1. Create a [github account](https://github.com/join?source=header-home) if you don't have one yet.
1. Fork [this repo](https://github.com/butchland/build-your-own-image-classifier-template) as a template for your own binder app repository. You can [click on this link to generate your own copy.](https://github.com/butchland/build-your-own-image-classifier-template/generate) 
   * Make sure to rename your repo to something other than `build-your-own-image-classifier-template`. Due to a github policy, `git-lfs` does not support uploads to public forks, which is what your repo will be if you name it the same as what you are copying from. For more info, please see [this issue](https://github.com/git-lfs/git-lfs/issues/1906). 

1. Continue with the steps discussed in the article.
