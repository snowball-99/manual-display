## AIDI Update description

### Version 3.2.2 Release Note

**Software upgrade**

(1) Update algorithm library

### Version 3.2.1 Release Note

**Software upgrade**

(1) The View Converter Tool now supports dividing into uniform sizes.

(2)  GUI Adaptation has been optimized for 2K/4K resolutions.

(3) Several other optimizations have been carried out.

### Version 3.2.0 Release Note

**Secondary development upgrade**

(1) Support secondary development example projects or sample code that can be exported and called based on optional rules

(2) New version switching tool added

(3) New environmental monitoring tools added

(4) Optimize Interface - C++Supplement Encoding Conversion Interface, Solve a Sample Repeated Inference Error Problem

(5) Optimize Interface - Supplement and Improve Image Format Conversion Interface

(6) Optimize Interface - C # Exceptions Can Distinguish Types

(7) Optimize Interface - C # supports custom log receiving objects

(8) The C # development framework can support a minimum of net framework 4.5

**Software upgrade**

(1) View converter supports Python scripts

(2) New area calculation tool added

(3) Upgrade of comprehensive judgment tool 　  The comprehensive judgment result can output comprehensive results (single result) and detailed algorithm results 　  Refactoring Script Editor

(4) New version conversion tool added

(5) Optimize annotation saving speed and engineering loading speed

(6) View reapplication, annotation saving logic optimization

(7) Support multi person collaborative training for different branches of the same project

**Algorithm upgrade**

(1) CPU inference performance upgrade

(2) Optimizing OCR inference time increases the problem

### Version 3.1.3 Release Note

(1) Fixed some known bugs

### Version 3.1.2 Release Note

(1) Fixed some known bugs

(2) Updated the default maximum value of region threshold

### Version 3.1.1 Release Note

(1) Fixed some crash problems

(2) Fixed some abnormal display issues

(3) Fixed the problem of importing third-party annotations that may possibly crash

### Version 3.1.0 Release Note

**Algorithm upgrade:**

**Level 1:**

(1) Detection: Added high-precision mode

(2) OCR: Added character correction and template correction

(3) Segmentation: Add high-precision model

(4) All modules: Improve Validation speed

**Level 2:**

(1) Lights-out segmentation: detection accuracy increased to 5*5

(2) Segmentation and classification: Added training recommendations based on data set type

(3) Improved multi-GPU training efficiency

(4) All modules support CPU training and validation

(5) Optimize classification and lights-out classification memory usage

**Level 3:**

(1) All modules optimize the slow validation speed of the first image.

(2) All modules have optimized the problem; the more annotations, the slower the training starts.

(3) Fix the crash problem of segmented incremental training

(4) Fix the problem of poor recommendation effect of segmented sample recommendation

(5) Optimize the training speed when segmenting complex data and labelling too much

(6) Fix the problem that lights-out segmentation of multiple GPU(s) is slower than that of a single GPU

(7) Fix the problem of edge over-inspection in lights-out segmentation

(8) Added OCR character polarity settings, focusing on optimizing the OCR detection effect of white text on black background scenes

(9) Added OCR single character matching string function

(10) Under the comprehensive judgment tool, the segmentation and unsupervised segmentation modules are newly added with "relative grayscale" and "roundness" judgments.

**Key software upgrades:**

**Level 1:**

(1) Support annotation import and export

(2) The speed of saving annotations is greatly improved.

(3) The Inspector supports rendering of inference results.

(4) New project cleaning (the volume can be greatly reduced)

(5) AQCloud adaptation completed

**Level 2:**

(1) Regular mode supports one-click validation for All

(2) Factory mode supports single-flow validation

(3) Inspector: "Other" category supports renaming

(4) Added magic wand hole tool for filling

(5) Training information displays adaptive accuracy value

**Level 3:**

(1) Image Tag supports quick deletion

(2) Comprehensive indicators support click jump

