node {

       stage('Checkout'){

          checkout scm
       }

       stage('Test'){
 
         bat 'npm install'
         
       } 
        stage('Run'){
 
         bat 'ng serve -o'
}
         stage('Stop'){
 
         bat 'npm stop'
}
}
