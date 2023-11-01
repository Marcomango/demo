pipeline {
    agent any

    stages {
        stage("parallel stages") {
            steps {
                parallel(
                    "StageA": {
                        echo "Parallel 1"
                    },
                    "StageB": {
                        echo "Parallel 2"
                    }
                )
            }
        }
    }
}