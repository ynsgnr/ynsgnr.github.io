---
layout: post<
title: C Dili ve Kullanıan Yorumlar
categories: programcılık okul ITU
---

<p>Merhabalar, yazının başlığına bakmayın çok ciddi bir yazı olmayacak, açıkcası geçenlerde başıma gelen bir olayı yazmak için yazıyorum ve tabiki bunu yaparken ucunu biraz nacizane okuluma da değdiriceceğim.</p>

<blockquote><i><h2>C Yazarken yorumlarda(commentlerde) backslash "/" kullanmayın<h2></i></blockquote>

<p> Başıma gelen olay buydu işte, geçen okul döneminde bir ödevi hazırlarken, nedendir hatırlamıyorum ama bir comment satırının içine backslash koymuştum. Bunun sonucunda gcc derleyici "<small><i>ITU'nün bana verdiği SSH serverda, Red Hat 4.8.5-4 üzerinde GCC 4.8.5 20150623 derleyicisi</i></small>" comment satırındaki backslash'ı görüp onun bir altındaki satırı da atlıyordu. Hatayı bulmam 1-2 günümü aldı açıkcası çok ilginç ve basit bir hata olmasına rağmen o satırı atlması memory overflow'a sebep olup programın fatal error vermesine sebep oluyordu</p>

<h1>Teknik kısımlarla ilgilenmeyenler yukardaki paragrafı okumasa da olur</h1>

<p>Şimdi bu hatayı neden bulamadım ben, çünkü Formal Languages and automata dersini alamadım. 3.sınıfa koymuşlar çok ilginçtir. Neyse tahminim derleyicinin <small><i>(yazılan programı bilgisayar diline çeviren arkadaş)</i></small> içindeki küçük bir hatadan dolayı. Ama ben derleyicinin nasıl çalıştığını az çok bilmesem bu hatayı bulmam imkansız hale gelirdi. Tam olarak nasıl oldu bilmiyorum, daha önce başına gelen var mı onu da bilmiyorum. Umarım bi ara yetkili abiler düzeltir. Daha önce de dediğim gibi bilgisayar bilimi piramit gibi, temelini öğrenmesi zor böyle şeylerin olması çok doğal ama gene de 1. sınıf öğrencilerine sudan çıkmış balık gibi kodlama dersi verilerek bilgisayarın yüzeyinden aşağı inmek biraz zorlama bir eğitim gibi oluyor dolayısıyla daha önce bişeyler bilmeyen veya bağlantı kuramayan arkadaşlar eğitimi tamamlayamıyor.</p>

<h3>Mühendislik okuyorsunuz bağlantı kuramayacak da napıcak öğrenci?</h3>
<p>Sonuna kadar haklı bir düşünce, zaten değişmeli falan demedim okumayı düşünenlere bir uyarı niteliğinde yazdım, sonuçta zor bölüm ama okuması zevkli. Neyse formal dersini alıp sorunu anlayınca bidaha yazarım belki.</p>

<small>Benden bu kadar arkadaşlar, görüşürüz...</small>