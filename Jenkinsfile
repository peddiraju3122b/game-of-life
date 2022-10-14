pipeline{
    agent(label 'JDK11'){
    stages{
        stage(maven){
            steps{
                git url 'https://github.com/peddiraju3122b/game-of-life.git',
            branch 'master'
             }
        stage(maven package){
            steps{
                sh 'mvn package'
              
               }
            }
        }
    }
   }
}

