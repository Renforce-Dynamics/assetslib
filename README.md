# Mujoco_Sim2Sim_Assets
[![Isaac Lab](https://img.shields.io/badge/IsaacLab-2.2.0-silver)](https://isaac-sim.github.io/IsaacLab)
[![Isaac Lab](https://img.shields.io/badge/IsaacLab-2.1.1-silver)](https://isaac-sim.github.io/IsaacLab)
[![MuJoCo](https://img.shields.io/badge/MuJoCo-3.x-blue.svg)](https://mujoco.org/)

This repository is used for Isaaclab training and Sim2Sim deployment (Mujoco), with all assets (urdf, mjcf, usd) aligned.

Our goal is to provide anyone involved in robot development with proven assets to ensure that the program implements the complete workflow of Sim2Sim2Real.


## Assets Structure

```
assets/
├── unitree_go2
│   ├── meshes
│   ├── mjcf
│   ├── urdf
│   └── usd
├── ...
│   ├── meshes
...
```

## Support List

<table>
  <tr>
    <td colspan="3"> Robot </td>
    <td colspan="4"> Assets </td>
    <td colspan="2"> Align Test </td>
  </tr>
  <tr>
    <td> robots dir </td>
    <td> robots name </td>
    <td> usd name </td>
    <td> meshes </td>
    <td> urdf </td>
    <td> mjcf </td>
    <td> usd </td>
    <td> Isaaclab </td>
    <td> Mujoco </td>
  </tr>
  <tr>
    <td> unitree_go2 </td>
    <td> unitree_go2 </td>
    <td> go2.usd </td>
    <td> ✅ </td>
    <td> ❌ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
  </tr>
  <tr>
    <td rowspan="2">unitree_g1</td>
    <td> unitree_g1_29dof </td>
    <td> g1_29dof_rev_1_0.usd </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
  </tr>
  <tr>
    <td> unitree_g1_23dof </td>
    <td> g1_23dof_rev_1_0.usd </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
  </tr>
  <tr>
    <td> pi_plus </td>
    <td> pi_plus_21dof </td>
    <td> pi_plus_21dof.usd </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td>  </td>
  </tr>
  <tr>
    <td> booster_k1 </td>
    <td> K1_serial </td>
    <td> K1_serial_rev.usd </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td>  </td>
  </tr>
  <tr>
    <td> unitree_go2w </td>
    <td> unitree_go2w </td>
    <td> go2w.usd </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td> ✅ </td>
    <td>  </td>
    <td>  </td>
  </tr>
  <tr>
    <td> unitree_h1 </td>
    <td> unitree_h1 </td>
    <td> h1.usd </td>
    <td>  </td>
    <td>  </td>
    <td>  </td>
    <td> ✅ </td>
    <td>  </td>
    <td>  </td>
  </tr>
  <tr>
    <td> smplx_humanoid </td>
    <td> smplx_humanoid </td>
    <td> smplx_humanoid.usd </td>
    <td>  </td>
    <td>  </td>
    <td> ✅ </td>
    <td> ✅ </td>
    <td>  </td>
    <td>  </td>
  </tr>
</table>



## Contribution

Welcome to contribute aligned robot assets to us, and we will provide documents to verify alignment in the future.

## Acknowledgement

Our assets come from multiple open source repositories, thanks to these repositories for their open source support.

The original robot models can be found at the following locations:

- [mujoco_menagerie](https://github.com/google-deepmind/mujoco_menagerie/tree/main): mjcf files for position actuator. 
- [unitree_model](https://huggingface.co/datasets/unitreerobotics/unitree_model/tree/main): unitree robots usd files.
