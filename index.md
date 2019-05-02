## WaveRNN + TTS Outputs
President Trump met with other leaders at the Group of 20 conference.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts1.wav?raw=true" controls preload></audio>
There's a way to measure the acute emotional intelligence that has never gone out of style.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts2.wav?raw=true" controls preload></audio>
Scientists at the CERN laboratory say they have discovered a new particle.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts3.wav?raw=true" controls preload></audio>
The Senate's bill to repeal and replace the Affordable Care-Act is now imperiled.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts4.wav?raw=true" controls preload></audio>
Generative adversarial network or variational auto-encoder.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts5.wav?raw=true" controls preload></audio>
Basilar membrane and otolaryngology are not auto-correlations.
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts6.wav?raw=true" controls preload></audio>
The buses aren't the problem, they acutally provide a solution
<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/tts7.wav?raw=true" controls preload></audio>

____

## WavRNN Vocoder Only

Mixture of Logistics Model trained to ~800k steps. Generation Rate benchmarked on a GTX1080. 

| Original | Not Batched (Generation Rate: 1.5kHz) | Batched | Batched Generation Rate |
|:---:|:---:|:---:|:---:|
|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_1_target.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_1_gen_NOT_BATCHED.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_1_gen_batched.wav?raw=true" controls preload></audio>|29kHz|
|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_2_target.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_2_gen_NOT_BATCHED.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_2_gen_batched.wav?raw=true" controls preload></audio>|26kHz|
|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_3_target.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_3_gen_NOT_BATCHED.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_3_gen_batched.wav?raw=true" controls preload></audio>|24kHz|
|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_4_target.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_4_gen_NOT_BATCHED.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_4_gen_batched.wav?raw=true" controls preload></audio>|15kHz|
|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_5_target.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_5_gen_NOT_BATCHED.wav?raw=true" controls preload></audio>|<audio src="https://github.com/fatchord/model_outputs/blob/master/ljspeech_9bit_mulaw/797k_steps_5_gen_batched.wav?raw=true" controls preload></audio>|18kHz|
