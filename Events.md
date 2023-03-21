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

# Daily Aggregated Price List API

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:278350005181:daily-aggregated-price-list-api:d4144657-7d47-4982-b1e4-ca5998cd6adb",
      "Sns": {
        "Type": "Notification",
        "MessageId": "5c604421-eec6-5490-84d0-16813dc15c3c",
        "TopicArn": "arn:aws:sns:us-east-1:278350005181:daily-aggregated-price-list-api",
        "Subject": "[AWS Pricing Update] We have published new versions of the service offer files.",
        "Message": "Hello,\n\nYou have received this notification because you subscribed to receiving updates from SNS topic arn:aws:sns:us-east-1:278350005181:daily-aggregated-price-list-api\n\nWe have published a new version of the offer file for Service AWSConfig. Use the following URLs to download the file:\n - JSON Format : https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/index.json\n - CSV Format : https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/index.csv\n - Region Index Url : https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AWSConfig/current/region_index.json\n\nTo learn more about the file formats, see http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-changes.html.\n\nThank You,\nAmazon Web Services Team",
        "Timestamp": "2017-12-05T17:00:55.397Z",
        "SignatureVersion": "1",
        "Signature": "KybgwfmRYd2vRYUPc8NBZBkiN167E2/xtpKVp1Skfh0PbvU0aVJm/Z3H0c/QZdL16w16I7v7YRdaKutTUhvRyQ2As7JycAUbMhopmckz2hz6IRvs40H0Csv3TCnGOvsaBCSeGfYq3u8MaBk0N8g93CczzZE3nChWESzrIPf5X0Hy15fm0tbD5wcxHttZGG4xsVbQ7zOy0PqdrD+FMgSNPFNcYY7bO6fPLm04TrwaxyZ2VKFVwAn3HxDa9SUukyR3EQrQ4I7x5sYD2iYrH6fWd8VM6fQulMg9qH4AfBlBxCEuFZiCurTY+sqFpREf0025vJUbpkNo52WFUZRHvaqOFQ==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:278350005181:daily-aggregated-price-list-api:d4144657-7d47-4982-b1e4-ca5998cd6adb",
        "MessageAttributes": {}
      }
    }
  ]
}
```

# Windows AMI Update

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:801119661308:ec2-windows-ami-update:04269066-485b-4e5a-86cc-3d96f446d8ce",
      "Sns": {
        "Type": "Notification",
        "MessageId": "c83c6837-707d-5cb0-a737-3afca0539aa2",
        "TopicArn": "arn:aws:sns:us-east-1:801119661308:ec2-windows-ami-update",
        "Subject": "New AMIs dated 2018.01.05 now available",
        "Message": "A new version of Amazon Machine Images has been released. All previous versions of Amazon published Windows AMIs will be deprecated on Monday, January 29th, 7AM (Pacific). Please use this time to update any dependencies such as CloudFormation or AutoScaling groups.\n\nEC2 Quickstart, AWS MarketPlace and CloudFormation templates will be updated over the next few days.\n\nNew AMIs are dated 2018.01.05. (search for this using the AWS Console or PowerShell ‘Get-EC2ImageByName’)\n\nChanges:\n• Microsoft Security Updates current to January 2018\n• Registry settings to enable the mitigations for the Spectre and Meltdown exploits\n• Updated .Net SDK/PowerShell Tools\n• Latest EC2Config\n• Cloud Formation\n\nReferences:\n\nEC2 Quickstart: https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstanceWizard:\nAWS Marketplace: https://aws.amazon.com/marketplace/seller-profile/ref=srh_res_product_vendor?ie=UTF8&id=e6a5002c-6dd0-4d1e-8196-0a1d1857229b\nWindows AMI Versions: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/windows-ami-version-history.html\nPowershell in AWS: http://aws.amazon.com/powershell/\nCloudFormation: http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/ReleaseHistory.html\nEC2Config Service: http://aws.amazon.com/developertools/5562082477397515\n\nRegards,\nAmazon EC2 for Windows Team",
        "Timestamp": "2018-01-07T07:36:14.987Z",
        "SignatureVersion": "1",
        "Signature": "Kvoxjj22vMg3Ov/rxwghPkjNMNoRKCNhQTbHO6Pv3ec6chLq4fqhEKJSzS9k1I0hxvbZ56Eoh4IaeDhkIrpTJhSYzghK4dhO4UfdN3nR2Sm0stm4YzGTEemDtD12Wn6qSzKQmzk/0WqwLkzxw2YMBHi43uY4Q56RN31B8bWMZj7yUIfocKsB6OYumLsk14/on09K6vavUa/Pvt89awQUZRQ60LwBbVAKFTm5XZIsqqpSMPL6ftrByG8iYLrgSS853dPO2daBElYvoT2d7CNdcZOAh+KoIWlcxffN7os5Ri61oatepmfA1PiWjDdl0/czkcltsoeuFggapTCe82QzGw==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:801119661308:ec2-windows-ami-update:04269066-485b-4e5a-86cc-3d96f446d8ce",
        "MessageAttributes": {
          "AWS.SNS.MOBILE.MPNS.Type": {
            "Type": "String",
            "Value": "token"
          },
          "AWS.SNS.MOBILE.MPNS.NotificationClass": {
            "Type": "String",
            "Value": "realtime"
          },
          "AWS.SNS.MOBILE.WNS.Type": {
            "Type": "String",
            "Value": "wns/badge"
          }
        }
      }
    }
  ]
}
```

