# Instalando Openshift Container Platform 4.0 - Libvirt / KVM

# Pre install

1. ansible-playbook config-ocp.yml
2. cd go/src/github.com/openshift/installer/bin/

# Install
1. ./openshift-install create manifests --dir=. --log-level=debug
2. Altere conforme suas necessidades os manifestos gerados
3. ./openshift-install create cluster --dir=. --log-level=debug
