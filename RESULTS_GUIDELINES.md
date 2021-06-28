# MLPerf™ Results Guidelines

The MLPerf name and logo are trademarks of MLCommons Association in the United States and other countries. Any use of the MLPerf trademark must conform to these terms of use. The MLCommons organization reserves the right to solely determine if a use of its name or logo, or the MLPerf trademark, is acceptable. Any use of the benchmark results under the MLPerf trademark must conform to the guidelines in this document.

## MLPerf results must clearly identify basic details in the main text, table, or figure

Any use of results must clearly identify the following in the main text, table, or figure: submitting organization, benchmark name, and system under test. For example:

_SmartAI Corp achieved a score of 0.6 on the MLPerf™ v0.7 Image Classification benchmark using a SmartCluster._

For Closed Division benchmarks, the model name may be used instead of the benchmark name, e.g. "SSD" instead of "Object Detection (light-weight)".

## MLPerf results must include a detailed footnote

Any use of results of must include the following in a footnote: benchmark suite, version, and division, benchmark name and scenario if applicable, date and source of retrieval, MLPerf result ID (major-version.minor-version.entry.benchmark), and clear reference to MLPerf trademark. For example:

_[1] MLPerf™ v0.5 Inference Closed ResNet-v1.5 offline. Retrieved from https://mlcommons.org/en/training-normal-05/ 21 December 2018, entry 0.5-12. The MLPerf name and logo are trademarks of MLCommons Association in the United States and other countries. All rights reserved. Unauthorized use strictly prohibited. See www.mlcommons.org for more information._

## MLPerf results may only be compared against similar MLPerf results

Whether comparing official results or unverified results, comparisons must be made between results of the same benchmark and scenario from compatible versions of an MLPerf benchmark. Compatible versions are determined by the MLCommons™ Association. MLPerf results may not be compared against non-MLPerf results.

MLPerf Training v0.5 and v0.6 are not directly compatible and should not be compared between submitters. A given system’s v0.5 and v0.6 submissions may be compared with each other provided that the base hardware is the same and the comparisons are done with sufficient analysis to remove influence of benchmark changes such as overheads and quality targets.

## When comparing MLPerf results, you must identify any submission differences

When comparing results the main text, table, or figure must clearly identify any difference in version, division, category, official or unverified status, scenario or chipcount. When comparing Open and Closed division results any ways in which the Open result would not qualify as a Closed result must be identified. 

_SmartAI Corp achieved a score of 0.6 on the MLPerf™ Image Classification benchmark using a SmartCluster with 8 chips in the RDI category of Closed Divsion which is faster than the result of 7.2 achieved by LessSmartAI Corp with 16 chips in the Available on-premise category of Closed Division._

## Official results must be clearly distinguished from unofficial results

You may cite either official results obtained from the MLPerf results page or unofficial results measured independently. If you cite an unofficial result you must clearly specify that the result is “Unverified” in text and clearly state “Result not verified by MLCommons™ Association” in a footnote. The result must comply with the letter and spirit of the relevant MLPerf rules. 

When claiming an unofficial result, you must specify all differences in HW/SW stack to a known official submission, if one exists on a similar platform.

For example:

_SmartAI Corp announced an unverified score of 0.3 on the MLPerf™ Image Classification benchmark using a SmartCluster running MLFramework v4.1 [1]._

_[1] MLPerf™ v0.5 Training ResNet-v1.5; Result not verified by the MLCommons™ Association. The MLPerf name and logo are trademarks of MLCommons Association in the United States and other countries. All rights reserved. Unauthorized use strictly prohibited. See www.mlcommons.org for more information._

Submitters are not allowed to publish any results for a given version before its official publication date. Non-submitters are not allowed to publish any unofficial results until two weeks after the official publication date for that version.

## MLCommons Association allows but does not endorse combining results of benchmarks

Users may see fit to combine or aggregate results from multiple MLPerf benchmark tests and/or other 3rd party results. If publicly disclosed, these composite results must cite MLPerf as required above and clearly describe the method of combination. However the composite result is not sanctioned by the MLCommons Association and may not be represented as an official MLPerf result or score.

## Comparisons based on secondary or derived metrics must be explicit

