# bookinfo, custom kiali labels
SMCP control plane istio-system 
add label: argocd.argoproj.io/managed-by: openshift-gitops to ns istio-system (to create smmr by gitops)
https://github.com/kiali/kiali/issues/1458
https://kiali.io/docs/configuration/kialis.kiali.io/   //istio_labels
  istio_labels:
    app_label_name: "app.kubernetes.io/instance"
    version_label_name: "app.kubernetes.io/version"
