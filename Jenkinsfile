pipeline {
    agent {
        node{
        label "maven"
    }
}
environment {
    PATH = "/home/ans1/apache-maven-3.9.6/bin:$PATH"
}
    stages {
        stage("build") {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
