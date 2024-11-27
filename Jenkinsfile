node{
  stage('SCM Checkout'){
    
    git 'https://github.com/charpitha-1/my-app-1.git'
  }
  stage('Compile-Package'){
    //Get maven home path
    def mvnhome = tool name: 'M2_HOME', type: 'maven'
    sh "${mvnhome}/bin/mvn package"
  }
}
