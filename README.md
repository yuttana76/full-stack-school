# Lama Dev School Management Dashboard

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Lama Dev Youtube Channel](https://youtube.com/lamadev) 
- [Next.js](https://nextjs.org/learn)

#DEPLOYMENT BOM dev


# AWS (EC2)
Setup environment.

## Install Docker AWS : TIME 8:23
>sudo apt-get update
>sudo apt-get install docker.io -y
>sudo systemctl start docker
>sudo docker run hello-world

>sudo chmod 666 /var/run/docker.sock
>sudo systemctl enable docker
>docker --version
>docker ps

## Install Github runner both of nodejs & react
Setting/Action/Runners/New self-hosted runner

Runner in backgroun
follow in steping
>sudo ./svc.sh install
>sudo ./svc.sh start

# github setup  secret key
Actions secrets and variables
'''
DOCKER_PASSWORD
DOCKER_USERNAME
'''