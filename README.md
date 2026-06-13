# Loss Landscape of Transformer Architechture

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Egor Petrov </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Nikita Kiselev </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Andrey Grabovoy, PhD </td>
    </tr>
</table>

## Assets

- [Code](code)
- [Paper](thesis)
- [Slides](slides)

## Abstract

The lack of theoretical results for Layer Normalization and feedforward Hessians
has left a gap in the study of Transformer optimization landscapes. We address
this by deriving explicit second-order expressions for these components, thereby
completing the Hessian characterization of full Transformer blocks. Our results
generalize prior self-attention analyses and yield estimations for the role of each
sublayer in curvature propagation. We demonstrate how these Hessian structures
inform both convergence dynamics and the empirical scaling laws governing largemodel performance. 
Further, we propose a Taylor-expansion–based framework 
for analyzing loss differences to quantify convergence trajectories. By extending
Hessian theory to the full Transformer architecture, this work establishes a new
foundation for theoretical and empirical investigations of optimization in large-scale
deep learning.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@misc{petrov2025closingcurvaturegaptransformer,
      title={Closing the Curvature Gap: Full Transformer Hessians and Their Implications for Scaling Laws}, 
      author={Egor Petrov and Nikita Kiselev and Vladislav Meshkov and Andrey Grabovoy},
      year={2025},
      eprint={2510.16927},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.16927}, 
}
```
