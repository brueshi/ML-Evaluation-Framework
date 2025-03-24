# ML-Evaluation-Framework
A flexible, object-oriented evaluation framework that quantifies ML model performance across multiple dimensions to reveal capability trade-offs and scale efficiently for large-scale assessments.
Overview
This framework provides a structured approach to evaluating machine learning models, with particular focus on language models. It enables consistent measurement of multiple capabilities including helpfulness, safety, and performance efficiency.
Key Features

Modular Architecture: Easily extensible with new evaluation dimensions
Multi-criteria Evaluation: Assess models across various capabilities simultaneously
Trade-off Analysis: Understand compromises between competing objectives (e.g., helpfulness vs. safety)
Scalability: Efficiently process large evaluation datasets with parallel execution
Result Persistence: Save, load, and compare evaluation results across model versions

Core Components

BaseEvaluator: Abstract foundation for all evaluators
ScoringEvaluator: Calculates weighted scores across multiple criteria
CompositeEvaluator: Combines multiple evaluators for comprehensive assessment
Specialized Evaluators:

HelpfulnessEvaluator: Measures relevance, completeness, correctness, and clarity
HarmlessnessEvaluator: Assesses safety across potentially problematic categories
