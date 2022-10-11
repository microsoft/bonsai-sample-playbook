# Bonsai Sample Playbook

## Objective

The Bonsai Sample Project Playbook intends to provide an overview of our approach for the successful delivery of a sample project. This site aggregates best practices and resources for project scoping and delivery.

## What is a Bonsai Sample?

A Bonsai Sample is a demonstrator that can be built to serve one or many purposes. Some examples include:

* Showcasing Bonsai functionality
* Proving Bonsai Brains can outperform prevailing industry methods
* Demonstrating a specific Bonsai use case or vertical
* Showcasing a specific simulator connection
* Demonstrating a Partner's capabilities

## Principles

When building a sample, keep the following principles in mind to make the most impact:

- **Reproducible** - repeatable results give credibility to the sample and story
- **Explainable** - keep the sample as simple as possible to make the story as concise and impactful as possible
- **Realistic Complexity** - make sure to have enough realistic complexity to show a brain outperforming the prevailing industry method. For example, the [Chemical Reactor sample simulation](https://github.com/microsoft/bonsai-cstr) includes noise to show when a brain succeeds over a gain scheduled PI controller.
- **Maintainable** - ensure the sample can be used at scale

## Recommended Bill of Materials

A great sample will include all of the following components:

### 1. AI Spec
This is the brain design document that describes what brain should be built and why. This is often written by a Solution Architect and used by an Applied AI engineer as a starting point to write the brain specification, called Inkling.

- See the [AI Spec Template](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/AISpec_TEMPLATE.docx)

- Take the free Coursera courses [Machine Teaching for Autonomous AI](https://www.coursera.org/learn/machine-teaching-ai) and [Designing Autonomous AI](https://www.coursera.org/learn/designing-autonomous-ai) to learn how to identify Bonsai use-cases and write an AI spec

- Talk to your Bonsai sales or partner representative to learn about enrolling in the instructor led Cultivate course

- Example: [Chemical Reactor AI Spec](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/AISpec_ChemicalReactorSample.docx)

- Example: [Moab AI Spec](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/AISpec_MoabBalance.docx)

### 2. Simulation
This is the training environment for the Bonsai brain.

+ See [simulation documentation](https://learn.microsoft.com/en-us/bonsai/product/components/simulation)

+ See [Python Samples](https://github.com/microsoft/microsoft-bonsai-api/tree/main/Python/samples) on github

+ See [MATLAB Simulink Samples](https://github.com/microsoft/bonsai-simulink/tree/main/samples) on github

+ See [AnyLogic Samples](https://github.com/microsoft/bonsai-anylogic/tree/master/samples) on github

+ See [VP Link Samples](https://github.com/capesoftware/bonsai-vplink/tree/main/samples) on github

+ See [ROS Samples](https://github.com/microsoft/ROS-bonsai-connector/tree/main/samples) on github

### 3. Inkling
This is the Brain specification that defines what and how a brain is trained. 

- See [Inkling Documentation](https://learn.microsoft.com/en-us/bonsai/inkling/basics)

- Talk to your Bonsai sales or partner representative to learn about enrolling in the Bonsai Advance Course

### 4. Visualizer
The Bonsai App visualizer allows you to create custom visualizations of your simulation that can be viewed in the Bonsai Web UI during brain training and assessment.

+ Learn about visualizers and find examples on [github](https://github.com/microsoft/bonsai-viz-example)

+ Example: [Chemical Reactor visualizer](https://github.com/microsoft/bonsai-cstr)

### 5. Benchmark 
This is the prevailing industry method that the brain will be compared against to define success.

- Example: [Chemical Reactor Sample](https://github.com/microsoft/bonsai-cstr)

### 6. Test protocol 
Documented instructions of how results were obtained so they can be replicated.

### 7. Results
The data that shows how a brain performs compared to a benchmark

- Example: see the final slide of the [Chemical Reactor Story Presentation](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/ChemicalReactorStory.pptx)

### 8. Sample Story
Storytelling is an important technique for communicating the value of the Sample that you design.

- You can learn how to tell a use case story by taking the free [Coursera course](https://www.coursera.org/learn/machine-teaching-ai) or the instructor led Cultivate course

- Example: [Chemical Reactor Story Presentation](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/ChemicalReactorStory.pptx)

### 9. Demo Script
A demo script allows others to tell the sample story and demo the sample for others.

- Example: [Moab Demo script](https://github.com/defeirst/defeirstpage.github.io/blob/main/docs/ProjectMoabDemoScript-1page%20.docx)

### 10. Demo Video
A demo video is a recording of the sample story and demo

- Example: [Chemical Reactor demo video](https://www.youtube.com/watch?v=mMhdItO21Bk&feature=youtu.be)

### 11. Publication (white paper)
Publication of sample results and why they are valuable

### 12. Azure Marketplace Listing

- Example: [CSTR marketplace listing](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoftcorporation1638560120339.bonsai_cstr_sample?tab=Overview)
