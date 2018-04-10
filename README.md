
#C3 Setup
Use this project to setup required DevOps-components for a C3 Prototype Instance. Keep in mind that a front-end and a backend project needs to be fetched from code repo seperately.


##How to use

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://git.ng.bluemix.net/lars.henrik.nordli/c3-setup&env_id=ibm:yp:us-south)

1. Select a name for the prototype. F.ex., 'cloud-airlines'. You will create two code repos: 'cloud-airlines-frontend' and 'cloud-airlines-backend'. 
2. Fetch front-end and backend projects locally.
3. Change the remote for the repos to the two repos created in last step
4. Make some changes and push the changes. This will trigger a deployment and you will have the following apps created:
    - cloud-airlines-frontend-test
    - cloud-airlines-frontend
    - cloud-airlines-backend-test
    - cloud-airlines-backend