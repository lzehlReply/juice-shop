pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh ''' echo " Building from docker file"
                          podman build -t first_try -f ./Dockerfile


                          podman run --rm -d -p 3000:3000 first_try '''
      }
    }

  }
}
