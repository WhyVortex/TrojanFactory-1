# TrojanFactory

# TrojanFactory, Truva Atı/Atları oluşturmak için basit python betiğidir.

TrojanFactory mümkün olduğu kadar genel konsept olarak tasarlanmıştır, herhangi bir normal dosyaya kötü dosyaları entegre etmek için kullanılabilir, bunu Autoit indirerek ve kullanarak yapabilirsiniz. 
İki temel mantığı vardır; 

**1. Standart bir dosyaya sahipsinizdir (pdf, mp3.doc, exe ...vb olabilir);**
**2. Buna farklı bir yazılım entegre etmek istiyorsunuzdur. (arka kapı(backdoor), (des, krp vb.)keylogger ...vs).
Sonuç olarak, kullanmış olduğunuz jpeg, icon eklentilerini yaratmış olduğunuz .exe uzantılı dosyaya entegre ederek kullanmış olduğunuz .exe dosyasının farklı biçimde kullanılmasını sağlarsınız.**

***Özellikleri:***
**-** Herhangi bir dosya türü ile kullanılabilir (pdf, mp3. png, jpg ...vb).
**-** Güncellenmiş sistemlerle çalışır. Güvenlik açığına dayanmadan hareket eder, yalnızca download edilerek çalışan bir dosya türüdür.
**-** Kullandığınız dosyaya göre doğru orantıda biçimlendirme yapar.
**-** Ekstra olarak özel bir simge, icon, jpeg kullanma imkanı sunar.
**-** TrojanFactory, --zip argümanı kullanılarak otomatik olarak bir zip dosyasına paketlenebilir.

***Gereksinimler:***
  - Autoit (https://www.autoitscript.com/site/autoit/downloads/).

  
***Kurulum:***

 **1. AutoIt'i indirin (https://www.autoitscript.com/site/autoit/downloads/).**

 **2. “Wine” kullanarak kurun**
      - Wine autoit-v3-setup.exe -

  3. **“Git Clone üzerinden kurulum”**

    >>> Git clone https://github.com/z00z/TrojanFactory.git
  4. **Artık bitti, TrojanFactory'yi açabilirsiniz.**

    >>> cd TrojanFactory.py
  5. **Kullanım için --help komutunu çalıştırın**

    >>> python trojan_factory.py -- help
