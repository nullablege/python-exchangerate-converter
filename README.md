Currency Converter
Description
This Python script allows you to convert an amount from one currency to another using the ExchangeRate-API. It also provides an option to list all available currencies.

Requirements
requests library: You can install it via pip if you haven't already.
pip install requests

How to Use
Run the Script

Execute the script in your Python environment.

Sort Currencies

When prompted with "If you want to sort currency, enter 1", enter 1 to list all available currencies.

Currency Conversion

Enter the amount you want to convert.
Enter the currency code for the first currency (e.g., USD).
Enter the currency code for the second currency (e.g., EUR).
The script will fetch the exchange rate and display the conversion result.

Example
If you want to sort currency, enter 1 1
USD EUR GBP
Enter the pcs : 100
Enter the first currency : USD
Enter the second currency : EUR
100 USD = 85.50 EUR

Error Handling
If there is an issue with fetching the exchange rate or if the entered currencies are invalid, an error message will be displayed.

--------------------------------------------------------------------

Döviz Çevirici
Açıklama
Bu Python betiği, ExchangeRate-API kullanarak bir miktarı bir dövizden diğerine çevirmenizi sağlar. Ayrıca, mevcut tüm dövizleri listeleme seçeneği de sunar.

Gereksinimler
requests kütüphanesi: Henüz kurulu değilse, pip ile kurabilirsiniz.
pip install requests

Kullanım
Betik Çalıştırma

Betiği Python ortamınızda çalıştırın.

Dövizleri Listeleme

"Dövizleri sıralamak istiyorsanız 1'i girin" mesajını gördüğünüzde 1 girerek tüm mevcut dövizleri listeleyin.

Döviz Çevirme

Çevirmek istediğiniz miktarı girin.
İlk dövizin kodunu (örneğin, USD) girin.
İkinci dövizin kodunu (örneğin, EUR) girin.
Betik, döviz kuru bilgilerini alacak ve dönüşüm sonucunu gösterecektir.

Örnek

Dövizleri sıralamak istiyorsanız 1'i girin 1
USD EUR GBP
Miktarı girin : 100
İlk döviz : USD
İkinci döviz : EUR
100 USD = 85.50 EUR

Hata Yönetimi
Döviz kuru alınırken bir sorun oluşursa veya girilen dövizler geçersizse, bir hata mesajı görüntülenir.
