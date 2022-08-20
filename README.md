# SMB-K8s

This repository is for performing an use case of mounting on premises SMB share on Windows Server to Kubernetes cluster in Linux Pods

Below are the steps to be carried out 
<ul>
<li>Provision a k8s cluster </li>
<li>Deploy a VM and create a SMB share </li>
<li>Install the csi-smb driver using helm/kubectl from this <a href="https://github.com/kubernetes-csi/csi-driver-smb">link</a></li>
<li>Create a Persistent Volume </li>
<li> Create a Persistent Volume Claim </li>
<li> Create a deployment referencing to the Volume claim created earlier </li>
</ul>




