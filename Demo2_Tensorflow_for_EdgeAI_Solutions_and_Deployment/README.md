<p align="center">
    <img src="./Additionals/Empa-Accelerator-Workshops-Template-Banner.jpg" alt="Accelerator Workshops" 
    style="display: block; margin: 0 auto"/>
</p>

## Demo: ST Platformları İçin Edge-AI Çözümleri Geliştirme

Bu kılavuz, modern makine öğrenimi kütüphaneleri ve standart yaklaşımlarla geliştilecek "El Karakteri Tanıma" demomuzun geliştirme adımlarında size rehberlik edecektir.

Demo içeriği olan "El Karakteri Tanıma" uygulaması,  workshop için Empa Electronics tarafından tasarlanmış ve üretilmiş Kafa Kart (_Mind Board_) kullanılarak gerçekleştirilecektir. Kart üzerindeki ivmeölçer ve jiroskop sensörlerinden alınan toplam 6 eksenli sensör ölçümleri, bir yapay zeka modeline girdi olarak kullanılacak ve uç birim (Kafa Kart) üzerinde 6 farklı el karakterini sınıflandırmak amacıyla kullanılacaktır. Kafa kartın elde tutulmasıyla gerçekleştirilecek el karakterleri görsel ile açıklanmıştır.

<img src="./Additionals/Hand-Characters.png" alt="Accelerator Workshops" width="800"/> 

## Uygulama
### ↳ [Google Colab üzerinde STM32 Platformları İçin Edge-AI Çözümleri Geliştirme: El Karakteri Sınıflandırma (Tensorflow ile Convolutional Neural Network Model)](https://colab.research.google.com/drive/1pfd_9qnLD5NGn-R2M1WAIx-leZCaGYzL)
### ↳ [Google Colab üzerinde STM32 Platformları İçin Edge-AI Çözümleri Geliştirme: El Karakteri Sınıflandırma (Scikit-learn ile Random Forest Model)](https://colab.research.google.com/drive/1wO8M6MTk8_UzeAT46pLQzRjOGNvulkDJ)
Demo içeriği olan "uçta yapay zeka" uygulamasının Google Colab üzerindeki geliştirme adımlarını içerir.

## ST Platformlarında Uçta Yapay Zeka

**Tensorflow İle Makine Öğrenimi Modelleri Geliştirme**  
Tensorflow, beraberinde barındırdığı Keras kütüphanesinin de gücüyle, modern derin öğrenme / yapay zeka uygulamalarının geliştirilmesine olanak sağlayan en önemli açık kaynaklı geliştirme kaynaklarından biridir. Tensorflow kütüphanesi, yüksek-seviye kullanım dili ve bu sayede edindiği kullanım kolaylığı sebebiyle workshop etkinliği içerisinde geliştirilecek derin öğrenme modelinin temeli olarak tercih edilmiştir.

**STM32 Cube-AI İle Uçta Yapay Zeka Çözümleri Dağıtımı**  
Geliştirilen bir makine öğrenmesi/derin öğrenme modelinin bir uç birimde, ST platformlarında tesis edilmesi, STMicroelectronics tarafından geliştirilen STM32CubeAI dönüşüm aracı ile sağlanabilmektedir. STM32CubeAI, pek çok popüler model formatı desteği ve dahili olarak gelen model sıkıştırma/derleme araçlarıyla geliştirilen modellerin kolayca çözümleştirilebilmesine imkan tanımaktadır.

**Kaynaklar & Okuma Önerileri** 

1- [Tensorflow2 Quick Start for Beginners](https://www.tensorflow.org/tutorials/quickstart/beginner)

1- [STM32Cube.AI - A Free Tool For Edge-AI Developers](https://stm32ai.st.com/stm32-cube-ai/)