(3) Added reset feature to image list under factory mode

(4) Switch module to automatically record list position

(5) Add image tag management function to the main interface of the algorithm module

(6) Factory mode adds classification and lights-out classification that validates graphics elements of results.

(7) Optimization of two-point circle drawing tool

(8) Annotation supports corrosion expansion

(9) Inspector: new judgment function management, supporting custom preset functions

(10) The default condition in Inspector is OR

(11) Add & optimize attention information, guidance information and prompts

(12) Optimize several displays: Workflow, coordinate values, confusion matrix, shortcut key information, and reports

(13) Optimize some interactions: the pop-up window supports enter, a shortcut key is added for switching annotation types, and the number of columns is automatically filled when the image list is stretched.

(14) Add manual refresh to project management

(15) Confusion matrix in the OCR module hides all 0 rows and columns

(16) Added module name to automatically match language settings

**Secondary development upgrade:**

(1) Secondary development supports asynchronous validation

(2) Secondary development supports Labview tool kit 

### Version 3.0.2 upgrades

(1) GPU driver installation link adapts to the system language.

(2) Add the user documentation and development documentation in English

### Version 3.0.1 upgrades

(1) Support Traditional Chinese version, Traditional Chinese operation system.

(2) Fixed connection problem in INTEGRATE

### Version 3.0.0 upgrades

**Key algorithm upgrades**

(1) Segmentation supports incremental training - improving the training speed during model iteration

(2) Positioning - single point annotation, the required sample size is reduced, the training parameters are adaptive, and the

usability is improved

(3) Unsupervised classification upgrade - Training speed is greatly improved

**Other algorithms upgradess**

(4) Improved segmentation stability

(5) Unsupervised segmentation inference video memory optimization

(6) Classification module low-precision scenarios, inference speed increased by 50%

(7) Assembly inspection supports multi-scale targets

(8) Assembly inspection supports Angle prediction

**Key software upgrades**

(1) Support tree flow chart: module series parallel

(2) Support full module factory mode

(3) New comprehensive decision node: used to summarize the results of each module and give the final classification

(4) New image tag & view tag system

(5) The annotation and test results of each module are stored in the original drawing, and do not disappear with the change of the

previous module

(6) Image list single-column multi-column display seamless switching, supported and/or/not filter conditions

(7) Add an automatic mask, which can automatically convert the results of the previous module into a mask

**Other software feature upgrades**

(8) Project management upgrade: increase the work area

(9) Project added version management: The version can be rolled back

(10) New UI upgrade: enhanced guidance

(11) Evaluation and upgrading of all modules

(12) Module reorganization: rapid detection and detection modules are merged, assembly inspection + layout templates are split

from positioning

(13) The module can be copied

(14) Reduce resource occupation during project use

(15) Annotation tool upgrade: OCR multi-line fast annotation, positioning/assembly fast annotation, segmentation/unsupervised

segmentation ROI magic stick

(16) Data division supports balance between classes

(17) Automatic weight removal of reasoning results

(18) Unsupervised segmentation score distribution map optimization

(19) Automatic allocation can be used for training inference by GPU

(20) The time consuming statistics increased to the maximum

**Secondary development upgrades**

(1) can directly return the inference result class

(2) provide direct parameter class modification interface

(3) the provided geometric library can be directly calculated for calculating the defect area and other features

(4) Flexible access to intermediate results of any tool

### Compatibility Notes

(1) AIDIV3.1 is compatible with AIDIV3.0 projects and can be opened directly. At the same time, a backup project file will be automatically generated in the source path. If there is insufficient disk space, an attention that the conversion failed will pop up. Now, you need to cut the original old version project to a disk with sufficient storage space and re-execute.

(2) Due to the significant upgrade of the software architecture, AIDI3.1 cannot directly open AIDI2.2/2.3/2.4 version project, but MarkMan (aqlabel) supports reuse.
