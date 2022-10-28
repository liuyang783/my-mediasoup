# my-mediasoup

os : ubuntu 18.04 or centos7

software: node>=12 python >= 3.6 pip3 setuptools meson ninja

server fast build(for mediasoup and demo server both):
PYTHON=python3 npm install --registry=http://registry.npm.taobao.org

client demo fast build:
PYTHON=python3 npm install --legacy-peer-deps --registry=http://registry.npm.taobao.org
