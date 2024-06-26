# Enhancing NLP Classification for Real-Time Response: Improvements with Fine-Tuning Optimizations

Numerous tasks these days depend on the quick and accurate 
classification from Natural Language Processing models for critical tasks. 
In order to decrease inference time and increase speed, model
quantization is a popular technique used now-a-days for resource
constrained devices and tasks. Model quantization techniques 
however trade fine-tuning and inference time for model efficacy. In
order to bridge this gap in accuracy, we are attempting model 
aggregation techniques on top of model quantization.

Our project, focused on optimizing NLP models for resource 
constrained devices, directly benefits queries requiring swift inference
like SQL injection classification, emergency response tweet 
categorization and stock market headline information extraction. By
implementing efficient model quantization and weight aggregation
techniques, our approach aims to rapidly classify text data without
compromising accuracy.

In reviewing related work, previous research has explored 
various techniques in quantization and model souping but in entirely
different domains. While these approaches have shown promise,
they often struggle to preserve the full complexity of the original
model, leading to suboptimal performance in downstream tasks.
Our approach differs by introducing model souping into the 
quantization framework, thus preserving some amount of information
lost. This weight aggregation strategy aims to mitigate loss 
effectively while maintaining or even 
improving the performance of the models.

We have made a script to run the training and inference together. Please run the following commands from inside the src folder:

```python3 run_everything.py```

The configurations are listed with their usage in the script itself, so any changes to the configurations can be made in this singular script. The results for each type of souping technique will get stored in the root directory.
