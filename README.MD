argocd app create petclinic --repo https://github.com/jacekwosz/knative.git --path petclinic --dest-server https://kubernetes.default.svc --dest-namespace serverless-demo

argocd app sync petclinic

