pipeline {
    agent {
        node {
            label "maven"
        }
    }

    stages {
        stage('clone repo') {
            steps {
                git branch: 'main', url: 'https://github.com/sschroeppel-ite/tweet-trend-new'
            }
        }
    }
}
