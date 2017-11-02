pipeline {
  agent any
  stages {
    stage('s6') {
      steps {
        sleep 6
      }
    }
    stage('mail jc') {
      steps {
        mail(subject: 'hola', body: 'hola', cc: 'jcruiz@openfinance.es', to: 'jcruiz@openfinance.es')
      }
    }
    stage('mail me') {
      steps {
        mail(subject: 'prueba', body: 'prueba', to: 'sistemas@openfinance.es')
      }
    }
  }
}