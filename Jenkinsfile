node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3.5', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
   
