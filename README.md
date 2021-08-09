When I run following command

kubectl apply -f charts/infrastructure/SolrCloud.yaml -n mynamespace

It gives following error

error: error validating "charts/infrastructure/SolrCloud.yaml": error validating data: ValidationError(SolrCloud.spec.dataStorage.ephemeral): unknown field "hostPath" in org.apache.solr.v1beta1.SolrCloud.spec.dataStorage.ephemeral; if you choose to ignore these errors, turn validation off with --validate=false
