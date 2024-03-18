## Install

### Docker
```shell
docker pull dongjunku/humaninter:cu11
```

### Project Structure
Please organize your project in the following structure:
```bash
ContactGen
├── body_models
|   ├── smplx
|   |   ├── SMPLX_NEUTRAL.npz
|   |   ├── SMPLX_NEUTRAL.pkl
├── datasets
|   ├── chi3d
|   |   ├── train
|   ├── chi3d_whoisactor_v2.pkl
|   ├── contact_regions.json
|   ├── r_sym_pair.pkl
├── ci3d.py
├── loss.py
├── model.py
├── optimizer.py
├── params.py
├── sample.py
├── test_diffusion.py
├── test_guidenet.py
├── train_diffusion.py
├── train_guidenet.py
├── utils.py
```

you can get contact_regions.json from https://github.com/sminchisescu-research/imar_vision_datasets_tools/blob/main/info/contact_regions.json
