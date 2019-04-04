# openshift-cicd-template

如果project名称不是myapp，则需要修改myapp-template-no-trigger.yaml的image字段:
image: docker-registry.default.svc:5000/<your_project_name>/${APPLICATION_NAME}:latest
