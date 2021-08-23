node {
  
  stage('SCM Checkout'){
     git credentialid: 'akhilhub', url: 

  //branch name from Jenkins environment variables
  echo "My branch is: ${env.BRANCH_NAME}"

  def flavor = flavor(env.BRANCH_NAME)
  echo "Building flavor ${flavor}"
  
  
