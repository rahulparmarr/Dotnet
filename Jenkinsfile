stage ('Clean workspace')
    cleanWs()
    
stage ('Git Checkout') 
    git 'https://github.com/rahulparmarr/Dotnet.git'
       
stage('Build') 
    bat "dotnet build C:\\Users\\parmar-rahul-ramesh\\.jenkins\\workspace\\dotnetPipeline\\Dotnet_SampleApp\\Dotnet_SampleApp.csproj --configuration Release"
        
stage ('Test')
    bat "dotnet test C:\\Users\\parmar-rahul-ramesh\\.jenkins\\workspace\\dotnetPipeline\\Test\\Test.csproj"

