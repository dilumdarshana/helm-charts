# helm-charts


helm package nginx
helm package redis
mv *.tgz packages/

Package charts:
$ helm package charts/nginx

Generate index.yaml:
$ helm repo index packages/ --url https://dilumdarshana.github.io/helm-charts/packages
