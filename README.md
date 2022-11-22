# Discrete Emotion Labeling

A custom label studio project for discrete emotion classification.

## Quick Start

1. Pull the official Label Studio image.
```bash
$ docker pull heartexlabs/label-studio:latest  
```


2. Then, download the ```label-studio-data``` folder to your working directory. Run the following command in your working directory.
```bash
$ docker run -it -p 8080:8080 -v $(pwd)/label-studio-data:/label-studio/data heartexlabs/label-studio:latest
```


3. Access the web application at ```127.0.0.1:8080```. (Note: You may set your desired port number in Step 2.)


4. Log in with the following credentials:
```
User: admin@admin.com
Password: 12345678
```

5. Click on the Emotion Classification, upload all files for annotation and start annotating.
