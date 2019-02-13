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
        stage('Run'){
 
         bat 'ng serve -o'
}
       stage('Build') {
        milestone()
        bat 'ng build --prod --aot --sm --progress=false'
       }
         stage('Stop'){
 
         bat 'npm stop'
}
}
