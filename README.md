# k8s-dashboard

* First run recommended.yaml: ``` kubectl apply -f rcmd.yaml ```
* Then run admin-user.yml: ``` kubectl apply -f admin-user.yml ```
* Then run admin-serviceaccount.yml: ``` kubectl apply -f admin-svc.yml ```
* We need to create Barer token for login: ```  kubectl -n kubernetes-dashboard create token deepchain ```

* For more dtails: https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/
