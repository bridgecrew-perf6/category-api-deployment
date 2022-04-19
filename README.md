# Category API Deployment

Repo ini digunakan untuk otomatisasi deployment aplikasi [Category API](https://github.com/rahadiangg/category-api) ke kubernetes dengan menggunakan Argo CD

# Deploy Huawei Cloud

- Siapkan SWR untuk container registry
- Buat [credentials](https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/) lalu samakan di di bagian ``imagePullSecrets`` di file ``app/huawei-cloud/dev/deployment.yaml`` 
- Khusus buat load balancer ada konfig khusus sesuai [dokumentasi ini](https://support.huaweicloud.com/intl/en-us/usermanual-cce/cce_01_0014.html#section8) 