# 以Python3.9.9-slim執行環境作為Docker Image基礎
FROM python:3.9.9-slim
# 在容器環境內，創建一個stock資料夾並指定為工作目錄
WORKDIR /stock
# 將主機當前目錄資料加入到容器內的stock資料夾
ADD . /stock
# pip安裝requirements.txt內的套件
RUN python3 -m pip install -r requirements.txt
# 執行main.py
# CMD python main.py
