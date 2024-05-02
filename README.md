

This Repository contains a Web App along with the model notebook that can be used to predict the breed of a dog based on the image uploaded.


## Model
[This Notebook](models/InceptionResNetV2.ipynb) trains the model on Stanford Dogs Dataset.
[This Repo](https://github.com/aka-vm/Hello-CV/tree/master/Stanford%20Dogs) contains the original code, but some modifications are made to make it better.

## Web App
The server uses [FastAPI](https://fastapi.tiangolo.com/).<br>
I've hosted the app on Azure and DigitalOcean, and it works fine. But I recommend using [ngrok](https://ngrok.com/) for quick testing. The Docker image is also available on [Docker Hub](https://hub.docker.com/repository/docker/akavm/dog-breed-app).

