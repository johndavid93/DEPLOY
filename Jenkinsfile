node {
  def mvnHome
  
  stage('Preparation') { // for display purposes
     // Get some code a GitHub jenkins repository
     git 'https://github.com/johndavid93/DEPLOY.git'
  }
  
  stage('Deploy') { 
  sh 'cp /var/lib/jenkins/workspace/automatization/sample.war /usr/share/tomcat/apache-tomcat-8.5.45/webapps'
  }
}
