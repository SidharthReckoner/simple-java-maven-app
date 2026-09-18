pipeline {
    agent any
    tools {
            maven 'mvn'   // must match the name you gave it in step 1
        }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}