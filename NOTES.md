 https://book.kubebuilder.io/quick-start
 kubebuilder init --domain squeeze.box.com --repo squeeze.box
 kubebuilder create api --group squeeze.box.com --version v1alpha1 --kind squeezebox --image=meherliatrio/squeezebox:latest --run-as-user="1001" --plugins="deploy-image/v1-alpha"