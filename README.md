# Person-Detection-COCO
 
## Latar Belakang
Deteksi manusia, terutama dengan menggunakan teknologi seperti deteksi wajah, memiliki pentingnya sendiri karena memiliki beberapa manfaat dan aplikasi yang relevan. Berikut adalah beberapa alasan mengapa deteksi manusia sangat penting:

1. Keamanan dan Perlindungan: Deteksi wajah dan deteksi manusia umumnya digunakan dalam sistem keamanan untuk mengenali orang yang dikenali atau tidak dikenali. Ini membantu dalam melacak dan mencegah akses yang tidak sah, serta memberikan perlindungan tambahan terhadap ancaman keamanan.
2. Sistem Keamanan dan Alarm: Deteksi manusia memungkinkan sistem keamanan untuk mendeteksi intrusi atau kehadiran orang asing di area sensitif seperti gedung, rumah, atau properti. Ini juga membantu mengurangi risiko kejahatan dan meningkatkan respons darurat.
3. Optimalisasi Aplikasi: Dengan adanya deteksi wajah, aplikasi dapat dioptimalkan untuk berbagai tujuan. Misalnya, dalam pengaturan rumah pintar, deteksi wajah dapat digunakan untuk mengenali penghuni rumah dan mengaktifkan perangkat secara otomatis sesuai dengan preferensi individu.
4. Analisis Data: Deteksi manusia memungkinkan analisis data berbasis wajah dan perilaku manusia. Informasi ini dapat digunakan dalam berbagai bidang seperti analisis konsumen, pemantauan kunjungan orang-orang, atau identifikasi karakteristik demografis.
5. Kepatuhan Privasi: Meskipun ada potensi masalah privasi dengan deteksi manusia ini, kemajuan teknologi juga membawa peluang untuk mematuhi privasi dengan merancang sistem yang menghormati hak privasi individu.
6. Kemudahan Penggunaan:Deteksi manusia menggunakan teknologi saat ini semakin mudah digunakan dan dapat diintegrasikan ke dalam berbagai perangkat dan sistem, seperti kamera CCTV, perangkat cerdas, dan aplikasi perangkat lunak. 
![196107891-bb8124de-99c6-4039-b556-2ade403bd985](https://github.com/sadisad/Person-Detection-COCO/assets/61278337/784cc8bf-1909-410c-9702-4482243266ea)

Dalam Project ini saya mencoba implementasikan FasterRCNN| untuk person detection menggunakan datasets [coco dataset](https://cocodataset.org/) yang diambil menggunakan library [FiftyOne](https://docs.voxel51.com/).<br/>

## Langkah-langkah
Proses implementasi:
1. Import library-library
2. Download dataset (coco dataset) dengan menggunakan FiftyOne dengan jumlah data train 3000 dan data test 500
3. Membuat function DataLoader menyesuaikan dengan coco dataset
4. Membuat Model FasterRCNN
5. Membuat function  untuk menghitung loss function
6. Melakukan training model
7. Melakukan evaluasi model dengan mAP

## Kesimpulan
Dalam Project ini saya mendapatkan mAP sebesar **0.00501** dengan epoch 50
