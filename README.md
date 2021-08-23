# mParticle_Personalize_Lambda
mParticle_Personalize_Lambda Function

This is the sample code that will allow you to process events captured by mParticle sent down to AWS Kinesis.

This will handle the transformation of the events that will be sent to AWS Personalize.

Aside from forwarding the information to AWS Personalize, this Lambda function will also sent the recommended product ids generated/calculated by AWS Personalize to the associated customer  profile.
