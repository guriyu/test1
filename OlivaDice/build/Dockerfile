FROM python:3.11-slim
WORKDIR /app
COPY OlivaDice.py .
RUN pip install -i https://pypi.tuna.tsinghua.edu.cn/simple olivos
CMD ["python", "OlivaDice.py"]