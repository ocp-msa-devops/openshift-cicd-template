# openshift-cicd-template

注意：
1. 如果project名称不是myapp，则需要修改myapp-template-no-trigger.yaml的image字段:
image: docker-registry.default.svc:5000/<your_project_name>/${APPLICATION_NAME}:latest
2. 如果project名称部署myapp，则需要修改Jenkinsfile中项目的定义：
def devProject = "<your_project_name>"
