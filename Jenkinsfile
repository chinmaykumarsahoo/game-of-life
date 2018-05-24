node{
    stage('SCM') {
    git 'https://github.com/chinmaykumarsahoo/game-of-life.git'
}
    stage('Build & Package'){
    sh 'mvn package'
    }
    stage('Results'){
    archiveArtifacts 'gameoflife-web/target/gameoflife.war'
    }
}
