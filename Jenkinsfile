pipeline {
    agent any
 stages {
  stage('Docker Build and Tag') {
           steps {
              echo "hii"
              //  sh 'docker build -t nginx:latest ' 
                sh 'docker tag nginxtest divyadockerhub1998/nginxtest:latest'
              //  sh 'docker tag nginxtest divyadockerhub1998/nginxtest:$BUILD_NUMBER'
               
          }
        }
     
//   stage('Publish image to Docker Hub') {
          
//             steps {
//         withDockerRegistry([ credentialsId: "dockerHub", url: "" ]) {
//           sh  'docker push divyadockerhub1998/nginxtest:latest'
//           sh  'docker push ndivyadockerhub1998/nginxtest:$BUILD_NUMBER' 
//         }
                  
//           }
//         }
     
//       stage('Run Docker container on Jenkins Agent') {
             
//             steps {
//                 sh "docker run -d -p 4030:80divyadockerhub1998/nginxtest"
 
//             }
//         }

    }
}
