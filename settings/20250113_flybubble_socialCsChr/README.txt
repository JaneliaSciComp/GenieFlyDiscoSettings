copied from FlyDiscoAnalysis/settings/20210806_flybubble_LED

modified the ctrax results movie params for the 20220414 LED protocol

20220609
changed VNC_barcode to VNC2__barcode in incoming checks

20220913
added jab classifiers

202201005
added parameters for APT tracking

20230213 from - 20220913_flybubble_LED_VNC2
adding parameters for apt results movie

20230307
updated the lbl file, same name in apt_params.txt 
Same tracker just updated the slots for tracking and training to work with APT update

20230518
added Alice updated walk jaaba classifier -> scores_walk2.mat

20230622
updated the singularity image pointer for cluster upgrade

20230907
added missing parameter to datalocs 
flytrackerbgstr,movie-bg.mat

20240906
update gpu queue to gpu_l4_large

20240908 
merged 20240507_flybubble_LED_VNC3 and 20150915_flybubble_centralcomplex to make flydisco settings directory for reprocessing

20240912
updated npad in indicator to get envelop instead of the following pulses. found new value analytically by testing with distinct_pulse_count_from_single_channel_protocol

20240913
changed queue to gpu_l4

20250113
added nottracking.jab file - uses APT features so increase storage space
