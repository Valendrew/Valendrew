# Andrea Valente

AI Computer Vision Engineer working across model development, geometric vision and inference systems. I build evaluation pipelines and practical tools for applied ML and operational R&D workflows.

I like building things when I have a real problem of my own to fix, and I usually end up making them public ([relevant xkcd](https://xkcd.com/1319/)).

[Portfolio](https://valendrew.github.io/) · [Read CV](https://valendrew.github.io/cv/) · [LinkedIn](https://www.linkedin.com/in/andrea-valente0)

## Selected public projects

### [Counterfactual explanations](https://github.com/Valendrew/counterfactual-explanations)

`Python` · `PyTorch` · `OMLT` · `Pyomo` · `CPLEX` · `DiCE`

What would a phone need to change for a price classifier to put it in another price range? The project encodes a PyTorch classifier as mixed-integer constraints (OMLT, Pyomo, CPLEX) and compares the resulting counterfactual explanations with DiCE's genetic search on validity, sparsity and realism. An interactive demo (FastAPI, Vue) shows which features change.

[Demo repository](https://github.com/Valendrew/counterfactual-demo)

### [Rectangular circuit placement (VLSI)](https://github.com/Valendrew/vlsi-design)

`Python` · `MiniZinc` · `Constraint programming` · `SMT` · `MIP` · `Strip packing`

Places rectangular circuits on a plate of fixed width without overlaps, keeping the plate as short as possible. The same problem is modelled in constraint programming (MiniZinc), SMT (Z3, CVC4) and mixed-integer programming (PuLP, CPLEX), with a shared Python harness that compares them on 40 instances.

### [Comparative argument retrieval](https://github.com/Valendrew/argument-retrieval-comparative-questions)

`Python` · `Pyserini` · `FAISS` · `MonoT5` · `DistilBERT`

Finds passages that answer comparative questions ("is X better than Y?") and classifies their stance. Compares keyword, dense, hybrid and MonoT5-reranked search over a large passage corpus: hybrid fusion gave the best recall, neural reranking the best top-five ranking.

### [Video context pipeline](https://github.com/Valendrew/video-context-pipeline)

`Python` · `Pydantic` · `HTTPX` · `Async` · `Dependency planning`

A Python library that turns a video link into a transcript, a visual description, metadata and media, so an application can use videos without handling the downloading and processing itself. Steps run in dependency order with bounded retries and cleanup, and a local browser builder shows each pipeline and exports its configuration.

[All public repositories](https://github.com/Valendrew?tab=repositories)
