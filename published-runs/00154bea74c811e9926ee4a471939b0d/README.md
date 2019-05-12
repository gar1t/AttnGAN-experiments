[Published runs](../README.md)

# damsm:train

| ID                | Operation         | Started           | Duration           | Status           | Label           |
| --                | ---------         | ---------         | --------           | ------           | -----           |
| 00154bea | damsm:train | 2019-05-12 10:09:55 | 0:02:20 | completed |  |

## Flags

| Name | Value |
| ---- | ----- |
| captions_per_image | 1 |
| df_dim | 96 |
| discriminator_lr | 0.0002 |
| embedding_dim | 128 |
| epochs | 1 |
| gamma1 | 72.4953 |
| gamma2 | 65.3585 |
| gamma3 | 89.2507 |
| generator_lr | 0.0002 |
| gf_dim | 48 |
| lambda_a | 50 |
| r_num | 3 |
| words_num | 244 |
| z_dim | 100 |



## Scalars

There are no scalars for this run.

## Files

| File | Size | Modified |
| ---- | ---- | -------- |
| [output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD0.pth](./output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD0.pth) | 47.4M | 2019-05-12 15:12:13 UTC |
| [output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD1.pth](./output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD1.pth) | 159.9M | 2019-05-12 15:12:13 UTC |
| [output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD2.pth](./output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netD2.pth) | 610.0M | 2019-05-12 15:12:13 UTC |
| [output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netG_epoch_0.pth](./output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netG_epoch_0.pth) | 52.7M | 2019-05-12 15:12:12 UTC |
| [output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netG_epoch_1.pth](./output/photosynthesis_glu-gan2_2019_05_12_10_11_24/Model/netG_epoch_1.pth) | 52.7M | 2019-05-12 15:12:13 UTC |
| [pretrain/image_encoder0.pth](./pretrain/image_encoder0.pth) | link | 2019-05-12 15:09:47 UTC |
| [pretrain/text_encoder0.pth](./pretrain/text_encoder0.pth) | link | 2019-05-12 15:09:47 UTC |



## Images

There are no images for this run.

## Source

| File | Size | Modified |
| ---- | ---- | -------- |
| [.gitignore](.guild/source/.gitignore) | 45 | 2019-05-12 15:09:55 UTC |
| [GlobalAttention.py](.guild/source/GlobalAttention.py) | 4.0K | 2019-05-12 15:09:55 UTC |
| [__init__.py](.guild/source/__init__.py) | 0 | 2019-05-12 15:09:55 UTC |
| [cfg/DAMSM/bird.yml](.guild/source/cfg/DAMSM/bird.yml) | 569 | 2019-05-12 15:09:55 UTC |
| [cfg/DAMSM/coco.yml](.guild/source/cfg/DAMSM/coco.yml) | 560 | 2019-05-12 15:09:55 UTC |
| [cfg/DAMSM/photosynthesis.yml](.guild/source/cfg/DAMSM/photosynthesis.yml) | 740 | 2019-05-12 15:09:55 UTC |
| [cfg/bird_attn2.yml](.guild/source/cfg/bird_attn2.yml) | 655 | 2019-05-12 15:09:55 UTC |
| [cfg/bird_attnDCGAN2.yml](.guild/source/cfg/bird_attnDCGAN2.yml) | 678 | 2019-05-12 15:09:55 UTC |
| [cfg/coco_attn2.yml](.guild/source/cfg/coco_attn2.yml) | 675 | 2019-05-12 15:09:55 UTC |
| [cfg/eval_bird.yml](.guild/source/cfg/eval_bird.yml) | 467 | 2019-05-12 15:09:55 UTC |
| [cfg/eval_bird_attnDCGAN2.yml](.guild/source/cfg/eval_bird_attnDCGAN2.yml) | 462 | 2019-05-12 15:09:55 UTC |
| [cfg/eval_coco.yml](.guild/source/cfg/eval_coco.yml) | 433 | 2019-05-12 15:09:55 UTC |
| [cfg/eval_photosynthesis.yml](.guild/source/cfg/eval_photosynthesis.yml) | 504 | 2019-05-12 15:09:55 UTC |
| [cfg/photosynthesis_attn2.yml](.guild/source/cfg/photosynthesis_attn2.yml) | 787 | 2019-05-12 15:09:55 UTC |
| [datasets.py](.guild/source/datasets.py) | 12.1K | 2019-05-12 15:09:55 UTC |
| [get_model_data.py](.guild/source/get_model_data.py) | 431 | 2019-05-12 15:09:55 UTC |
| [guild.yml](.guild/source/guild.yml) | 3.4K | 2019-05-12 15:09:55 UTC |
| [main.py](.guild/source/main.py) | 8.1K | 2019-05-12 15:09:55 UTC |
| [miscc/__init__.py](.guild/source/miscc/__init__.py) | 70 | 2019-05-12 15:09:55 UTC |
| [miscc/config.py](.guild/source/miscc/config.py) | 2.6K | 2019-05-12 15:09:55 UTC |
| [miscc/losses.py](.guild/source/miscc/losses.py) | 7.9K | 2019-05-12 15:09:55 UTC |
| [miscc/prepareData_files.py](.guild/source/miscc/prepareData_files.py) | 4.5K | 2019-05-12 15:09:55 UTC |
| [miscc/utils.py](.guild/source/miscc/utils.py) | 12.0K | 2019-05-12 15:09:55 UTC |
| [model.py](.guild/source/model.py) | 21.5K | 2019-05-12 15:09:55 UTC |
| [pretrain_DAMSM.py](.guild/source/pretrain_DAMSM.py) | 13.8K | 2019-05-12 15:09:55 UTC |
| [requirements.txt](.guild/source/requirements.txt) | 87 | 2019-05-12 15:09:55 UTC |
| [trainer.py](.guild/source/trainer.py) | 23.2K | 2019-05-12 15:09:55 UTC |



## Attributes

| Name        | Value                 |
| -           | -                     |
| ID          | 00154bea74c811e9926ee4a471939b0d          |
| Model       | damsm       |
| Operation   | train     |
| Status      | completed      |
| Marked      | no      |
| Started     | 2019-05-12 10:09:55     |
| Stopped     | 2019-05-12 10:12:16     |
| Label       |        |
| Exit Status | 0 |
