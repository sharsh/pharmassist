node {
  git url: 'https://github.com/sharsh/pharmassist.git'
  def mvnHome = tool 'M3'
  sh "${mvnHome}/bin/mvn -B -Dmaven.test.failure.ignore verify"


}