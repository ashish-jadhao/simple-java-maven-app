pipeline {
    agent {
    tools { 
        maven 'Maven 3.6.90' 
        jdk 'jdk8' 
    }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
