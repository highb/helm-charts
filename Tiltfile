
# If not using a standard local dev name, specify your k8s context here
#allow_k8s_contexts('jenkins-dev')
k8s_yaml(helm('charts/jenkins', values='charts/jenkins/values.yaml', set=['master.adminPassword=1234']))
watch_file('./charts/jenkins')
