pipeline {
    
    agent any 
    
    environment {
        IMAGE_TAG = "${BUILD_NUMBER}"
    }
    
    stages {
        
        stage('Checkout'){
           steps {
                git credentialsId: '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', 
                url: 'https://github.com/busipatianil/Codetest.git',
                branch: 'main'
           }
        }
