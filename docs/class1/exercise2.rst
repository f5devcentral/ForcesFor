Exercise 2: Access the Lab Environment - BIG-IP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Next is to verify that the security policy has been configured deployed to BIG-IP.

#. To do so, open the BIG-IP TMUI by selecting the bookmark on Chrome and login with username/password **admin/admin**
#. The previous deployed pipeline created a new partition called "Web-Prod". Beside the security policy a Virtual Server, Pool and Node have been deployed inside this new partition
#. To check the security policy, select the new partition called "Web-Prod" and navigate to Security -> Application Security -> Security Policies -> Policies List
#. You will see a new security policy named "Arcadia_WAF_policy"

|intro008|

#. Within the "General Settings" of the "Policy Configuration" check if the settings align with what has been declared in the Pipeline

|intro009|

#. Within next Exercise - Exercise Number 3 - we want to deploy a security policy which will be compliant for OWASP Top 10 2021 compliant. For that, please delete the current deployment on BIG-IP with help of GitLab.
#. Remember the different Modes available when you issue a Pipeline

|intro005|

#. You can verify that the deplyoment has been deleted propper by either check it within the "run pipeline" in GitLab or whether the partition called "Web-Prod" has been deleted.

|intro007|

|intro010|

.. |intro008| image:: ./images/big-ipno1.png
   :width: 800px

.. |intro009| image:: ./images/big-ipno2.png
   :width: 800px

.. |intro005| image:: ./images/gitlab_no4.png
   :width: 800px

.. |intro007| image:: ./images/gitlab_no7.png
   :width: 800px

.. |intro010| image:: ./images/big-ipno3.png
   :width: 800px

