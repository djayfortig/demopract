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
allowmissing:true,
alwaysLinbkToLastBuild:false,
KeepAll:false,
reportDir:'.',
reportFiles:'Index.html',
reportName:'My Html Page'
])
}
}
}
}
