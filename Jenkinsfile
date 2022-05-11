pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh ''' echo " Building from docker file"
                         sh podman build -t first try -f ./Dockerfile


                         sh podman run -p 3000:3000 '''
      }
    }

  }
}