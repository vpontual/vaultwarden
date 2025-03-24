To install helm stay on the root directory, which has a child directory named helm.

You may need to adjust the my-values.yaml

helm install vaultwarden helm/ -f ./helm/values.yaml -f ./helm/my-values.yaml -n vaultwarden
