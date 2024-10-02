docker run -it -e NGROK_AUTHTOKEN=xyz ngrok/ngrok:latest http --url=baz.ngrok.dev 8080   # port 8080 available at baz.ngrok.dev


docker run -it -e NGROK_AUTHTOKEN=2mpvQjckoRJBhgMWbYb5VsRAZAb_3ZKFBLKEhzqUhRfUxbF7V ngrok/ngrok:latest http --url=gibbon-absolute-daily.ngrok-free.app 6060         

docker run -it -v ./ngrok.yml:/home/ngrok/ngrok.yml -e NGROK_CONFIG=/home/ngrok/ngrok.yml ngrok/ngrok:latest http --url=gibbon-absolute-daily.ngrok-free.app 80 
