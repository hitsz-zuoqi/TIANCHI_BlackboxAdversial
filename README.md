# TIANCHI_BlackboxAdversial




## Environment & Run
- python3
- pytorch>=1.0
- pillow>=5.0
- dlib ver.19.17   only support python3.5    with [shape_predictor_68_face_landmarks.dat_百度云盘提取码：4qjg](https://pan.baidu.com/s/1LMhhW2tXa8a1m2dx8-mCzQ&shfl=shareset) or [shape_predictor_68_face_landmarks.dat_Google drive](https://drive.google.com/open?id=1iMXiyvu3nYcNumtUHifVauU3-P_I_ssV)
- scikit-image>=0.14
- [models_百度云盘提取码：u46u](https://pan.baidu.com/s/1USe0e12jyeVj49AELL7KLw&shfl=shareset) or [models_Google drive](https://drive.google.com/open?id=1KrBN9-vlpmcbX5N-vc0QtKVsXuxF0jXd)

Download and unzip models
```bash
$ python target_iteration.py
```
If you only add noise to the face area, you need to leverage dlib to crop the face, which will be elaborated later.
