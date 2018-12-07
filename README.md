# GCPDeployementManager
This is the sample configuration file  for deployment manager with README.md file with more details

Please follow the below Details step to make it worked
1.Open cloud shell
2.Mkdir test
3.cd  test
4. copy file deployment.yaml attached in repo.
5 run :
 1.gcloud deployment-manager deployments create advanced-configurationtest --config deployment.yaml 
  -It will create new VM with named as my first VM ,Please get extenal ip and try invoking extenal ip:80 -> its outshould be      hello world.It take sometime to make apache server up. so try until 5-10 min after script is invoked successfully.
 2. to delete the deployment :
    gcloud deployment-manager deployments delete advanced-configurationtest
    -advanced-configurationtest : is the deployement name.You can search the details of this deployment in GCP search             "Deployment manager"
  
  3.Read more : https://cloud.google.com/deployment-manager/docs/step-by-step-guide
