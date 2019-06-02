
[Published runs](../README.md)




# damsm:pretrain+gp



| ID                   | Operation           | Started                  | Time                | Status           | Label                |
| --                   | ---------           | ---------                | ----                | ------           | -----                |
| d5dd7016 | damsm:pretrain+gp | 2019&#8209;05&#8209;29 15:31:32 UTC | 0:00:47 | completed | &nbsp; |



[run.yml](run.yml)


## Contents

- [Flags](#flags)
- [Scalars](#scalars)
- [Run Files](#run-files)
- [Source Code](#source-code)
- [Output](#output)




## Flags

| Name | Value |
| ---- | ----- |
| acq-func | gp_hedge |
| kappa | 1.96 |
| noise | gaussian |
| random-starts | 0 |
| xi | 0.01 |

[flags.yml](flags.yml)




## Scalars

There are no scalars for this run.



## Run Files

| Path | Type | Size | Modified | MD5 |
| ---- | ---- | ---- | -------- | --- |
| d6337c36822611e9b16de4a471939b0d | dir link | 4.0K | 2019-05-29 10:31:34 UTC |  |
| d6337c36822611e9b16de4a471939b0d/cfg | dir link | 4.0K | 2019-05-24 18:40:10 UTC |  |
| d6337c36822611e9b16de4a471939b0d/cfg/DAMSM | dir | 4.0K | 2019-05-24 18:40:10 UTC |  |
| d6337c36822611e9b16de4a471939b0d/cfg/DAMSM/bird.yml | file | 569 | 2019-04-15 16:11:50 UTC | a89c7dd759a2dd29e0dfda78986d7c8f |
| d6337c36822611e9b16de4a471939b0d/cfg/DAMSM/coco.yml | file | 560 | 2019-05-11 17:45:45 UTC | e487ab3dad4178b9881c41365f2c90c3 |
| d6337c36822611e9b16de4a471939b0d/cfg/DAMSM/photosynthesis.yml | file | 711 | 2019-05-24 18:40:10 UTC | 8053d460a96460ff8f58c011e622e9e7 |
| d6337c36822611e9b16de4a471939b0d/cfg/bird_attn2.yml | file | 655 | 2019-04-15 16:11:50 UTC | 2722ade64f2320627552913bcf927f64 |
| d6337c36822611e9b16de4a471939b0d/cfg/bird_attnDCGAN2.yml | file | 678 | 2019-04-15 16:11:50 UTC | 179b045390fd4b34d575d1153666d4a9 |
| d6337c36822611e9b16de4a471939b0d/cfg/coco_attn2.yml | file | 675 | 2019-04-15 16:11:50 UTC | 580cac555983441a7f97ff883101cc4a |
| d6337c36822611e9b16de4a471939b0d/cfg/eval_bird.yml | file | 467 | 2019-05-11 17:45:45 UTC | c948d31c7a4497fefe037246aef35502 |
| d6337c36822611e9b16de4a471939b0d/cfg/eval_bird_attnDCGAN2.yml | file | 462 | 2019-04-15 16:11:50 UTC | 10caf4840bdad181c1c453fc8657ee5a |
| d6337c36822611e9b16de4a471939b0d/cfg/eval_coco.yml | file | 433 | 2019-04-15 16:11:50 UTC | d9947cab90b776834b8a88d635da3fea |
| d6337c36822611e9b16de4a471939b0d/cfg/eval_photosynthesis.yml | file | 684 | 2019-05-24 18:40:10 UTC | ac5cc38f4f70e18e0979385ce54979dd |
| d6337c36822611e9b16de4a471939b0d/cfg/photosynthesis_attn2.yml | file | 846 | 2019-05-24 18:40:10 UTC | 6d68c5f5bc00ee987b17f7d64d6a5f45 |
| d6337c36822611e9b16de4a471939b0d/output | dir | 4.0K | 2019-05-29 10:31:34 UTC |  |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34 | dir | 4.0K | 2019-05-29 10:31:34 UTC |  |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34/Image | dir | 4.0K | 2019-05-29 10:32:13 UTC |  |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34/Image/attention_maps0.png | file | 2.3M | 2019-05-29 10:32:14 UTC | 53e87e3f9ae6ee537422a87f83226df5 |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34/Model | dir | 4.0K | 2019-05-29 10:32:15 UTC |  |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34/Model/image_encoder0.pth | file | 94.3M | 2019-05-29 10:32:15 UTC | aba63c06704ff13e39d0f9611f3cd9d8 |
| d6337c36822611e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_10_31_34/Model/text_encoder0.pth | file | 13.0M | 2019-05-29 10:32:15 UTC | 239d6c507e8de9d88877672cc7711791 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis | dir link | 4.0K | 2019-05-29 10:40:11 UTC |  |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/captions.pickle | file | 7.5K | 2019-05-29 10:40:11 UTC | 59e6afe12e458a2b13307e30450cd86d |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/example_captions.txt | file | 215 | 2019-04-28 16:36:14 UTC | 25f5802a94725a302e91474eb94620a2 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/example_filenames.txt | file | 118 | 2019-04-30 14:54:24 UTC | cf9a3b2bce980c32eb69f3aacfc87ac1 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/filenames.txt | file | 118 | 2019-05-29 10:40:11 UTC | 45b4bdaa13571e90b331a28c25303b97 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images | dir | 4.0K | 2019-05-11 17:46:02 UTC |  |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_0.jpg | file | 6.7K | 2019-05-11 17:46:02 UTC | d2b19d30fef1ee6b69038f7b5c42473c |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_1.jpg | file | 29.9K | 2019-05-11 17:46:02 UTC | 08a829bb4ef302cdab53bb5bf3d03c78 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_2.jpg | file | 15.3K | 2019-05-11 17:46:02 UTC | 225ef20fe57d159c98d5e4796627b407 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_3.jpg | file | 18.2K | 2019-05-11 17:46:02 UTC | cacdacb56cfb25981f79734326d48f7c |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_4.jpg | file | 38.9K | 2019-05-11 17:46:02 UTC | a527227fdfc9304fac7c5cf35bbcd60f |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_5.jpg | file | 34.4K | 2019-05-11 17:46:02 UTC | dd56967d9f2b999f43c05fe2af7f504f |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/images/photosynthesis_6.jpg | file | 34.4K | 2019-05-11 17:46:02 UTC | dd56967d9f2b999f43c05fe2af7f504f |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/test | dir | 4.0K | 2019-05-29 10:40:11 UTC |  |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/test/filenames.pickle | file | 169 | 2019-05-29 10:40:11 UTC | 28d64193ad08c887b2968c9850ae6cbd |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text | dir | 4.0K | 2019-05-11 17:46:02 UTC |  |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_0.txt | file | 190 | 2019-05-11 17:46:02 UTC | 4d593f3823347899748f253742558cb1 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_1.txt | file | 75 | 2019-05-11 17:46:02 UTC | 8d411b026874ec0bbb0798607a5ab55b |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_2.txt | file | 147 | 2019-05-11 17:46:02 UTC | 03024adc72436cda286732abe2318ef5 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_3.txt | file | 2.8K | 2019-05-11 17:46:02 UTC | 5aedbf8904c5bde393829f78e45c1d9b |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_4.txt | file | 236 | 2019-05-11 17:46:02 UTC | 894d5eca3c23a13948beae3d4b5e2b91 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_5.txt | file | 749 | 2019-05-11 17:46:02 UTC | ff1f5e4ad6cc662e0b88b66cb7958031 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/text/photosynthesis_6.txt | file | 216 | 2019-05-11 17:46:02 UTC | 8691d253c0118707f4f80a7004aac4c6 |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/train | dir | 4.0K | 2019-05-29 10:40:11 UTC |  |
| d6337c36822611e9b16de4a471939b0d/photosynthesis/train/filenames.pickle | file | 169 | 2019-05-29 10:40:11 UTC | 28d64193ad08c887b2968c9850ae6cbd |
| d6337c37822611e9b16de4a471939b0d | link |  |  |  |

[runfiles.csv](runfiles.csv)




## Source Code

There are no source code files for this run.



## Output

```
INFO: [guild] Found 0 previous trial(s) for use in optimization
INFO: [guild] Initialized trial d6337c36 (batch_size=7, captions_per_image=1, delete_captions_pickle=yes, embedding_dim=1024, encoder_lr=0.0382, epochs=1, gamma2=51.1301, gamma3=26.8084, gpu=0, rnn_grad_clip=0.93, snapshot-interval=100, train_split=1.0, validation_split=1.0, words_num=244)
INFO: [guild] Running trial d6337c36: damsm:pretrain (batch_size=7, captions_per_image=1, delete_captions_pickle=yes, embedding_dim=1024, encoder_lr=0.0382, epochs=1, gamma2=51.1301, gamma3=26.8084, gpu=0, rnn_grad_clip=0.93, snapshot-interval=100, train_split=1.0, validation_split=1.0, words_num=244)
Resolving config dependency
Resolving data dependency
/home/garrett/SCM/AttnGAN/code/miscc/config.py:106: YAMLLoadWarning: calling yaml.load() without Loader=... is deprecated, as the default Loader is unsafe. Please read https://msg.pyyaml.org/load for full details.
  yaml_cfg = edict(yaml.load(f))
Using config:
{'B_VALIDATION': False,
 'CONFIG_NAME': 'DAMSM',
 'CUDA': True,
 'DATASET_NAME': 'photosynthesis',
 'DATA_DIR': 'photosynthesis',
 'GAN': {'B_ATTENTION': True,
         'B_DCGAN': False,
         'CONDITION_DIM': 100,
         'DF_DIM': 64,
         'GF_DIM': 128,
         'R_NUM': 2,
         'Z_DIM': 100},
 'GPU_ID': 0,
 'OUTPUT_DIR': 'output',
 'RNN_TYPE': 'LSTM',
 'TEXT': {'CAPTIONS_PER_IMAGE': 1, 'EMBEDDING_DIM': 1024, 'WORDS_NUM': 244},
INFO: [root] Number of text files: 7
 'TRAIN': {'BATCH_SIZE': 7,
           'B_NET_D': True,
           'DISCRIMINATOR_LR': 0.0002,
           'ENCODER_LR': 0.0382,
           'FLAG': True,
           'GENERATOR_LR': 0.0002,
           'MAX_EPOCH': 1,
           'NET_E': '',
           'NET_G': '',
           'RNN_GRAD_CLIP': 0.93,
           'SMOOTH': {'GAMMA1': 168.6969,
                      'GAMMA2': 51.1301,
                      'GAMMA3': 26.8084,
                      'LAMBDA': 1.0},
           'SNAPSHOT_INTERVAL': 100},
 'TRAIN_SPLIT': 1.0,
DEBUG: [root] Deleting file: photosynthesis/captions.pickle
 'TREE': {'BASE_SIZE': 5, 'BRANCH_NUM': 1},
 'VALIDATION_SPLIT': 1.0,
 'WORKERS': 1}
photosynthesis/filenames.txt
Number of Train files: 7
Number of Test files: 7
DEBUG: [root] splitType: test 
DEBUG: [root] Deleting file: photosynthesis/test/filenames.pickle
DEBUG: [root] Number of items in pickled list: 7
DEBUG: [root] splitType: train 
DEBUG: [root] Deleting file: photosynthesis/train/filenames.pickle
DEBUG: [root] Number of items in pickled list: 7
INFO: [root] FINISHED WRITING TEXT TO <<{'test': 'photosynthesis/test/filenames.pickle', 'train': 'photosynthesis/train/filenames.pickle'}>>
Split Directory: photosynthesis/train
DEBUG: [root] data_dir: photosynthesis
Load filenames from: photosynthesis/train/filenames.pickle (7)
Load filenames from: photosynthesis/test/filenames.pickle (7)
DEBUG: [root] Check if captions.pickle does not exists
Save to:  photosynthesis/captions.pickle
data_dir Directory: photosynthesis
DEBUG: [root] data_dir: photosynthesis
Number words: 244
Embedding Number: 1
Split Directory: photosynthesis/test
Load filenames from: photosynthesis/train/filenames.pickle (7)
Load filenames from: photosynthesis/test/filenames.pickle (7)
DEBUG: [root] Check if captions.pickle does not exists
Load from:  photosynthesis/captions.pickle
data_dir Directory: photosynthesis
DEBUG: [root] captions.pickle exists
DEBUG: [root] Loading pickle text file names: photosynthesis/captions.pickle
/home/garrett/SCM/AttnGAN/code/env/lib/python3.5/site-packages/torch/nn/modules/rnn.py:46: UserWarning: dropout option adds dropout after all but last recurrent layer, so non-zero dropout expects num_layers greater than 1, but got dropout=0.5 and num_layers=1
  "num_layers={}".format(dropout, num_layers))
Load pretrained model from  https://download.pytorch.org/models/inception_v3_google-1a9a5a14.pth
| epoch   0 |     0/    1 batches | ms/batch 29.47 | s_loss  0.01  0.01 | w_loss  0.13  0.06
att_sze equal to 17
DEBUG: [PIL.PngImagePlugin] STREAM b'IHDR' 16 13
DEBUG: [PIL.PngImagePlugin] STREAM b'IDAT' 41 1216
-----------------------------------------------------------------------------------------
| end epoch   0 | valid loss 421.61 25628.04 | lr 0.03820|
-----------------------------------------------------------------------------------------
Save G/Ds models.
INFO: [guild] Found 1 previous trial(s) for use in optimization
INFO: [guild] Initialized trial d6337c37 (batch_size=7.0, captions_per_image=1.0, delete_captions_pickle=1.0, embedding_dim=1024.0, encoder_lr=0.0382, epochs=1.0, gamma2=51.1301, gamma3=26.8084, gpu=0.0, rnn_grad_clip=0.93, snapshot-interval=100.0, train_split=1.0, validation_split=1.0, words_num=244.0)
INFO: [guild] Running trial d6337c37: damsm:pretrain (batch_size=7.0, captions_per_image=1.0, delete_captions_pickle=1.0, embedding_dim=1024.0, encoder_lr=0.0382, epochs=1.0, gamma2=51.1301, gamma3=26.8084, gpu=0.0, rnn_grad_clip=0.93, snapshot-interval=100.0, train_split=1.0, validation_split=1.0, words_num=244.0)
Resolving config dependency
Resolving data dependency
usage: pretrain_DAMSM.py [-h] [--cfg CFG_FILE] [--gpu GPU_ID]
                         [--data_dir DATA_DIR] [--output_dir OUTPUT_DIR]
                         [--manualSeed MANUALSEED] [--batch_size BATCH_SIZE]
                         [--delete_captions_pickle]
                         [--train_split TRAIN_SPLIT]
                         [--validation_split VALIDATION_SPLIT]
                         [--embedding_dim EMBEDDING_DIM]
                         [--captions_per_image CAPTIONS_PER_IMAGE]
                         [--words_num WORDS_NUM]
                         [--snapshot_interval SNAPSHOT_INTERVAL]
                         [--max_epoch MAX_EPOCH]
                         [--snapshot-interval SNAPSHOT_INTERVAL]
                         [--encoder_lr ENCODER_LR]
                         [--rnn_grad_clip RNN_GRAD_CLIP] [--gamma1 GAMMA1]
                         [--gamma2 GAMMA2] [--gamma3 GAMMA3]
pretrain_DAMSM.py: error: argument --batch_size: invalid int value: '7.0'
ERROR: [guild] Run d6337c37822611e9b16de4a471939b0d failed - see logs for details

```

[output.txt](output.txt)








