pipeline{
    agent any
    stages{
        stage(' clean'){
            steps{
            sh 'sudo mvn clean' 
            }
        }
        stage('Test'){
            steps{
                sh 'sudo mvn test'
            }
        }
        stage('Deploy'){
            steps{
                sh "sudo mvn package"
            }
        }
        
    }
}
