# Deep Learning Stack
 
Amazon [Sagemaker Python SDK](https://github.com/aws/sagemaker-python-sdk) is a higher level python interface to Sagemaker which is a really convenient way to orchestrate training and inference. 

* [TensorFlow Estimators](https://sagemaker.readthedocs.io/en/stable/using_tf.html)
* [Pytorch estimators](https://github.com/aws/sagemaker-python-sdk#pytorch-sagemaker-estimators)
* [Bring your own docker containers](https://sagemaker.readthedocs.io/en/stable/overview.html#byo-docker-containers-with-sagemaker-estimators)
 
The [Sagemaker Examples Repository](https://github.com/awslabs/amazon-sagemaker-examples) has a variety of examples that could be of interest:
* [Hyperparameter Tuning with Tensor Flow](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/hyperparameter_tuning/tensorflow_mnist)
* [Using Sagemaker Debugger with a Custom Pytorch Container](https://github.com/awslabs/amazon-sagemaker-examples/blob/master/sagemaker-debugger/pytorch_custom_container/pytorch_byoc_smdebug.ipynb)
 
More links:
* [Hyperparameter Tuning](https://docs.aws.amazon.com/sagemaker/latest/dg/automatic-model-tuning-ex.html) – Search for optimal parameter settings (in parallel)
* [Sagemaker Debugger](https://docs.aws.amazon.com/sagemaker/latest/dg/train-debugger.html) – Detect issues, e.g., with vanishing gradients
* [Experiments](https://github.com/aws/sagemaker-experiments) — to track different training/tuning jobs
* [Managed Spot Training](https://docs.aws.amazon.com/sagemaker/latest/dg/model-managed-spot-training.html) – to save costs during training
 
# Vision Stack 
 
## Frameworks Layer: 
[Sagemaker Python SDK](https://github.com/aws/sagemaker-python-sdk) is a higher level python interface to Sagemaker which is a really convenient way to orchestrate training and inference. The [Sagemaker Examples Repository](https://github.com/awslabs/amazon-sagemaker-examples) has a variety of examples that could be of interest:
* [Hyperparameter Tuning with TensorFlow](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/hyperparameter_tuning/tensorflow_mnist)
* [Using Sagemaker Debugger with a Custom Pytorch Container](https://github.com/awslabs/amazon-sagemaker-examples/blob/master/sagemaker-debugger/pytorch_custom_container/pytorch_byoc_smdebug.ipynb)
 
## ML Services: 
Sagemaker has built-in algorithms for [object detection](https://docs.aws.amazon.com/sagemaker/latest/dg/object-detection.html) and [semantic segmentation[](https://docs.aws.amazon.com/sagemaker/latest/dg/semantic-segmentation.html). [Sagemaker Ground Truth](https://docs.aws.amazon.com/sagemaker/latest/dg/sms.html) enables a combination of labeling/annotation workflows with active learning. Examples demonstrating all these features can be found in the [Sagemaker examples repository](https://github.com/awslabs/amazon-sagemaker-examples).
 
## AI Services: 
[Rekognition](https://docs.aws.amazon.com/rekognition/latest/dg/what-is.html) supports a variety of use cases related to image and video including object detection, face and celebrity recognition, and content moderation. For cases where you need domain-specific object labels (e.g., road signs, company logs), we offer [Rekognition Custom Labels](https://docs.aws.amazon.com/rekognition/latest/customlabels-dg/what-is.html) where you can upload training data to customize the detected objects.
[Textract](https://docs.aws.amazon.com/textract/latest/dg/what-is.html) enables high-accuracy text extraction/OCR from images (PDF, JPEG etc)
 
# Partnerships: 
[AWS Data Exchange](https://aws.amazon.com/data-exchange/) provides startups a way to monetize the expensive datasets that need to be created for visionuse cases.
