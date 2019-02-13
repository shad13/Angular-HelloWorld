node {

       stage('Checkout'){

          checkout scm
       }

       stage('Test'){
 
         bat 'npm install'
         
       } 
       stage('Build') {
        milestone()
        bat 'ng build --prod --aot --sm --progress=false'
       }
   
}
