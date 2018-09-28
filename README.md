# is_mouth_open_detector

Hello everyone! It is a program for detect to mouth and select mouth open or not. First, you should download [shape_predictor_68_face_landmarks.dat](https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat) .You can give a folder name so program open photos in folder and do his job. Also you can use this with your webcam or a video. Check "How to use" for more information.

# How to use

1-)You can use this do jobs on images in a folder: find_and_mark_face_parts_on_images('your_path', hold = 4)

2-)You can use this for webcam: find_and_mark_face_parts_on_webcam_or_video(0, hold = 8)

3-)You can use this for video: find_and_mark_face_parts_on_webcam_or_video('video_path',hold = 4)

'hold' means min euclidean for choose close. It is multivariable.

![Alt Text](https://media.giphy.com/media/9JnIwwgwiQm4NqJ8ud/200w_d.gif)
