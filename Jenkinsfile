pipeline{
agent any
stages{
stage("build"){
steps{
bat "mvn clean"
bat "mvn install"
bat "mvn compile"
bat "mvn exec:java -Dexec.mainClass=com.ramya.project.App" 
}
}
stage("test"){
steps{
echo "testing stage"
}
}
stage("deploy"){
steps{
echo "testing stage"
}
}
}
}
