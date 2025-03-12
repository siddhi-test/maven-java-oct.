node{

def maven = tool name: "latest"

//checkout stage
stage('checkout'){
  git 'https://github.com/sanchitraj5/maven-java-oct.git'
}
//build stage
stage('building'){
sh "$maven/bin/mvn clean package"
/*
//sonarqube report
stage ('sonarqubereport'){
sh "$maven/bin/mvn sonar:sonar"
}


//upload nexus
stage ('nexus upload'){
sh "$maven/bin/mvn deploy"
}
*/

}
}//Node closing
