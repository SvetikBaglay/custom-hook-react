docker build -t custom-hook ./ 
docker run -it -v "$(pwd):/app" -p 3000:3000 custom-hook:latest bash 
npm start
