node{
  stage('SCM Checkout'){
    git 'https://github.com/Carilyn00/BOTW'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: '3.6.3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
