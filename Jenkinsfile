pipeline {
    
    agent any
    
    parameters {
        string(name: 'tracker', defaultValue: 'master')
    }

    stages {

        stage('smoke') { steps {
            echo "tracker: ${params.tracker}"
        }}

    }

}
