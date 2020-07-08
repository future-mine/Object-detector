Object Detector
License
Object Detector is licensed under a GNU AGPLv3 License.

Download the model and put in 'models' folder
resnet50_coco_best_v2.0.1.h5


## Run the script
1. Install python 3.7

2. Install opencv module
    pip install opencv-python
    pip install tensorflow==1.15.1
    pip install keras==2.3.1
    pip install imageai

    * If you are using linux or mac os.
        pip3 install opencv-python
        pip3 install tensorflow==1.15.1
        pip3 install keras==2.3.1
        pip3 install imageai
3. Run the script
    python piidetectobject.py <image folder name> <percent number [0-100]>
    ex:
    python piidetectobject.py images 35



The list of detectable objects

person,  bicycle,  car, motorcycle, airplane, bus, train,  truck,  boat,  traffic light,  fire hydrant, stop_sign,
parking meter,   bench,   bird,   cat,   dog,   horse,   sheep,   cow,   elephant,   bear,   zebra,
giraffe,   backpack,   umbrella,   handbag,   tie,   suitcase,   frisbee,   skis,   snowboard,
sports ball,   kite,   baseball bat,   baseball glove,   skateboard,   surfboard,   tennis racket,
bottle,   wine glass,   cup,   fork,   knife,   spoon,   bowl,   banana,   apple,   sandwich,   orange,
broccoli,   carrot,   hot dog,   pizza,   donot,   cake,   chair,   couch,   potted plant,   bed,
dining table,   toilet,   tv,   laptop,   mouse,   remote,   keyboard,   cell phone,   microwave,   oven,
toaster,   sink,   refrigerator,   book,   clock,   vase,   scissors,   teddy bear,   hair dryer,   toothbrush
