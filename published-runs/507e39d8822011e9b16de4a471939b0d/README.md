
[Published runs](../README.md)




# damsm:pretrain+gp



| ID                   | Operation           | Started                  | Duration                | Status           | Label                |
| --                   | ---------           | ---------                | --------                | ------           | -----                |
| 507e39d8 | damsm:pretrain+gp | 2019&#8209;05&#8209;29 14:44:51 UTC | &nbsp; | completed | &nbsp; |



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
| 515966ca822011e9b16de4a471939b0d | dir link | 4.0K | 2019-05-29 09:45:47 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild | dir | 4.0K | 2019-05-29 09:47:35 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs | dir | 4.0K | 2019-05-29 09:47:35 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/_flag_map | file | 18 | 2019-05-29 09:45:42 UTC | cc526aff6c4ffa08516cfdc4e1470cf3 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/batch | file | 33 | 2019-05-29 09:45:41 UTC | 74304c57217b4d569be818a5119e065e |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/cmd | file | 546 | 2019-05-29 09:45:42 UTC | b1514c5b5d2c9b0475cce8edf55ed6f9 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/deps | file | 99 | 2019-05-29 09:45:42 UTC | 703daacb192911ec8ecd52a8920bfa5e |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/env | file | 4.4K | 2019-05-29 09:45:42 UTC | 3d0c754c129aafe5d802aaa15e1a64b0 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/exit_status | file | 2 | 2019-05-29 09:47:35 UTC | 897316929176464ebc9ad085f31e7284 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/flags | file | 267 | 2019-05-29 09:45:42 UTC | d4b23421c7b1b4a53509fe379d4eabd0 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/host | file | 6 | 2019-05-29 09:45:42 UTC | 73a548c246139510e6e6df34ed023b70 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/id | file | 6 | 2019-05-29 09:44:51 UTC | 70cb886733059df7a7e1513a7fa71167 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/initialized | file | 17 | 2019-05-29 09:45:41 UTC | 25d15eb2758b73fec157235e0794b7d5 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/label | file | 242 | 2019-05-29 09:45:42 UTC | b2afe6b3f7fdf466e10a5fd881e88062 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/max_trials | file | 2 | 2019-05-29 09:45:42 UTC | 26ab0db90d72e28ad0ba1e22ee510510 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/objective | file | 7 | 2019-05-29 09:45:42 UTC | 0ad3f075a4d6508d319700a6d0cc20aa |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/opdef | file | 645 | 2019-05-29 09:45:42 UTC | 1aeaf06bb61f46b874b03542c46056a6 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/optimizer | file | 9 | 2019-05-29 09:44:51 UTC | 14ee7cec0d905746f0a61b231a0f673a |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/random_seed | file | 11 | 2019-05-29 09:45:42 UTC | a8a95c6dbf39110ce3384a6fbfe26193 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/run_params | file | 1.0K | 2019-05-29 09:45:42 UTC | 65b985a165b609ff8c220462101ade9a |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/started | file | 17 | 2019-05-29 09:45:42 UTC | ff5360a61d1deccf212fd52d0e3e7823 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/stopped | file | 17 | 2019-05-29 09:47:35 UTC | 025362ec650fe0579d08a3571830dcf7 |
| 515966ca822011e9b16de4a471939b0d/.guild/attrs/user | file | 8 | 2019-05-29 09:45:42 UTC | d4c03030439d2dbc19fa339d84ffd1fb |
| 515966ca822011e9b16de4a471939b0d/.guild/events.out.tfevents.1559141254.omaha | file | 109 | 2019-05-29 09:47:34 UTC | cd5c2408c9e4483df865b57021eeb320 |
| 515966ca822011e9b16de4a471939b0d/.guild/opref | file | 98 | 2019-05-29 09:45:42 UTC | 1dff57b401b224aa594844635dca3cfe |
| 515966ca822011e9b16de4a471939b0d/.guild/output | file | 3.5K | 2019-05-29 09:47:34 UTC | 32bbf00d1deadc93665a1867595eedd3 |
| 515966ca822011e9b16de4a471939b0d/.guild/output.index | file | 711 | 2019-05-29 09:47:34 UTC | 25a9fa8b12fc2d8c71aff9a48f0a23b2 |
| 515966ca822011e9b16de4a471939b0d/.guild/source | dir | 4.0K | 2019-05-29 09:45:41 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/source/.gitignore | file | 45 | 2019-05-29 09:45:42 UTC | b906f3f8c658d719e59a1f427603edc6 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/GlobalAttention.py | file | 4.0K | 2019-05-29 09:45:42 UTC | 60e7482314e07ac757bb2147ea5cce24 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/README.md | file | 197 | 2019-05-29 09:45:42 UTC | ce9db08abe616a8858e86eff578b49ec |
| 515966ca822011e9b16de4a471939b0d/.guild/source/__init__.py | file | 0 | 2019-05-29 09:45:42 UTC | d41d8cd98f00b204e9800998ecf8427e |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg | dir | 4.0K | 2019-05-29 09:45:41 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/DAMSM | dir | 4.0K | 2019-05-29 09:45:41 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/DAMSM/bird.yml | file | 569 | 2019-05-29 09:45:42 UTC | a89c7dd759a2dd29e0dfda78986d7c8f |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/DAMSM/coco.yml | file | 560 | 2019-05-29 09:45:42 UTC | e487ab3dad4178b9881c41365f2c90c3 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/DAMSM/photosynthesis.yml | file | 711 | 2019-05-29 09:45:42 UTC | 8053d460a96460ff8f58c011e622e9e7 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/bird_attn2.yml | file | 655 | 2019-05-29 09:45:42 UTC | 2722ade64f2320627552913bcf927f64 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/bird_attnDCGAN2.yml | file | 678 | 2019-05-29 09:45:42 UTC | 179b045390fd4b34d575d1153666d4a9 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/coco_attn2.yml | file | 675 | 2019-05-29 09:45:42 UTC | 580cac555983441a7f97ff883101cc4a |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/eval_bird.yml | file | 467 | 2019-05-29 09:45:42 UTC | c948d31c7a4497fefe037246aef35502 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/eval_bird_attnDCGAN2.yml | file | 462 | 2019-05-29 09:45:42 UTC | 10caf4840bdad181c1c453fc8657ee5a |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/eval_coco.yml | file | 433 | 2019-05-29 09:45:42 UTC | d9947cab90b776834b8a88d635da3fea |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/eval_photosynthesis.yml | file | 684 | 2019-05-29 09:45:42 UTC | ac5cc38f4f70e18e0979385ce54979dd |
| 515966ca822011e9b16de4a471939b0d/.guild/source/cfg/photosynthesis_attn2.yml | file | 846 | 2019-05-29 09:45:42 UTC | 6d68c5f5bc00ee987b17f7d64d6a5f45 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/datasets.py | file | 12.1K | 2019-05-29 09:45:42 UTC | c4aa7379f88a5564030dc3f78298d004 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/get_model_data.py | file | 431 | 2019-05-29 09:45:42 UTC | 5da898cfefdb8a4a1813de524b1aa7a8 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/guild.yml | file | 6.1K | 2019-05-29 09:45:42 UTC | 34573952d9d9affab0c04f2f726c2d7a |
| 515966ca822011e9b16de4a471939b0d/.guild/source/main.py | file | 8.4K | 2019-05-29 09:45:42 UTC | f89163f9003f229025d9b0a273590219 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc | dir | 4.0K | 2019-05-29 09:45:41 UTC |  |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc/__init__.py | file | 70 | 2019-05-29 09:45:42 UTC | dc923e6b5aba4ba41ffdcbedefc6dd47 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc/config.py | file | 2.6K | 2019-05-29 09:45:42 UTC | 531d44cd91926036e1078a9596581b67 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc/losses.py | file | 7.9K | 2019-05-29 09:45:42 UTC | fb353760434bd3ed770a82008d967039 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc/prepareData_files.py | file | 4.5K | 2019-05-29 09:45:42 UTC | da4e1e51b37d06a897e51115e5d9ad47 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/miscc/utils.py | file | 12.0K | 2019-05-29 09:45:42 UTC | eeb9508226f4d51a83e81da8553b8230 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/model.py | file | 21.5K | 2019-05-29 09:45:42 UTC | b2a85fb5ad388e6fa14847efde159390 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/pretrain_DAMSM.py | file | 14.1K | 2019-05-29 09:45:42 UTC | cd0a2e7bcb22c4a242cae2419f92e2ce |
| 515966ca822011e9b16de4a471939b0d/.guild/source/requirements.txt | file | 87 | 2019-05-29 09:45:42 UTC | a79c71319a4274bcd10201295c6afd25 |
| 515966ca822011e9b16de4a471939b0d/.guild/source/trainer.py | file | 23.3K | 2019-05-29 09:45:42 UTC | 16fbb67d6f4b218f722625e9fb21ddc9 |
| 515966ca822011e9b16de4a471939b0d/cfg | dir link | 4.0K | 2019-05-24 18:40:10 UTC |  |
| 515966ca822011e9b16de4a471939b0d/cfg/DAMSM | dir | 4.0K | 2019-05-24 18:40:10 UTC |  |
| 515966ca822011e9b16de4a471939b0d/cfg/DAMSM/bird.yml | file | 569 | 2019-04-15 16:11:50 UTC | a89c7dd759a2dd29e0dfda78986d7c8f |
| 515966ca822011e9b16de4a471939b0d/cfg/DAMSM/coco.yml | file | 560 | 2019-05-11 17:45:45 UTC | e487ab3dad4178b9881c41365f2c90c3 |
| 515966ca822011e9b16de4a471939b0d/cfg/DAMSM/photosynthesis.yml | file | 711 | 2019-05-24 18:40:10 UTC | 8053d460a96460ff8f58c011e622e9e7 |
| 515966ca822011e9b16de4a471939b0d/cfg/bird_attn2.yml | file | 655 | 2019-04-15 16:11:50 UTC | 2722ade64f2320627552913bcf927f64 |
| 515966ca822011e9b16de4a471939b0d/cfg/bird_attnDCGAN2.yml | file | 678 | 2019-04-15 16:11:50 UTC | 179b045390fd4b34d575d1153666d4a9 |
| 515966ca822011e9b16de4a471939b0d/cfg/coco_attn2.yml | file | 675 | 2019-04-15 16:11:50 UTC | 580cac555983441a7f97ff883101cc4a |
| 515966ca822011e9b16de4a471939b0d/cfg/eval_bird.yml | file | 467 | 2019-05-11 17:45:45 UTC | c948d31c7a4497fefe037246aef35502 |
| 515966ca822011e9b16de4a471939b0d/cfg/eval_bird_attnDCGAN2.yml | file | 462 | 2019-04-15 16:11:50 UTC | 10caf4840bdad181c1c453fc8657ee5a |
| 515966ca822011e9b16de4a471939b0d/cfg/eval_coco.yml | file | 433 | 2019-04-15 16:11:50 UTC | d9947cab90b776834b8a88d635da3fea |
| 515966ca822011e9b16de4a471939b0d/cfg/eval_photosynthesis.yml | file | 684 | 2019-05-24 18:40:10 UTC | ac5cc38f4f70e18e0979385ce54979dd |
| 515966ca822011e9b16de4a471939b0d/cfg/photosynthesis_attn2.yml | file | 846 | 2019-05-24 18:40:10 UTC | 6d68c5f5bc00ee987b17f7d64d6a5f45 |
| 515966ca822011e9b16de4a471939b0d/output | dir | 4.0K | 2019-05-29 09:45:47 UTC |  |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47 | dir | 4.0K | 2019-05-29 09:45:47 UTC |  |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47/Image | dir | 4.0K | 2019-05-29 09:47:27 UTC |  |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47/Image/attention_maps0.png | file | 2.2M | 2019-05-29 09:47:32 UTC | 53502bcc21d801c56981a42b9e6b379a |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47/Model | dir | 4.0K | 2019-05-29 09:47:34 UTC |  |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47/Model/image_encoder0.pth | file | 94.3M | 2019-05-29 09:47:34 UTC | 39347e96de55f16fb0bdeee2646ea6f6 |
| 515966ca822011e9b16de4a471939b0d/output/photosynthesis_DAMSM_2019_05_29_09_45_47/Model/text_encoder0.pth | file | 13.0M | 2019-05-29 09:47:34 UTC | a2acec3f8916c5354a1a486eeca271cb |
| 515966ca822011e9b16de4a471939b0d/photosynthesis | dir link | 4.0K | 2019-05-29 10:40:11 UTC |  |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/captions.pickle | file | 7.5K | 2019-05-29 10:40:11 UTC | 59e6afe12e458a2b13307e30450cd86d |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/example_captions.txt | file | 215 | 2019-04-28 16:36:14 UTC | 25f5802a94725a302e91474eb94620a2 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/example_filenames.txt | file | 118 | 2019-04-30 14:54:24 UTC | cf9a3b2bce980c32eb69f3aacfc87ac1 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/filenames.txt | file | 118 | 2019-05-29 10:40:11 UTC | 45b4bdaa13571e90b331a28c25303b97 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images | dir | 4.0K | 2019-05-11 17:46:02 UTC |  |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_0.jpg | file | 6.7K | 2019-05-11 17:46:02 UTC | d2b19d30fef1ee6b69038f7b5c42473c |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_1.jpg | file | 29.9K | 2019-05-11 17:46:02 UTC | 08a829bb4ef302cdab53bb5bf3d03c78 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_2.jpg | file | 15.3K | 2019-05-11 17:46:02 UTC | 225ef20fe57d159c98d5e4796627b407 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_3.jpg | file | 18.2K | 2019-05-11 17:46:02 UTC | cacdacb56cfb25981f79734326d48f7c |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_4.jpg | file | 38.9K | 2019-05-11 17:46:02 UTC | a527227fdfc9304fac7c5cf35bbcd60f |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_5.jpg | file | 34.4K | 2019-05-11 17:46:02 UTC | dd56967d9f2b999f43c05fe2af7f504f |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/images/photosynthesis_6.jpg | file | 34.4K | 2019-05-11 17:46:02 UTC | dd56967d9f2b999f43c05fe2af7f504f |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/test | dir | 4.0K | 2019-05-29 10:40:11 UTC |  |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/test/filenames.pickle | file | 169 | 2019-05-29 10:40:11 UTC | 28d64193ad08c887b2968c9850ae6cbd |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text | dir | 4.0K | 2019-05-11 17:46:02 UTC |  |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_0.txt | file | 190 | 2019-05-11 17:46:02 UTC | 4d593f3823347899748f253742558cb1 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_1.txt | file | 75 | 2019-05-11 17:46:02 UTC | 8d411b026874ec0bbb0798607a5ab55b |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_2.txt | file | 147 | 2019-05-11 17:46:02 UTC | 03024adc72436cda286732abe2318ef5 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_3.txt | file | 2.8K | 2019-05-11 17:46:02 UTC | 5aedbf8904c5bde393829f78e45c1d9b |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_4.txt | file | 236 | 2019-05-11 17:46:02 UTC | 894d5eca3c23a13948beae3d4b5e2b91 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_5.txt | file | 749 | 2019-05-11 17:46:02 UTC | ff1f5e4ad6cc662e0b88b66cb7958031 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/text/photosynthesis_6.txt | file | 216 | 2019-05-11 17:46:02 UTC | 8691d253c0118707f4f80a7004aac4c6 |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/train | dir | 4.0K | 2019-05-29 10:40:11 UTC |  |
| 515966ca822011e9b16de4a471939b0d/photosynthesis/train/filenames.pickle | file | 169 | 2019-05-29 10:40:11 UTC | 28d64193ad08c887b2968c9850ae6cbd |
| 515966cb822011e9b16de4a471939b0d | link |  |  |  |

