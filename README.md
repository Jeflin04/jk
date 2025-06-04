**Deploying Jenkins CICD Pipeline with Github and NodeJs:**

launch and connect the instance 

Install Java and Jenkins in that particular server

create a repo and push it 

In Jenkins create a freestyle project and add description allow the source code management git 

Install the wanted plugins (Github Integration Plugin and NodeJs Plugin)

from tools ----> git - path - from the server take the path (which path) ,then NodeJs Installation - Name

configure the project and provide the path (Provide Node & npm bin/folder to path)

Build steps ---> Execute shell ----> #!/bin/bash , npm install, npm start![jenkins1](https://github.com/user-attachments/assets/43ad11b4-3e68-4217-9aaa-e44ecd16d696)![jenkins2](https://github.com/user-attachments/assets/c287f006-1b27-4730-9edf-dbf51bac592b)
![jenkins3](https://github.com/user-attachments/assets/0249090a-5fd2-4353-a597-e22d1fa8bf8d)


Then build now , the console output will be ![console output](https://github.com/user-attachments/assets/1a373543-dc2d-49d9-96e0-23805aeca761),![console output2](https://github.com/user-attachments/assets/ca824699-8aad-4081-aef3-91fe4be97300)

Then add a webhook ![webhook](https://github.com/user-attachments/assets/80168f7b-06d4-4940-8b5a-9b2a18154cc4)
