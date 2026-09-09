# Andrea Valente

AI Computer Vision Engineer working across model development, geometric vision and inference systems. I build evaluation pipelines and practical tools for applied ML and operational R&D workflows.

[Portfolio](https://valendrew.github.io/) · [Read CV](https://valendrew.github.io/cv/) · [LinkedIn](https://www.linkedin.com/in/andrea-valente0)

## Selected public projects

### [Counterfactual explanations](https://github.com/Valendrew/counterfactual-explanations)

`Python` · `OMLT` · `Pyomo` · `CPLEX` · `DiCE` · `Genetic search`

Co-developed an academic comparison of counterfactual explanations for smartphone price-class predictions: what feature changes would lead the model to a different class? The project compares optimisation with OMLT/Pyomo/CPLEX against DiCE, including genetic search for neural networks.

[Demo repository](https://github.com/Valendrew/counterfactual-demo)

### [NLP: POS tagging & abstractive QA](https://github.com/Valendrew/pos-tagging-abstractive-qa)

`Jupyter Notebook` · `GloVe` · `BiLSTM / BiGRU` · `TinyBERT` · `DistilRoBERTa` · `CoQA`

Contributed to comparisons of recurrent part-of-speech taggers and transformer encoder-decoder question-answering models. POS experiments compare frozen GloVe embeddings with BiLSTM, BiGRU and dual-layer variants; QA combines TinyBERT and DistilRoBERTa on CoQA, varying seeds and conversation history. QA results remained weak under a three-epoch, hardware-limited training budget; unanswerable questions were excluded.

### [VLSI design](https://github.com/Valendrew/vlsi-design)

`Python` · `MiniZinc` · `Constraint programming` · `Chuffed / Gecode` · `Strip packing`

Contributed to a university circuit-placement project that minimises plate height while preventing rectangular circuits from overlapping, with fixed and rotatable variants. My focus was constraint programming and Python solver comparisons; the team explored MiniZinc constraints, symmetry handling and search strategies alongside SMT and MIP approaches.

### [Video context pipeline](https://github.com/Valendrew/video-context-pipeline)

`Python` · `Pydantic` · `HTTPX` · `Async` · `Dependency planning`

A Python library and local browser builder for assembling transcription, video-understanding, metadata, media and text services. The documented architecture uses typed asynchronous configuration with Pydantic, dependency-based service planning and HTTPX provider adapters, with bounded retries, cancellation and owned-file cleanup. The browser builder exposes dependency graphs and JSON configuration export.

[All public repositories](https://github.com/Valendrew?tab=repositories)
