# Night-vision system supporting driver
### Praca inżynierska

![docelowo](http://blog.truecar.com/wp-content/uploads/2014/11/Night_Vision_by_AutoLiv-Person_Gen3.jpg)

System ma za zadanie przechwycić obraz z kamery termowizyjnej, a następnie wyszukać odpowiednie obiekty wydzielające ciepło i śledząc ich ruch oznaczać je na ekranie.

Do wykorzystania:

1. **Tracking Pedestrians from a Moving Car**
[link](https://www.mathworks.com/examples/matlab-computer-vision/mw/vision_product-PedestrianTrackingFromMovingCameraExample-tracking-pedestrians-from-a-moving-car#7 "link")
![przechodnie](https://www.mathworks.com/help/releases/R2017a/examples/vision_product/win64/PedestrianTrackingFromMovingCameraExample_01.png)

Gotowy matlabowy kod, który oznacza przechodniów na obrazie z kamery - można przerobić na wykrywanie przez progowanie.

2. **Detecting Cars Using Gaussian Mixture Models**
>[link](https://www.mathworks.com/examples/matlab-computer-vision/mw/vision_product-videotrafficgmm-detecting-cars-using-gaussian-mixture-models "link")
>![auta](https://www.mathworks.com/help/releases/R2017a/examples/vision_product/win64/videotrafficgmm_04.png)

>Również matlabowy kod, który zaznacza wyszukane na filmie auta oparty na wyszukiwaniu pierwszego planu przy pomocy modeli Gaussa.

3. **Background Subtraction Methods**
[link](http://docs.opencv.org/master/d1/dc5/tutorial_background_subtraction.html "link")
>![tło](http://docs.opencv.org/master/Background_Subtraction_Tutorial_Scheme.png)

>Kod do oddzielania tła od pierwszego planu.

4. **PyImageSearch**
[link](http://www.pyimagesearch.com/2015/11/09/pedestrian-detection-opencv/ "link")
>![wykrywanie_na_obrazie](http://www.pyimagesearch.com/wp-content/uploads/2015/11/pedestrian_detection_person_175.jpg)

>Gotowy kod w OpenCV do wykrywania pieszych na obrazie.
