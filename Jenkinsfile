node {

    stage('Install Dependencies') {
        bat """
        python -m venv venv
        venv\\Scripts\\pip install -r requirements.txt
        """
    }

    stage('Run Application') {
        bat "venv\\Scripts\\python app.py"
    }
}
