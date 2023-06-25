pipeline {
    agent any
    tools (nodejs "NodeJS")
    
    stages {
        stage ('cloning git repo'){
            steps {
                echo "cloning the repo"
                git 'https://github.com/Timothy-creator400/gallery'
            }
        }
    }
}