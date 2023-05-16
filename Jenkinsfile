pipeline {
    agent any
    stages {
        stage ("Parallel Build") {
            parallel {
                stage ("Windows") {
                    steps {
                        echo "TEST Windows"
                    }
                }
                stage ("Linux") {
                    steps {
                        echo "TEST Linux"
                    }
                }
            }
        }
    }
}