# ECS Optimized Windows AMI Update

```json
{
  "Records": [
    {
      "EventSource": "aws:sns",
      "EventVersion": "1.0",
      "EventSubscriptionArn": "arn:aws:sns:us-east-1:177427601217:ecs-optimized-amazon-ami-update:6858e335-bc5b-4788-971e-4207f48728da",
      "Sns": {
        "Type": "Notification",
        "MessageId": "163ab552-da6f-596f-9437-e79a17ccfcd0",
        "TopicArn": "arn:aws:sns:us-east-1:177427601217:ecs-optimized-amazon-ami-update",
        "Subject": "None",
        "Message": {
          "ECSAgent": {
            "ReleaseVersion": "1.16.1"
          },
          "ECSAmis": [
            {
              "ReleaseVersion": "2017.09.e",
              "AgentVersion": "1.16.1",
              "ReleaseNotes": "This AMI includes the latest ECS agent 1.16.1",
              "OsType": "linux",
              "OperatingSystemName": "Amazon Linux",
              "Regions": {
                "ap-northeast-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-af46dbc9"
                },
                "ap-northeast-2": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-d6f454b8"
                },
                "ap-south-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-c80b5fa7"
                },
                "ap-southeast-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-fec3b482"
                },
                "ap-southeast-2": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-b88e7cda"
                },
                "ca-central-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-e8cb4e8c"
                },
                "cn-north-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-f9a37e94"
                },
                "eu-central-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-b378e8dc"
                },
                "eu-west-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-7827b301"
                },
                "eu-west-2": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-acd5cdc8"
                },
                "eu-west-3": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-bd10a7c0"
                },
                "sa-east-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-ca95d6a6"
                },
                "us-east-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-13401669"
                },
                "us-east-2": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-901338f5"
                },
                "us-west-1": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-b3adacd3"
                },
                "us-west-2": {
                  "Name": "amzn-ami-2017.09.e-amazon-ecs-optimized",
                  "ImageId": "ami-9a02a9e2"
                }
              }
            }
          ]
        },
        "Timestamp": "2018-01-05T00:48:35.408Z",
        "SignatureVersion": "1",
        "Signature": "GLI53lDnjNxuMLLHy+dDlMlmYaToxbuke9eiLZvue9Wji7CQJBNmETVYqTDqCRdGLwKexEuPDD5L7OR1H8fC3sAKu3xNJ5VnkxKal0bvbu4SWPUQCddu4V701v2Wn9Cr+MBd4s5/7nwifIqFZ7A8speJZ9HO362pkU3ZT08DRzex0ZDq/5CHXVmFVmUWI0gfsWBS7a41H0KPOn9nUo74VYB7Cc1lLFDbWSGGMLZ75poIB4tx8BxS9TQI5ZrhNhZ7Q6X0XCUPyAeOEKhepFtn007xfZTxJwUpkdNHib/Ih98B9z4T6FTNDyx071o8meTH6cUZL7K5eJEE1i9l75Z6XA==",
        "SigningCertUrl": "https://sns.us-east-1.amazonaws.com/SimpleNotificationService-433026a4050d206028891664da859041.pem",
        "UnsubscribeUrl": "https://sns.us-east-1.amazonaws.com/?Action=Unsubscribe&SubscriptionArn=arn:aws:sns:us-east-1:177427601217:ecs-optimized-amazon-ami-update:6858e335-bc5b-4788-971e-4207f48728da",
        "MessageAttributes": {}
      }
    }
  ]
}
```

