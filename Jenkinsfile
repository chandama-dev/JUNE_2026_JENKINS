pipeline{
    agent any
    stages{
        stage('STAGE1'){
            steps {
            sh 'ls -lrt'
            }
        }

    stage('STAGE2'){
        steps {
         sh '''
            pwd
            sleep 10
            ls -lrt
            '''

        }
    }
}
}