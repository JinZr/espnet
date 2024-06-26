<!-- Generated by /export/db/chime4/egs/chime4/asr1/../../../utils/show_result.sh -->
# Conformer result(mix si284 + speed perturb + SpecAugment, n_average = 10, epoch = 100, ngpu=1)
## Environments
- Model files (archived to train_pytorch_sp.tar.gz by `$ pack_model.sh`)
  - model link: https://drive.google.com/file/d/12Y_95zOsuAvNrDem9B_wD9nTC6ed10uc/view?usp=sharing
  - training config file: `conf/train_pytorch_conformer_kernel15.yaml`
  - decoding config file: `conf/decode.yaml`
  - cmvn file: `data-fbank/tr05_multi_noisy_si284_sp/cmvn.ark`
  - e2e file: `exp/tr05_multi_noisy_si284_sp_pytorch_train_pytorch_conformer_kernel15_specaug/results/model.last10.avg.best`
  - e2e JSON file: `exp/tr05_multi_noisy_si284_sp_pytorch_train_pytorch_conformer_kernel15_specaug/results/model.json`
  - lm file: `exp/train_rnnlm_pytorch_lm_word65000/rnnlm.model.best`
  - lm JSON file: `exp/train_rnnlm_pytorch_lm_word65000/model.json`
  - etc file:`[lm vocab] data/local/wordlm_train/wordlist_65000.txt`

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|160390|96.1|2.0|2.0|0.9|4.8|62.2|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|160390|96.9|1.5|1.6|0.7|3.8|57.4|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|160390|95.1|2.6|2.3|1.3|6.1|67.3|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|160400|95.0|2.3|2.7|1.1|6.1|66.4|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|160400|96.2|1.7|2.1|0.9|4.7|60.9|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|160400|94.0|2.9|3.0|1.4|7.4|70.0|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|126796|92.6|3.7|3.7|1.5|8.9|70.8|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|126796|94.2|2.8|3.0|1.2|7.0|65.5|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|126796|90.8|4.9|4.3|2.1|11.3|77.4|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|126812|91.4|3.7|4.8|1.6|10.1|74.4|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|126812|93.3|2.9|3.8|1.3|8.0|70.3|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|126812|89.7|5.0|5.3|2.2|12.5|77.3|
|decode_et05_simu_clean_decode_lm_word65000|330|31703|98.2|0.9|0.9|0.3|2.1|44.8|
|decode_dt05_simu_clean_decode_lm_word65000|410|40100|98.3|1.0|0.7|0.3|2.0|47.3|

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|27119|91.2|6.9|1.8|0.9|9.7|62.2|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|27119|92.8|5.7|1.5|0.7|7.9|57.4|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|27119|89.5|8.4|2.1|1.2|11.7|67.3|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|27120|89.6|7.9|2.5|1.0|11.4|66.4|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|27120|91.7|6.4|2.0|0.8|9.1|60.9|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|27120|87.8|9.5|2.7|1.3|13.5|70.0|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|21409|85.2|11.6|3.2|1.6|16.4|70.8|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|21409|87.9|9.5|2.6|1.3|13.4|65.6|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|21409|81.6|14.7|3.7|2.3|20.6|77.4|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|21416|84.1|11.7|4.2|1.5|17.4|74.4|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|21416|87.2|9.5|3.3|1.4|14.2|70.3|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|21416|81.2|14.3|4.5|2.1|20.9|77.3|
|decode_et05_simu_clean_decode_lm_word65000|330|5354|95.2|4.0|0.9|0.3|5.1|44.8|
|decode_dt05_simu_clean_decode_lm_word65000|410|6780|95.5|3.8|0.7|0.4|4.8|47.3||

# Transformer result(mix si284 + default transformer with n_average = 10, epoch = 100, ngpu=2)
## Environments
- date: `Wed Jun 26 15:16:41 JST 2019`
- python version: `3.7.3 (default, Mar 27 2019, 22:11:17)  [GCC 7.3.0]`
- espnet version: `espnet 0.3.1`
- chainer version: `chainer 6.0.0`
- pytorch version: `pytorch 1.0.1.post2`
- Git hash: `540f0d2b8ed482e8242a25bd3535b65c9bc50b17`
  - Commit date: `Wed Jun 26 14:25:15 2019 +0900`
