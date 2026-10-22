# SAGE project page

Source of the project page of **SAGE: A hybrid vision–language and geometry framework for work-zone pathway prediction under temporary traffic control**.

Jiaxi Liu, Keshu Wu, Weizhe Tang, Bofeng Cao, Sikai Chen, Xiaopeng Li, Steven T. Parker, Bin Ran — University of Wisconsin–Madison (corresponding author: Keshu Wu)

Live page: https://hhjj233.github.io/SAGE-page/

SAGE (Semantic-to-Action Grounded Execution) predicts the path of an automated vehicle through road work zones under temporary traffic control: a geometric generator proposes intact candidate paths, a vision–language model's trajectory re-ranks them as an opinion, and checks derived from the Manual on Uniform Traffic Control Devices (MUTCD) bound the final choice. It is evaluated on the ROADWork benchmark. SAGE here names this work-zone framework; it is unrelated to GraphSAGE and to other methods called SAGE.

A plain-text summary for language models: [`llms.txt`](llms.txt) (served at https://hhjj233.github.io/SAGE-page/llms.txt).

Paper link: to be added.

Citation:

```bibtex
@misc{liu2026sage,
  title  = {{SAGE}: A hybrid vision--language and geometry framework for
            work-zone pathway prediction under temporary traffic control},
  author = {Liu, Jiaxi and Wu, Keshu and Tang, Weizhe and Cao, Bofeng and Chen, Sikai and Li, Xiaopeng and Parker, Steven T. and Ran, Bin},
  year   = {2026}
}
```

The page is a static site (`index.html` and `static/`). To view it locally, run `python -m http.server` in this folder and open `http://localhost:8000`. The code link will be added when it is released.

Camera frames come from the ROADWork dataset (Ghosh et al., ICCV 2025). The videos, the bird's-eye viewer, and the figures show stored outputs of the evaluated system on validation frames. The page layout follows the [Nerfies](https://github.com/nerfies/nerfies.github.io) project-page template (CC BY-SA 4.0).
