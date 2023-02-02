## Sample Solution for Low Power Computer Vision Challenge 2023
## Training for TDNet

### 1. Prepare Data
Download and save the training/validation data [G-Drive](https://drive.google.com/file/d/1MZhohaJHxvDbcGMMDn2CPGtaH1uyxyW6/view?usp=sharing). 

### 2. Modify Codes
Modify `*.yml` files in `./config`
* ''data:path'': path to dataset 
* ''training:batch_size'': batch_size
* ''training:train_augmentations:rcrop'': input size for training

### 3. Training
Run
```bash
python train.py --config configs/*.yml
```

### 4. Sample Solution

Taining log for the sample solution is provided in `sample_solution/runs/FA_Res18/86059/run_2023_01_18_17_48_22.log`
