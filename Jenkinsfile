@Library(['mm-dsl'])_
mm_java_build
{
    AGENT                   = "master"
}
mm_docker_build
{
    REGISTRY_NAME           = "modernization-dev-832770"
    IMAGE_NAME              = "agmchat"
    CLOUD                   = "gcp"
    AGENT                   = "modernization-dev-832770"
}
mm_k8s_deployment_pipeline_gcp
{
    PROJECT                 = "modernization-dev-832770"
    REGION                  = "asia-south1-a"
    CLUSTER_NAME            = "mgcmdmodkew01-gke-k8s"
    ENVIRONMENT             = "dev"
    DEPLOYMENT_NAME         = "agmchat"
    DEPLOYMENT_TYPE         = "automatic"
    RESTRICT_TO_BRANCH      = "gcp_dev"
}
mm_k8s_deployment_pipeline_gcp
{
    PROJECT                 = "modernization-uatx-505932"
    REGION                  = "asia-south1-a"
    CLUSTER_NAME            = "mgcmumodkew01-gke-k8s"
    ENVIRONMENT             = "uat"
    DEPLOYMENT_NAME         = "agmchat"
    DEPLOYMENT_TYPE         = "automatic"
    RESTRICT_TO_BRANCH      = "gcp_uat"
}
mm_k8s_deployment_pipeline_gcp
{
    PROJECT                 = "modernization-prod-566335"
    REGION                  = "asia-south1-a"
    CLUSTER_NAME            = "mgcmpmodkew01-gke-k8s"
    ENVIRONMENT             = "prod"
    DEPLOYMENT_NAME         = "agmchat"
    DEPLOYMENT_TYPE         = "automatic"
    RESTRICT_TO_BRANCH      = "gcp_prod"
}
