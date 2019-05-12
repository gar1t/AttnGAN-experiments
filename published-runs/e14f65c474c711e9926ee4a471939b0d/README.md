[Published runs](../README.md)

# damsm:pretrain

| ID                | Operation         | Started           | Duration           | Status           | Label           |
| --                | ---------         | ---------         | --------           | ------           | -----           |
| e14f65c4 | damsm:pretrain | 2019-05-12 10:09:03 | 0:00:44 | completed |  |

## Flags

| Name | Value |
| ---- | ----- |
| captions_per_image | 1 |
| embedding_dim | 128 |
| encoder_lr | 0.003189 |
| epochs | 1 |
| gamma1 | 72.4953 |
| gamma2 | 65.3585 |
| gamma3 | 89.2507 |
| rnn_grad_clip | 2.0 |
| words_num | 244 |



## Scalars

| Key | Step | Value |
| --- | ---- | ----- |
| s_loss | 0 | 18.209999084472656 |
| w_loss | 0 | 708.5700073242188 |



## Files

| File | Size | Modified |
| ---- | ---- | -------- |
| [output/photosynthesis_DAMSM_2019_05_12_10_09_27/Image/attention_maps0.png](./output/photosynthesis_DAMSM_2019_05_12_10_09_27/Image/attention_maps0.png) | 1.3M | 2019-05-12 15:09:47 UTC |
| [output/photosynthesis_DAMSM_2019_05_12_10_09_27/Model/image_encoder0.pth](./output/photosynthesis_DAMSM_2019_05_12_10_09_27/Model/image_encoder0.pth) | 84.7M | 2019-05-12 15:09:47 UTC |
| [output/photosynthesis_DAMSM_2019_05_12_10_09_27/Model/text_encoder0.pth](./output/photosynthesis_DAMSM_2019_05_12_10_09_27/Model/text_encoder0.pth) | 1019.3K | 2019-05-12 15:09:47 UTC |



## Images

![](./output/photosynthesis_DAMSM_2019_05_12_10_09_27/Image/attention_maps0.png)

[output/photosynthesis_DAMSM_2019_05_12_10_09_27/Image/attention_maps0.png (1.3M)](./output/photosynthesis_DAMSM_2019_05_12_10_09_27/Image/attention_maps0.png)



## Source

| File | Size | Modified |
| ---- | ---- | -------- |
| [.gitignore](.guild/source/.gitignore) | 45 | 2019-05-12 15:09:03 UTC |
| [GlobalAttention.py](.guild/source/GlobalAttention.py) | 4.0K | 2019-05-12 15:09:03 UTC |
| [__init__.py](.guild/source/__init__.py) | 0 | 2019-05-12 15:09:03 UTC |
| [cfg/DAMSM/bird.yml](.guild/source/cfg/DAMSM/bird.yml) | 569 | 2019-05-12 15:09:03 UTC |
| [cfg/DAMSM/coco.yml](.guild/source/cfg/DAMSM/coco.yml) | 560 | 2019-05-12 15:09:03 UTC |
| [cfg/DAMSM/photosynthesis.yml](.guild/source/cfg/DAMSM/photosynthesis.yml) | 740 | 2019-05-12 15:09:03 UTC |
| [cfg/bird_attn2.yml](.guild/source/cfg/bird_attn2.yml) | 655 | 2019-05-12 15:09:03 UTC |
| [cfg/bird_attnDCGAN2.yml](.guild/source/cfg/bird_attnDCGAN2.yml) | 678 | 2019-05-12 15:09:03 UTC |
| [cfg/coco_attn2.yml](.guild/source/cfg/coco_attn2.yml) | 675 | 2019-05-12 15:09:03 UTC |
| [cfg/eval_bird.yml](.guild/source/cfg/eval_bird.yml) | 467 | 2019-05-12 15:09:03 UTC |
| [cfg/eval_bird_attnDCGAN2.yml](.guild/source/cfg/eval_bird_attnDCGAN2.yml) | 462 | 2019-05-12 15:09:03 UTC |
| [cfg/eval_coco.yml](.guild/source/cfg/eval_coco.yml) | 433 | 2019-05-12 15:09:03 UTC |
| [cfg/eval_photosynthesis.yml](.guild/source/cfg/eval_photosynthesis.yml) | 504 | 2019-05-12 15:09:03 UTC |
| [cfg/photosynthesis_attn2.yml](.guild/source/cfg/photosynthesis_attn2.yml) | 787 | 2019-05-12 15:09:03 UTC |
| [datasets.py](.guild/source/datasets.py) | 12.1K | 2019-05-12 15:09:03 UTC |
| [get_model_data.py](.guild/source/get_model_data.py) | 431 | 2019-05-12 15:09:03 UTC |
| [guild.yml](.guild/source/guild.yml) | 3.4K | 2019-05-12 15:09:03 UTC |
| [main.py](.guild/source/main.py) | 8.1K | 2019-05-12 15:09:03 UTC |
| [miscc/__init__.py](.guild/source/miscc/__init__.py) | 70 | 2019-05-12 15:09:03 UTC |
| [miscc/config.py](.guild/source/miscc/config.py) | 2.6K | 2019-05-12 15:09:03 UTC |
| [miscc/losses.py](.guild/source/miscc/losses.py) | 7.9K | 2019-05-12 15:09:03 UTC |
| [miscc/prepareData_files.py](.guild/source/miscc/prepareData_files.py) | 4.5K | 2019-05-12 15:09:03 UTC |
| [miscc/utils.py](.guild/source/miscc/utils.py) | 12.0K | 2019-05-12 15:09:03 UTC |
| [model.py](.guild/source/model.py) | 21.5K | 2019-05-12 15:09:03 UTC |
| [pretrain_DAMSM.py](.guild/source/pretrain_DAMSM.py) | 13.8K | 2019-05-12 15:09:03 UTC |
| [requirements.txt](.guild/source/requirements.txt) | 87 | 2019-05-12 15:09:03 UTC |
| [trainer.py](.guild/source/trainer.py) | 23.2K | 2019-05-12 15:09:03 UTC |



## Attributes

| Name        | Value                 |
| -           | -                     |
| ID          | e14f65c474c711e9926ee4a471939b0d          |
| Model       | damsm       |
| Operation   | pretrain     |
| Status      | completed      |
| Marked      | no      |
| Started     | 2019-05-12 10:09:03     |
| Stopped     | 2019-05-12 10:09:48     |
| Label       |        |
| Exit Status | 0 |
