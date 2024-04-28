for s3 bucket
create 
policy generate 

{
  "Id": "7657",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "5765",
      "Action": [
        "s3:GetObject",
        "s3:GetObjectAcl"
      ],
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::name/*",
      "Principal": "*"
    }
  ]
}


putobject 
getobject asl if req
remove private access
