pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build the code using a build automation tool to compile and package your code.'
        echo 'Tool: Maven'
      }
    }

    stage('Unit and Integration Tests') {
      steps {
        echo 'Run unit tests and integration tests to ensure components work together.'
        echo 'Tool: JUnit with Maven Surefire/Failsafe'
      }
    }

    stage('Code Analysis') {
      steps {
        echo 'Analyse code quality against standards.'
        echo 'Tool: SonarQube'
      }
    }

    stage('Security Scan') {
      steps {
        echo 'Scan the code for vulnerabilities.'
        echo 'Tool: OWASP Dependency-Check'
      }
    }

    stage('Deploy to Staging') {
      steps {
        echo 'Deploy the application to a staging server.'
        echo 'Tool: Ansible to AWS EC2'
      }
    }

    stage('Integration Tests on Staging') {
      steps {
        echo 'Run integration/End-to-end tests against staging.'
        echo 'Tool: Selenium WebDriver'
      }
    }

    stage('Deploy to Production') {
      steps {
        echo 'Deploy the application to a production server.'
        echo 'Tool: Ansible to AWS EC2'
      }
    }
  }
}
