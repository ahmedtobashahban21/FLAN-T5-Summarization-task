# 1.FLAN-T5-Summarization-Task
**Prompt Engineering**

## Notebook Overview 
This notebook consists of two primary sections:

1. **Summarize Dialogue Without Prompt Engineering**
   In this section, we employ the LLM (FLAN-T5-Base) model to generate summaries without relying on specific prompt texts.

2. **Summarize Dialogue With Instructional Prompts**
   Within this section, we delve into multiple phases:
   - Zero-Shot Inference
   - One-Shot Inference
   - Few-Shot Inference

   To provide precision, we explore various prompt sentence structures, with two distinct methods showcased in the notebook.

Throughout the notebook, we emphasize the augmentation of inferences and examples fed into the model to enhance overall accuracy.

# 2.Fine Tuning


use FLAN-T5 model, which provides high quality instruction tuned model and can summarize text out of the box, I will explore the full fine tuning approach and evaluate the result using Rouge metrics, then perform Parameter efficient Fine Tuning (PEFT), evaluate the result model and see the benefits of PEFT.

# Content
- 1.Load require dependencies,Dataset and LLM
  - 1.1-load the dataset and LLM
  - 1.2-test the model with zero shot inference


- 2.Perform Full Fine Tuning
  - 2.1-process the Dialogue summary dataset
  - 2.2-Fine-tune the model with perprocessed dataset
  - 2.3-Evaluate the model quality with Human Evaluate
  - 2.4-Evaluate the model quality with Rouge metrics.
- 3.Perform Parameter Efficient Fine Tuning
  - 3.1-Setup the PEFt/LoRa model for fine-tuning
  - 3.2-Train PEFT adapter
  - 3.3-Evaluate model quality with Human Evaluate
  - 3.4-Evaluate model quality with Rouge Metrics
