## Amazon Ip Space Changed

```json
{
   "Records":[
      {
         "EventVersion":"1.0",
         "EventSubscriptionArn":"arn:aws:sns:us-east-1:806199016981:AmazonIpSpaceChanged:330481fc-c27e-41db-bc7c-06540b6ff460",
         "EventSource":"aws:sns",
         "Sns":{
            "SignatureVersion":"1",
            "Timestamp":"2017-11-30T18:49:56.720Z",
            "Signature":"N8HL5PC4Moq19YHY1HhsWPQsrnP6WT9PZMfYSGMX+NEh8rh6w5NUBWPrljt7sRw6hOsOxUtky5ovfdlyVQQ9xfPQeHOG15hD+VQdhNk2v+eqhVrq7JyZO9Tap2K1Pf5WauRNZYr9LH6VOQa2G0Mr/aM3Qjg4uUH7sPyAFQlkjEAbWyMdQG6oipXpDDIFSGqX3bYg9cqMoJy7cMwDemfCuZk1f2i3WX/jjyOf4x4vXEfoEPsE61A/b3L0/rjtygavII0JF7lL8eQ5g4GVGGgjr+wci9FsJNcEJlIydZ73I6pKkhCrhqhkY/EIuxb1e+A2ItPwGhoEXCHal7gpv10vwA==",
            "SigningCertUrl":"https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
            "MessageId":"ff28ed80-ad39-5706-b41c-bf1af82d15b2",
            "Message":"{\"create-time\":\"2017-11-30-18-42-12\",\"synctoken\":\"1512067332\",\"md5\":\"e0a38abfb954152e33ccdd4a19fea03e\",\"url\":\"https://ip-ranges.amazonaws.com/ip-ranges.json\"}",
            "MessageAttributes":{

            },
            "Type":"Notification",
            "UnsubscribeUrl":"https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:806199016981:AmazonIpSpaceChanged:330481fc-c27e-41db-bc7c-06540b6ff460",
            "TopicArn":"arn:aws:sns:us-east-1:806199016981:AmazonIpSpaceChanged",
            "Subject":"IP Space Changed"
         }
      }
   ]
} 
```


