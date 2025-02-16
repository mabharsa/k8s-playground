TODO

Add PV support for remote storage like NFS, GlusterFS

Handle Minio ACCESS_KEY AND ACCESS_SECRET using kubernetes secret

Run Minio behind Ingress and LoadBalancer


Troubleshooting Scenario 
1. Update the image 
kubectl set image deploy/minio minio=minio/minio:RELEASE.2020-12-03T05-49-24Z --record

2. Expected Scenario User should not able to loss connectivity with minio storage api/UI

3. refer: https://www.bluematador.com/blog/kubernetes-deployments-rolling-update-configuration

