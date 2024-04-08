# install-traccar-kubernetes
01. Change variabel {host},{port},{username}, and {password} in configmap.yml
02. Change image source in deployment.yml
03. Apply modified config using:
3.1 kubectl apply -f configmap.yml
3.2 kubectl apply -f deployment.yml
3.3 kubectl apply -f service.yml
