# project: housing

This is my first Docker and GitHub use to host my hands-on practice of chapter 2 example project of 
  Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, 
  by Aurélien Géron (O’Reilly). Copyright 2019 Aurélien Géron, 978-1-492-03264-9.

## To launch

```bash
docker build -t housing .
docker run -p 8888:8888 housing
```

> Tip: If you're using Docker, make sure to install from `requirements.txt` only.  
> For debugging or replicating the local environment exactly, use `requirements-freeze.txt`.
