stage('Install Dependencies') {
    steps {
        bat '''
        python -m venv venv
        venv\\Scripts\\pip install -r requirements.txt
        '''
    }
}

stage('Run Application') {
    steps {
        bat 'venv\\Scripts\\python app.py'
    }
}
