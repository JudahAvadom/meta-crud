# Run

To run the aplication

```
docker build -t lamp .
docker run -p 3000:80 -d -v $(pwd):/var/www/html lamp
```