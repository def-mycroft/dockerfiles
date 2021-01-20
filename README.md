Run `make qualtlib-jupyter` to build docker image for quantlib.

```
sudo docker run -d -p 7777:7777 --mount src=/l/cr/quantlib-dockerfiles/quantlib-jupyter,target=/home/notebooks,type=bind \
    --name qlnb lballabio/quantlib-jupyter
```
