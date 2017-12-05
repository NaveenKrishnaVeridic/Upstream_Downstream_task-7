pipeline 
{ agent any

stages
{ stage('execute stage')
	steps {echo "this job execution is a success"}

  stage('execute downstream job')
	steps {echo "trigger build of the next job"
		build job: 'task 7 upstream job'}
}

}
