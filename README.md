

<div align="center">
<h1>SD<sup>2</sup>-CFNet: Shared-Difference Disentangled Continuous Fusion Network for Multispectral Object Detection</h1>

</div>
<div>

<img src="Figure\Fig1.png" alt="fig1"  />

# The core innovation points of the paper

1.We propose a lightweight multispectral object detection framework, termed **SD<sup>2</sup>-CFNet**,  based on a progressive disentanglement-interaction-fusion paradigm.
    
2.We design a Shared-Difference Disentangled Interaction(SDDI) module to disentangle shared semantics from modality-specific discrepancies for more discriminative feature learning.
    
3.We develop a Multi-Scale Cross-Modal Mixture-of-Experts (MSCME)} module for scale-aware adaptive cross-modal interaction.
    
4.We introduce a Difference-aware Continuous Interpolation Fusion(DCIF) module  to achieve stable continuous fusion while mitigating modality conflicts.


# TODO List
- [x] Figure of results
- [ ] Code and datasets
- [ ] Release Code
- [ ] Inference code and checkpoint



# Core Module Description

<img src="Figure\Fig2.png" alt="fig2"  />

**The illustration of our designed modules.(a) is the brightness prior learning, (b) is the case 2 of CBGA, (c) is the case 3 of CBGA, and (d) is the APSF**





# Result

<img src="Figure\Fig3.png" alt="fig3"  />

 **Visual comparisons of different approaches on the DroneVehicle, RGBTDronePerson, M3FD and FLIR datasets**





<img src="Figure\Fig4.png" alt="fig3"  />

**The visual comparisons of ours and MIR on four datasets**

#  Citation
If you find this codebase useful for your research, please cite as follows:
```
@article{song2025,
  title={How Local Details Meet Global Structures: A Parallel Multi-Scale Dual-Branch Network for Low-Light Image Enhancement},
  author={Song,jiayin and Zhang, Kaibing and Li, yingjian et al.},
  journal={IEEE TRANSACTIONS ON MULTIMEDIA},
  year={2025}
}
```
