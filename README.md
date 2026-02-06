# helm-charts


helm package nginx
helm package redis
mv *.tgz docs/

Package charts:
$ helm package charts/nginx

Generate index.yaml:
$ helm repo index docs/ --url https://dilumdarshana.github.io/helm-charts/docs
