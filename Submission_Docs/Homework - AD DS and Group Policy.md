David Thomsen

SYS-255

 

1. In dealing with Group Policy, what are two commands and their use for verifying and
troubleshooting group policies applied by a Domain Controller?

gpresult /r is one command that is useful in seeing what policies had actually been applied. In the lab when it was typed in, it shows "Applied Group Policy Objects: SYS-255-desktop

Another important command is gpudate. gpupdate will update the policies and make sure that they are applied.

2. When are COMPUTER group policy settings applied, and when are USER group policy
settings applied.

Computer group policies are applied immediately when they are done in the AD, however, user policies are applied after the gpupdate command is run.

3. Within a Windows Domain, why is it important that Domain Controllers replicate Active
Directory information?

It is important to have a backup in case anything happens to the original AD info so that all the policies or users do not get lost or must be remade. 

4. What is the purpose of an Organizational Unit?

It is similar to using folders in a file manager. It keeps everything together and organized making group policies or user policies easier to configure. 

5. You have a group policy setup and want to test it on a particular account or computer before
making changes everywhere? How could you accomplish this?

You could make a spare user account called Test or something similar and apply the policy to the test user first. If the policy works after logging in as this test user then it is okay to use for other uses but if not you can use the test user to troubleshoot with the policy. 