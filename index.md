---
layout: page
---

# Yin-Yang: A Neuro-Symbolic Framework For Developing Motifs With Long-Term Structure And Controllability

**Abstract**  
Transformer models have made great strides in generating symbolic music with local coherence. Yet, controlling the development of motifs in a structured way with global form remains an open research area. One of the reasons for this challenge is due to the note-by-note autoregressive generation of such models which lack the ability to correct themselves after deviations from the motif. In addition, their structural performance on datasets with shorter durations has not been studied in the literature. In this study, we propose Yin-Yang, a neuro-symbolic framework consisting of a phrase generator, phrase refiner and phrase selector models for development of motifs with long-term structure and controllability. The phrase refiner is trained on a novel corruption-refinement strategy which allows it to produce melodic and rhythmic variations of the original motif at generation time, thereby rectifying deviations of the phrase generator. We also introduce a new objective evaluation metric for quantifying how smoothly the motif manifests itself within the piece. Subjective evaluation results show our model achieves better performance compared to state of the art transformer models while having the advantage of being controllable and semi-interpretable, paving the path for musical analysis.




## Audio Generation Framework

<audio src="Audio_Generation_Framework/YY_Generation_Framework.mp3" controls ></audio>

## Example 1

<!-- Adjust the width of the table -->
<!-- <table style="width: 100%;">
    <tr>
        <th style="width: 25%;">Compound Word Transformer</th>
        <th style="width: 25%;">Music Transformer</th>
        <th style="width: 25%;">YinYang</th>
        <th style="width: 25%;">YinYang Ablated</th>
    </tr>
    <tr>
        <td><audio src="Audio_Type_1/NLB150927_01_CP.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_1/NLB150927_01_MT.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_1/NLB150927_01_YY.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_1/NLB150927_01_YYA.mp3" controls ></audio></td>
    </tr>
</table> -->

<table style="width: 200%;">
    <tr>
        <th style="width: 20%;">Model</th>
        <th style="width: 30%;">Audio</th>
        <th style="width: 50%;">Description</th>
    </tr>
    <tr>
        <td>Prompt</td>
        <td><audio src="Audio_Type_1/NLB150927_01_GT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Compound Word Transformer</td>
        <td><audio src="Audio_Type_1/NLB150927_01_CP.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Music Transformer</td>
        <td><audio src="Audio_Type_1/NLB150927_01_MT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang</td>
        <td><audio src="Audio_Type_1/NLB150927_01_YY.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang Ablated</td>
        <td><audio src="Audio_Type_1/NLB150927_01_YYA.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
</table>


## Example 2

<!-- Adjust the width of the table -->
<!-- <table style="width: 100%;">
    <tr>
        <th style="width: 25%;">Compound Word Transformer</th>
        <th style="width: 25%;">Music Transformer</th>
        <th style="width: 25%;">YinYang</th>
        <th style="width: 25%;">YinYang Ablated</th>
    </tr>
    <tr>
        <td><audio src="Audio_Type_2/NLB075093_01_CP.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_2/NLB075093_01_MT.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_2/NLB075093_01_YY.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_2/NLB075093_01_YYA.mp3" controls ></audio></td>
    </tr>
</table> -->

<table style="width: 200%;">
    <tr>
        <th style="width: 20%;">Model</th>
        <th style="width: 30%;">Audio</th>
        <th style="width: 50%;">Description</th>
    </tr>
    <tr>
        <td>Prompt</td>
        <td><audio src="Audio_Type_2/NLB075093_01_GT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Compound Word Transformer</td>
        <td><audio src="Audio_Type_2/NLB075093_01_CP.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Music Transformer</td>
        <td><audio src="Audio_Type_2/NLB075093_01_MT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang</td>
        <td><audio src="Audio_Type_2/NLB075093_01_YY.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang Ablated</td>
        <td><audio src="Audio_Type_2/NLB075093_01_YYA.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
</table>

## Example 3

<!-- Adjust the width of the table -->
<!-- <table style="width: 100%;">
    <tr>
        <th style="width: 25%;">Compound Word Transformer</th>
        <th style="width: 25%;">Music Transformer</th>
        <th style="width: 25%;">YinYang</th>
        <th style="width: 25%;">YinYang Ablated</th>
    </tr>
    <tr>
        <td><audio src="Audio_Type_3/tirol12_CP.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_3/tirol12_MT.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_3/tirol12_YY.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_3/tirol12_YYA.mp3" controls ></audio></td>
    </tr>
</table> -->

<table style="width: 200%;">
    <tr>
        <th style="width: 20%;">Model</th>
        <th style="width: 30%;">Audio</th>
        <th style="width: 50%;">Description</th>
    </tr>
    <tr>
        <td>Prompt</td>
        <td><audio src="Audio_Type_3/tirol12_GT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Compound Word Transformer</td>
        <td><audio src="Audio_Type_3/tirol12_CP.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Music Transformer</td>
        <td><audio src="Audio_Type_3/tirol12_MT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang</td>
        <td><audio src="Audio_Type_3/tirol12_YY.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang Ablated</td>
        <td><audio src="Audio_Type_3/tirol12_YYA.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
</table>

## Example 4

