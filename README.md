Git Repostiry LInks to sync the bitbucket with the github:
 -->https://support.atlassian.com/bitbucket-cloud/docs/set-up-an-ssh-key/ 
 -->https://medium.com/@dmitryshaposhnik/sync-bitbucket-repo-to-github-669458ea9a5e
 
Jenkins Details in my local:
Username:ashaurya
password: #Abhi411

https://plugins.jenkins.io/atlassian-bitbucket-server-integration/
https://www.jenkins.io/blog/2020/01/08/atlassians-new-bitbucket-server-integration-for-jenkins/

Adding web hook : 
To resolve unexpected URL in webhook:
https://stackoverflow.com/questions/46822898/ip-address-of-localhost8080-in-webhooks-of-github-jenkins

git init

git remote add origin https://abhinav2231989-admin@bitbucket.org/abhinav2231989/pc8_bitbuck.git
git add -A
git commit -m "Initial commit"
git push origin master

if unrelated history error comes:
git pull origin branchname --allow-unrelated-histories9:00pm