## Amazon Linux AMI Updates

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:137112412989:amazon-linux-ami-updates:34dbb48f-f00d-4971-8d2d-0978f42e3330",
      "Sns": {
        "Type": "Notification",
        "MessageId": "31f1fd07-4074-560c-abac-af7d84c69e32",
        "TopicArn": "arn:aws:sns:us-east-1:137112412989:amazon-linux-ami-updates",
        "Subject": "Amazon Linux AMI: new images are available (2017.09.1.20171103)",
        "Message": {
          "v1": {
            "ReleaseVersion": "2017.09",
            "ImageVersion": "2017.09.1.20171103",
            "ReleaseNotes": "We\"ve updated the base AMI to include kernel 4.9.58 version that contains updates for ena 1.4.0, EC2 P3 instance support, and security updates.",
            "Regions": {
              "ap-northeast-1": [
                {
                  "ImageId": "ami-9d07a8fb",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-2803ac4e",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-df08a7b9",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-cc06a9aa",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-900aa5f6",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-9f08a7f9",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-f206a994",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-9808a7fe",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-9208a7f4",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-9a06a9fc",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "ap-northeast-2": [
                {
                  "ImageId": "ami-bc8723d2",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-fc862292",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-3081255e",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-a08024ce",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-7b802415",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-3181255f",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "ap-south-1": [
                {
                  "ImageId": "ami-a2d29fcd",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-2ed19c41",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-0ed09d61",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-b0d09ddf",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-efd29f80",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-bdd09dd2",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "ap-southeast-1": [
                {
                  "ImageId": "ami-60783403",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-dd7935be",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-3879355b",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-6f7a360c",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-bc7f33df",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-ac7834cf",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-07783464",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-13793570",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-62793501",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-047a3667",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "ap-southeast-2": [
                {
                  "ImageId": "ami-ab6b85c9",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-1a668878",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-42698720",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-31698753",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-6d66880f",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-4d69872f",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-4c69872e",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-40698722",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-35698757",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-a96a84cb",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "ca-central-1": [
                {
                  "ImageId": "ami-3a3f875e",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-ef3b838b",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-ea3c848e",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-e83c848c",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-4c3a8228",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-cb3a82af",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "eu-central-1": [
                {
                  "ImageId": "ami-4d890d22",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-e28d098d",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-c78e0aa8",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-08880c67",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-f18c089e",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-788f0b17",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-f38c089c",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-c88e0aa7",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-c98e0aa6",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-6b890d04",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "eu-west-1": [
                {
                  "ImageId": "ami-0a0cac73",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-760aaa0f",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-210bab58",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-4d06a634",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-b509a9cc",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-5008a829",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-c606a6bf",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-8104a4f8",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-0609a97f",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-790dad00",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "eu-west-2": [
                {
                  "ImageId": "ami-6d061a09",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-e3051987",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-db071bbf",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-70061a14",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-6a05190e",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-9b011dff",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "sa-east-1": [
                {
                  "ImageId": "ami-a27902ce",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-1678037a",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-bc7803d0",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-b07f04dc",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-cc7803a0",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-dc7902b0",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-3e790252",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-c47902a8",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-cf7902a3",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-577e053b",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "us-east-1": [
                {
                  "ImageId": "ami-c555e0bf",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-6057e21a",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-6d50e517",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-ff55e085",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-f957e283",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-dc54e1a6",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-aa56e3d0",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-8e55e0f4",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-d86adfa2",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-8b57e2f1",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "us-east-2": [
                {
                  "ImageId": "ami-a91b34cc",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-aa1b34cf",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-b51c33d0",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-4f1c332a",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-8d1b34e8",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-021e3167",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "us-west-1": [
                {
                  "ImageId": "ami-99023df9",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-1a033c7a",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-a8013ec8",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-44053a24",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-79023d19",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-7e023d1e",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-30013e50",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-7d033c1d",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-ab013ecb",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-33023d53",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ],
              "us-west-2": [
                {
                  "ImageId": "ami-d4d913ac",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-32d8124a",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-gp2"
                },
                {
                  "ImageId": "ami-93da10eb",
                  "Name": "amzn-ami-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-96da10ee",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-50df1528",
                  "Name": "amzn-ami-minimal-hvm-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-96c50fee",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-58de1420",
                  "Name": "amzn-ami-minimal-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-0ad81272",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-ebs"
                },
                {
                  "ImageId": "ami-cada10b2",
                  "Name": "amzn-ami-pv-2017.09.1.20171103-x86_64-s3"
                },
                {
                  "ImageId": "ami-d2da10aa",
                  "Name": "amzn-ami-vpc-nat-hvm-2017.09.1.20171103-x86_64-ebs"
                }
              ]
            }
          }
        },
        "Timestamp": "2017-11-06T20:13:38.882Z",
        "SignatureVersion": "1",
        "Signature": "OcaqRo/XUreULD+vlGjyd5IEMsXztKUDs6RlV5exfXWej8c66buZ6zwGQ2ZctPlk/kF0Rte7B2XAcDd1+k4++Stf1x6fiFgsEPSLM2HIp2GcKURsOdCUfQeW0HxtFsuDaSiqzh/YBc98ak9nXn2W/Cuanuo6nrvQQrxj7zz0dDn77Osk+hw7RKFC+Bik0jHIbHRH2u+dGhq6pZAy1S89BkGYd3A/0nDntOHrbwX9BKrY77W8lHhrn57eDbvqIn9y764oPLHKekAkIHUow2+nyygjsmzLGY88mPk+dWNKgTsdcB2M/IA2yKAyDQsVO3IBy8fZliASzKfynbhQbrotNw==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:137112412989:amazon-linux-ami-updates:34dbb48f-f00d-4971-8d2d-0978f42e3330",
        "MessageAttributes": {}
      }
    }
  ]
}
```

# Unreliable Town CLock

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:522480313337:unreliable-town-clock-topic-178F1OQACHTYF:fc67f648-dbbe-4979-823f-e5a4fae48b0c",
      "Sns": {
        "Type": "Notification",
        "MessageId": "808693f4-a27a-5906-a9de-c16a7dc68c80",
        "TopicArn": "arn:aws:sns:us-east-1:522480313337:unreliable-town-clock-topic-178F1OQACHTYF",
        "Subject": "[Unreliable Town Clock] chime: 2017-12-04 05:30 UTC",
        "Message": {
          "source": "townclock.chime",
          "type": "chime",
          "version": "3.0",
          "timestamp": "2017-12-04 05:30 UTC",
          "year": "2017",
          "month": "12",
          "day": "04",
          "hour": "05",
          "minute": "30",
          "day_of_week": "Mon",
          "unique_id": "956a1990-a8fa-66cc-66a1-8560bfa20597",
          "region": "us-east-1",
          "sns_topic_arn": "arn:aws:sns:us-east-1:522480313337:unreliable-town-clock-topic-178F1OQACHTYF",
          "reference": "http://townclock.io",
          "support": "Eric Hammond <eric-townclock@alestic.com>",
          "disclaimer": "UNRELIABLE SERVICE"
        },
        "Timestamp": "2017-12-04T05:30:36.107Z",
        "SignatureVersion": "1",
        "Signature": "HKVaq5cCc6hJGhJuiqQEYYOcr32gNei5jQ6rHAurdu0gLnV/Gi8jHNcsGjTcMVjvN2DQk+fM49fv6WlzFXEeNSz1JTl/XZ0KPbjK/Lq4qrtblc4tVVbZW1tGTc2hBkPN/qmkgzqfmYeVVZy3aoRQFHszFzkF6Mo1vPdgdYws6WJosFjmdD7N58mm71CjwZ3Lz4yEWK681VVctr/+QcAQA66sRhlvc6DQ68H+caRGb+aebi3Tq5KNrCCpPs23egA6KX3iTwCd1SKO2W8Gsl1G1ttrDEOP1CbV9aGq6khpTXa3QmPBbdeCpYwtWOUobdxYVGJcu4+6PG13ZEZXOd3T6w==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:522480313337:unreliable-town-clock-topic-178F1OQACHTYF:fc67f648-dbbe-4979-823f-e5a4fae48b0c",
        "MessageAttributes": {}
      }
    }
  ]
}
```

# Price List API

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:278350005181:price-list-api:b6dc2c01-c50a-43dd-ac75-b36bcb06a29b",
      "Sns": {
        "Type": "Notification",
        "MessageId": "3db593a2-5be7-5db0-8e5c-c13dac8cb9c0",
        "TopicArn": "arn:aws:sns:us-east-1:278350005181:price-list-api",
        "Subject": "[Pricing Update] New AWSConfig offer file available.",
        "Message": {
          "formatVersion": "v1.0",
          "offerCode": "AWSConfig",
          "version": "20171205010842",
          "timeStamp": "2017-12-05T01:08:44Z",
          "url": {
            "JSON": "https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/index.json",
            "CSV": "https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/index.csv"
          },
          "regionIndex": "https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/region_index.json",
          "operation": "Publish"
        },
        "Timestamp": "2017-12-05T01:23:55.452Z",
        "SignatureVersion": "1",
        "Signature": "IJqowmQrEPAuO7wODctUMyX2H9wNljZ4vm7z13zaK5mFfE6hwxU4zuusuCh+wGHg6bBU6/cCAva+u36nUuERqpahtMPu+tzkftFslDVOQaOFqot2c1giKvlpeROdiJt7oKsrdoVL9rkykoQ0Efvhv9I6IchezfllTt7J+SW55WanUUbc6Ot2xokvWedyXtqTEfCrrViVNGew16LWIH5VcsKbryYiF93LHJ19xGBCRHO/LrgpYt4lOS5fgNA+1jqTsYG3kGdDZICjQFM1N6St8WD29AxYu9XxbC5r+MU8KFRD99ATSgMyYGWVb+NqFAifNYtOAJPCTerKLlQgeHrTVA==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:278350005181:price-list-api:b6dc2c01-c50a-43dd-ac75-b36bcb06a29b",
        "MessageAttributes": {}
      }
    }
  ]
}
```
