# ServiceAccount
**serviceaccount** konusuyla ilgili dosyalara buradan erişebilirsiniz.

controlplane ~ ✖ k exec -it web-dashboard-767bc588bc-6wfjw -- /bin/sh
/opt/webapp-conntest # cd /var/run/secrets/kubernetes.io/serviceaccount/
/run/secrets/kubernetes.io/serviceaccount # ls
ca.crt     namespace  token

image.png

# 
