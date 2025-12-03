#for docker to run

vi dockerfile
docker build -t harsh2 .                                  #instead of harsh2 anyname can be given
docker run -dt -p 3001:3000 harsh2                        #give port so that we can access the application 
                                                          #http://3.80.90.224:3001/  public ip and port (eg)





