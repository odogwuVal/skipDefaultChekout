pipeline {
  agent any
      stages {
        stage('build') {
            when {
              BuildingTag()
            }
            steps {
                echo "Building master"
            }
        }
     }
}
