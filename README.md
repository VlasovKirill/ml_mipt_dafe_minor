# Факультативный курс "Введение в машинное обучение" на ФАЛТ МФТИ
Зеркало на <img src='https://github.com/VlasovKirill/ml_mipt_dafe_minor/blob/master/pic/drive.png' height="20px" width="20px" align="top"> [Google Drive](https://goo.gl/xwbPUK)

## Tools 

### <img src='https://github.com/VlasovKirill/ml_mipt_dafe_minor/blob/master/pic/anaconda.png' height="20px" width="20px" align="top"> Вариант 1
- Установить [Anaconda](https://www.anaconda.com/distribution/)
- Написать в командной строке: `jupyter notebook`
- Открыть в браузере [http://localhost:8888](http://localhost:8888)
- Использовать по назначению

### <img src='https://github.com/VlasovKirill/ml_mipt_dafe_minor/blob/master/pic/docker.png' height="20px" width="20px" align="top"> Вариант 2
- Устанавливаем Docker с [официального сайта](https://www.docker.com/products/docker-desktop)
- В командной строке пишем: `sudo docker run -d -p 4545:4545 -v ‘путь_на_основной_машине‘:/home/user vlasoff/ml jupyter notebook`
- Заходим через браузер на [http://localhost:4545](http://localhost:4545)
- Использовать по назначению
