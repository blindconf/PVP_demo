# Adversarial example demo

Supplementary material containing a selection of benign, adversarial, and noisy data employed in our [*paper*](https://arxiv.org/abs/2305.17000).

For each sample, we include the word error rate (WER) or the character error rate (CER) as an accuracy metric and the segmental signal-to-noise ratio (SNR<sub>seg</sub>) as a quality noise metric.
An SNR<sub>seg</sub> exceeding 0 dB indicates a stronger signal presence compared to noise. 
These samples are sourced from the [*Librispeech*](https://www.openslr.org/12) corpus dataset.

## Librispeech - English
###### Sample 1 
<pre>Benign transcription:       <em>THEN HE LOOKED DOWN THE LAGOON WAS DRY</em>
Adversarial transcription:  <em>PEARL WAS A BORN OUTCAST OF THE INFANTILE WORLD</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=62.50, SNR<sub>seg</sub>=-4.79]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/clean/61-70968-0038.flac" type="audio/wav" />
</audio>

[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=24.50],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=25.36]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/fp32-cw-seq2seq/61-70968-0038.wav" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/fp32-psy-seq2seq" type="audio/wav" />
</audio>


###### Sample 2 
<pre>Benign transcription:       <em>HOW JOLLY IT WAS BEING YOUNG HILDA</em>
Adversarial transcription:  <em>THERE WAS A GRIM SMILE OF AMUSEMENT ON HIS SHREWD FACE</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=0.00, SNR<sub>seg</sub>=6.03]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/clean/61-70968-0058.flac" type="audio/wav" />
</audio>

[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=22.04],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=22.95]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/fp16 CW-trans" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/fp16-psy-trans" type="audio/wav" />
</audio>




###### Sample 3
<pre>Benign transcription:       <em>ICH GLAUBE ES AUCH NICHT</em>
Adversarial transcription:  <em>WAS SOLLS ICH BIN BEREIT</em>
</pre> &nbsp;
[**benign**: *WER*=0.00],               [**noisy**: *WER*=20.00, SNR<sub>seg</sub>=-17.16]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/clean/61-70968-0059.flac" />
</audio>

[**C&W adversarial**: *WER*=0.00, SNR<sub>seg</sub>=8.86],   [**psychoacoustic**: *WER*=0.00, SNR<sub>seg</sub>=11.23]
 <audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/bf16-cw-CTC" type="audio/wav" />
</audio>
<audio style="width:320px" controls="controls">
	<source src="PVP_DEMO_AUDIO/PVP demos/bf16-psy-ctc" type="audio/wav" />
</audio>



</audio>
