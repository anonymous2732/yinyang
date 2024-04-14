---
layout: page
---

# Yin-Yang: A Neuro-Symbolic Framework For Developing Motifs With Long-Term Structure And Controllability

**Abstract**  
Transformer models have made great strides in generating symbolic music with local coherence. Yet, controlling the development of motifs in a structured way with global form remains an open research area. One of the reasons for this challenge is due to the note-by-note autoregressive generation of such models which lack the ability to correct themselves after deviations from the motif. In addition, their structural performance on datasets with shorter durations has not been studied in the literature. In this study, we propose Yin-Yang, a neuro-symbolic framework consisting of a phrase generator, phrase refiner and phrase selector models for development of motifs with long-term structure and controllability. The phrase refiner is trained on a novel corruption-refinement strategy which allows it to produce melodic and rhythmic variations of the original motif at generation time, thereby rectifying deviations of the phrase generator. We also introduce a new objective evaluation metric for quantifying how smoothly the motif manifests itself within the piece. Subjective evaluation results show our model achieves better performance compared to state of the art transformer models while having the advantage of being controllable and semi-interpretable, paving the path for musical analysis.




## Audio Generation Framework

<audio src="Audio_Generation_Framework/4/YY_Generation_Framework.mp3" controls ></audio>


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
