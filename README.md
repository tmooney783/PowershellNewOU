<h1>Using Powershell to create a new OU</h1>

<h2>Environments used:</h2>

- Oracle VirtualBox
- Windows Server 2022
- Powershell ISE

<h2>Project walk-through</h2>


<p align="center">
First I had to import the AD  module to Powershell using the 'import-module' cmdlet: <br/>
<img src="https://i.imgur.com/AOWMi4h.png" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Then created a new OU using the cmdlet 'New-ADorganizationalunit: <br/>
<img src="https://i.imgur.com/aForGOJ.png" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Refreshed the domain: <br/>
<img src="https://i.imgur.com/xwCrYvU.png" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Added some subdivisions within the new OU: <br/>
<img src="https://i.imgur.com/T85dTde.png" height="80%" width="80%"/>
<br />
<br />
<p align="center">
Added a new user to the OU and set their password: <br/>
<img src="https://i.imgur.com/1aIvn96.png" height="80%" width="80%"/>
<br />
<br />
<p align="center">
New user added to OU: <br/>
<img src="https://i.imgur.com/a1k5IOu.png" height="80%" width="80%"/>
<br />
<br />
</p>
