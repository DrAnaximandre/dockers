FROM dranax/pytorch

RUN pip install jupyter


EXPOSE 8888

RUN mkdir -p -m 700 /root/.jupyter/ && \
    echo "c.NotebookApp.ip = '*'" >> /root/.jupyter/jupyter_notebook_config.py

CMD ["jupyter","notebook","--allow-root"]