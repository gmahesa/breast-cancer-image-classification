Klasifikasi Citra Histologi Kanker Payudara Menggunakan Metode Ensemble CNN.

Dataset memiliki 2 label, a_no_idc (kelas 0) dan b_has_idc (kelas 1).
Jumlah data tiap kelas 25420 citra, dengan data train 20336 dan test 5084.
Total dataset 50840.

Model CNN yang digunakan MobileNet, MobileNetV2, dan Vgg16. Dengan mengimplementasikan transfer learing dan fine tuning. 

Ensemble menggunakan metode averaging, yang di test dengan kombinasi 2 model ("two models ensemble test averaging.ipnyb) dan 3 model ("ensemble test averaging.ipnyb).
