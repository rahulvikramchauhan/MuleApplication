pipeline{
	agent any
    stages{
        stage('build'){
            steps {
                bat 'mvn clean deploy -Pdev -DmuleDeploy'
            }
        }
    }
}