pipeline{
    agent any
    stages{
        stage("Buld"){
            steps{
                sh 'mvn -DskipTests clean package'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
}
