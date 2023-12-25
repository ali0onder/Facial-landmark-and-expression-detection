# Facial feature and expression detection using MediaPipe
This is a basic application to detect facial features (eyes, nose, upper and lower lips) and to determine whether you are surprised or not. Code also detects when you are talking or not. It uses webcam, so if you want to run it through some images or videos, you need modify it a little.

I used the map for facial landmark detection which shows the 468 indices MediaPipe uses when creating a face mesh. If you need the indice numbers for right and left eyes, upper and lover lips, nose or mouth area, it is in the code.

![canonical_face_model_uv_visualization](https://github.com/ali0onder/Facial-landmark-and-expression-detection/assets/129281448/ee73d10c-aac3-43ab-a149-02919c4a47f3)
(Source:https://github.com/google/mediapipe/blob/a908d668c730da128dfa8d9f6bd25d519d006692/mediapipe/modules/face_geometry/data/canonical_face_model_uv_visualization.png)
