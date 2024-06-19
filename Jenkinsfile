pipeline {
    agent any

    stages {
        stage("Clone Repository") {
            steps {
                git "https://github.com/atulkamble/Git-Jenkins-Pipeline.git"
            }
        }

        stage("Build") {
            steps {
                sh "./hello.sh"
            }
        }
    }
}
