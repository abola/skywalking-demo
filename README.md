# skywalking-demo

```
kubectl create configmap skywalking-config \
  --from-file=./config/alarm-settings.yml \
  --from-file=./config/application.yml \
  --from-file=./config/component-libraries.yml \
  --from-file=./config/datasource-settings.properties \
  --from-file=./config/gateways.yml \
  --from-file=./config/log4j2.xml \
  --from-file=./config/official_analysis.oal
```
