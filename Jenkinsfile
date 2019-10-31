node {
   echo 'Hello World'
   def nodeImage = docker.image('node:alpine')
   stage('Get Ecr Image') {
      nodeImage.inside{
          sh 'node - v'
          
      }
   }
}
