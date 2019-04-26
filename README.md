# object_tracking
Цель задания: разработать алгоритм трекинга людей с переназначением окна интереса (ROI) при потере объекта трекером (или появлении нового объекта). Так как нам нужно будет дать ответ до конца этой недели, то достаточно будет псевдокода / описание того, что делается, но нужно будет указать используемые технологии, модели и библиотеки. Пример данных: видеопоследовательности университета EPFL для трекинга объектов.


Необходимые "тяжелые" файлы:
1) [Веса](https://pjreddie.com/media/files/yolov3-tiny.weights) по пути yolo-coco/yolov3.weights
2) [Видео](https://documents.epfl.ch/groups/c/cv/cvlab-pom-video1/www/campus4-c0.avi) videos/campus4-c0.avi

Запуск: 
```bash
python video.py --input videos\campus4-c0.avi --output output\c4_0.avi --yolo yolo-coco
```