checkout scm
pipeline {
    agent master

    stages {
        stage("Build Test") {
            parallel {
                stage("Build Daily") {
                    steps {
                        echo "Hello World"
                    }
                }
            }
        }
    }
}
