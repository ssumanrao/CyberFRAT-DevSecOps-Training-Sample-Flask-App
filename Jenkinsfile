pipeline {
agent any

stages{
stage('Build Docker Image'){
steps{
sh'dpcker build -t cyberfrat:$BUILD_NUMBER.'
}
}
}
}
