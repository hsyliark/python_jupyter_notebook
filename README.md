# python_jupyter_notebook

## 파이썬 주피터노트북 활용 연습

### Jupyter Notebook 디렉토리 변경방법
1. cmd를 실행합니다.
2. cmd창에 jupyter notebook --generate-config 입력 한 후 jupyter_notebook_config.py 파일의 위치를 확인합니다.
3. 파일위치에서 jupyter_notebook_config.py파일을 엽니다. (VS CODE,  등등)
4. Ctrl+F를 통해 #c.NotebookApp.notebook_dir 를 찾습니다.
5. #c.NotebookApp.notebook_dir = ' '에서 ' ' 사이에 원하는 절대 경로를 설정해줍니다. (단, 경로설정시 \를 /로 변경해야 합니다.)
6. 경로설정 후 앞에있는 주석(#)을 없애고 파일을 저장합니다.
7. Jupyter Notebook을 재실행 한 후 기본 디렉토리를 확인합니다.
