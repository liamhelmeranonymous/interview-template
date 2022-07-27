# interview-argocd-repo

To use this repo, check it out to your local machine. This exercise requires git, yq, bash and helm 3.

This is a simple excercise in creating a helm chart. The object is to create a valid service that will install in kubernetes (1.19 or greater). The cluster where this would be installed uses the nginx ingress controller. You may use the format herein, or you can make your own from scratch, but the chart must use the values.yaml format in this repo: the service will be installed on a random port and hostname elsewhere that you have no control over.

When you're done with your helm chart, run the validator.sh script on it. If it passes the test, then test it's in
