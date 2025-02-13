Questions for Task B and C


B) Configure and deploy below application  on linux server (3 tier application)


Frontend server( apache webserver) -> backend application (Node app) - database (mongo)


Create .env file in you project to pass environment =>


MONGODB_URL=mongodb://localhost:27017/demo

PORT=3000


Application source - https://github.com/BL-AniketChile/NodeJs-API



C) Install and configure NFS server


i) Install NFS server component package on server X and NFS client component on client machine Y


ii) export folder /sample from NFS server X  which should be available to client machine Y only. No other client should be able to access /sample


iii) Mount exported nfs folder to the client machine Y on /mnt (client machine) and create folder, files inside mount point /mnt - troubleshoot if you are not able to create folder or files inside mount point /mnt
