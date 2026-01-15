<h1>CTF / OSINT Challenge N1</h1>

<b>Achievement Link:</b><br>
<b>https://labs.hackthebox.com/achievement/challenge/3053827/976</b>

<h3>Challenge Link:</h3>
<b>https://app.hackthebox.com/challenges/Follow%2520The%2520Money</b>

<h4>Difficulty: Easy – Low Medium</h4>

---------------------------------------------------------

<b>
Hello everyone!! To fully solve this challenge, it is essential to clearly understand the scenario, scope, and investigative objectives.
This write-up documents the analytical process used to complete the “Follow The Money” OSINT challenge, focusing on
blockchain forensics and real-world attribution.
</b>

---------------------------------------------------------

<h2>
<i>
A sophisticated cryptocurrency fraud operation has victimized multiple individuals over a four-month period.
The San Francisco Police Department Cyber Crimes Unit has seized blockchain evidence and requires a comprehensive forensic analysis
to identify perpetrators, trace fund flows, and attribute real-world identities.
</i>
</h2>

<h4>
The case revolves around a cryptocurrency fraud operation conducted over a prolonged four-month period, resulting in multiple
confirmed victims. The primary objective is to analyze blockchain data in order to identify the individuals behind the operation
and attribute their activity to real-world identities.
</h4>

---------------------------------------------------------

<br>

<img width="1468" height="741" alt="image" src="https://github.com/user-attachments/assets/8c1c33c0-a22e-4353-a605-c1d6786dcb64" />

<ul>
  <li>A suspect cryptocurrency address is provided as the primary starting point for the investigation</li>
  <li>There are 7 confirmed victims and a total of 54 identified transactions</li>
  <li>The objectives include identifying the perpetrator, total victim loss, funding exchange, privacy protocols, geographic location, and real-world attribution</li>
</ul>

<h3>Flag n1</h3>

<img width="533" height="571" alt="image" src="https://github.com/user-attachments/assets/17397d89-53c3-4146-ace2-4d86223103fb" />

---------------------------------------------------------

<img width="1062" height="384" alt="Screenshot 2026-01-15 170758" src="https://github.com/user-attachments/assets/f392c1b8-d6ef-42f3-9b5a-8108d1239b3a" />
<img width="1065" height="611" alt="Screenshot 2026-01-15 170733" src="https://github.com/user-attachments/assets/7475fd61-c580-482f-9797-cc75b1733ba7" />
<img width="1049" height="621" alt="Screenshot 2026-01-15 170836" src="https://github.com/user-attachments/assets/9ac2a2ae-4b26-446e-b33b-da8c2c8f72a3" />

<b>
Based on transaction clustering and exchange attribution analysis, the primary funding exchange associated with the suspect address
was identified as Binance. The confidence score remained consistent at 94% throughout the investigation.
</b>

<h3>Flag n2</h3>

---------------------------------------------------------

<img width="379" height="401" alt="image" src="https://github.com/user-attachments/assets/5cfcc788-bc11-4cdb-8329-851798d722ed" />

---------------------------------------------------------

<img width="1091" height="548" alt="image" src="https://github.com/user-attachments/assets/7b274070-a132-4848-bf51-0c76a9ad03a9" />
<img width="1044" height="374" alt="image" src="https://github.com/user-attachments/assets/815ed468-c830-4243-a52c-58b7427cb3b3" />

<b>
To calculate the total victim loss, all transactions linked to the seven confirmed victims (T1 CHARLIE through T7) were aggregated.
The final total loss amounted to 0.01891004 BTC. This value was verified using blockchain explorers and Crystal Analytics fraud
payment data.
</b>

<h3>Flag n3</h3>

---------------------------------------------------------

<img width="405" height="447" alt="image" src="https://github.com/user-attachments/assets/5c7c0f4f-c01d-4951-af94-4b606f5ee02d" />

---------------------------------------------------------

<img width="1062" height="389" alt="image" src="https://github.com/user-attachments/assets/b5db44f7-cdad-4446-8a04-a349a921a0b2" />

<b>
Analysis performed using OXT indicated a strong likelihood of CoinJoin usage. The transaction patterns matched those associated
with Wasabi Wallet CoinJoin, with a confidence score of approximately 94%.
</b>

<h3>Flag n4</h3>

---------------------------------------------------------

<img width="333" height="395" alt="image" src="https://github.com/user-attachments/assets/eccfd499-d5c5-48f8-9324-16d654472dd2" />
<img width="307" height="301" alt="image" src="https://github.com/user-attachments/assets/030737f2-62f4-45b5-9d5e-886c7962bd6f" />

---------------------------------------------------------

<b>
By leveraging exchange attribution and KYC-linked intelligence, the suspect wallet activity was correlated with a primary email
address, allowing partial real-world attribution.
</b>

<h3>Flag n5</h3>

---------------------------------------------------------

<b>
Based on the accumulated intelligence and attribution analysis, the identified perpetrator is James Mitchell Chen.
</b>

<h2>Flag n6 – Final</h2>

--------------------------------------------------------

<b>
Using Arkham Intelligence for geographic attribution, the suspect’s location was identified with the following coordinates:
37.774929, -122.419416.
</b>

<h1>Final Flag Successfully Captured. Thank you for your time!</h1>

<img width="887" height="820" alt="image" src="https://github.com/user-attachments/assets/c943dac9-a98b-4573-b4b9-bde0da665051" />

