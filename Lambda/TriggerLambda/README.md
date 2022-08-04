Trigger a Lambda function using SQS. This Lambda function will process messages from the SQS queue and insert the message data as records into a DynamoDB table.


Start sending messages to our DynamoDB table from our Messages SQS queue with an interval of 0.1 seconds.

./send_message.py -q Messages -i 0.1