[runfiles.csv](runfiles.csv)




## Source Code

There are no source code files for this run.



## Output

```
INFO: [guild] Found 0 previous trial(s) for use in optimization
> /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(42)_init_trial()
-> res = util.log_apply(
(Pdb)  37  	
 38  	def _init_trial(trial, state):
 39  	    import skopt
 40  	    random_starts, x0, y0, dims = state.minimize_inputs(trial.run_id)
 41  	    import pdb;pdb.set_trace()
 42  ->	    res = util.log_apply(
 43  	        skopt.gp_minimize,
 44  	        lambda *args: 0,
 45  	        dims,
 46  	        n_calls=1,
 47  	        n_random_starts=random_starts,
(Pdb) [[7], [1], [True], [1024], [0.0382], [1], [51.1301], [26.8084], [0], [0.93], [100], [1.0], [1.0], [244]]
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(43)_init_trial()
-> skopt.gp_minimize,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(44)_init_trial()
-> lambda *args: 0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(45)_init_trial()
-> dims,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(46)_init_trial()
-> n_calls=1,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(47)_init_trial()
-> n_random_starts=random_starts,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(48)_init_trial()
-> x0=x0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(49)_init_trial()
-> y0=y0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(50)_init_trial()
-> random_state=state.random_state,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(51)_init_trial()
-> acq_func=state.batch_flags["acq-func"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(52)_init_trial()
-> kappa=state.batch_flags["kappa"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(53)_init_trial()
-> xi=state.batch_flags["xi"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(54)_init_trial()
-> noise=state.batch_flags["noise"])
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(55)_init_trial()
-> state.random_state = res.random_state
(Pdb)  50  	        random_state=state.random_state,
 51  	        acq_func=state.batch_flags["acq-func"],
 52  	        kappa=state.batch_flags["kappa"],
 53  	        xi=state.batch_flags["xi"],
 54  	        noise=state.batch_flags["noise"])
 55  ->	    state.random_state = res.random_state
 56  	    return skopt_util.trial_flags(state.flag_names, res.x_iters[-1])
 57  	
 58  	if __name__ == "__main__":
 59  	    skopt_util.default_main(_init_trial)
[EOF]
(Pdb) [7, 1, True, 1024, 0.0382, 1, 51.1301, 26.8084, 0, 0.93, 100, 1.0, 1.0, 244]
INFO: [guild] Initialized trial 515966ca (batch_size=7, captions_per_image=1, delete_captions_pickle=yes, embedding_dim=1024, encoder_lr=0.0382, epochs=1, gamma2=51.1301, gamma3=26.8084, gpu=0, rnn_grad_clip=0.93, snapshot-interval=100, train_split=1.0, validation_split=1.0, words_num=244)
INFO: [guild] Running trial 515966ca: damsm:pretrain (batch_size=7, captions_per_image=1, delete_captions_pickle=yes, embedding_dim=1024, encoder_lr=0.0382, epochs=1, gamma2=51.1301, gamma3=26.8084, gpu=0, rnn_grad_clip=0.93, snapshot-interval=100, train_split=1.0, validation_split=1.0, words_num=244)
Resolving config dependency
Resolving data dependency
/home/garrett/SCM/AttnGAN/code/miscc/config.py:106: YAMLLoadWarning: calling yaml.load() without Loader=... is deprecated, as the default Loader is unsafe. Please read https://msg.pyyaml.org/load for full details.
  yaml_cfg = edict(yaml.load(f))
(Pdb) Using config:
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
INFO: [root] Number of text files: 7
DEBUG: [root] Deleting file: photosynthesis/captions.pickle
DEBUG: [root] splitType: test 
DEBUG: [root] Deleting file: photosynthesis/test/filenames.pickle
DEBUG: [root] Number of items in pickled list: 7
DEBUG: [root] splitType: train 
DEBUG: [root] Deleting file: photosynthesis/train/filenames.pickle
DEBUG: [root] Number of items in pickled list: 7
INFO: [root] FINISHED WRITING TEXT TO <<{'test': 'photosynthesis/test/filenames.pickle', 'train': 'photosynthesis/train/filenames.pickle'}>>
           'SMOOTH': {'GAMMA1': 168.6969,
                      'GAMMA2': 51.1301,
                      'GAMMA3': 26.8084,
                      'LAMBDA': 1.0},
           'SNAPSHOT_INTERVAL': 100},
 'TRAIN_SPLIT': 1.0,
 'TREE': {'BASE_SIZE': 5, 'BRANCH_NUM': 1},
 'VALIDATION_SPLIT': 1.0,
 'WORKERS': 1}
photosynthesis/filenames.txt
Number of Train files: 7
Number of Test files: 7
Split Directory: photosynthesis/train
DEBUG: [root] data_dir: photosynthesis
Load filenames from: photosynthesis/train/filenames.pickle (7)
Load filenames from: photosynthesis/test/filenames.pickle (7)
DEBUG: [root] Check if captions.pickle does not exists
Save to:  photosynthesis/captions.pickle
data_dir Directory: photosynthesis
Number words: 244
Embedding Number: 1
Split Directory: photosynthesis/test
Load filenames from: photosynthesis/train/filenames.pickle (7)
Load filenames from: photosynthesis/test/filenames.pickle (7)
DEBUG: [root] data_dir: photosynthesis
DEBUG: [root] Check if captions.pickle does not exists
DEBUG: [root] captions.pickle exists
DEBUG: [root] Loading pickle text file names: photosynthesis/captions.pickle
Load from:  photosynthesis/captions.pickle
data_dir Directory: photosynthesis
/home/garrett/SCM/AttnGAN/code/env/lib/python3.5/site-packages/torch/nn/modules/rnn.py:46: UserWarning: dropout option adds dropout after all but last recurrent layer, so non-zero dropout expects num_layers greater than 1, but got dropout=0.5 and num_layers=1
  "num_layers={}".format(dropout, num_layers))
Load pretrained model from  https://download.pytorch.org/models/inception_v3_google-1a9a5a14.pth
| epoch   0 |     0/    1 batches | ms/batch 63.25 | s_loss  0.01  0.01 | w_loss  0.14  0.07
att_sze equal to 17
DEBUG: [PIL.PngImagePlugin] STREAM b'IHDR' 16 13
DEBUG: [PIL.PngImagePlugin] STREAM b'IDAT' 41 1216
-----------------------------------------------------------------------------------------
| end epoch   0 | valid loss 423.23 7008.60 | lr 0.03820|
-----------------------------------------------------------------------------------------
Save G/Ds models.
INFO: [guild] Found 1 previous trial(s) for use in optimization
> /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(42)_init_trial()
-> res = util.log_apply(
(Pdb) [Categorical(categories=(7,), prior=None), Categorical(categories=(1,), prior=None), Categorical(categories=(True,), prior=None), Categorical(categories=(1024,), prior=None), Categorical(categories=(0.0382,), prior=None), Categorical(categories=(1,), prior=None), Categorical(categories=(51.1301,), prior=None), Categorical(categories=(26.8084,), prior=None), Categorical(categories=(0,), prior=None), Categorical(categories=(0.93,), prior=None), Categorical(categories=(100,), prior=None), Categorical(categories=(1.0,), prior=None), Categorical(categories=(1.0,), prior=None), Categorical(categories=(244,), prior=None)]
(Pdb)  37  	
 38  	def _init_trial(trial, state):
 39  	    import skopt
 40  	    random_starts, x0, y0, dims = state.minimize_inputs(trial.run_id)
 41  	    import pdb;pdb.set_trace()
 42  ->	    res = util.log_apply(
 43  	        skopt.gp_minimize,
 44  	        lambda *args: 0,
 45  	        dims,
 46  	        n_calls=1,
 47  	        n_random_starts=random_starts,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(43)_init_trial()
-> skopt.gp_minimize,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(44)_init_trial()
-> lambda *args: 0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(45)_init_trial()
-> dims,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(46)_init_trial()
-> n_calls=1,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(47)_init_trial()
-> n_random_starts=random_starts,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(48)_init_trial()
-> x0=x0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(49)_init_trial()
-> y0=y0,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(50)_init_trial()
-> random_state=state.random_state,
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(51)_init_trial()
-> acq_func=state.batch_flags["acq-func"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(52)_init_trial()
-> kappa=state.batch_flags["kappa"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(53)_init_trial()
-> xi=state.batch_flags["xi"],
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(54)_init_trial()
-> noise=state.batch_flags["noise"])
(Pdb) > /home/garrett/SCM/guild/guild/plugins/skopt_gp_main.py(55)_init_trial()
-> state.random_state = res.random_state
(Pdb)  50  	        random_state=state.random_state,
 51  	        acq_func=state.batch_flags["acq-func"],
 52  	        kappa=state.batch_flags["kappa"],
 53  	        xi=state.batch_flags["xi"],
 54  	        noise=state.batch_flags["noise"])
 55  ->	    state.random_state = res.random_state
 56  	    return skopt_util.trial_flags(state.flag_names, res.x_iters[-1])
 57  	
 58  	if __name__ == "__main__":
 59  	    skopt_util.default_main(_init_trial)
[EOF]
(Pdb) [7.0, 1.0, 1.0, 1024.0, 0.0382, 1.0, 51.1301, 26.8084, 0.0, 0.93, 100.0, 1.0, 1.0, 244.0]
(Pdb) [[7, 1, True, 1024, 0.0382, 1, 51.1301, 26.8084, 0, 0.93, 100, 1.0, 1.0, 244]]
(Pdb) [EOF]
(Pdb) 0
INFO: [guild] Initialized trial 515966cb (batch_size=7.0, captions_per_image=1.0, delete_captions_pickle=1.0, embedding_dim=1024.0, encoder_lr=0.0382, epochs=1.0, gamma2=51.1301, gamma3=26.8084, gpu=0.0, rnn_grad_clip=0.93, snapshot-interval=100.0, train_split=1.0, validation_split=1.0, words_num=244.0)
INFO: [guild] Running trial 515966cb: damsm:pretrain (batch_size=7.0, captions_per_image=1.0, delete_captions_pickle=1.0, embedding_dim=1024.0, encoder_lr=0.0382, epochs=1.0, gamma2=51.1301, gamma3=26.8084, gpu=0.0, rnn_grad_clip=0.93, snapshot-interval=100.0, train_split=1.0, validation_split=1.0, words_num=244.0)
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
ERROR: [guild] Run 515966cb822011e9b16de4a471939b0d failed - see logs for details

```

[output.txt](output.txt)








