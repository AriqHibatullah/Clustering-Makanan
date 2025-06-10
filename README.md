# Clustering Makanan Berdasarkan Kandungan Gizi

# Dataset
Dataset yang dipakai adalah data kandungan karbohidrat, protein, lemak, kalori, energi, lemak jenuh, kolestrol, serat, gula, sodium, dan kalium pada setiap makanan. Data yang digunakan diperoleh dari hasil scraping website yang menyediakan informasi gizi seperti website FatSecret.

# Algoritma yang digunakan
1. K-Means, membagi data ke dalam k cluster berdasarkan kedekatan ke titik pusat tiap cluster.
2. Density-Based Spatial Clustering of Applications with Noise (DBSCAN), mencari area dengan kepadatan tinggi sebagai cluster, dan menganggap titik-titik noise sebagai outlier.
3. Hierarchical Clustering, mulai dari setiap titik sebagai cluster sendiri lalu gabungkan dua cluster terdekat secara bertahap hingga membentuk satu cluster besar.
4. Gaussian Mixture Model (GMM), mengasumsikan data berasal dari campuran beberapa distribusi Gaussian, dan menghitung probabilitas tiap titik berasal dari masing-masing cluster.

# Hasil
## Hasil Cluster
- Cluster 0 (Lauk pauk tinggi protein)
Pada cluster ini diketahui bahwa kandungan nutrisi dengan nilai tertinggi yang ada pada setiap makanan adalah kandungan protein dengan nilai 0.62 dan nilai terendah ada pada kandungan gula yaitu 0.015. Jenis makanan pada cluster ini  merupakan makanan yang kaya protein namun rendah kandungan karbohidrat, gula, dan serat, biasanya jenis makanan dengan kandungan nutrisi ini adalah lauk pauk seperti ayam, telur, daging, tahu, dan tempe.

- Cluster 1 (Cemilan ringan tinggi energi)
Pada cluster 1 kandungan nutrisi tertinggi ada pada kalori dan energi dengan nilai 0.82, didukung dengan kandungan karbohidrat dan lemak dengan nilai 0,56 dan 0,55. Dan kandungan terendah pada cluster ini adalah kolesterol dan serat dengan nilai 0.027. Makanan pada cluster ini isinya adalah cemilan ringan yang memiliki kandungan energi yang tinggi seperti keripik kentang dan jagung, donat, kue, wafer, kacang almond, bolu, dan popcorn. 

- Cluster 2 (Cemilan berat energi sedang)
Pada cluster 2 kandungan nutrisi tertinggi ada pada karbohidrat, kalori, dan energi dengan nilai 0.46 dan 0.47, sedangkan rendah pada kolestrol, serat, dan gula. Makanan pada cluster ini isinya adalah cemilan berat tetapi memiliki proprosi yang cukup rata dikarenakan termasuk makanan olahan seperti roti, pizza, risol, eskrim. 

- Cluster 3 (Makanan seimbang rendah lemak)
Pada cluster 3 kandungan nutrisi tergolong rata pada setiap aspek. Hal tersebut dikarenakan makanan dikelompok ini merupakan makanan yang seimbang dan merupakan makanan yang dikonsumsi untuk mencukupi kebutuhan gizi, seperti nasi, mie, pasta, oatmeal, dan salad.

- Cluster 4 (Cemilan ringan manis tinggi gula)
Pada cluster 4 kandungan nutrisi tertinggi ada pada karbohidrat dan gula dengan nilai 0.74, dan kandungan terendah pada cluster ini adalah protein, lemak, dan sodium. Makanan pada cluster ini isinya adalah makanan ringan yang manis seperti buah-buahan kering, brownis, macaron, permen, dan kismis.