<!-- Adjust the width of the table -->
<!-- <table style="width: 100%;">
    <tr>
        <th style="width: 25%;">Compound Word Transformer</th>
        <th style="width: 25%;">Music Transformer</th>
        <th style="width: 25%;">YinYang</th>
        <th style="width: 25%;">YinYang Ablated</th>
    </tr>
    <tr>
        <td><audio src="Audio_Type_4/NLB011074_01_CP.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_4/NLB011074_01_MT.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_4/NLB011074_01_YY.mp3" controls ></audio></td>
        <td><audio src="Audio_Type_4/NLB011074_01_YYA.mp3" controls ></audio></td>
    </tr>
</table> -->

<table style="width: 200%;">
    <tr>
        <th style="width: 20%;">Model</th>
        <th style="width: 30%;">Audio</th>
        <th style="width: 50%;">Description</th>
    </tr>
    <tr>
        <td>Prompt</td>
        <td><audio src="Audio_Type_4/NLB011074_01_GT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Compound Word Transformer</td>
        <td><audio src="Audio_Type_4/NLB011074_01_CP.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>Music Transformer</td>
        <td><audio src="Audio_Type_4/NLB011074_01_MT.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang</td>
        <td><audio src="Audio_Type_4/NLB011074_01_YY.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
    <tr>
        <td>YinYang Ablated</td>
        <td><audio src="Audio_Type_4/NLB011074_01_YYA.mp3" controls ></audio></td>
        <td>abc, additional text here abc, additional text here</td>
    </tr>
</table>


## Audio Variations
The following samples display various transformations paired with corruption tokens to produce interesting variations of the motif.

Augmentation Transformation with Melodic Stripping Corruption
<audio src="Audio_Variations/han1006_mono_expand_melody_combined.mp3" controls ></audio>
Modal Inversion Transformation with Incorrect Inversion Corruption
<audio src="Audio_Variations/han1006_mono_invert_melody_strict_combined.mp3" controls ></audio>
Fragmentation Transformation with Fragmentation Corruption
<audio src="Audio_Variations/han1006_mono_fragmentation_combined.mp3" controls ></audio>
Pitch Rhythm Permutation Transformation with Pitch Rhythm Permutation Corruption
<audio src="Audio_Variations/han1006_mono_permute_melody_pitch_rhythm_combined.mp3" controls ></audio>
Pitch Rythm Retrograde with Incorrect Inversion Corruption
<audio src="Audio_Variations/han1006_mono_retrograde_melody_pitch_rhythm_combined.mp3" controls ></audio>


<!-- We finally present some audio samples of separations produced by the system. By cross-referencing the cluster index with the histogram shown above, it is possible to recognize the class of sources characteristic of each cluster. -->


<!-- ### Example 0

Mix
<audio src="audio/4/mix.wav" controls ></audio>
Cluster 3 (Drums)
<audio src="audio/4/3.wav" controls ></audio>
Cluster 5 (Drums)
<audio src="audio/4/5.wav" controls ></audio>
Cluster 6 (Bass/Toms)
<audio src="audio/4/6.wav" controls ></audio>
Cluster 12 (Crash)
<audio src="audio/4/12.wav" controls ></audio>
Cluster 14 (Vocals)
<audio src="audio/4/14.wav" controls ></audio>

### Example 1

Mix
<audio src="audio/5/mix.wav" controls ></audio>
Cluster 3 (Drums)
<audio src="audio/5/3.wav" controls ></audio>
Cluster 5 (Drums)
<audio src="audio/5/5.wav" controls ></audio>
Cluster 6 (Bass/Toms)
<audio src="audio/5/6.wav" controls ></audio>
Cluster 8 (Guitar)
<audio src="audio/5/8.wav" controls ></audio>

### Example 2

Mix
<audio src="audio/3/mix.wav" controls ></audio>
Cluster 3 (Drums)
<audio src="audio/3/3.wav" controls ></audio>
Cluster 5 (Drums)
<audio src="audio/3/5.wav" controls ></audio>
Cluster 10 (Misc)
<audio src="audio/3/10.wav" controls ></audio>
Cluster 14 (Vocals)
<audio src="audio/3/14.wav" controls ></audio>

### Example 3

Mix
<audio src="audio/6/mix.wav" controls ></audio>
Cluster 3 (Drums)
<audio src="audio/6/3.wav" controls ></audio>
Cluster 5 (Drums)
<audio src="audio/6/5.wav" controls ></audio>
Cluster 6 (Bass/Toms)
<audio src="audio/6/6.wav" controls ></audio>
Cluster 12 (Crash)
<audio src="audio/6/12.wav" controls ></audio>
Cluster 14 (Vocals)
<audio src="audio/6/14.wav" controls ></audio>


### Example 4

Mix
<audio src="audio/0/mix.wav" controls ></audio>
Cluster 6 (Bass/Toms)
<audio src="audio/0/6.wav" controls ></audio>
Cluster 8 (Guitar)
<audio src="audio/0/8.wav" controls ></audio>
Cluster 14 (Vocals)
<audio src="audio/0/14.wav" controls ></audio>

### Example 5

Mix
<audio src="audio/1/mix.wav" controls ></audio>
Cluster 3 (Drums)
<audio src="audio/1/3.wav" controls ></audio>
Cluster 5 (Drums)
<audio src="audio/1/5.wav" controls ></audio>
Cluster 8 (Guitar)
<audio src="audio/1/8.wav" controls ></audio>
Cluster 12 (Crash)
<audio src="audio/1/12.wav" controls ></audio>
Cluster 14 (Vocals)
<audio src="audio/1/14.wav" controls ></audio>




 -->
