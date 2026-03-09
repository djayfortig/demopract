pipeline{
agent any
stages{
stage('Checkout'){
steps{
git 'url'
}
}
stage('Publish'){
steps{
publishHTML([
allowMissing:true,
alwaysLinkToLastBuild:false,
keepAll:false,
reportDir:'.',
reportFiles:'Index.html',
reportName:'My Html Page'
])
}
}
}
}