## FreeBSD AMI Updates
```json
{
  "v1": {
    "ReleaseVersion": "12.1-STABLE",
    "ImageVersion": "stable/12@359721",
    "Regions": {
      "eu-north-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0c9026fb1430fb964"
        }
      ],
      "ap-south-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-026a386a9a07f333d"
        }
      ],
      "eu-west-3": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0e380a6aef2779cb2"
        }
      ],
      "eu-west-2": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-00565f668f1e256c6"
        }
      ],
      "eu-west-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-026672494c9785811"
        }
      ],
      "ap-northeast-2": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0fe0d283973f681a5"
        }
      ],
      "ap-northeast-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0c7d805d429ad174b"
        }
      ],
      "sa-east-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-048a8f6a5802a05d4"
        }
      ],
      "ca-central-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0fe8b29626948a2e2"
        }
      ],
      "ap-east-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0e2f7f202ea54a809"
        }
      ],
      "ap-southeast-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-00af1fa716cc8014d"
        }
      ],
      "ap-southeast-2": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0855baa38c3a1fc55"
        }
      ],
      "eu-central-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0deb1a0ed6415473e"
        }
      ],
      "us-east-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-00b2f5724fe65bf9d"
        }
      ],
      "us-east-2": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0596badf8e2f106b7"
        }
      ],
      "us-west-1": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-03763231e27835f38"
        }
      ],
      "us-west-2": [
        {
          "Name": "FreeBSD 12.1-STABLE-arm64-2020-04-09",
          "Architecture": "arm64",
          "ImageId": "ami-0003334bd58102bb5"
        }
      ]
    }
  }
}
```

## New post on What's New blog

```json
{
    "title": "AWS CodeCommit Supports VPC Endpoints",
    "date": "2019-03-07T19:53:39",
    "description": "You can now access AWS CodeCommit from your Amazon Virtual Private Cloud (Amazon VPC) using VPC endpoints. &nbsp;",
    "link": "https://aws.amazon.com/about-aws/whats-new/2019/03/aws-codecommit-supports-vpc-endpoints/"
}
```
## AWS Daily Feature Updates

```json
{
    "NEW_awscli_1.27.91_updates": [
        "* api-change:``application-autoscaling``: Application Auto Scaling customers can now use mathematical functions to customize the metric used with Target Tracking policies within the policy configuration itself, saving the cost and effort of publishing the customizations as a separate metric.",
        "* api-change:``dataexchange``: This release enables data providers to license direct access to S3 objects encrypted with Customer Managed Keys (CMK) in AWS KMS through AWS Data Exchange. Subscribers can use these keys to decrypt, then use the encrypted S3 objects shared with them, without creating or managing copies.",
        "* api-change:``directconnect``: describe-direct-connect-gateway-associations includes a new status, updating, indicating that the association is currently in-process of updating.",
        "* api-change:``ec2``: This release adds a new DnsOptions key (PrivateDnsOnlyForInboundResolverEndpoint) to CreateVpcEndpoint and ModifyVpcEndpoint APIs.",
        "* api-change:``iam``: Documentation only updates to correct customer-reported issues",
        "* api-change:``keyspaces``: Adding support for client-side timestamps"
    ],
    "NEW_AWS_Tools_for_Powershell": {
        "old_version": " 4.1.290 (2023-03-13 21:04Z)",
        "new_version": " 4.1.291 (2023-03-14 21:12Z)",
        "change_log": "https://raw.githubusercontent.com/aws/aws-tools-for-powershell/master/CHANGELOG.md"
    },
    "NEW_aws_sdk_net": {
        "old_version": "3.7.502.0 (2023-03-13 18:23 UTC)",
        "new_version": "3.7.503.0 (2023-03-14 18:29 UTC)",
        "change_log": "https://raw.githubusercontent.com/aws/aws-sdk-net/master/SDK.CHANGELOG.md"
    },
    "DATE": "2023-03-15-1015"
}
```