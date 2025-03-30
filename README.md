# voting-app-using-k8

Steps:
- aws eks cluster setup (+nodegroup)
- ec2 instance
- edit configmap to give role (iam)
- mongodb through statefulset + headless service
- setup replicaset + load data in db
- api deployment - expose it through loadbalancer
- deploy frontend pods
- loadbalancer again
- app deployed

(DNS)
DB: http://abe325e566fbf42308bee38560cea84a-546187670.eu-north-1.elb.amazonaws.com/languages
WA: http://add9093abdbcf45058c4568ed1178315-144921249.eu-north-1.elb.amazonaws.com/

{og:@N4si,cloudacademy}
