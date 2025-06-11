# **Studi Kasus: Analisis Efisiensi Gaji dan Performa Skuad dalam Kemenangan Liverpool di Premier League**

## Latar Belakang

Proyek ini menganalisis bagaimana Liverpool memenangkan Premier League musim 2024/2025 dengan menantang asumsi umum bahwa gelar juara harus dibeli dengan pengeluaran gaji yang masif. Hipotesis utamanya adalah kemenangan Liverpool didorong oleh efisiensi skuad yang dimaksimalkan oleh manajer baru, bukan semata oleh kekuatan finansial. Analisis mencakup perbandingan finansial antar klub, identifikasi kontributor utama di level pemain, dan pengukuran 'value for money' untuk membuktikan efisiensi tersebut melalui data.

## Sumber data berasal dari Kaggle berkut link dataset untuk proyek kali ini :

https://www.kaggle.com/datasets/flynn28/2025-premier-league-stats-matches-salaries/data

## Tools: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Kesimpulan:

Liverpool terbukti berhasil menjuarai Premier League. Kemenangan ini diraih bukan karena menjadi klub dengan belanja gaji terbesar, melainkan karena efisiensi pengeluaran yang luar biasa dibandingkan para pesaingnya. Efisiensi di level klub ini terwujud karena manajer baru (Arne Slott) berhasil meramu skuad yang ada menjadi sebuah "mesin" yang sempurna: satu mega bintang yang produktivitasnya setara dengan harganya (Salah), didukung oleh pemain-pemain 'best value' yang sangat efisien (Díaz), dan ditopang oleh inti tim yang solid dan konsisten (Gakpo, Szoboszlai, Mac Allister). Mereka berhasil memaksimalkan output dari skuad yang ada, bukan sekadar membeli kesuksesan instan.

### Temuan Kunci

Liverpool berhasil menjuarai liga meskipun total pengeluaran gajinya berada di luar 3 besar teratas.

Mohamed Salah, sebagai pemain dengan gaji tertinggi, membuktikan efisiensinya dengan menjadi top skorer dan top assist tim, menghasilkan "biaya per kontribusi gol" yang sangat baik.

Pemain seperti Luis Díaz menjadi contoh "value for money" terbaik, memberikan kontribusi gol yang tinggi dengan gaji yang relatif lebih rendah.

Kemenangan ini didukung oleh kontribusi merata dari seluruh lini, menunjukkan keberhasilan manajer dalam memaksimalkan potensi skuad yang ada.

### Visualisasi Utama

![Scatter Plot](Visualisasi/Salary%20Spending%20Efficiency%20vs.%20Total%20Points%20in%20the%20Premier%20League%20.png)
Grafik tersebut menunjukan efisiensi pengeluaran gaji yang dikeluarkan oleh klub dan poin yang didapatkan di premier league musim 2024/2025. Dapat dilihat liverpool dengan spending +/- 150 jt GBP menjadi team yang bisa menjuarai liga musim 2024/2025, bisa disimpulkan spending besar tidak menjamin untuk menjuarai liga.

![Grafik Pemain Kunci Liverpool](Visualisasi/Liverpool%20Key%20Players%20Analysis.png)
Visualisasi performa pemain kunci Liverpool di berbagai metrik. Grafik ini menyoroti dominasi Mohamed Salah dalam kontribusi gol (gol & assist), dan peran vital Trent Alexander-Arnold sebagai playmaker utama tim dari lini pertahanan.

![Grafik kontribusi goal(G/A)](<Visualisasi/Cost%20per%20goal%20contribution%20(Goal-Assist)%20-%20Liverpool.png>)
Grafik di atas membandingkan biaya per kontribusi gol (gabungan gol dan assist) para pemain Liverpool. Mohamed Salah menonjol sebagai kontributor utama dengan efisiensi biaya yang tinggi, sementara Díaz, Gakpo, dan Szoboszlai juga menunjukkan rasio biaya per kontribusi yang rendah. Data ini menegaskan bahwa efisiensi finansial skuad menjadi faktor kunci keberhasilan Liverpool musim ini.

