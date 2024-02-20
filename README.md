# Person-Detection-COCO
 
![196107891-bb8124de-99c6-4039-b556-2ade403bd985](https://github.com/sadisad/Person-Detection-COCO/assets/61278337/784cc8bf-1909-410c-9702-4482243266ea)

Dalam Project ini saya mencoba implementasikan FasterRCNN| untuk person detection menggunakan datasets [coco dataset](https://cocodataset.org/) yang diambil menggunakan library [FiftyOne](https://docs.voxel51.com/).<br/>

## Langkah-langkah
Proses implementasi:
1. Import library-library
2. Download dataset (coco dataset) dengan menggunakan FiftyOne dengan jumlah data train 3000 dan data test 500
3. Membuat function DataLoader menyesuaikan dengan coco dataset
4. Membuat Model FasterRCNN Dengan Backbone GoogleNet Optimizer SGD, Learning Rate 5e-3, Weight Decay 5e-4, Epoch 10
5. Melakukan training model
6. Melakukan evaluasi model dengan mAP

## Kesimpulan
Dalam Project ini saya mendapatkan mAP sebesar **0.24516742** 
