### Launch the docker environment.

```bash
docker-compose up
```

### Run the Node.js app.  

If docker is running with docker-machine or on a different server, please edit the JUPYTER_HOST variable in docker_env.sh

```bash
npm install
. ./docker_env.sh
node --harmony app.js
```