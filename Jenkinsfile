pipeline {
  agent any
  stages {
    stage('Preparacion') {
      steps {
        sh 'aaa'
      }
    }
    stage('Ejecucion') {
      steps {
        sh 'a'
      }
    }
    stage('Tratamiento') {
      steps {
        sh 'a'
      }
    }
    stage('PreparacionHijos') {
      parallel {
        stage('PreparacionHijo1') {
          steps {
            sh 'a'
          }
        }
        stage('PreparacionHijo2') {
          steps {
            sh 'a'
          }
        }
        stage('PreparacionH3') {
          steps {
            sh 'a'
          }
        }
      }
    }
    stage('EjecucionHijos') {
      parallel {
        stage('EjecucionHijo1') {
          steps {
            sh 'a'
          }
        }
        stage('EjecucionHijo2') {
          steps {
            sh 'a'
          }
        }
        stage('EjecucionHijo3') {
          steps {
            sh 'a'
          }
        }
      }
    }
    stage('TratamientoHijos') {
      parallel {
        stage('TratamientoHijo1') {
          steps {
            sh 'a'
          }
        }
        stage('TratamientoHijo2') {
          steps {
            sh 'a'
          }
        }
        stage('TratamientoHijo3') {
          steps {
            sh 'a'
          }
        }
      }
    }
    stage('End') {
      steps {
        sh 'a'
      }
    }
  }
}