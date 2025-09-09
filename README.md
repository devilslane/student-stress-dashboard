# student-stress-dashboard
This dashboard provides an analytical view of the factors influencing student stress, sleep quality, and academic performance. It was built in Power BI using the StressLevelDataset.csv dataset, with custom DAX commands for calculated measures. The analysis explores how stress is shaped by depression, study load, bullying, peer pressure, and academic outcomes.

<img width="1414" height="795" alt="image" src="https://github.com/user-attachments/assets/0be3fe9f-04ec-4c1a-a97f-46e5e3837802" />

🔍 Key Insights

Average Metrics:

Stress Level: 1.00

Academic Performance: 2.77

Sleep Quality: 2.66

Academic Performance vs Stress: Students with lower academic performance tend to report higher stress levels.

Depression Impact: Higher depression levels are linked to poor sleep quality, higher stress, and reduced academic performance.

Bullying & Stress: Bullying is identified as a major driver of student stress.

Study Load Effect: Stress levels rise with higher study load but decline at the extreme end, possibly due to coping strategies or reduced expectations.

Stress Distribution: Students are fairly evenly distributed across stress levels (~34% low, ~33% medium, ~33% high).

⚙️ Technical Details

Dataset Used: StressLevelDataset.csv

Tool: Microsoft Power BI

DAX Functions Applied:

Average and Sum measures (AVERAGE, SUM)

Conditional aggregations for depression vs stress/sleep/performance

Stress segmentation by bullying, peer pressure, and study load

