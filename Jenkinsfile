node{
   stage('Code Pull')
   {
   git branch: 'main', url: 'https://github.com/rohitthaware/devops-210940120172'
   }
   stage('Code Compile')
   {
   sh 'javac helloworld.java'
   }
   stage("Execute Code")
   {
   sh 'java helloworld'
   }
}
