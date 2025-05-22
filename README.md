# Spotify-Project
Targeting a Loyal Spotify User for Apple Music - Data Analysis and Recommendations

## Data Structure & Initial Checks
Spotify's personal database structure as seen below consists of four tables: main, sessions, artists, and platforms, with a total row count of 131454

<table> <tr valign="top"> <td align="center"> <strong>Main</strong><br> <img width="264" src="https://github.com/user-attachments/assets/700ae432-9c6e-4227-a66d-09439da599ba" /> </td> <td align="center"> <strong>Artists</strong><br> <img width="262" src="https://github.com/user-attachments/assets/c5ae3983-3299-4659-8fab-16614ea17dfb" /> </td> </tr> <tr valign="top"> <td align="center"> <strong>Platform</strong><br> <img width="263" src="https://github.com/user-attachments/assets/f80b6ea5-c29b-428d-aa6c-739224a9d052" /> </td> <td align="center"> <strong>Sessions</strong><br> <img width="263" src="https://github.com/user-attachments/assets/1230264b-9e90-460d-b701-36ffa5aab454" /> </td> </tr> </table>

Prior to beginning the analysis, a variety of checks were conducted for quality control, data integrity, and familiarization with the datasets. Extensive data cleaning was also performed using SQL to standardize formats. The SQL queries utilized for both inspection and cleaning can be found [here](spotify_data_cleaning.sql)
