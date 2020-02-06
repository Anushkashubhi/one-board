pipeline{
agent any
stages{

stage('Jenkins job'){
 steps {
 sh '''
 curl -X GET \
  http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/agile/1.0/board/558 \
  -H 'accept: application/json' \
  -H 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 458000f9-e50f-7f4f-1233-a141ff5e0cc3'
 '''
 }
 }
 }
 }
