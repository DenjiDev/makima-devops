## Help commands 

# Install at first time:

1. helm install -f ./makima-ms/values_dev.yaml makima-sender makima-ms
1. helm upgrade --install --reset-values -f ./makima-ms/values_dev.yaml makima-sender makima-ms