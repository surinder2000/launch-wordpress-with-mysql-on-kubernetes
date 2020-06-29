# Launch Wordpress with Mysql on Kubernetes
Launching wordpress with mysql database on top of kubernetes and making the data persistent using PVC. The whole environment is launched by just executing one file which is kustomization.yaml

To execute this file use the following command

If you are in the same directory where the files are kept then use

    kubectl create -k .
    
Otherwise use

    kubectl create -k path_of_file
