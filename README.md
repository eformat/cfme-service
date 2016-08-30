# cfme-service

Create an external route, service and endpoint to point to a CloudForms instance routing via Openshift

    oc create -f ./cfme-external-service-template.yaml
    oc new-app cfme-external-service-template

