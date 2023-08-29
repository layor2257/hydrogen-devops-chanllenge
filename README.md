# hydrogen-devops-chanllenge

## Tasks:

#### 1. Provide steps to set up Nginx reverse proxy, as well as reasons for it.

#### 2. There are two node pools in a Kubernetes cluster, which pool contains a single node. The computing resources for each node pool are 1GB Memory and 1 CPU, 3GB Memory, and 2 CPU. How will you deploy an application that requires 2.5 GB of Memory? Kubernetes manifest codes can be pushed to Github, documentation is appreciated

#### 3. You have ssh access to an Ubuntu or Debian Linux server, The disk is full and you need to clean it up, what would you do and which specific commands should you run?

#### 4. The following NodeJs app has been developed, and the team is requesting a complete deployment approach. You have a pair of ACCESS_KEY and SECRET_KEY of an AWS user.

NB: You can use Terraform, Ansible, Bash, etc. Code can be pushed in Github, documentation is appreciated.

```
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello from Hydrogen!')
})

app.listen(port, () => {
  console.log(Example app listening on port ${port})
})
```