## HybridVC: Efficient Voice Style Conversion with Text and Audio Prompts

### About 

This is a [demo](https://XinleiNIU.github.io/demo-HybridVC/) for our [paper](https://arxiv.org/abs/2404.15637) '_HybridVC: Efficient Voice Style Conversion with Text and Audio Prompts_'. 

### Citation

We introduce HybridVC, a voice conversion (VC) framework built upon a pre-trained conditional variational autoencoder (CVAE) that combines the strengths of a latent model with contrastive learning. HybridVC supports text and audio prompts, enabling more flexible voice style conversion. HybridVC models a latent distribution conditioned on speaker embeddings acquired by a pretrained speaker encoder and optimises style text embeddings to align with the speaker style information through contrastive learning in parallel. Therefore, HybridVC can be efficiently trained under limited computational resources. Our experiments demonstrate HybridVC's superior training efficiency and its capability for advanced multi-modal voice style conversion. This underscores its potential for widespread applications such as user-defined personalised voice in various social media platforms. A comprehensive ablation study further validates the effectiveness of our method.



### Citation

If you are interesting in our work, please cite it as below:

```
@article{niu2024hybridvc,
  title={HybridVC: Efficient Voice Style Conversion with Text and Audio Prompts},
  author={Niu, Xinlei and Zhang, Jing and Martin, Charles Patrick},
  journal={arXiv preprint arXiv:2404.15637},
  year={2024}
}
```
