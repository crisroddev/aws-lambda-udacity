# See storage usage
`df -h'
# Resize
chmod +x resize.sh

# Initialize New Lambda 
sam init
cd HelloWorld
sam build
sam local invoke
sam deploy --guided