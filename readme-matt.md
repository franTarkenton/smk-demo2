
# install smk-cli and setup the paths
`npm install @bcgov/smk-cli`
`export PATH=${PWD}/node_modules/.bin:$PATH`

# start smk
`smk create|edit`

# creat git repo:
* go into the map directory with the index.html and other files in it
`git init`

* create the .gitignore
* push your changes

# populate secrets
GHCR_TOKEN
GHCR_USER
OPENSHIFT_SERVER_URL
OPENSHIFT_TOKEN_DEV=
OPENSHIFT_TOKEN_PROD=