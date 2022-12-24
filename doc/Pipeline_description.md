# Pipeline description

Firstly: Push the updated code to Github  
Merge the code to main branch

CircleCI grab the code and run following process to deploy it to AWS

Then Install node.js 14.15  

Then Install Front-End/Back-End Dependencies  
By running script `npm run install` on corresponding directory

Then Linting Front-End project  
By `ng lint` on FE directory  

Then Build both project  
By running script `npm run build` on corresponding directory

Then hold to wait developer approve to continue process (deploy)

After developer click approve, it running script `npm run deploy` on corresponding directory to deploy both app to AWS