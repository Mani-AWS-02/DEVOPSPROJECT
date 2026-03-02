pipeline{
agent any
stages{
stage('Build'){
steps {
echo "welcome to jenkins"
}
}
stage('Test') {
steps {
echo "welcome to testing team"
sh 'touch day'
}
}
stage('Deploy') {
steps {
echo "welcome to deploying team"
sh 'pwd'
}
}
}
}
