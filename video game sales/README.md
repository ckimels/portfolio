This Project was started to accomplish exploratory data analysis for a data set of video game sales. The goal is to explore the data, clean and prep as necessary, then find interesting insights and plot them.

## First 20 records
*df.head(20)*
<img width="1581" height="946" alt="Screenshot 2026-05-17 114959" src="https://github.com/user-attachments/assets/93adf1bf-b24e-429b-addd-cfdba479ddbd" />

## Descriptive statistics for DataFrame
*df.describe()*
<img width="1057" height="412" alt="Screenshot 2026-05-17 115043" src="https://github.com/user-attachments/assets/1be302ea-9f52-4ec3-8553-0daef6043a52" />

## Non-null count and data types
*Year and Publisher columns contain null values since their Non-Null Count is less than 16598*
*df.info()*
<img width="545" height="456" alt="Screenshot 2026-05-17 115052" src="https://github.com/user-attachments/assets/b37ff9ca-c3b6-4216-a349-015c743580d1" />

## Null count per column
<img width="245" height="316" alt="Screenshot 2026-05-17 115059" src="https://github.com/user-attachments/assets/81a6be24-91d1-4fcd-9cee-9e6b3a347f8e" />

## Every record containing null values
*Decided not to remove null values. Not all games have a Publisher, and Year column did not effect graphs.*

<img width="1636" height="633" alt="Screenshot 2026-05-17 115106" src="https://github.com/user-attachments/assets/41dc6103-59e2-48d0-94fb-b5a8817a35c8" />

## Sales distribution by region
*NA makes up nearly half of all video game sales*

<img width="1267" height="723" alt="Screenshot 2026-05-17 115116" src="https://github.com/user-attachments/assets/cb8b9136-d34f-45eb-9364-77dc83c123af" />

## Sales over time by Region
*Video Game sales had exponential growth in NA*

<img width="1570" height="879" alt="Screenshot 2026-05-17 115123" src="https://github.com/user-attachments/assets/f923ee9d-653d-44fa-8740-7dd752fc3998" />

<img width="750" height="1057" alt="Screenshot 2026-05-17 115128" src="https://github.com/user-attachments/assets/0efcb7a8-1c63-4896-b165-37c4a69530e5" />

<img width="1670" height="682" alt="Screenshot 2026-05-17 115137" src="https://github.com/user-attachments/assets/818355e0-1e11-41bd-a445-52273d6eb057" />

Global Sales by Platform (Stack by Region)

Xbox consoles (X360, XB, XOne) do not sell well in Japan
PC Sales are also almost non-existent in Japan

<img width="1670" height="715" alt="Screenshot 2026-05-17 115146" src="https://github.com/user-attachments/assets/7f15ee05-644e-4304-b86c-926a3f0922c4" />












