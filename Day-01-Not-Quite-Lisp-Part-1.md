[Lisp gibi bir şey](http://adventofcode.com/day/1)
===================
Santa beyaz bir Noel ümit ediyordu fakat, hava durumu değiştirme aracının "kar" fonksiyonu yıldızlar ile çalışıyor, ve malesef Santa'nın hiç yıldızı kalmadı! Noeli kurtarmak için, 50 yıldız toplamanıza ihtiyacı var.

Bilmeceleri çözerek yıldız toplayın. Noel takviminde her gün 2 adet bilmece açılaca, ikinci bilmece, ilk bilmeceyi çözdükten sonra gösterilecektir. Her bilmece 1 yıldız kazandırıyor. İyi şanslar!

Sizi ısındırmak için kolay bir bilmece;

Santa yüksek bir apartmanda hediye dağıtmaya çalışıyor fakat doğru katı bulamıyor - aldığı yönlendirmeler biraz kafa karıştırıcı -. En alt kattan başlayarak(kat= 0) her seferinde bir talimat takip ederek kat değiştiriyor.

Parantez açma işareti "(", 1 kat yukarıya gitmesini, ve Parantez kapama işareti ")" 1 kat aşağıya gitmesini söylüyor.

Apartman çok yüksek ve bodrumu çok derin. Hiç bir zaman en küst kata veya bodrumun en dibine ulaşamıyacak.

Örneğin:
- "(())" ve "()()" ikiside 0. kat ile sonuçlanır.
- "(((" ve "(()(()(" ikiside 3. kat ile sonuçlanır.
- "))(((((" de aynı şekilde 3. katda sonuçlanır.
- "())" ve "))(" ikiside -1. katda(ilk bodrum katı) sonuçlanır.
- ")))" ve ")())())" ikiside -3. katda sonuçlanır.

Part 1
------
Verilen girdideki komutlardan sonra, Santa hangi katda olur?
