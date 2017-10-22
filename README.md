# aws-elk-all-in-one
How to install ELK on an AWS EC2 instance

This aims to help people setup their own ELK stack on AWS quickly on a server for evaluation purposes.

------------------------------------------------------------------------------------------

You will need t2.medium EC2 instance with 20Gb prior to starting.
<br>
<br>The EC2 instance will require following security group access:
<br>* PORT 22     - SSH access
<br>* PORT 5601   - Kibana access
<br>* PORT 9200   - ElasticSearch access
<br>* PORT 5000   - Logstash access
<br>
<br>Once you have the above pre-requisites you can paste the command in the ec2 instaces command line.
