# Time-Series
DESCRIPTION

1. Implemented an Unsupervised Domain Adaptation (UDA) framework for time-series forecasting using  Domain Adversarial Neural Networks (DANN) to enable effective model generalization across distinct data distributions without requiring target-domain labels. 

2. Integrated a Gradient Reversal Layer (GRL) and domain discriminator to facilitate adversarial training, optimized via a custom bottleneck Adapter module to extract domain-invariant temporal features while freezing the pre-trained backbone by fine-tuning only 16% of total parameters. 

3. The architecture effectively balanced task-specific Mean Squared Error (MSE) loss with binary cross-entropy to adapt universal temporal patterns to target-domain characteristics. 

4. Developed a Autoregressive training procedure that simulates real-world domain shift by feeding iterative predictions back into the model, significantly improving target-domain performance on electricity transformer datasets. 
