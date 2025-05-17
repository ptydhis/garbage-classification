## 🌐 Bahasa | Language
- 🇮🇩 [Bahasa Indonesia](#🇮🇩-analisis-perbandingan-akurasi-arsitektur-resnet-50-dan-vgg16-pada-sistem-klasifikasi-sampah)
- 🇬🇧 [English](#🇬🇧-comparative-analysis-of-resnet-50-and-vgg16-architecture-accuracy-in-garbage-classification-system)

---

## 🇮🇩 Analisis Perbandingan Akurasi Arsitektur ResNet-50 Dan VGG16 Pada Sistem Klasifikasi Sampah

<div align="justify"> Proyek ini bertujuan untuk menerapkan metode Convolutional Neural Network (CNN) dalam melakukan klasifikasi jenis sampah menjadi enam kategori: cardboard, glass, metal, paper, plastic, dan trash. Dalam proses pelatihan model klasifikasi CNN, proyek ini menggunakan pendekatan transfer learning dengan memanfaatkan model pre-trained dari pustaka Keras Applications, yaitu VGG16 dan ResNet-50. Kedua arsitektur tersebut dipilih karena telah terbukti efektif dalam tugas klasifikasi citra dan banyak digunakan dalam berbagai penelitian sebelumnya. Penelitian ini melakukan perbandingan performa kedua model untuk menentukan arsitektur mana yang memberikan hasil klasifikasi paling optimal. Berdasarkan hasil evaluasi, model VGG16 menunjukkan tingkat akurasi, presisi, recall, dan F1-score sedikit lebih tinggi (97%) dibandingkan dengan ResNet-50 (96%), meskipun ResNet-50 memiliki keunggulan dalam efisiensi komputasi dengan waktu pelatihan lebih cepat. Perbandingan ini diharapkan dapat menjadi dasar dalam pengembangan sistem klasifikasi sampah otomatis berbasis AI yang lebih akurat dan efisien. </div>

## 🇬🇧 Comparative Analysis of ResNet-50 and VGG16 Architecture Accuracy in Garbage Classification System

<div align="justify"> This project aims to implement the Convolutional Neural Network (CNN) method to classify garbage types into six categories: cardboard, glass, metal, paper, plastic, and trash. The classification model was trained using a transfer learning approach by utilizing pre-trained models from the Keras Applications library, namely VGG16 and ResNet-50. Both architectures were chosen due to their proven effectiveness in image classification tasks and their frequent use in previous research. The study compares the performance of both models to determine which architecture yields the most optimal classification results. Based on the evaluation, the VGG16 model achieved slightly higher accuracy, precision, recall, and F1-score (97%) compared to ResNet-50 (96%), although ResNet-50 demonstrated better computational efficiency with a faster training time. This comparison is expected to serve as a foundation for the development of more accurate and efficient AI-based automatic garbage classification systems. </div>

---

## 🇮🇩 Hasil

1. <div align="justify"> Percobaan yang dilakukan dalam proyek ini menghasilkan model klasifikasi CNN terbaik yang dibangun menggunakan pendekatan transfer learning, dengan memanfaatkan model pre-trained dari pustaka Keras Applications, yaitu VGG16 dan ResNet-50. Berdasarkan hasil evaluasi, VGG16 menunjukkan performa klasifikasi yang lebih unggul dibandingkan ResNet-50, dengan nilai akurasi, presisi, recall, dan F1-score sebesar 97%, sedangkan ResNet-50 memperoleh nilai 96% untuk keempat metrik tersebut. </div>

2. <div align="justify"> Proses pelatihan dilakukan selama 60 epoch, menggunakan dataset yang terdiri dari 2.467 citra sampah yang terbagi dalam enam kelas: cardboard, glass, metal, paper, plastic, dan trash. Data dibagi menjadi 80% data pelatihan, 10% data validasi, dan 10% data pengujian, dengan penerapan teknik augmentasi data dan preprocessing (resizing ke 180x180 piksel) untuk meningkatkan kemampuan generalisasi model. </div>

3. <div align="justify"> Selama pelatihan, VGG16 mencapai akurasi pelatihan lebih dari 95% dan akurasi validasi lebih dari 93%, sementara ResNet-50 mencapai akurasi validasi sekitar 96%. Meskipun ResNet-50 memiliki waktu pelatihan lebih cepat (rata-rata 1 detik per epoch dibandingkan 3 detik pada VGG16), VGG16 menunjukkan performa yang lebih stabil dan akurat. Oleh karena itu, VGG16 dipilih sebagai model klasifikasi terbaik dalam penelitian ini berdasarkan keseimbangan antara akurasi, stabilitas performa, dan kemampuan generalisasi pada dataset terbatas. </div>

## 🇬🇧 Results

1. <div align="justify"> The experiment in this project resulted in the best CNN classification model built using a transfer learning approach with pre-trained models from the Keras Applications library, namely VGG16 and ResNet-50. Based on evaluation results, VGG16 demonstrated superior classification performance compared to ResNet-50, achieving 97% for accuracy, precision, recall, and F1-score, while ResNet-50 reached 96% on the same metrics. </div>

2. <div align="justify"> The training process was conducted for 60 epochs using a dataset of 2,467 garbage images divided into six classes: cardboard, glass, metal, paper, plastic, and trash. The data was split into 80% training, 10% validation, and 10% testing sets, with data augmentation and preprocessing (resizing to 180x180 pixels) applied to improve the model’s generalization ability. </div>

3. <div align="justify"> During training, VGG16 achieved over 95% training accuracy and over 93% validation accuracy, while ResNet-50 reached approximately 96% validation accuracy. Although ResNet-50 had faster training time (1 second per epoch on average vs. 3 seconds for VGG16), VGG16 showed more stable and accurate performance. Therefore, VGG16 was selected as the best classification model in this study due to its balance of accuracy, performance stability, and generalization capability on a limited dataset. </div>

---

## 📁 Resource Links

- 📦 Dataset: [Link 1](https://drive.google.com/file/d/1CyjUb8IS4auFMlfIPWOzfnlz4LReXnii/view?usp=sharing)
- 🤖 Trained Model: [Link 2](https://drive.google.com/file/d/1lbVbGWYPs7uNLioAG84aBCOQ-peFNaU4/view?usp=sharing)
- 📄 Research Paper: [Link 3](https://drive.google.com/file/d/1ESsXFK23ujvRDQl7OF-XuaZ5Cfg7A71y/view?usp=sharing)
