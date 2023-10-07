# contact-form-spam-detection

## Text Classification for email-spam detection
This model is based on Text classification using pytorch library. In this model we propose to used a torchtext library for tokenize & vectorize data. This model is used in corporate and industrial area for mail detection. It is used three label like job, enquiry and spam. It achieve the following results on the evalution set:
* accuracy : 0.866

## model architecture for text classification :
![](https://github.com/foduucom/contact-form-spam-detection/blob/main/text%20classification.jpeg)

## Label for text classification:
* Enquiry
* Job
* Spam

## Training hyperparameters
The following hyperparameters were used during training:
* learning_rate: 0.01
* train_batch_size: 64
* step_size: 10
* optimizer: Adam
* lr_scheduler_type: StepLR
* lr_scheduler.StepLR:(optimizer,step_size=10,gamma=0.1)
* num_epochs: 10
