
 #AUTOMATE-INFRASTRUCTURE-WITH-IAC-USING-TERRAFORM.-PART-3-REFACTORING
 
 In this project we were intoduced to the concept of modules which makes our code reuseable. We also learnt about remote backend wish makes contribution among  remote     teams possible.
 
 We implemented remote backend using s3 bucket which holds the state file and RDS table that implements state lock so that team memeber can not update state               concurrently.
 
 # Screenshots
 
 
 
 


![prj-18-final-num-resources](https://user-images.githubusercontent.com/52359007/175934492-ce9f9f68-fc98-4ec7-b16d-55ff2cd10e96.PNG)

![prj-18-remote-backend-ini](https://user-images.githubusercontent.com/52359007/175934546-b48130b7-6aa2-4b94-b15d-ac80a188c496.PNG)
![prj-18-final-num-resources](https://user-images.githubusercontent.com/52359007/175934681-e370a8c2-7067-4687-afbc-bf43f4f70a82.PNG)
![project-18-lockid-digest](https://user-images.githubusercontent.com/52359007/175934786-b441e4b8-eac6-4afa-b04e-bcbce9246308.PNG)
![project-18-state file in s3](https://user-images.githubusercontent.com/52359007/175934810-ce2600ba-3ff4-47b3-8054-1871681696d6.PNG)
![project-18-state-lock-file](https://user-images.githubusercontent.com/52359007/175934832-3130fbab-0113-40de-b533-4478e41a35c9.PNG)
![project-18-version-2-tfstatefile](https://user-images.githubusercontent.com/52359007/175934856-cf95f1c6-92ae-4f57-bf30-10a318a827b7.PNG)
