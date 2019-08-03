## This Project is to show Cat-Dog Training on kubeflow
* Pre-requisite:
	* A K8S Cluster
	* cat/dog training data: must reside in ./data
	* DGX or any GPU-accelerated K8S node (optional)
	* kubeflow is pre-installed
* How to Start:
	* Install NVidia Docker on DGX
        * Use Kubeadm to install Essential PKS 1.13.7
        * Deploy Kubeflow
	* Use Kubeflow framework to initialize a Jupyter server POD.
        * Mount this folder inside Jupyter server POD.
	* Must first run pip3 install -r requirement.txt inside Jupyter server POD.
	* Open .ipynb file inside Jupyter notebook to begin with. 
  
