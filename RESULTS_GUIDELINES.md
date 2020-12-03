# MLPerf Results Guidelines

## MLPerf results must clearly identify basic details in the main text, table, or figure

Any use of results must clearly identify the following in the main text, table, or figure: submitting organization, benchmark name, and system under test. For example:

_SmartAI Corp achieved a score of 0.6 on the MLPerf Image Classification benchmark using a SmartCluster._

For Closed Division benchmarks, the model name may be used instead of the benchmark name, e.g. "SSD" instead of "Object Detection (light-weight)".

## MLPerf results must include a detailed footnote

Any use of results of must include the following in a footnote: benchmark suite, version, and division, benchmark name and scenario if applicable, date and source of retrieval, MLPerf result ID (major-version.minor-version.entry.benchmark), and clear reference to MLPerf trademark. For example:

_[1] MLPerf v0.5 Inference Closed ResNet-v1.5 offline. Retrieved from www.mlcommons.org 21 December 2018, entry 0.5-12. MLPerf name and logo are trademarks. See www.mlcommons.org for more information._

## MLPerf results may only be compared against similar MLPerf results

Whether comparing official results or unverified results, comparisons must be made between results of the same benchmark and scenario from compatible versions of an MLPerf benchmark. Compatible versions are determined by the MLPerf organization. MLPerf results may not be compared against non-MLPerf results.

MLPerf Training v0.5 and v0.6 are not directly compatible and should not be compared between submitters. A given system’s v0.5 and v0.6 submissions may be compared with each other provided that the base hardware is the same and the comparisons are done with sufficient analysis to remove influence of benchmark changes such as overheads and quality targets.

## When comparing MLPerf results, you must identify any benchmark differences

When comparing results the main text, table, or figure must clearly identify any difference in version, division, category, official or unverified status, or chipcount. When comparing Open and Closed division results any ways in which the Open result would not qualify as a Closed result must be identified. 

_SmartAI Corp achieved a score of 0.6 on the MLPerf Image Classification benchmark using a SmartCluster with 8 chips in the Open Divsion with an accuracy that is only 0.01% lower than the Closed requirement, which is faster than the result of 7.2 achieved by LessSmartAI Corp with 16 chips in the Closed Division._

## Official results must be clearly distinguished from unofficial results

You may cite either official results obtained from the MLPerf results page or unofficial results measured independently. If you cite an unofficial result you must clearly specify that the result is “Unverified” in text and clearly state “Result not verified by MLPerf” in a footnote. The result must comply with the letter and spirit of the relevant MLPerf rules. For example:

_SmartAI Corp announced an unverified score of 0.3 on the MLPerf Image Classification benchmark using a SmartCluster running MLFramework v4.1 [1]._

_[1] MLPerf v0.5 Training ResNet-v1.5; Result not verified by MLPerf. MLPerf name and logo are trademarks. See www.mlcommons.org for more information._

## MLPerf allows but does not endorse combining results of benchmarks

Users may see fit to combine or aggregate results from multiple MLPerf benchmark tests and/or other 3rd party results. If publicly disclosed, these composite results must cite MLPerf as required above and clearly describe the method of combination. However the composite result is not sanctioned by MLPerf and may not be represented as an official MLPerf result or score.

## Comparisons based on secondary or derived metrics must be explicit

Each MLPerf benchmark has a primary metric, for instance time-to-train for Training Image Classification. Any comparison based on different or derived metric such as power, cost, model size/architecture, accuracy, etc. must make the basis for comparison clear in the text and in a footnote. Secondary and derived metrics must not be presented as official MLPerf metrics.

_Prestigious Research University has created a new neural network model called MagicEightBall that is
100% accurate for Top-1 image classification on the MLPerf v0.5 Training Open Division Image Classification benchmark using a cluster of 10 SmartChips running MLFramework v4.1 [1]._

_[1] Accuracy is not the primary metric of MLPerf. MLPerf name and logo are registered trademarks. See www.mlcommons.org for more information._
