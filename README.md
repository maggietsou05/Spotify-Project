# Targeted Strategy for Loyal Spotify User - Data Analysis

## Project Background

Spotify, launched in 2008, leads the streaming market with a dominant global presence. Apple Music, introduced in 2015, competes with exclusive content, high-fidelity audio, and seamless integration within the Apple ecosystem. Using real listening behavior, this project explores personalized, data-driven strategies Apple could use to win over even the most committed Spotify users.

This project is built around a dataset that’s as personal as it gets: my best friend, a self-proclaimed music connoisseur, has been logging her Spotify listening activity since 2016. With years of streaming data, this project explores her listening habits and asks: *what would it take to persuade this loyal Spotify user to switch to Apple Music?*

This project doesn’t pretend to answer that at scale, but it does explore how one user’s deep behavioral data can inspire realistic strategies and insights.

Insights and recommendations are provided in the following key areas:
- Listening behavior over time
- Content loyalty patterns
- Session-level context
- Platform and environment context
<br/>

An interactive Tableau dashboard can be downloaded [here]<br/><br/>
The SQL queries utilized to inspect and perform quality checks can be found [here]<br/><br/>
The SQL queries utilized to clean, organize, and prepare data can be found [here]<br/><br/>
Targeted SQL queries regarding various business questions can be found [here]<br/><br/>


## Data Structure & Initial Checks

Spotify's personal database structure as seen below consists of four tables: main, sessions, artists, and platforms, with a total row count of 131454

<table> <tr valign="top"> <td align="center"> <strong>Main</strong><br> <img width="264" src="https://github.com/user-attachments/assets/530a5fd5-8621-40b0-8533-dc9e5db1bad1" /> </td> <td align="center"> <strong>Artists</strong><br> <img width="262" src="https://github.com/user-attachments/assets/c5ae3983-3299-4659-8fab-16614ea17dfb" /> </td> </tr> <tr valign="top"> <td align="center"> <strong>Platform</strong><br> <img width="263" src="https://github.com/user-attachments/assets/f80b6ea5-c29b-428d-aa6c-739224a9d052" /> </td> <td align="center"> <strong>Sessions</strong><br> <img width="263" src="https://github.com/user-attachments/assets/1230264b-9e90-460d-b701-36ffa5aab454" /> </td> </tr> </table>

<img width="259" alt="image" src="https://github.com/user-attachments/assets/530a5fd5-8621-40b0-8533-dc9e5db1bad1" />


Prior to beginning the analysis, a variety of checks were conducted for quality control, data integrity, and familiarization with the datasets. Extensive data cleaning was also performed using SQL to standardize formats. The SQL queries utilized for both inspection and cleaning can be found [here](spotify_data_cleaning.sql)<br/>
<br/>
## Executive Summary


### Overview of Findings
