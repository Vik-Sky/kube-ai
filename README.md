| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| configmap | Create a ConfigMap | ConfigMap is used to store configuration data | [ configmap ](./yaml/app-configmap.yaml) |
| cronjob | Define a CronJob | CronJob is used to schedule and run jobs at intervals | [ cronjob ](./yaml/app-cronjob.yaml) |
| job | Create a Job | Job is used to run a single task to completion | [ job ](./yaml/app-job.yaml) |
| livenessProbe | Add a Liveness Probe to a container | Liveness Probe checks if a container is healthy | [ livenessProbe ](./yaml/app-livenessProbe.yaml) |
| multicontainer | Create a Pod with multiple containers | Pod with multiple containers sharing resources | [ multicontainer ](./yaml/app-multicontainer.yaml) |
| eadinessProbe | Add a Readiness Probe to a container | Readiness Probe checks if a container is ready | [ readinessProbe ](./yaml/app-readinessProbe.yaml) |
| resources | Define resource limits for a container | Set resource constraints for a container | [ resources ](./yaml/app-resources.yaml) |
| secret-env | Use a Secret as environment variables | Inject sensitive information as environment variables | [ secret-env ](./yaml/app-secret-env.yaml) |
| secret | Create a Secret | Secret is used to store sensitive data securely | [ secret ](./yaml/app-secret.yaml) |
| volumeMounts | Mount a volume to a container | Mount external storage to a container | [ volumeMounts ](./yaml/app-volumeMounts.yaml) |
| app | Deploy an application using a Deployment | Deploy an application using Kubernetes Deployment | [ app ](./yaml/app.yaml) |
