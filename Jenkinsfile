    
node{

stage('SCM checkout'){
 
  git 'https://github.com/tcdmv/SeleniumWithCucucumber.git'
}
stage('compile-package'){
sh'mvn package'
}
 stage('email-Notificatio'){
  mail bcc: '', body: 'this is an alert from Jenkins', cc: '', from: '', replyTo: '', subject: 'Jenkins Alert', to: '20testqa19@gmail.com'
 }

}
