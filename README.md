# ACM Observability playbooks

The goal of this playbook is automate the observability
in RHACM. In this case, the playbook will manipulate a 
OCP cluster with ACM 2.2 created in RHPDS.

Modify extra-vars-example.yml with OCP URL and credentials.
Bucket name can be specified in extra-vars.yml as well.


## Usage:

```
ansible-playbook acm_setup_observability.yml -e @extra_vars.yml
```

 aws s3api create-bucket --bucket testcstark  --region eu-central-1 --create-bucket-configuration LocationConstraint=eu-central-1 
{
    "Location": "http://testcstark.s3.amazonaws.com/"
}


