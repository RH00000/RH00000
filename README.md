<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-light.svg" alt="Ruiyang (Richard) Huang, Software Engineering, Machine Learning, Applied Mathematics">
</picture>

I build software, from CLI tools to algorithmic visualizers, and study Applied Mathematics at UT Austin. My recent work sits includes optimization, model efficiency, and evaluation pipelines.

## Selected work

**Guitar Tab Fingering Visualizer**
*Python · optimization · desktop app*
Built a tool that reads a plain-text guitar tab and computes the least effortful fingering for the whole song, then animates it on a fretboard. The pipeline (parser, moment grouping, rhythm estimation, optimizer, visualizer) treats fingering choice as a shortest-path problem over a layered graph, the same structure as the Viterbi algorithm, solved with dynamic programming over hand-shape costs (stretch, hand shift, finger preference), calibrated against real fret spacing so a two-fret stretch high on the neck isn't priced the same as one near the nut.
[Repository](https://github.com/RH00000/guitar-tab-visualizer)

**UT Course Schedule Optimizer**
*Python · constraint optimization · CLI tool*
Built a course-scheduling tool for UT registration: enumerates every valid combination of sections, drops any with time conflicts, and ranks the rest by walking distance between back-to-back classes and instructor quality (grade distributions, RateMyProfessor). The walking-cost model runs through four regimes based on schedule slack, calibrated against real UT building coordinates and validated against my own actual Fall schedule.
[Repository](https://github.com/RH00000/ut-schedule-optimizer)

**LLM Replicability Evaluation**
*Python · prompt engineering · evaluation*
Built an evaluation pipeline testing whether Gemini 2.5 Pro/Flash can predict which psychology studies replicate, using the Reproducibility Project: Psychology dataset. Iterated across several prompt designs, ensembled predictions across prompt variants, and ran confidence recalibration across multiple trials.
[Repository](https://github.com/RH00000/Rice_LLM_Replicability_Project)

**Confidence-Based ResNet Cascades**
*Python · PyTorch/TensorFlow · inference efficiency*
Built and benchmarked dynamic-skipping ResNet cascades that stop early on inputs the model is already confident about, evaluated on ImageNetV2 across multiple cascade depths and confidence thresholds to map out the accuracy/latency tradeoff on GPU. Done as part of the University of Houston RTS Summer Research Group; related work was submitted to IEEE RTSS.
[Repository](https://github.com/RH00000/UH_RTS_Research_ML)

## Currently

Applied Mathematics at UT Austin. Building software and ML/data projects outside coursework, and looking at a CS/Math double major. Interested in software engineering, product, and ML/AI, particularly where systems, data, and quantitative methods overlap.

## Tools

**Languages**
Python · Java

**Software**
Git · Jupyter · CLI tools

**ML / Data**
PyTorch · TensorFlow · scikit-learn · NumPy · Pandas · Matplotlib · NetworkX
