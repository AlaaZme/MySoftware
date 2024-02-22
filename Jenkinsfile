properties([[$class: 'JobLocalConfiguration', changeReasonComment: ''], pipelineTriggers([pollSCM('30 * * * *')])])
node {
    stage("clone") {
        git branch: 'master', url: 'https://github.com/AlaaZme/MySoftware.git'
    }
    stage("show files"){
       steps {
            dir('C:\\Users\\AlaaZme1\\PycharmProjects\\MySoftware') {
            bat 'MySoftware.py'
                  }
       }
   }

}