- Model files (archived to train_pytorch_sp.tar.gz by `$ pack_model.sh`)
  - model link: https://drive.google.com/open?id=1jWfcDknm6EcMQlVtrpiTIg_5f7F36_7A
  - training config file: `conf/tuning/train_pytorch_transformer.sp.yaml`
  - decoding config file: `conf/tuning/decode_pytorch_transformer.yaml`
  - cmvn file: `data-fbank/tr05_multi_noisy_si284_sp/cmvn.ark`
  - e2e file: `exp/tr05_multi_noisy_si284_sp_pytorch_train_pytorch_transformer.sp/results/model.last10.avg.best`
  - e2e JSON file: `exp/tr05_multi_noisy_si284_sp_pytorch_train_pytorch_transformer.sp/results/model.json`
  - lm file: `exp/train_rnnlm_pytorch_lm_word65000/rnnlm.model.best`
  - lm JSON file: `exp/train_rnnlm_pytorch_lm_word65000/model.json`
  - etc file:`[lm vocab] data/local/wordlm_train/wordlist_65000.txt`

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|160390|94.7|2.6|2.7|1.1|6.4|73.9|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|160390|96.1|2.0|1.9|0.9|4.9|62.8|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|160390|93.7|3.2|3.1|1.4|7.7|77.9|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|160400|93.3|3.5|3.2|1.4|8.1|76.0|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|160400|95.2|2.4|2.3|1.2|5.9|66.5|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|160400|92.6|4.0|3.4|1.7|9.1|76.8|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|126796|90.7|4.9|4.3|2.2|11.4|79.5|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|126796|92.5|3.8|3.7|1.7|9.3|75.2|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|126796|88.3|6.2|5.4|2.6|14.3|86.4|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|126812|89.8|5.2|5.0|2.4|12.7|80.2|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|126812|91.7|4.1|4.2|1.9|10.2|77.0|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|126812|88.1|6.3|5.6|2.8|14.7|84.8|

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|27119|87.4|10.3|2.3|1.4|14.0|73.9|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|27119|90.9|7.4|1.7|1.2|10.3|62.8|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|27119|85.3|12.1|2.6|1.8|16.4|77.9|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|27120|85.6|11.9|2.5|1.6|16.0|76.0|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|27120|89.8|8.2|1.9|1.4|11.6|66.5|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|27120|84.0|13.3|2.7|2.0|18.0|76.8|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|21409|81.1|15.9|3.0|2.8|21.8|79.5|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|21409|84.2|13.1|2.7|2.2|18.0|75.2|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|21409|75.7|20.3|4.0|3.2|27.5|86.4|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|21416|80.2|16.1|3.7|2.9|22.6|80.2|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|21416|83.6|13.3|3.2|2.3|18.7|77.0|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|21416|76.1|19.8|4.0|3.2|27.0|84.8|

# Transformer result(mix si284 + speed perturb + default transformer with n_average = 10, epoch = 35, ngpu=2)
## speed perturbation at 0.9, 1.0, 1.1
### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|160390|96.3|2.1|1.6|1.2|4.9|60.9|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|160390|97.0|1.6|1.4|0.9|3.9|56.3|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|160390|95.3|2.7|2.1|1.6|6.3|66.6|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|160400|95.0|2.7|2.3|1.4|6.4|66.4|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|160400|96.2|2.0|1.8|1.1|4.9|60.9|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|160400|94.1|3.4|2.5|1.9|7.8|68.8|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|126796|92.5|4.2|3.3|2.0|9.5|72.7|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|126796|94.2|3.1|2.7|1.5|7.4|68.3|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|126796|90.8|5.3|3.9|2.7|11.9|77.3|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|126812|91.3|4.5|4.2|2.3|11.0|75.3|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|126812|93.2|3.4|3.4|1.8|8.7|72.9|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|126812|89.9|5.5|4.6|2.9|12.9|78.0|

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_lm_word65000|1640|27119|91.5|7.2|1.3|1.5|10.0|60.9|
|decode_dt05_real_beamformit_5mics_decode_lm_word65000|1640|27119|92.8|6.0|1.2|1.1|8.2|56.3|
|decode_dt05_real_isolated_1ch_track_decode_lm_word65000|1640|27119|89.6|8.7|1.7|1.9|12.4|66.6|
|decode_dt05_simu_beamformit_2mics_decode_lm_word65000|1640|27120|89.6|8.6|1.8|1.8|12.2|66.4|
|decode_dt05_simu_beamformit_5mics_decode_lm_word65000|1640|27120|91.7|6.9|1.4|1.3|9.6|60.9|
|decode_dt05_simu_isolated_1ch_track_decode_lm_word65000|1640|27120|87.7|10.4|1.9|2.2|14.5|68.8|
|decode_et05_real_beamformit_2mics_decode_lm_word65000|1320|21409|84.5|13.1|2.4|2.6|18.1|72.7|
|decode_et05_real_beamformit_5mics_decode_lm_word65000|1320|21409|87.4|10.5|2.1|1.9|14.5|68.3|
|decode_et05_real_isolated_1ch_track_decode_lm_word65000|1320|21409|81.4|15.9|2.8|3.2|21.9|77.3|
|decode_et05_simu_beamformit_2mics_decode_lm_word65000|1320|21416|83.5|13.3|3.1|2.6|19.0|75.3|
|decode_et05_simu_beamformit_5mics_decode_lm_word65000|1320|21416|86.6|10.7|2.7|2.3|15.7|72.9|
|decode_et05_simu_isolated_1ch_track_decode_lm_word65000|1320|21416|81.1|15.6|3.3|3.3|22.1|78.0|

