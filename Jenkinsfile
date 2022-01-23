pipeline {
  agent any
      stages {
        stage('build Master') {
            when {
               branch 'master' //executes when branch is master
            }
            steps {
                echo "Building master"
            }
        }
        stage('build Dev') {
            when {
               branch 'dev' //executes when branch is dev
            }
            steps {
                echo "Building dev"
            }
        }
     }
}
