# Clustering Makanan Berdasarkan Kandungan Gizi

# Algoritma yang digunakan
1. K-Means, membagi data ke dalam k cluster berdasarkan kedekatan ke titik pusat tiap cluster.
2. Density-Based Spatial Clustering of Applications with Noise (DBSCAN), mencari area dengan kepadatan tinggi sebagai cluster, dan menganggap titik-titik noise sebagai outlier.
3. Hierarchical Clustering, mulai dari setiap titik sebagai cluster sendiri lalu gabungkan dua cluster terdekat secara bertahap hingga membentuk satu cluster besar.
4. Gaussian Mixture Model (GMM), mengasumsikan data berasal dari campuran beberapa distribusi Gaussian, dan menghitung probabilitas tiap titik berasal dari masing-masing cluster.