# Result for RNN based(mix si284 + speed perturb + wordlm + default network with epoch = 10, ngpu = 2)
## speed perturbation at 0.9, 1.0, 1.1
### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_rnn_lm_word65000|1640|160390|95.6|2.3|2.1|1.2|5.6|65.9|
|decode_dt05_real_beamformit_5mics_decode_rnn_lm_word65000|1640|160390|96.6|1.7|1.7|0.9|4.3|59.8|
|decode_dt05_real_isolated_1ch_track_decode_rnn_lm_word65000|1640|160390|94.6|2.9|2.5|1.5|6.9|69.2|
|decode_dt05_simu_beamformit_2mics_decode_rnn_lm_word65000|1640|160400|94.8|2.6|2.5|1.3|6.5|67.0|
|decode_dt05_simu_beamformit_5mics_decode_rnn_lm_word65000|1640|160400|96.1|1.9|2.0|1.0|4.9|61.3|
|decode_dt05_simu_isolated_1ch_track_decode_rnn_lm_word65000|1640|160400|93.8|3.4|2.9|1.8|8.0|69.9|
|decode_et05_real_beamformit_2mics_decode_rnn_lm_word65000|1320|126796|91.0|5.0|4.0|2.3|11.3|75.8|
|decode_et05_real_beamformit_5mics_decode_rnn_lm_word65000|1320|126796|93.0|3.8|3.2|1.7|8.8|71.7|
|decode_et05_real_isolated_1ch_track_decode_rnn_lm_word65000|1320|126796|88.7|6.4|4.8|2.9|14.2|81.4|
|decode_et05_simu_beamformit_2mics_decode_rnn_lm_word65000|1320|126812|89.8|5.2|4.9|2.4|12.6|80.8|
|decode_et05_simu_beamformit_5mics_decode_rnn_lm_word65000|1320|126812|91.9|4.1|4.0|2.0|10.1|76.4|
|decode_et05_simu_isolated_1ch_track_decode_rnn_lm_word65000|1320|126812|88.7|6.1|5.1|3.1|14.4|81.4|

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_dt05_real_beamformit_2mics_decode_rnn_lm_word65000|1640|27119|90.2|8.0|1.8|1.3|11.1|65.9|
|decode_dt05_real_beamformit_5mics_decode_rnn_lm_word65000|1640|27119|92.1|6.4|1.5|1.0|8.9|59.8|
|decode_dt05_real_isolated_1ch_track_decode_rnn_lm_word65000|1640|27119|88.3|9.5|2.2|1.7|13.4|69.2|
|decode_dt05_simu_beamformit_2mics_decode_rnn_lm_word65000|1640|27120|89.2|8.7|2.1|1.4|12.2|67.0|
|decode_dt05_simu_beamformit_5mics_decode_rnn_lm_word65000|1640|27120|91.5|6.7|1.7|1.0|9.5|61.3|
|decode_dt05_simu_isolated_1ch_track_decode_rnn_lm_word65000|1640|27120|87.2|10.4|2.3|1.8|14.6|69.9|
|decode_et05_real_beamformit_2mics_decode_rnn_lm_word65000|1320|21409|81.9|15.0|3.1|2.5|20.6|75.8|
|decode_et05_real_beamformit_5mics_decode_rnn_lm_word65000|1320|21409|85.3|12.0|2.6|2.0|16.6|71.7|
|decode_et05_real_isolated_1ch_track_decode_rnn_lm_word65000|1320|21409|78.1|18.3|3.7|3.2|25.1|81.4|
|decode_et05_simu_beamformit_2mics_decode_rnn_lm_word65000|1320|21416|80.6|15.8|3.6|2.8|22.2|80.8|
|decode_et05_simu_beamformit_5mics_decode_rnn_lm_word65000|1320|21416|84.1|13.0|3.0|2.4|18.3|76.4|
|decode_et05_simu_isolated_1ch_track_decode_rnn_lm_word65000|1320|21416|78.5|17.7|3.8|3.1|24.6|81.4|

