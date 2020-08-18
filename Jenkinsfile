pipeline {
    agent any
    environment {
        BUILD_VERSION = "1.${currentBuild.number}.0-RELEASE"
    }

    stages{ 
      stage("Stage 1") {
        steps {
            echo "Stage 1"
        }
      }

      stage("Stage 2") {
        steps {
            echo "Stage 2"
        }
      }

      stage("Stage 3") {
        steps {
            echo "Stage 3"
        }
      }
    }
}
