pipeline{
    agent any
    stages{
        stage('Git Code Cheeckout'){
        git 'https://github.com/bharathj0/star-agile-insurance-project.git'
    }
    stage('Code Compile'){
        sh 'mvn compile'
    }
    stage('Code Test'){
        sh 'mvn test'
    }
    stage('Code Building'){
        sh 'mvn clean package'
    }
}
}
