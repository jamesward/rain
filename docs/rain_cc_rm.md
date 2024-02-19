## rain cc rm

Delete a deployment created by cc deploy (Experimental!)

### Synopsis

Deletes the resources in the cc deploy deployment named <name> and waits for all CloudControl API calls to complete. This is an experimental feature that requires the -x flag to run.

```
rain cc rm <name>
```

### Options

```
      --debug              Output debugging information
  -x, --experimental       Acknowledge that this is an experimental feature
  -h, --help               help for rm
  -p, --profile string     AWS profile name; read from the AWS CLI configuration file
  -r, --region string      AWS region to use
      --s3-bucket string   Name of the S3 bucket that is used to upload assets
      --s3-prefix string   Prefix to add to objects uploaded to S3 bucket
  -y, --yes                don't ask questions; just delete
```

### Options inherited from parent commands

```
      --no-colour   Disable colour output
```

### SEE ALSO

* [rain cc](rain_cc.md)	 - Interact with templates using Cloud Control API instead of CloudFormation

###### Auto generated by spf13/cobra on 11-Feb-2024