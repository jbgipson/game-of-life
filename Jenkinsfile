node {
   git url: 'https://github.com/jbgipson/game-of-life.git'
   withEnv(["PATH+MAVEN=${tool 'Maven'}/bin"]) {
     sh 'mvn -B verify'
   }
 }
