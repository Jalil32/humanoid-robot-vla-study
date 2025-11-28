# VLA Humanoid Robotics Benchmark

A comprehensive benchmarking framework for evaluating Vision-Language-Action (VLA) models on humanoid robots, with empirical assessment of NVIDIA Isaac GR00T N1.5 deployed on the Unitree G1 platform.

## Overview

This research investigates the practical viability of transformer-based VLA models as a foundation for embodied intelligence. Through rigorous real-world testing, this study provides the **first independent empirical assessment** of Isaac GR00T's performance outside controlled laboratory environments.

### Key Findings

- **Strong Object Detection**: Robust object recognition and semantic understanding
- **Critical Limitations**: Significant fragility in spatial reasoning and depth estimation
- **Generalization Gap**: Minor environmental changes (10cm table height variance, distractor objects) caused complete task failure
- **Industry Reality Check**: Revealed substantial gaps between reported benchmark performance and real-world deployment reliability

## Research Contributions

### 1. Comprehensive Benchmarking Framework
Evaluates VLA systems across five capability dimensions:
- **Perception** - Object detection and scene understanding
- **Language Understanding** - Natural language instruction processing
- **Planning** - Task decomposition and sequencing
- **Manipulation** - Physical interaction and control
- **Generalization** - Performance on unseen tasks and environments

### 2. Hierarchical Task Structure
30+ trials across increasing complexity levels, designed to systematically stress-test model capabilities in realistic scenarios.

### 3. Real-World Deployment Insights
Empirical evidence of the environmental sensitivity and embodiment-dependence that limit current VLA models to structured, tightly calibrated domains.

## Technical Stack

- **VLA Model**: NVIDIA Isaac GR00T N1.5
- **Hardware Platform**: Unitree G1 Humanoid Robot
- **Methodology**: Iterative fine-tuning, system integration, experimental evaluation

## Key Conclusions

While transformer-based VLA models represent a major conceptual advance in unifying perception and action sequences, this research demonstrates that:

1. Current models exhibit high sensitivity to environmental variations
2. Performance degrades rapidly outside trained configurations
3. A persistent gap exists between controlled benchmark results and real-world reliability
4. Deployment remains limited to structured, calibrated environments

These findings have important implications for the development and deployment of embodied AI systems in unstructured real-world settings.

## Repository Structure
```
├── benchmarking-framework/    # Evaluation framework implementation
├── experiments/               # Experimental protocols and results
├── data/                      # Dataset and task configurations
├── paper/                     # Thesis document (LaTeX + PDF)
└── docs/                      # Additional documentation
```

## Citation

If you use this work in your research, please cite:
```bibtex
@mastersthesis{[Jalil Inayat-Hussain]2025,
  title={Vision Language Action Models for Humanoid Robotics: Evaluating Capabilities, Limitations, and Future Directions},
  author={[Your Name]},
  year={2025},
  school={University of Western Australia},
  type={Master's Thesis}
}
```

## Acknowledgments

Supervised by Professor Thomas Bräunl at the University of Western Australia.

---

**Note**: This research was conducted as part of a Master of Professional Engineering in Software Engineering at UWA.
