# Thermal-Bookery-Counter
Thermal People Counter for The Bookery

Install:

```
curl -sL https://github.com/Seeed-Studio/grove.py/raw/master/install.sh | sudo bash -s -
pip3 install seeed-python-mlx90640
sudo pip3 install seeed-python-mlx90640
pip3 install --upgrade seeed-python-mlx90640
```
To test:
```
i2cdetect -y -r 1
```

To run live stream thermal program:
```
sudo git clone https://github.com/gobuyun/seeed_ircamera.git
cd seeed_ircamera
sudo python3 seeed_python_ircamera.py

```