Each MLPerf benchmark has a primary metric, for instance time-to-train for Training Image Classification, or queries/sec for the Server scenario of Inference Image Classification (Datacenter system type). Any comparison based on different or derived metric such as power rating, cost, model size/architecture, accuracy, etc. must make the basis for comparison clear in the text and in a footnote. Secondary and derived metrics must not be presented as official MLPerf metrics.

_Prestigious Research University has created a new neural network model called MagicEightBall that is 100% accurate for Top-1 image classification on the MLPerf™ v0.5 Training Open Division Image Classification benchmark using a cluster of 10 SmartChips running MLFramework v4.1 [1]. MagicEightBall achieved a score of 20 minutes._

_[1] Accuracy is not the primary metric of MLPerf Training. The MLPerf name and logo are trademarks of MLCommons Association in the United States and other countries. All rights reserved. Unauthorized use strictly prohibited. See www.mlcommons.org for more information._

## Violation Determination, Remedies, and Penalties
 
Any MLCommons member may report a violation of Result Guidelines via email to the Executive Director & WG Chairs of appropriate benchmark. ED & WG chairs would inform potential violator and request remedial action. If ED, chairs, objector, and potential violator are unable to reach a mutually satisfactory conclusion, the issue can be raised in WG to seek resolution via WG vote.

A non-exhaustive list of possible remedial actions or penalties based on the degree of violation is noted below:
  1. Minor corrections to published materials in the form of marketing blog posts, journals, papers & other digital media
  2. If the violation was at a public event such as a conference, the committee may direct the violator to issue a public statement to correct claims in ways that conform to the guidelines
  3. The committee may issue a public statement citing the violation; suspend publication privileges or terminate license
  4. Continued failure to conform to these guidelines by a submitter may lead to marking the results as non-compliant in the results database permanently
  
THE SERVICE AND SOFTWARE ARE PROVIDED TO YOU "AS IS" WITHOUT ANY WARRANTY OR IMPLIED WARRANTY. NEITHER THE MLCOMMONS ASSOCIATION NOR ITS PARENT, SUBSIDIARIES, OR AFFILIATES (“MLCOMMONS”) TAKE ANY RESPONSIBILITY FOR ANY DIFFICULTIES YOU MAY ENCOUNTER WITH THE SERVICE OR SOFTWARE. MLPERF DOES NOT WARRANT THAT THE FUNCTIONS CONTAINED IN THE SOFTWARE OR OTHER PRODUCTS WILL MEET YOUR REQUIREMENTS, OR THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT DEFECTS IN THE SOFTWARE OR OTHER PRODUCTS WILL BE CORRECTED. NO ORAL OR WRITTEN INFORMATION, BENCHMARKS, BENCHMARK RESULTS, OR ADVICE GIVEN BY MLPERF (THE “MLCOMMONS CONTENT”) SHALL CREATE ANY WARRANTY.

MLCOMMONS IS NOT RESPONSIBLE FOR ANY PRODUCTS YOU MAY CHOOSE TO PURCHASE OR CHOOSE NOT TO PURCHASE AS A RESULT OF THE MLPERF CONTENT. MLCOMMONS DISCLAIMS ANY AND ALL LOSS OR LIABILITY RELATED TO YOUR USE OF THE WEBSITE, THE MLCOMMONS CONTENT GIVEN TO YOU ON THE WEBSITE OR SOFTWARE FROM THE WEBSITE, OR THIS AGREEMENT.

MLCommons is not liable for, among other things, any loss of data, hardware or software, or any liability resulting from: access delays; access interruptions; viruses; hackers; crackers; data non-delivery or mis-delivery; negligent acts, grossly negligent acts, or omissions by MLCommons; errors in any information, goods, or documents obtained due to the MLCommons Content; or force majeure, or any damages whatsoever resulting from loss of use, data or profits, whether in an action of contract, negligence or other action, arising out of or in connection with the use or performance of the Website, the MLCommons Content, the Service or the Software.

MLCommons makes no representations whatsoever about any other website that you may access through the Website. MLCommons has no control over the content or claims of websites outside the MLCommons domain, and does not endorse or accept any responsibility for the content of such websites.

MLCOMMONS, ITS REPRESENTATIVES, LICENSORS, AND PARTNERS WILL NOT BE LIABLE FOR ANY DAMAGES (INCLUDING DIRECT, INDIRECT, INCIDENTAL, CONSEQUENTIAL, SPECIAL OR PUNITIVE).

