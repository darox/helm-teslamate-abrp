# A Helm Chart for Teslamate ABRP

## Instructions

1. Add the Helm repository:
    ```
    helm repo add teslamate-abrp https://darox.github.io/helm-teslamate-abrp
    ``` 
2. Install the chart:
    ```
    helm install teslamate-abrp teslamate-abrp/teslamate-abrp -n <namespace> --create-namespace
    ```
