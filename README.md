# Reproducer for the race condition issue between Cert-Manager and OpenShift Service CA Operator
I've created a Jupyter notebook specifically aimed at reproducing the race condition issue observed between Cert-Manager and the OpenShift Service CA Operator.

**Prerequisites:**
- kind (https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
- Jupyter Runtime (https://jupyter.org/install)

**References:**
- https://github.com/openshift/service-ca-operator
- https://github.com/cert-manager/cert-manager/issues/6988