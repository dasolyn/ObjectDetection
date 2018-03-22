# ObjectDetection

이 저장소는 제가 사용해 본 적이 있는 딥러닝 기반 객체 검출 스크립트를 보존하기 위해 만들어졌습니다.

## Dependencies

이 저장소에 있는 스크립트는 주로 다음 Python 패키지에 의존합니다.

- [keras](https://github.com/fchollet/keras)
- [tensorflow](https://github.com/tensorflow/tensorflow)
- [h5py](https://github.com/h5py/h5py)
- [opencv-python](https://github.com/skvark/opencv-python)
- [pillow](https://github.com/python-pillow/Pillow)

또한 ipynb 파일을 열기 위해서는 [jupyter notebook](https://jupyter.org/)을 시스템에 설치할 필요가 있습니다.

각 스크립트 별로 추가적인 의존이 필요할 수 있습니다. 그런 경우에는 각 노트북 파일에 정보가 기록되어 있습니다.

## Algorithms

제 스크립트에서 사용한 딥러닝 객체 검출 알고리즘은 다음과 같습니다.

- Faster RCNN: [논문](https://arxiv.org/abs/1506.01497), [저장소](https://github.com/yhenon/keras-frcnn)
- RetinaNet: [논문](https://arxiv.org/abs/1708.02002), [저장소](https://github.com/fizyr/keras-retinanet)

제 스크립트를 작성하는데 위 저장소에 있는 스크립트를 많이 참조하였습니다. 논문을 작성하는데 사용된 코드와 위 저장소에 있는 코드는 다를 수 있습니다.

## License

제 스크립트는 [MIT License](https://opensource.org/licenses/MIT)로 배포됩니다. 자세한 것은 [LICENSE](https://github.com/dasolyn/ObjectDetection/blob/master/LICENSE)를 참조하십시오.
