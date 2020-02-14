# Kubernetes cluster with VMSS Cluster Autoscaler using Kubeadm
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbart-jansen%2Fkubernetes-on-ubuntu-vmss%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fbart-jansen%2Fkubernetes-on-ubuntu-vmss%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

This ARM template deploys a vanilla kubernetes cluster initialized using kubeadm. It deploys a configured master node with a [cluster autoscaler](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler/cloudprovider/azure). A pre-configured Virtual Machine Scale Set (VMSS) is also deployed and automatically attached to the cluster.
