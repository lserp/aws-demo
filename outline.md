1. Package the application locally through Docker - the container base image must be already on the local machine, do not rely on the internet. never
2. Show how it runs locally
3. Package it for EB
4. Had to install docker compose to bring the voting app up (should I use it?)
5. is docker compose supported in EB?
6. 

Build the single container application before everything
Run it locally `docker run -it -p 8000:8000 <$(docker images -q | head -n 1)>`

NOTES:
`git remote set-url origin git@github.com:lserpietri/aws-demo.git` -- sets up the upstream Git to use SSH keys (2fa activated)
