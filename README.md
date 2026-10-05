# CtrlCache: Accelerating Interactive Video World Models with Control-Aware Caching

**[Project page](https://wrecklong.github.io/CtrlCache/)** · **[Paper (PDF)](https://wrecklong.github.io/CtrlCache/static/paper.pdf)** · arXiv (coming soon) · Code (coming soon)

Shangye Song<sup>1</sup>, Dong Gong<sup>2</sup>, Hong Jia<sup>1</sup>, Yun Sing Koh<sup>1</sup>, Xinyu Zhang<sup>1,*</sup>

<sup>1</sup>University of Auckland · <sup>2</sup>UNSW Sydney · <sup>*</sup>Corresponding author

---

CtrlCache is a training-free caching framework for interactive video world models. The controls for a chunk are known
before the chunk is denoised, so CtrlCache uses them to decide when cached transformer computation can be reused and
when it must be refreshed. A frequency-mixed history prior also carries coarse scene structure forward during steady
interaction. On Matrix-Game 2.0 and LingBot-World v1/v2, CtrlCache speeds up the DiT backbone by 1.21×–1.41× and
improves WBench Overall over original inference on all three models.

This repository hosts the project page. The method code will be released separately.

## Citation

```bibtex
@article{ctrlcache2026,
  title   = {CtrlCache: Accelerating Interactive Video World Models with Control-Aware Caching},
  author  = {Song, Shangye and Gong, Dong and Jia, Hong and Koh, Yun Sing and Zhang, Xinyu},
  journal = {arXiv preprint},
  year    = {2026}
}
```
