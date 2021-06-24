properties([parameters([string(defaultValue: 'shay', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/shay09/pycharm-repo.git'
        sh "cat 1.txt"
    }
}
