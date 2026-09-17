pipeline{ 
    agent any
    stages{
        stage('STAGE1'){

        steps{
            sh 'ls -lrt'

        }
    }
}

    
        stage('STAGE2'){
        steps{
            sh '''
              #!/bin/bash
              pwd
              sleep 
            '''

        }
    }

     
        stage('STAGE3'){
        steps{
            echo " this is stage3"

        }
    }
     
        stage('SATGE4'){
        steps{
            sh 'echo this is stage4'

        }
    }

}
