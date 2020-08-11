---
title: Windows WSL2 ile Linux Kerneline Destek Veriyor
date: 2020-08-11T15:42:21.744Z
lastmod: 2020-08-11T15:42:21.815Z
draft: false
categories:
  - WSL
tags:
  - WSL
  - Linux
  - Windows
author: Yakup Ataş
description: Ne dediğinizi duyar gibiyim. Bende ilk duyduğumda öyle demiştim.
  Microsoft açık kaynak verilerine destek vermesi bana çok garip geldi ama
  yapmış, şaşırtıcı. Windows bu desteği sunması bize nasıl bir fayda sağlayacak?
hiddenFromHomePage: false
hiddenFromSearch: false
lightgallery: false
---
Ne dediğinizi duyar gibiyim. Bende ilk duyduğumda öyle demiştim. Microsoft açık kaynak verilerine destek vermesi bana çok garip geldi ama yapmış şaşırtıcı 🙂 Windows bu desteği sunması bize nasıl bir fayda sağlayacak ?

Hala yaygın olarak kullanılan sanal makine kurma ile istenilen her işletim sistemi windowsa kurulabilir fakat bu biraz zahmetli ve uğraştırıcı bir yoldur. Bunu yapmak için bilgisayarınıza virtualbox kurmanız ve sanal makineyi aktif etmeniz için, kullanmak istediğiniz linux dağıtımını indirmeniz gerekir. Genel de yeni kullanıcılar için biraz zahmetli bir yoldur ve kaynak kullanımı fazladır. Tabi Sanal makine de ayarladığınız kaynak kadar kaynak tüketir. Kurarken size sorar bu sanal makine için kaç GB ram kullanılsın diye.. virtualbox üçüncü taraf bir yazılım olduğu için bozulma ve kaydedilen verilerin kaybolma ihtimali de vardır. BU sebepten dolayı verilerinizin kaybolması ve bozulması ihtimali vardır.Tabi bu verileri kurtarabilirsiniz ama araştırmalarıma göre biraz zahmetli bir yol 🙂

Microsoft, windows 10 2004 güncellemesiyle gelen WSL(Windows Subsystem For Linux) teknolojisiyle, yukarıda bahsettiğim adımları kullanmadan bir linux dağıtımını windows üzerinden kullanmanızı sağlayan bir sistemdir.

Windows ve linux temelde donanımla haberleşirken farklı yöntemler kullanılmaktadır. Yani linux donanım ile haberleşirken kullandığı arka plan işlemleri, windowsun kullandığı işlemler arasında farklılıklar olduğu kesin. hoş linux hangi işlemleri kullanıyor biliyoruz ama mesele windows olunca arka planda neler yapıyor en ufak bir fikrimiz yok.Çünkü açık kaynak bir yazılım değil. Windows ve para ayrılmaz ikililer:D. Windows bu problemi çözmek için arka planda bir sanallaştırma teknolojisi kullanmış. Okuduğum yorumlara ve araştırmalarda, sanal makineye göre daha stabil ve performanslı çalışmaktadır. Ehh okadar para kazanıyorsun bir zahmet olsun diyenlerdenseniz emin olun doğru yoldasınız.

**Hadi gelin kurulum detaylarına geçelim.**

1. Öncelikle windows 10 sürümünüzün 2004 olması gerekir. eğer değilse yükseltme yapmadan kurmanızı tavsiye etmiyorum. Çünkü 2004 ten önceki sürümler WSL1 teknolojisi kullanıyor ve bu teknoloji linux kerneline destek vermemektedir.