# added beamforming results for 2ch and 6ch tracks
### CER
```
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd      |    Corr          Sub          Del          Ins           Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160390     |    92.4          4.0          3.6          1.8           9.3         80.0    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd      |    Corr          Sub          Del          Ins           Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160400     |    91.8          4.6          3.6          2.3          10.5         78.7    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd      |    Corr          Sub          Del          Ins           Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126796     |    86.1          7.8          6.1          3.5          17.4         88.3    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd      |    Corr          Sub          Del          Ins           Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126812     |    86.3          7.8          6.0          3.8          17.5         88.0    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160390    |    94.1          2.9          3.0          1.3          7.2         72.9    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160400    |    93.4          3.5          3.1          1.7          8.3         73.8    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126796    |    88.6          6.1          5.3          2.7         14.2         84.4    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126812    |    88.0          6.5          5.5          3.0         15.0         87.2    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160390    |    95.3          2.2          2.5          1.0          5.7         66.8    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1640         160400    |    94.9          2.5          2.6          1.2          6.3         69.5    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126796    |    90.8          4.8          4.4          2.2         11.4         81.2    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    SPKR      |    # Snt        # Wrd     |    Corr          Sub          Del          Ins          Err        S.Err    |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.txt:|    Sum/Avg   |    1320         126812    |    90.0          5.3          4.7          2.5         12.5         84.4    |
```

### WER
```
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt         # Wrd    |    Corr           Sub           Del           Ins          Err         S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640          27119    |    84.2          12.9           2.9           2.1         17.9          80.0     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt         # Wrd    |    Corr           Sub           Del           Ins          Err         S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640          27120    |    83.5          13.8           2.6           2.6         19.1          78.7     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt         # Wrd    |    Corr           Sub           Del           Ins          Err         S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320          21409    |    73.1          22.4           4.6           4.1         31.1          88.3     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt         # Wrd    |    Corr           Sub           Del           Ins          Err         S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_isolated_1ch_track_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320          21416    |    73.8          22.1           4.2           4.3         30.6          88.0     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640         27119     |    87.4         10.2           2.5          1.6          14.2         72.9     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640         27120     |    86.5         11.1           2.4          2.0          15.5         73.8     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320         21409     |    77.2         18.9           3.9          3.3          26.1         84.4     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_2mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320         21416     |    76.6         19.5           3.8          3.5          26.8         87.2     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640         27119     |    89.6          8.2           2.2          1.2          11.7         66.8     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_dt05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1640         27120     |    89.0          8.9           2.0          1.5          12.4         69.5     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_real_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320         21409     |    81.1         15.5           3.3          2.6          21.5         81.2     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    SPKR       |    # Snt        # Wrd     |    Corr          Sub           Del          Ins           Err        S.Err     |
exp/tr05_multi_noisy_a01_alltracks/decode_et05_simu_beamformit_5mics_beam20_emodel.acc.best_p0_len0.0-0.0_ctcw0.3_wordrnnlm1.0/result.wrd.txt:|    Sum/Avg    |    1320         21416     |    80.0         16.7           3.3          3.1          23.2         84.4     |
```

# 4 -> 6 layers in the encoder network
```
exp/tr05_multi_noisy_a03_ch_vggblstmp_e6/decode_dt05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|    SPKR      |   # Snt        # Wrd     |   Corr          Sub         Del          Ins         Err        S.Err    |
exp/tr05_multi_noisy_a03_ch_vggblstmp_e6/decode_dt05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|    Sum/Avg   |   3280         320790    |   81.9         10.3         7.8          4.3        22.4         98.8    |
exp/tr05_multi_noisy_a03_ch_vggblstmp_e6/decode_et05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|    SPKR      |   # Snt        # Wrd     |   Corr          Sub         Del          Ins         Err        S.Err    |
exp/tr05_multi_noisy_a03_ch_vggblstmp_e6/decode_et05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|    Sum/Avg   |   2640         253608    |   74.7         14.8        10.5          6.2        31.5         99.2    |
```

# First result
```
exp/tr05_multi_noisy_a01/decode_dt05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|  SPKR     |  # Snt     # Wrd    |  Corr       Sub      Del       Ins       Err     S.Err   |
exp/tr05_multi_noisy_a01/decode_dt05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|  Sum/Avg  |  3280      320790   |  80.8      11.0      8.1       4.7      23.8      99.1   |
exp/tr05_multi_noisy_a01/decode_et05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|  SPKR     |  # Snt     # Wrd    |  Corr       Sub      Del       Ins       Err     S.Err   |
exp/tr05_multi_noisy_a01/decode_et05_multi_isolated_1ch_track_beam20_eacc.best_p0_len0.3-0.8/result.txt:|  Sum/Avg  |  2640      253608   |  73.9      15.6     10.5       7.1      33.2      99.7   |
```
