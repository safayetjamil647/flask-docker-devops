node {
   stage('Get Source') {
      // copy source code from local file system and test
      // for a Dockerfile to build the Docker image
      git ('https://github.com/safayetjamil647/flask-docker-devops')
      if (!fileExists("Dockerfile")) {
         error('Dockerfile missing.')
      }else{
          echo 'everything fine'
      }
   }
}