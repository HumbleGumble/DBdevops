node('built-in')
{
  stage(Download)
  {
    git ('https://github.com/HumbleGumble/DBdevops.git')
  } 
  stage(Build)
  {
    sudo docker rm -f $(docker ps -aq)  
  }
  
}
