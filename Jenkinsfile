#!groovy
echo 'hello today from master'

node {
  stage 'Build'
  checkout scm  
  echo 'Building'
  sh 'ls -l'
  stage 'Test'  
  echo 'Test'
  echo 'unit tests'
}
