pipeline {
    agent none
    
    environment {
        IMAGE_BUILD_PROJECT = "Documentary-Website/CD/Wordpress/Build Wordpress Docker Image"
        DEPLOY_STAGE_PROJECT = "Documentary-Website/CD/Wordpress/Deploy Wordpress to Stage"
        PROMOTE_STAGE_PROJECT = "Documentary-Website/CD/Wordpress/Promote Wordpress to Production"
        IMAGE_BUILD_DETAILS = "image_build_details"
        OUTPUT_FILE = "output"
    }
    
    stages {
        stage('Build-Deploy-Promote') {
            agent {
                label 'ireland-jenkins-slaves'
            }
            steps {
                
                script {
                    echo "Upstream tag: $GIT_BRANCH"
                    
                }
            }
        }
    }
}