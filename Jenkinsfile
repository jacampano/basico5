pipeline {
    agent any
        stages {
            stage('Example') {
                steps {
                    script{
                        if (env.BRANCH_NAME == 'master') {
                        echo 'I only execute on the master branch'
                        } else {
                            echo 'I execute elsewhere'
                        }

                    }

                }
                
            }
        }
}
