## Assigment-10
# Data visualization with Power BI

![Customer demoghraphy](https://user-images.githubusercontent.com/127901613/229225264-0bf2c92a-4f1e-4b24-a535-fd96071f9e48.PNG)

Dari data customer diketahui terdapat 3 outlet dengan id 3, 5, dan 8. Outlet 3 beralamatkan di 32-20 Broadway Long Island City, outlet 5 di 100 Church Street New York, dan outlet 8 di 687 9th Avenue New York.
customer dari keseluruhan outlet didominasi oleh perempuan dengan presentase 43,5%, disusul oleh gender laki-laki dengan presentase 32,32%, dan 24,18% sisanya adalah gender lainnya. Dari ketiga outlet semuanya memiliki customer paling banyak perempuan.

Dilihat dari persebaran umurnya, customer paling banyak pada rentang usia 30-40. Tetapi 7 usia customer paling banyak berada pada rentang 23-32 yang merupakan usia produktif dan bisa diasumsikan status mereka adalah pekerja dan sebagian mungkin mahasiswa. Dilihat dari persebarannya, customer dengan usia lebih dari 50 juga banyak.

Dari customer demoghraphy tersebut, strategi yang bisa dilakukan untuk meningkatkan revenue adalah sebagai berikut.

1. Memberikan diskon untuk menu dengan penjualan yang tidak terlalu tinggi tetapi harganya mahal.
Dilihat dari banyaknya customer yang bergender perempuan, memberikan promo untuk menu tersebut kemungkinan akan menarik perhatian dan meningkatkan penjualan menu tersebut. Bagi wanita, membeli sesuatu dengan harga diskon memberikan kepuasan lebih dibandingkan membeli dengan harga normal.

2. Membuat bundling menu bakery + drinking (coffee/tea/chocolate drinking) yang disesuaikan dengan data transaksi masing-masing outlet.

3. Melakukan marketing memalui media sosial untuk menarik lebih banyak pengunjung.
Strategi ini bisa dilakukan dengan membuat konten kreatif di Instagram dan Tiktok (sasaran usia 20-40) dan konten di Facebook (sasaran usia > 40).

4. Menjual lebih banyak menu dengan penjualan paling banyak dan mengurangi menu dengan waste yang lebih besar dibanding dengan penjualannya.

5. Meningkatkan pelayanan yang ramah dan dapat bersosial dengan baik kepada customer yang rentang usianya dari 22-73.


Berikutnya adalah rekomendasi produk yang bisa diberikan harga diskon dan bundling berdasarkan penjualan di outlet masing-masing (3, 5, dan 8).


**sales_outlet id = 3**

![outlet 3](https://user-images.githubusercontent.com/127901613/229225376-dba6b1a9-8148-4266-a3dd-fd147905ceb3.PNG)

- menu yang dijual lebih banyak:
  + Earl Grey Reguler size (576 terjual)
  + Dark Chocolate Large size (568 terjual)
  + Hazelnut Biscotti (terjual 18,77% dengan waste hanya 12,47%)

- menu yang harus dikurangi: Ginger Scone (terjual 29,16% dengan waste yang jauh lebih besar, yaitu 48,88%)

- menu bundling:
  + Ginger Scone (penjualan tertinggi di kategori bakery) + Cappucino Large size (sum of unit_price tertinggi di kategori drinking) > apabila penjualan ini meningkat maka waste dari Ginger Scone dapat terkurangi
  + Cranberry Scone (penjualan terendah di kategori bakery) + Papermint Regular size (penjualan tertinggi ketiga di kategori drinking) > menyatukan menu dengan penjualan rendah dan tinggi untuk meningkatkan penjualan menu dengan penjualan rendah

- menu diskon (penjualan masih > 450 dengan harga >= 300 per menu)
  + Ethiopia Large size : penjualan (452) harga (350)
  + English Breakfat Large size : penjualan (459) harga (300)
  + Lemon Grass Large size : penjualan (457) harga (300)


**sales_outlet id = 5**

![outlet 5](https://user-images.githubusercontent.com/127901613/229225426-85eb0d07-01e2-4178-94d5-b4af4ca8279e.PNG)

- menu yang dijual lebih banyak:
  + Euthiopia Regular size (512 terjual)
  + Euthiopia Small size (510 terjual)
  + Chocolate Croissant (terjual 18,17% dengan waste hanya 13,14%)

- menu yang harus dikurangi: Ginger Scone (terjual 28,06% dengan waste yang jauh lebih besar, yaitu 49,98%)

- menu bundling:
  + Ginger Scone (penjualan tertinggi di kategori bakery) + Dark Chocolate Large size (sum of unit_price tertinggi di kategori drinking)
  + Cranberry Scone (penjualan terendah di kategori bakery) + Latte (penjualan tertinggi ketiga di kategori drinking)

- menu diskon (penjualan masih > 410 dengan harga > 300 per menu)
  + Dark Chocolate Regular size : penjualan (412) harga (350)
  + Jamaican Coffe River Regular size : penjualan (411) harga (310)
  + Sustainably Grown Organic Large size : penjualan (454) harga (475)


**sales_outlet id = 8**

![outlet 8](https://user-images.githubusercontent.com/127901613/229225400-cab4a7e7-054a-42c4-8279-5a2f89785e74.PNG)

- menu yang dijual lebih banyak:
  + Ouro Brasileiro shot (629 terjual)
  + Cranberry Scone (terjual 18,38% dengan waste hanya 12,47%)

- menu yang harus dikurangi: Ginger Scone (terjual 30,83% dengan waste yang jauh lebih besar, yaitu 46,85%)

- menu bundling:
  + Ginger Scone (penjualan tertinggi di kategori bakery) + Dark Chocolate Large size (sum of unit_price tertinggi di kategori drinking)
  + Almond Croissant (penjualan terendah di kategori bakery) + Ethiopia Large size (penjualan tertinggi kedua di kategori drinking)

- menu diskon (penjualan masih >= 430 dengan harga > 300 per menu)
  + Dark Chocolate Regular size : penjualan (435) harga (350)
  + Jamaican Coffe River Regular size : penjualan (430) harga (310)
  + Cappuccino : penjualan (497) harga (375)
