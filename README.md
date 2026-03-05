# Inter Industry Wage Differentials
## Motivation
While working on an essay for my International Politics of Economic Relations class, I came accross these nice graphs by Michael J. Hiscox for inter-industry variations in wages in the 19th and 20th century for 6 key countries. An example for the United-States:
<img width="589" height="371" alt="Screenshot from 2026-03-03 17-12-16" src="https://github.com/user-attachments/assets/17a42051-5bb1-43ad-adaf-e328f542fa87" />
 Source:  Hiscox MJ. Class versus Industry Cleavages: Inter-Industry Factor Mobility and the Politics of Trade. International Organization. 2001: 55 (1), pp 1-46.

He uses this variable as a proxy for levels of factor mobility during a given time.
Unfortunately, my essay focuses on 2 countries which he did not study: Germany and Italy during the 1920s and 1930s.
I then found this text full of very valuable data: 
  
Bry, G., & Boschan, C. (1960). Wages in Germany, 1871–1945 (NBER General Series     No. 68). Princeton University Press. Retrieved from https://aaap.be/Pdf/Nachschlagewerke/Bryde-1960-Wages-In-Germany-1871-1945.pdf

Page 110 led me to create an R script, which computes the coefficient of variation inter-industries for hourly wages of skilled and unskilled workers, and produces a graph very similar to Hiscox's work.
<img width="1800" height="1200" alt="Wage_Differentials_Germany" src="https://github.com/user-attachments/assets/9ffc1eb5-c094-4677-a116-98d89ee318d3" />

I shared the R script and CSV file I used for my analysis of Germany. I think this could be used for other countries.
