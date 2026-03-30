Pre-processing :- The raw EEG is cleaned to remove noise like power line interference, eye and muscle artifacts, and slow drift. This gives a clearer signal for analysis.

Adaptive Segmentation :- Instead of fixed 30-second windows, the signal is split based on actual changes in brain activity, giving more meaningful segments.

Feature Extraction :- Relationships between different frequency bands (delta to beta) are captured, showing how brain rhythms interact.

Quantum Embedding :- These features are mapped into a richer space using a quantum-inspired method (or a classical alternative if needed).

Backbone Model :- The model learns patterns over time and across channels, producing scores for each sleep stage.

Structured Decoder :- Predictions are refined using rules about how sleep stages normally transition and how long they last, along with uncertainty estimates.

Explainability :- Key sleep events are detected and combined with known rules to generate simple, interpretable reports.
