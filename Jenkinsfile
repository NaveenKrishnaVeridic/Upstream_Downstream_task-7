properties([[$class: 'GithubProjectProperty', displayName: '', projectUrlStr: 'https://github.com/NaveenKrishnaVeridic/Upstream_Downstream_task-7.git/'], pipelineTriggers([githubPush()])])

pipeline 
{ agent any

stages
{ stage('execute stage')
    {	steps {echo "this job execution is a success"}
}
  stage('execute downstream job')
{	steps {echo "trigger build of the next job"
		build job: 'task 7 job being triggered'}
} }

}

