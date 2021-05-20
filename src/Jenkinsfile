pipeline {
  agent any
  
  tools {nodejs "node"}
  
        
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/ashaik65/realnodejs.git'
                sh 'npm install'
            }
        }
        

    }
}
