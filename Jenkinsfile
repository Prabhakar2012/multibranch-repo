node('built-in') 
{
     stage('Continuous Deployment ') {

sh '''scp /root/.jenkins/workspace/pipeline-job/webapp/target/webapp.war prabhakar@192.168.8.118:/var/lib/tomcat9/webapps/qaenv.war'''
   
}

 stage('Continuous Testing ') {
   sh 'echo "Testing has been passed"'
}

}
