# mgh-de
de site for mgh

step for app engine deploy

    name: gcr.io/cloud-builders/gcloud-slim
    dir: public
    args: ['--project=$PROJECT_ID', 'app', 'deploy', 'app.yaml', '--quiet', --version=$PROJECT_ID']

