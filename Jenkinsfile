node {
    stage('scm') {
    git 'https://github.com/wakaleo/game-of-life.git'
}
stage('new') {
sh 'echo hello'
}
stage('one'){
 when { 
            not { 
                branch 'master' 
            }
        }
}
