pipeline {
    agent {
        docker {
            image 'maven:3.9.9-amazoncorretto-21-debian'
            args '-v /home/peter/docker/jenkins/mvnm2:/root/.m2'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
