
node {
    stage("clone") {
        git branch: 'master', url: 'https://github.com/AlaaZme/MySoftware.git'
    }
    stage("show files"){
            dir('C:\\Users\\AlaaZme1\\PycharmProjects\\MySoftware') {
            bat 'MySoftware.py'
       }
   }

}