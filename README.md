# EC-NoOpClusterPlatform
CloudBees Flow environment cluster platform plugin that does nothing. This implements functionality that is available with environment tiers. If an evironment tier is empty (contains no resources), component deployments to such a tier will be skipped. This operation is necessary if the list of components to be deployed varies from one environment to another.
