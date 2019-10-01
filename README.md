# awsAlarm
aws configure can make enstance create alarms and upload to cloudwatch automated.
AWS configure need access_Key_id, secret key, region and output format. I don't know the aws account of school, so I make it manually when first time set up. Good news is just need to set up once :).
region should be something like us-east-1 and output format is text. 

1. The alarm.py will create sns with a topic named alarm.
2. You will receive an email to verify.This would enable your email to connect with aws alarm.
3. We create 4 alarms:
