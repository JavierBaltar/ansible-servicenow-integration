# ansible-servicenow-integration
<p align="center">
  <a href="#Getting-Started">Getting Started</a> •
  <a href="#Tower-CLI">Tower CLI</a> •
  <a href="#API">API</a> •
  <a href="#Notifications">Notifications</a> •
  <a href="#Docker-Security">Docker Security</a> •
  <a href="#related">Related</a> •
  <a href="#Authors">Authors</a>
</p>
 


## Getting Started

In short, you have to create the Ansible AWX endpoint and a workflow as shown below (you can also add approvals, permissions, notification, etc):



### Create a ServiceNow Workflow
The workflow is just running a "hello world" playbook but it can trigger any playbook available. 

![](servicenow-workflow.png)


### Order your request
![](servicenow-order.png)

## Related

* [Ansible Modules](https://docs.ansible.com/ansible/latest/modules/modules_by_category.html) - List of Ansible modules
* [ServiceNow Sandbox](https://developer.servicenow.com/app.do#!/home) - Request ServiceNow sandbox

## Authors

* **Javier Baltar** - *Initial work* - [GitHub](https://github.com/JavierBaltar)



