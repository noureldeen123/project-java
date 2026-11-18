pipeline {    
    agent any    
    stages {        
        stage('Compile') {            
            steps {                
                echo 'Compiling...'                
                bat '"C:\\Program Files\\Java\\jdk-21\\bin\\javac.exe" HelloWorld.java'            
            }        
        }        
        stage('Run') {            
            steps {                
                echo 'Running...'                
                bat '"C:\\Program Files\\Java\\jdk-21\\bin\\java.exe" HelloWorld'            
            }        
        }    
    }
}