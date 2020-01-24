#!/usr/bin/env groovy
@Library('gr00vy')_
pipeline{
  agent any
  options {
   timeout (time: 1, unit: 'HOURS')
   skipDefaultCheckout()
  }
  stages{
  
     stage ('Prepare'){
  
       steps{
         script {checkoutsource()}
        }
      }
      
  }  
  
}
