# Submitting a Pig job

1. Open the Amazon EMR console at [https://console.aws.amazon.com/elasticmapreduce/](https://console.aws.amazon.com/elasticmapreduce/).

2. In the Cluster List, select the name of your cluster.

3. Scroll to the Steps section and expand it, then choose Add step.

4. In the Add Step dialog:

  * For Step type, choose Pig program.

  * For Name, accept the default name (Pig program) or type a new name.

  * For Script S3 location, type the location of the Pig script. For example: s3://your-s3-bucket/aws.example.pig.

  * For Input S3 location, type the location of the input data. For example: s3://elasticmapreduce/samples/pig-apache/input.

  * For Output S3 location, type or browse to the name of your Amazon S3 output bucket. For example: s3://your-s3-bucket/

  * For Arguments, leave the field blank.

  * For Action on failure, accept the default option (Continue).

5. Choose Add. The step appears in the console with a status of Pending.

6. The status of the step changes from Pending to Running to Completed as the step runs. To update the status, choose the Refresh icon above the Actions column.

