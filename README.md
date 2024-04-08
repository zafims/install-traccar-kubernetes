# install-traccar-kubernetes
01. Change variable ------- {host},{port},{username}, and {password} in -----------> configmap.yml
02. Change image source in ----------> deployment.yml
03. Apply modified config using:

    kubectl apply -f configmap.yml

    kubectl apply -f deployment.yml

    kubectl apply -f service.yml