## Cara Menjalankan Proyek

### Instalasi & Cara Menjalankan

1. Clone repositori ini:

   ```bash
   git clone [Link](Link)

   ```

2. Pasang Library yang dibutuhkan

   pip install pandas matplotlib seaborn jupyter

3. Buka dan jalankan file analisis_premier_league.ipynb di Jupyter Notebook.

# **Case Study: Analysis of Squad Salary Efficiency and Performance in Liverpool's Premier League Victory**

## Background

This project analyzes how Liverpool won the 2024/2025 Premier League by challenging the common assumption that the title must be bought with massive wage spending. The main hypothesis is that Liverpool's victory was driven by squad efficiency maximized by the new manager, not merely by financial power. The analysis includes financial comparisons between clubs, identification of key player contributors, and measurement of 'value for money' to prove this efficiency through data.

## Data source is from Kaggle, here is the dataset link for this project:

https://www.kaggle.com/datasets/flynn28/2025-premier-league-stats-matches-salaries/data

## Tools: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Conclusion:

Liverpool has proven to be the Premier League champion. This victory was achieved not by being the club with the highest wage expenditure, but due to extraordinary spending efficiency compared to its competitors. This club-level efficiency was realized because the new manager (Arne Slott) managed to turn the existing squad into a perfect "machine": one mega star whose productivity matches his price (Salah), supported by 'best value' players who are highly efficient (Díaz), and backed by a solid and consistent core team (Gakpo, Szoboszlai, Mac Allister). They managed to maximize the output from the existing squad, not just buy instant success.

### Key Findings

Liverpool managed to win the league even though their total wage expenditure was outside the top 3.

Mohamed Salah, as the highest-paid player, proved his efficiency by becoming the team's top scorer and top assist provider, resulting in an excellent "cost per goal contribution".

Players like Luis Díaz are examples of the best "value for money", providing high goal contributions with relatively lower wages.

This victory was supported by evenly distributed contributions from all lines, demonstrating the manager's success in maximizing the squad's potential.

### Main Visualizations

![Scatter Plot](Visualisasi/Salary%20Spending%20Efficiency%20vs.%20Total%20Points%20in%20the%20Premier%20League%20.png)
The chart shows the efficiency of wage expenditure by clubs and the points obtained in the 2024/2025 Premier League season. It can be seen that Liverpool, with spending of +/- 150 million GBP, became the team that could win the league in the 2024/2025 season, concluding that high spending does not guarantee winning the league.

![Liverpool Key Players Chart](Visualisasi/Liverpool%20Key%20Players%20Analysis.png)
Visualization of the performance of Liverpool's key players across various metrics. This chart highlights Mohamed Salah's dominance in goal contributions (goals & assists), and the vital role of Trent Alexander-Arnold as the team's main playmaker from the defense.

![Goal Contribution Chart (G/A)](<Visualisasi/Cost%20per%20goal%20contribution%20(Goal-Assist)%20-%20Liverpool.png>)
The chart above compares the cost per goal contribution (combined goals and assists) of Liverpool players. Mohamed Salah stands out as the main contributor with high cost efficiency, while Díaz, Gakpo, and Szoboszlai also show low cost per contribution ratios. This data confirms that the squad's financial efficiency was a key factor in Liverpool's success this season.

## How to Run the Project

### Installation & How to Run

1. Clone this repository:

   ```bash
   git clone [https://github.com/maulthepublic](https://github.com/maulthepublic/Premier_league_analysis))
   ```

2. Install the required libraries

   pip install pandas matplotlib seaborn jupyter

3. Open and run the file analisis_premier_league.ipynb in Jupyter Notebook.

**Terima kasih atas perhatianya**
**Thank you for your attention**

Connect to me in:
Linkedin: https://www.linkedin.com/in/maulana-ardi23/
Instagram : @mauardnsyh
