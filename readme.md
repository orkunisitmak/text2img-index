# Text2img Yapay Zeka Index

Yazıdan görsel üretebileceğiniz, üretim öncesinde ya da sonrasında işinize yarayabilecek tüm linkleri aşağıda derledim. Aşağıdaki linkleri kullanarak yazıdan görsel ve videolar üretebilirsiniz. 

Dalle2, Midjourney, Stable Diffusion, Hugging Face gibi kolaydan zora farklı alternatifleri aşağıda sizlerle paylaşacağım.

![image](https://user-images.githubusercontent.com/68860338/190371681-cc229b7b-7e28-428c-9071-bce538b42180.png)

## Contents

---

- Text-to-image Models:
    - Ticari (ücretli kullanım)
    - Ücretsiz cloud’da çalışan uygulamalar
    - Ücretsiz kendi bilgisayarınızda çalışan uygulamalar
    - Video Oluşturma Araçları
- Prompt Engineering (Görsel üretmek için kullanılan komutlar için olan araçlar)
    - Araçlar
    - İlham alma araçları
- Post-Processing Tools (Görsel oluştuktan sonra rötüş yapma araçları)
    - Çözünürlük Yükseltme - cloud
    - Çözünürlük Yükseltme - ücretsiz
    - Yüzleri düzeltme
    - Outpainting (Dış Boyama)
    - Inpainting (İç boyama)
    - Güzelleştirme
- Eğitim
    - Videolar
    - Makaleler

### Text-to-image Models

---

Ücretli, ücretsiz ve açık kaynak kodlu olan modelleri ister ücretsiz olarak isterseniz de cloud’da çalıştırarak işlem başı ücret ödeyerek kullanabilirsiniz.

Aşağıdaki görsel oluşturma metnini farklı yapay zeka ve yapay zeka modeli kullanarak oluşturdum. Farklı yapay zekalardaki farklı sonuçlara bakabilirsiniz.

```bash
PROMPT:	super macro of a glass spider sitting on a flower, in the forest, Fantasy magic style, Highly detailed 8k, Intricate, Nikon d850 300mm, Award winning photography
```

### Ticari:

- [DreamStudio](https://beta.dreamstudio.ai/dream) - Stable Diffusion cloud (en güncel sürüm ve bence en iyi ve en kolay çalışanı)
    
    ![image](https://user-images.githubusercontent.com/68860338/190371772-45aa3f0c-6067-4571-a0c2-b9de13e1afd9.png)
    

- [Midjourney](https://www.notion.so/Text2img-Yapay-Zeka-Index-e966037bc2284d2180440abc16dfbbb3) - Discord kanalına girip bota mesaj atarak görsel oluşturuyorsunuz

   ![3444081242_a_picture_of_a_rainbow_and_a_tree_by_David_Gilmour_Blythe__highly_detailed__trending_on_artstation__4k copy](https://user-images.githubusercontent.com/68860338/190380660-9990cd3f-ea3c-4d3c-b052-61c736d231fc.jpg)

- [Dalle2](https://labs.openai.com/) - OpenAi tarafından geliştirilen, cloudda çalışan ve üretim başı kredi ödemeli bir uygulama
    
   ![image](https://user-images.githubusercontent.com/68860338/190371928-78b94a2b-e632-4aff-a391-fd4eb774a4dd.png)
    

- [Night Cafe](https://nightcafe.studio/) - Yine Stable Diffusion modeli kullanan bir web uygulaması
- [ArtBreeder Collage](https://www.artbreeder.com/beta/collage) - Yapay zeka ile fotoğraf oluşturarak kolaj yapma aracı
- [Photoroom](https://www.photoroom.com/) - Photoshop gibi bir uygulama. Yeni gelen özelliği ile yapay zeka kullanarak yazıyla fotoğraf arkaplanı üretebiliyorsunuz

### Ücretsiz Cloud’da Çalışan:

- [Craiyon](https://www.craiyon.com/) - Eski DalleMini, düşük kalite, açık kaynak kodlu, güze kompozisyon
- [Stable Diffusion on HuggingFace](https://huggingface.co/spaces/stabilityai/stable-diffusion) - HuggingFace websitesinden direk arayüzü kullanarak görsel oluşturma
- [Stable Diffusion on Replicate](https://replicate.com/stability-ai/stable-diffusion) - Replicate websitesinden direk görsel oluşturma
- Google Colab - Google’ın ücretsiz sağladığı bir hizmet. Hazır Google Colab Notebook’larını kullanarak her modeli çalıştırabilirsiniz. Kullanabileceğiniz bazı linkleri aşağıda paylaşıyorum, videolar kısmında da detaylı anlatımlarına ulaşabilirsiniz.
    - [Stable Diffusion + Web GUI](https://colab.research.google.com/github/altryne/sd-webui-colab/blob/main/Stable_Diffusion_WebUi_Altryne.ipynb)  Google Colab

### Ücretsiz Lokal Çalışan:

- [StableDiffusion + Web GUI](https://github.com/hlky/stable-diffusion-webui) - İçerisinde çözünürlük yükseltmeden yüz düzeltmeye pek çok farklı yapay zeka modelini barındıran arayüze sahip ve Google Colab üzerinden çok kolay çalıştırılabilecek bir kütüphane
    - [Google Colab tek tıkla çalıştırma linki](https://colab.research.google.com/github/altryne/sd-webui-colab/blob/main/Stable_Diffusion_WebUi_Altryne.ipynb)
- [StableDiffusion with Diffusers](https://huggingface.co/blog/stable_diffusion) - Hugging face Difüzörlerini kullanarak kolay çalıştırılabilecek bir kütüphane
- [Dream by Wombo](https://www.wombo.art/) - Stable Diffusion Mobil Uygulama
- [Diffusion Bee](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui?ref=producthunt) - M1 işlemcili Mac’ler için kolay yükleme ve kullanımlı uygulama (Stable Diffusion GUI App for Mac M1)
- [Stable Diffusion Photoshop Eklentisi](https://christiancantrell.com/#ai-ml) - Direk photoshop içerisine bu eklentiyi kurarak istediğiniz görseli üretebilirsiniz.
- [Stable Diffusion Krita Eklentisi](https://github.com/sddebz/stable-diffusion-krita-plugin/tree/master) - Direk krita içerisine bu eklentiyi kurarak istediğiniz görseli üretebilirsiniz.

### Video Oluşturma Araçları

Aşağıdaki araçları kullanarak metinle animasyonlu videolar oluşturabilirsiniz.

- [Deforum Stable Diffusion](https://replicate.com/deforum/deforum_stable_diffusion) - Başlangıç ve bitiş için farklı metin komutları yazarak oluşan görseller arası geçiş sağlayan bir araç

### img2img - Örnek görsel ve komut kullanarak görsel üretme

---

![3444081242_a_picture_of_a_rainbow_and_a_tree_by_David_Gilmour_Blythe__highly_detailed__trending_on_artstation__4k copy](https://user-images.githubusercontent.com/68860338/190373385-78330750-ae49-44d1-a608-d9f9a7be5214.jpg)


- [Stable Diffusion img2img](https://huggingface.co/spaces/fffiloni/stable-diffusion-img2img) - Cloud’da çalışan görsel ve komut girerek farklı görseller üretmenizi sağlayan bir araç
- [Stable Diffusion + Web GUI](https://colab.research.google.com/github/altryne/sd-webui-colab/blob/main/Stable_Diffusion_WebUi_Altryne.ipynb)  Google Colab
- Dalle2 - Fotoğrafınızı upload ettikten sonra “Edit Image” ya da “Generate Variations” a tıklayarak girdiğiniz fotoğrafa benzer farklı fotoğraflar yaratabilirsiniz.

### Prompt Engineering (Görsel üretimi için metin/komut hazırlama araçları)

---

### Görsel ve komut arama motorları:

- [Lexica](https://lexica.art/) - Stable Diffusion komutlarını aratabileceğiniz bir arama motoru
- [Librarire](https://libraire.ai/)
- [Krea.ai](https://krea.ai/)
- [Arthub.ai](https://arthub.ai/)

### Diğer Araçlar

- [img2prompt](https://replicate.com/methexis-inc/img2prompt) - Herhangi bir görselden komut üretme (beğendiğiniz görseli buraya atıp oluşan komuttan ilham alabilirsiniz)
- [img2prompt Clip Interrogator](https://colab.research.google.com/github/pharmapsychotic/clip-interrogator/blob/main/clip_interrogator.ipynb#scrollTo=rbDEMDGJrJEo) - Aynı işlemi Google Colab Notebook’u üzerinde yapan basit bir araç
- [3D’ciler için Yazıdan Texture Üretme](https://replicate.com/tommoore515/material_stable_diffusion) - Tüm 3d programlarında kullanılabilecek tileable texture üretir.

### Post Processing (Görsel üretildikten sonra düzenleme/rötüş araçları)

---

Çıktı olan görsellerinizi aşağıdaki tüm araçlarda deneyin, bazı araçlar farklı durumlarda daha iyi sonuç verebiliyor. Hepsini denemekte fayda var.

- [Codeformer](https://replicate.com/sczhou/codeformer) - Yapay zeka ile oluşan görseldeki çözünürlüğü yükseltir, yüzlerde kayıklıklar varsa onları düzeltir
- [RealESRGAN](https://replicate.com/xinntao/realesrgan) - Yine yüz düzeltme ve çözünürlük yükseltme (animasyon görüntülerde daha iyi çalışıyor)
- [GFPGAN](https://replicate.com/tencentarc/gfpgan) - Bozuk yüzleri ve cildi düzeltme, çözünürlük yükseltme
- [Gigapixel](https://www.topazlabs.com/gigapixel-ai) - Harici bir uygulama. Windows, Mac’te çalışıyor. Çözünürlük yükseltme, görsel ya da videolardaki bozuklukları giderme, eski fotoğrafları iyileştirme gibi alanlarda kullanılabilir.
- [Stable Diffusion Image Variation](https://replicate.com/lambdal/stable-diffusion-image-variation) - Bir görselden farklı görseller oluşturma aracı
    
    ![image](https://user-images.githubusercontent.com/68860338/190380756-c5e0c0e7-749b-44ec-a0c0-d0da2a97c7c1.png)
    

### Eğitim

---

### Videolar

- [Stable Diffusion Photoshop Eklentisi](https://www.youtube.com/watch?v=XVR3xGeH2Zw)
- [Krita Stable Diffusion Eklentisi](https://www.youtube.com/watch?v=-1iKI_yxsLo)
- [Amazon AWS Serverinde Stable Diffusion Çalıştırma](https://www.youtube.com/watch?v=C20XUPbTdE4)
- [Generating Art using Stable Diffusion](https://www.youtube.com/watch?v=0zQyCihHjQU)
- [Google Colab Notebook’a Google VM Instance Bağlama (daha hızlı çalıştırmak için)](https://www.youtube.com/watch?v=VsOb2W7AOoo)

### Makaleler:

- Yakında..


### NOTLAR!!!:

---

- Cloud’da çalışan tüm yapay zeka uygulama ve modelleri NSFW içerik üretilmesini engelleyen filtreler kullanıyor. Eğer Google Colab kullanır ya da modelleri kendi bilgisayarınızda çalıştırırsanız bu filtreleri editlemek mümkün. Google Colab notebook’una aşağıdaki satır kodu yapıştırırak filtreleri kapatabilirsiniz.
    
    ```bash
    !sed -i 's/x_checked_image, has_nsfw_concept = check_safety(x_samples_ddim)/x_checked_image = x_samples_ddim/g' scripts/txt2img.py
    ```
    
- Benim en çok kullandığım yapay zeka ve modeller:
    - [DreamStudio](https://beta.dreamstudio.ai/dream) - Stable Diffusion cloud (en güncel sürüm ve bence en iyi ve en kolay çalışanı)
    - [Stable Diffusion + Web GUI](https://colab.research.google.com/github/altryne/sd-webui-colab/blob/main/Stable_Diffusion_WebUi_Altryne.ipynb)  Google Colab
    - [Dalle2](https://labs.openai.com/) - OpenAi tarafından geliştirilen, cloudda çalışan ve üretim başı kredi ödemeli bir uygulama
    - [GFPGAN](https://replicate.com/tencentarc/gfpgan) - Bozuk yüzleri ve cildi düzeltme, çözünürlük yükseltme
    - [Gigapixel](https://www.topazlabs.com/gigapixel-ai) - Harici bir uygulama. Windows, Mac’te çalışıyor. Çözünürlük yükseltme, görsel ya da videolardaki bozuklukları giderme, eski fotoğrafları iyileştirme gibi alanlarda kullanılabilir.
