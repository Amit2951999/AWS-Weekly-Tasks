File landing in S3 bucket trigger lambda function that reads a small configuration from dynamodb<br />
and depending on file size and file type runs appropriate glue job.<br />
On successful glue job run, lambda should be triggered that runs a crawler and runs Athena query on the table created to create a view.<br />
On Failure of glue job, the lambda should send an alert.<br />



