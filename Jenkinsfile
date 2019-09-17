node('UBUNTU') {
    stage('GIT') {
    git 'https://github.com/RajeshKilladi/game-of-life.git'
}
stage('PACKAGE') {
 sh label: '', script: 'mvn package'
}
}