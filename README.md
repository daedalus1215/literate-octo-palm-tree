# literate-octo-palm-tree
kubernetes


# secretreader-deployment.yaml
1. create a secret for `apiKey`: `kubectl create secret generic apikey --from-literal=api_key=123456767`
2. `kubectl create -f secretreader-deployment.yaml`