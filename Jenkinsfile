pipeline {
  agent any
      stages {
        stage('build') {
            when {
              buildingTag()
            }
            steps {
                echo "Building master"
            }
        }
     }
}
