# CtrlCache: Accelerating Interactive Video World Models with Control-Aware Caching

**[Project page](https://wrecklong.github.io/CtrlCache/)** · **[arXiv](https://arxiv.org/abs/2610.08777)** · **[Paper (PDF)](https://arxiv.org/pdf/2610.08777)**

Shangye Song<sup>1</sup>, Dong Gong<sup>2</sup>, Hong Jia<sup>1</sup>, Yun Sing Koh<sup>1</sup>, Xinyu Zhang<sup>1,*</sup>

<sup>1</sup>University of Auckland · <sup>2</sup>UNSW Sydney<br>
<sup>*</sup>Corresponding author

---

![CtrlCache overview](https://wrecklong.github.io/CtrlCache/static/images/pipeline.png)

CtrlCache is a training-free caching framework for interactive video world models. The controls for a chunk are known
before the chunk is denoised, so CtrlCache uses them to decide when cached transformer computation can be reused and
when it must be refreshed. A frequency-mixed history prior also carries coarse scene structure forward during steady
interaction. On Matrix-Game 2.0 and LingBot-World v1/v2, CtrlCache speeds up the DiT backbone by 1.21×–1.41× and
improves WBench Overall over original inference on all three models.

## News

- **2026-10** — Paper released on [arXiv](https://arxiv.org/abs/2610.08777).

## Code

Code will be released in this repository. In the meantime, side-by-side video comparisons with the original models,
TeaCache and EasyCache are on the [project page](https://wrecklong.github.io/CtrlCache/#videos).

## Citation

```bibtex
@article{song2026ctrlcache,
  title   = {CtrlCache: Accelerating Interactive Video World Models with Control-Aware Caching},
  author  = {Song, Shangye and Gong, Dong and Jia, Hong and Koh, Yun Sing and Zhang, Xinyu},
  journal = {arXiv preprint arXiv:2610.08777},
  year    = {2026}
}
```
